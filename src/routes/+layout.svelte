<script lang="ts">
	import './layout.css';
	import Footer from '$lib/components/footer.svelte';
	import Header from '$lib/components/header.svelte';
	import { ScrollArea } from '$lib/components/ui/scroll-area';
	import { onMount } from 'svelte';
	import { browser } from '$app/environment';
	import { initLang, getLang, t } from '$lib/i18n.svelte';

	const siteUrl = 'https://ai2participa.pt'; // TODO: replace with production URL
	const title = 'AI²Participa';
	const image = `${siteUrl}/AI2-logo.png`;

	onMount(() => {
		initLang();
	});

	$effect(() => {
		if (browser) {
			document.documentElement.lang = getLang();
		}
	});

	let { children } = $props();
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={t('site.description')} />

	<!-- Open Graph -->
	<meta property="og:type" content="website" />
	<meta property="og:site_name" content={title} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={t('site.description')} />
	<meta property="og:url" content={siteUrl} />
	<meta property="og:image" content={image} />
	<meta property="og:locale" content={getLang() === 'pt' ? 'pt_PT' : 'en_GB'} />

	<!-- Twitter / X -->
	<meta name="twitter:card" content="summary" />
	<meta name="twitter:title" content={title} />
	<meta name="twitter:description" content={t('site.description')} />
	<meta name="twitter:image" content={image} />
</svelte:head>

<ScrollArea class="h-screen w-full">
	<div id="top"></div>
	<Header />
	<main class="min-h-[calc(100vh-4rem)]">
		{@render children()}
	</main>
	<Footer />
</ScrollArea>

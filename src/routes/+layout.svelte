<script lang="ts">
	import './layout.css';
	import Footer from '$lib/components/footer.svelte';
	import Header from '$lib/components/header.svelte';
	import { ScrollArea } from '$lib/components/ui/scroll-area';

	const siteUrl = 'https://TODO.example.pt'; // TODO: replace with production URL
	const title = 'AI²Participa';
	const description =
		'Espaço de participação sobre a Avaliação Estratégica para a definição das prioridades nacionais de investigação e inovação no âmbito da criação da AI².';
	const image = `${siteUrl}/AI2-logo.svg`;

	let { children } = $props();
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={description} />

	<!-- Open Graph -->
	<meta property="og:type" content="website" />
	<meta property="og:site_name" content={title} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={description} />
	<meta property="og:url" content={siteUrl} />
	<meta property="og:image" content={image} />
	<meta property="og:locale" content="pt_PT" />

	<!-- Twitter / X -->
	<meta name="twitter:card" content="summary" />
	<meta name="twitter:title" content={title} />
	<meta name="twitter:description" content={description} />
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

<script lang="ts">
	import { resolve } from '$app/paths';
	import MainNav from '$lib/components/nav/main-nav.svelte';
	import MobileNav from '$lib/components/nav/mobile-nav.svelte';
	import { Button } from '$lib/components/ui/button';
	import { getLang, toggleLang, t } from '$lib/i18n.svelte';
</script>

<header class="sticky top-0 z-50 w-full border-b bg-background">
	<div class="container flex h-16 items-center gap-4">
		<div class="mr-auto">
			<a href={resolve('/')} class="flex items-center gap-2">
				<span class="font-title text-lg font-bold sm:text-xl">AI²Participa</span>
			</a>
		</div>
		<MainNav class="hidden lg:flex" />
		<MobileNav class="flex lg:hidden" />
		<!-- Language toggle -->
		<button
			onclick={toggleLang}
			title={t('lang.switchTo')}
			aria-label={t('lang.switchTo')}
			class="flex items-center rounded border px-2 py-1 text-xs font-semibold tracking-wide transition-colors hover:bg-muted"
		>
			<span class={getLang() === 'pt' ? 'text-foreground' : 'text-muted-foreground'}>PT</span>
			<span class="mx-0.5 text-muted-foreground">|</span>
			<span class={getLang() === 'en' ? 'text-foreground' : 'text-muted-foreground'}>EN</span>
		</button>
		<Button href="https://ai2participa.eu.consider.it/" target="_blank" rel="noopener noreferrer">
			{t('header.participate')}
		</Button>
	</div>
</header>

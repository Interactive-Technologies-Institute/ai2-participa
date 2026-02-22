<script lang="ts">
	import { resolve } from '$app/paths';
	import MainNav from '$lib/components/nav/main-nav.svelte';
	import MobileNav from '$lib/components/nav/mobile-nav.svelte';
	import { Button } from '$lib/components/ui/button';
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
		<Button href="https://ai2participa.eu.consider.it/" target="_blank" rel="noopener noreferrer">
			Participe no Diálogo
		</Button>
	</div>
</header>

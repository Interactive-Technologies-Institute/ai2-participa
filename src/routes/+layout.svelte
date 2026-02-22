<script lang="ts">
	import './layout.css';
	import Footer from '$lib/components/footer.svelte';
	import Header from '$lib/components/header.svelte';
	import { ScrollArea } from '$lib/components/ui/scroll-area';

	let { children } = $props();
</script>

<ScrollArea class="h-screen w-full">
	<div id="top"></div>
	<Header />
	<main class="min-h-[calc(100vh-4rem)]">
		{@render children()}
	</main>
	<Footer />
</ScrollArea>

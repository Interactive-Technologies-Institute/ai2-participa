<script lang="ts">
	import { buttonVariants } from '$lib/components/ui/button';
	import * as Popover from '$lib/components/ui/popover';
	import { cn } from '$lib/utils';
	import type { HTMLAnchorAttributes, HTMLAttributes } from 'svelte/elements';

	type NavItemProps = HTMLAnchorAttributes & {
		content?: string;
	};

	let {
		class: className
	}: {
		class?: string;
	} & HTMLAttributes<HTMLElement> = $props();

	let open = $state(false);
</script>

{#snippet NavItem({ href, content, class: itemClassName, ...props }: NavItemProps)}
	<a
		{href}
		onclick={() => {
			open = false;
		}}
		class={cn('text-xl font-medium', itemClassName)}
		{...props}
	>
		{content}
	</a>
{/snippet}

<Popover.Root bind:open>
	<Popover.Trigger class={cn(buttonVariants({ variant: 'ghost', size: 'icon' }), className)}>
		<div class="relative flex h-8 w-4 items-center justify-center">
			<div class="relative size-4">
				<span
					class={cn(
						'absolute left-0 block h-0.5 w-4 bg-foreground transition-all duration-100',
						open ? 'top-[0.4rem] -rotate-45' : 'top-1'
					)}
				></span>
				<span
					class={cn(
						'absolute left-0 block h-0.5 w-4 bg-foreground transition-all duration-100',
						open ? 'top-[0.4rem] rotate-45' : 'top-2.5'
					)}
				></span>
			</div>
			<span class="sr-only">Toggle Menu</span>
		</div>
	</Popover.Trigger>
	<Popover.Content
		class="no-scrollbar h-(--bits-popover-content-available-height) w-(--bits-popover-content-available-width) overflow-y-auto rounded-none border-none bg-background/90 p-0 shadow-none backdrop-blur duration-100"
		align="start"
		side="bottom"
		alignOffset={-16}
		sideOffset={14}
		preventScroll
	>
		<div class="flex flex-col gap-5 overflow-auto px-6 py-6">
			{@render NavItem({ href: '/relatorios/', content: 'Relatórios' })}
			<div class="flex flex-col gap-2">
				<div class="text-sm font-medium text-muted-foreground">Estratégia de Participação</div>
				<div class="flex flex-col gap-2">
					{@render NavItem({ href: '/participacao-publica/', content: 'Participação Pública' })}
					{@render NavItem({
						href: '/metodologia-participacao-publica/',
						content: 'Metodologia de Participação Pública'
					})}
					{@render NavItem({
						href: '/comissao-acompanhamento/',
						content: 'Comissão de Acompanhamento'
					})}
					{@render NavItem({ href: '/reunioes-entidades/', content: 'Reuniões com Entidades' })}
					{@render NavItem({ href: '/mesas-tematicas/', content: 'Mesas Temáticas' })}
					{@render NavItem({
						href: '/conferencias-reunioes-descentralizadas/',
						content: 'Conferências e Reuniões Descentralizadas'
					})}
					{@render NavItem({ href: '/iniciativas-bottom-up/', content: 'Iniciativas Bottom-up' })}
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<div class="text-sm font-medium text-muted-foreground">O que é</div>
				<div class="flex flex-col gap-2">
					{@render NavItem({ href: '/metodologia-st4s/', content: 'Metodologia ST4S' })}
					{@render NavItem({
						href: '/metodologia-avaliacao-estrategica-ai2/',
						content: 'Metodologia de Avaliação Estratégica da AI²'
					})}
					{@render NavItem({ href: '/legislacao-nacional/', content: 'Legislação Nacional' })}
				</div>
			</div>
			<div class="flex flex-col gap-2">
				<div class="text-sm font-medium text-muted-foreground">Sobre a Equipa</div>
				<div class="flex flex-col gap-2">
					{@render NavItem({ href: '/coordenacao/', content: 'Coordenação' })}
					{@render NavItem({ href: '/equipa-peritos/', content: 'Equipa de Peritos' })}
				</div>
			</div>
		</div>
	</Popover.Content>
</Popover.Root>

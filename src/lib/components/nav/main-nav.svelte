<script lang="ts">
	import { resolve } from '$app/paths';
	import * as NavigationMenu from '$lib/components/ui/navigation-menu';
	import { navigationMenuTriggerStyle } from '$lib/components/ui/navigation-menu/navigation-menu-trigger.svelte';
	import type { HTMLAttributes } from 'svelte/elements';

	let {
		class: className
	}: {
		class?: string;
	} & HTMLAttributes<HTMLElement> = $props();
</script>

<NavigationMenu.Root class={className} viewport={false}>
	<NavigationMenu.List>
		<NavigationMenu.Item>
			<NavigationMenu.Link>
				{#snippet child()}
					<a href={resolve('/relatorios/')} class={navigationMenuTriggerStyle()}>Relatórios</a>
				{/snippet}
			</NavigationMenu.Link>
		</NavigationMenu.Item>
		<NavigationMenu.Item>
			<NavigationMenu.Trigger>Estratégia de Participação</NavigationMenu.Trigger>
			<NavigationMenu.Content>
				<ul class="grid w-[260px] gap-4 p-2">
					<li>
						<NavigationMenu.Link href={resolve('/participacao-publica/')}>
							Participação Pública
						</NavigationMenu.Link>
						<NavigationMenu.Link href={resolve('/metodologia-participacao-publica/')}>
							Metodologia de Participação Pública
						</NavigationMenu.Link>
						<NavigationMenu.Link href={resolve('/comissao-acompanhamento/')}>
							Comissão de Acompanhamento
						</NavigationMenu.Link>
						<NavigationMenu.Link href={resolve('/reunioes-entidades/')}>
							Reuniões com Entidades
						</NavigationMenu.Link>
						<NavigationMenu.Link href={resolve('/mesas-tematicas/')}
							>Mesas Temáticas</NavigationMenu.Link
						>
						<NavigationMenu.Link href={resolve('/conferencias-reunioes-descentralizadas/')}>
							Conferências e Reuniões Descentralizadas
						</NavigationMenu.Link>
						<NavigationMenu.Link href={resolve('/iniciativas-bottom-up/')}>
							Iniciativas Bottom-up
						</NavigationMenu.Link>
					</li>
				</ul>
			</NavigationMenu.Content>
		</NavigationMenu.Item>
		<NavigationMenu.Item>
			<NavigationMenu.Trigger>O que é</NavigationMenu.Trigger>
			<NavigationMenu.Content>
				<ul class="grid w-[280px] gap-4 p-2">
					<li>
						<NavigationMenu.Link href={resolve('/metodologia-st4s/')}
							>Metodologia ST4S</NavigationMenu.Link
						>
						<NavigationMenu.Link href={resolve('/metodologia-avaliacao-estrategica-ai2/')}>
							Metodologia de Avaliação Estratégica da AI²
						</NavigationMenu.Link>
						<NavigationMenu.Link href={resolve('/legislacao-nacional/')}>
							Legislação Nacional
						</NavigationMenu.Link>
					</li>
				</ul>
			</NavigationMenu.Content>
		</NavigationMenu.Item>
		<NavigationMenu.Item>
			<NavigationMenu.Trigger>Sobre a Equipa</NavigationMenu.Trigger>
			<NavigationMenu.Content>
				<ul class="grid w-[220px] gap-4 p-2">
					<li>
						<NavigationMenu.Link href={resolve('/coordenacao/')}>Coordenação</NavigationMenu.Link>
						<NavigationMenu.Link href={resolve('/equipa-peritos/')}
							>Equipa de Peritos</NavigationMenu.Link
						>
					</li>
				</ul>
			</NavigationMenu.Content>
		</NavigationMenu.Item>
	</NavigationMenu.List>
</NavigationMenu.Root>

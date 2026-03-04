<script lang="ts">
	import { asset } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { Button } from '$lib/components/ui/button';
	import * as Item from '$lib/components/ui/item';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.reports.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}

		<h2>Entregáveis</h2>
			<ul>
				<li>
					Documento com a <strong>metodologia de avaliação estratégica</strong> (<a
					href={asset('/docs/RelatMetod_PT.pdf')}
					target="_blank"
					rel="noreferrer">link</a>);
				</li>

			</ul>

		<h2>Outros Documentos</h2>

			<ul>
				<li>
				<strong>Relatório do Grupo de Trabalho de Análise do Ecossistema Nacional de Investigação e Inovação</strong>, criado nos termos do Despacho n.º 1994/2026, de 17 de fevereiro
				(<a
					href={asset('/docs/RelatGrupoTrab_PT.pdf')}
					target="_blank"
					rel="noreferrer">link</a>);
				</li>
			</ul>
		{:else}

			<h2>Deliverables</h2>
			<ul>
				<li>
					Document with the <strong>strategic assessment methodology</strong> (<a
					href={asset('/docs/RelatMetod_PT.pdf')}
					target="_blank"
					rel="noreferrer">link in Portuguese</a>);
				</li>

			</ul>

			<h2>Other Documents</h2>

			<ul>
				<li>
				<strong>Report of the Working Group on National R&D Ecosystem</strong>, created under Despacho n.º 1994/2026, de 17 of February
				(<a
					href={asset('/docs/RelatGrupoTrab_PT.pdf')}
					target="_blank"
					rel="noreferrer">link in Portuguese</a>);
				</li>

			</ul>
		{/if}
	</div>
</div>

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
					<strong>Relatório Final da Avaliação Estratégica</strong> (<a
						href={asset('/docs/RelatorioFinalConsultaPublica.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					<strong>Relatório Complementar - Relatório de Envolvimento e Participação Pública</strong>
					(<a
						href={asset('/docs/RelatorioEnvolvimentoParticipacaoPublica.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					<strong
						>Relatório Complementar - Proposta de sistema de monitorização e avaliação da AI²</strong
					>
					(<a
						href={asset('/docs/PropostaSistemaMonitorizacaoAvaliacao.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					Documento com a <strong>metodologia de avaliação estratégica</strong> (<a
						href={asset('/docs/RelatMetod_PT.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					Relatório de Focagem Estratégica - versão preliminar (<a
						href={asset('/docs/20260621_RELATÓRIO DE FOCAGEM ESTRATEGICA.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					Anexos do Relatório de Focagem Estratégica - versão preliminar (<a
						href={asset('/docs/20260621_RELATÓRIO DE FOCAGEM_Anexos.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					Relatório de Focagem Estratégica - versão final (<a
						href={asset('/docs/20260802_RELATORIO_FOCAGEM_ESTRATEGICA_FINAL_PT.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					Anexos do Relatório de Focagem Estratégica - versão final (<a
						href={asset('/docs/20260802_RELATORIO_FOCAGEM_ESTRATEGICA_ANEXOS_FINAL_PT.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					Quadro de Avaliação Estratégica - versão final (<a
						href={asset('/docs/20260802_QUADRO_AVALIACAO_ESTRATEGICA_FINAL_PT.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
			</ul>

			<h2>Outros Documentos</h2>

			<ul>
				<li>
					<strong
						>Relatório do Grupo de Trabalho de Análise do Ecossistema Nacional de Investigação e
						Inovação</strong
					>, criado nos termos do Despacho n.º 1994/2026, de 17 de fevereiro (<a
						href={asset('/docs/RelatGrupoTrab_PT.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
			</ul>
		{:else}
			<h2>Deliverables</h2>
			<ul>
				<li>
					<strong>Final Strategic Assessment Report</strong> (<a
						href={asset('/docs/RelatorioFinalConsultaPublica.pdf')}
						target="_blank"
						rel="noreferrer">link in Portuguese</a
					>);
				</li>
				<li>
					<strong>Complementary Report - Public Engagement and Participation Report</strong> (<a
						href={asset('/docs/RelatorioEnvolvimentoParticipacaoPublica.pdf')}
						target="_blank"
						rel="noreferrer">link in Portuguese</a
					>);
				</li>
				<li>
					<strong
						>Complementary Report - Proposal for a monitoring and evaluation system for AI²</strong
					>
					(<a
						href={asset('/docs/PropostaSistemaMonitorizacaoAvaliacao.pdf')}
						target="_blank"
						rel="noreferrer">link in Portuguese</a
					>);
				</li>
				<li>
					Document with the <strong>strategic assessment methodology</strong> (<a
						href={asset('/docs/RelatMetod_PT.pdf')}
						target="_blank"
						rel="noreferrer">link in Portuguese</a
					>);
				</li>
				<li>
					Strategic Focus Report - preliminary version (<a
						href={asset('/docs/20260621_RELATÓRIO DE FOCAGEM ESTRATEGICA.pdf')}
						target="_blank"
						rel="noreferrer">link in Portuguese</a
					>);
				</li>
				<li>
					Annexes to the Strategic Focus Report - preliminary version (<a
						href={asset('/docs/20260621_RELATÓRIO DE FOCAGEM_Anexos.pdf')}
						target="_blank"
						rel="noreferrer">link in Portuguese</a
					>);
				</li>
				<li>
					Strategic Focus Report - final version (<a
						href={asset('/docs/20260802_STRATEGIC_FOCUS_REPORT_FINAL_EN.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					Annexes to the Strategic Focus Report - final version (<a
						href={asset('/docs/20260802_STRATEGIC_FOCUS_REPORT_ANNEXES_FINAL_EN.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
				<li>
					Strategic Assessment Framework - final version (<a
						href={asset('/docs/20260802_STRATEGIC_ASSESSMENT_FRAMEWORK_FINAL_EN.pdf')}
						target="_blank"
						rel="noreferrer">link</a
					>);
				</li>
			</ul>

			<h2>Other Documents</h2>

			<ul>
				<li>
					<strong>Report of the Working Group on National R&D Ecosystem</strong>, created under
					Despacho n.º 1994/2026, de 17 of February (<a
						href={asset('/docs/RelatGrupoTrab_PT.pdf')}
						target="_blank"
						rel="noreferrer">link in Portuguese</a
					>);
				</li>
			</ul>
		{/if}
	</div>
</div>

<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.reports.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				No âmbito da Avaliação Estratégica da AI², está prevista a elaboração dos seguintes
				relatórios:
			</p>
			<ul>
				<li>
					Documento com a <strong>metodologia de avaliação estratégica</strong> (<a
						href="/docs/RelatMetod_PT.pdf"
						target="_blank"
						rel="noreferrer"
						>link</a
					>);
				</li>
				<li>
					<strong>Relatório de fatores críticos para a decisão (FCD)</strong>, incluindo o quadro de
					referência estratégico, o quadro de avaliação estratégica e a proposta do perímetro dos
					diálogos;
				</li>
				<li>
					<strong>Opções estratégicas</strong> para a definição da alocação orçamental plurianual e de domínios
					estratégicos;
				</li>
				<li>
					<strong>Resultados da avaliação estratégica das oportunidades e riscos, e recomendações</strong>;
				</li>
				<li><strong>Proposta de plano de monitorização e avaliação ex-post</strong>;</li>
				<li>
					<strong>Proposta preliminar</strong> da alocação orçamental das áreas de I&amp;D, dos domínios
					estratégicos e da UPI da AI², definição dos domínios estratégicos e respetiva justificação;
				</li>
				<li>
					<strong>Relatório final</strong>, integrando os contributos do CNCTI, do Conselho Científico
					e do Conselho de Administração da AI²;
				</li>
				<li>
					<strong>Relatório de consulta pública</strong> com a análise qualitativa e quantitativa dos contributos
					recebidos nos diálogos públicos, com apoio de ferramentas de IA, se aplicável.
				</li>
			</ul>
		{:else}
			<p>
				As part of the AI² Strategic Assessment, the following reports are planned:
			</p>
			<ul>
				<li>
					Document with the <strong>strategic assessment methodology</strong> (<a
						href="/docs/RelatMetod_PT.pdf"
						target="_blank"
						rel="noreferrer"
						>link</a
					>);
				</li>
				<li>
					<strong>Report on critical decision factors (CDF)</strong>, including the strategic reference
					framework, the strategic assessment framework and the proposed scope of the dialogues;
				</li>
				<li>
					<strong>Strategic options</strong> for defining the multi-annual budget allocation and strategic
					domains;
				</li>
				<li>
					<strong>Results of the strategic assessment of opportunities and risks, and recommendations</strong>;
				</li>
				<li><strong>Proposed monitoring and ex-post evaluation plan</strong>;</li>
				<li>
					<strong>Preliminary proposal</strong> for the budget allocation of AI²'s R&amp;D areas, strategic
					domains and UPI, definition of strategic domains and respective justification;
				</li>
				<li>
					<strong>Final report</strong>, integrating contributions from the CNCTI, the Scientific Council
					and the AI² Board of Directors;
				</li>
				<li>
					<strong>Public consultation report</strong> with qualitative and quantitative analysis of contributions
					received in public dialogues, with AI tool support where applicable.
				</li>
			</ul>
		{/if}
	</div>
</div>

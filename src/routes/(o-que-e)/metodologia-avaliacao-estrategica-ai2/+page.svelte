<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { Button } from '$lib/components/ui/button';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.strategicAssessmentMethodology.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A Avaliação Estratégica da AI² visa apoiar decisões sobre prioridades nacionais de
				investigação e inovação, incluindo:
			</p>
			<ul>
				<li>
					Alocação orçamental às áreas de I&amp;D, aos domínios estratégicos e à Unidade de Promoção
					da Inovação (UPI);
				</li>
				<li>
					Definição dos domínios estratégicos da AI², que podem incluir subdomínios específicos.
				</li>
			</ul>
			<p>
				O processo identifica opções estratégicas, avalia oportunidades e riscos, e sustenta a
				elaboração do contrato-programa plurianual da AI², respondendo a quatro questões centrais:
			</p>
			<ul>
				<li>Percentagem do orçamento a alocar às áreas de I&amp;D, domínios estratégicos e UPI.</li>
				<li>Número e definição dos domínios estratégicos.</li>
				<li>Distribuição orçamental entre domínios estratégicos.</li>
				<li>Distribuição orçamental entre áreas de I&amp;D.</li>
			</ul>
			<p>
				A metodologia foi construída com contributos de entidades do SNCTI, incorporando sugestões
				relevantes ao longo do processo.
			</p>
			<h2>{t('page.strategicAssessment.anchors')}</h2>
			<ul>
				<li>
					<strong>Objetivo:</strong> valorizar a investigação fundamental e aplicada, reforçar ligação entre
					conhecimento, inovação e valor económico, social, cultural e ambiental.
				</li>
				<li>
					<strong>Visão 2050:</strong> Portugal como país que gera talento e conhecimento, com sistema científico
					e de inovação dinâmico, interligado, competitivo e sustentável.
				</li>
				<li>
					<strong>Princípios:</strong> excelência, mérito e impacto; alinhamento nacional e internacional;
					transparência e participação; coerência e eficiência; responsabilidade e avaliação contínua.
				</li>
				<li>
					<strong>Pilares:</strong> orçamento plurianual estável; investigação fundamental; prioridades
					top-down; ligação investigação-inovação; infraestruturas; emprego científico e qualificação.
				</li>
			</ul>
			<h2>{t('page.strategicAssessment.phases')}</h2>
			<ol>
				<li>
					<strong>Focagem estratégica:</strong> definição participada das prioridades, construção do Quadro
					de Avaliação Estratégica com FCD, critérios e indicadores, e identificação de seis temas-chave.
				</li>
				<li>
					<strong>Identificação de opções estratégicas:</strong> definição participada de alternativas para
					alocação orçamental e domínios estratégicos, integrando contributos de mesas temáticas e discussões
					técnicas.
				</li>
				<li>
					<strong>Avaliação de oportunidades e riscos:</strong> análise de tendências, macropolíticas, evolução
					dos FCD, evidências de impacto e benchmarking internacional.
				</li>
				<li>
					<strong>Plano de monitorização e avaliação ex-post:</strong> sistema de indicadores de desempenho,
					resultados e impacto, frequência de reporte e mecanismos de acompanhamento.
				</li>
			</ol>
			<h2>{t('page.strategicAssessment.participation')}</h2>
			<p>A participação de atores relevantes é contínua, combinando:</p>
			<ul>
				<li>Consulta pública online e contributos em mesas temáticas e workshops.</li>
				<li>Interação com peritos e stakeholders do SNCTI e sociedade civil.</li>
				<li>Sessões descentralizadas por região, incluindo conferências e workshops abertos.</li>
			</ul>
		{:else}
			<p>
				The AI² Strategic Assessment aims to support decisions on national research and innovation
				priorities, including:
			</p>
			<ul>
				<li>
					Budget allocation to R&amp;D areas, strategic domains and the Innovation Promotion Unit
					(UPI);
				</li>
				<li>
					Definition of AI²'s strategic domains, which may include specific sub-domains.
				</li>
			</ul>
			<p>
				The process identifies strategic options, evaluates opportunities and risks, and supports the
				preparation of AI²'s multi-annual programme contract, addressing four central questions:
			</p>
			<ul>
				<li>Percentage of budget to allocate to R&amp;D areas, strategic domains and UPI.</li>
				<li>Number and definition of strategic domains.</li>
				<li>Budget distribution among strategic domains.</li>
				<li>Budget distribution among R&amp;D areas.</li>
			</ul>
			<p>
				Contributions from entities across the National Science, Technology and Innovation System,
				incorporating relevant suggestions throughout the process.
			</p>
			<h2>{t('page.strategicAssessment.anchors')}</h2>
			<ul>
				<li>
					<strong>Objective:</strong> to value basic and applied research, strengthening the link between
					knowledge, innovation and economic, social, cultural and environmental value.
				</li>
				<li>
					<strong>Vision 2050:</strong> Portugal as a country that generates talent and knowledge, with a dynamic,
					interconnected, competitive and sustainable scientific and innovation system.
				</li>
				<li>
					<strong>Principles:</strong> excellence, merit and impact; national and international alignment;
					transparency and participation; coherence and efficiency; accountability and continuous evaluation.
				</li>
				<li>
					<strong>Pillars:</strong> stable multi-annual budget; basic research; top-down priorities;
					research-innovation relationship; infrastructures; scientific employment and qualification.
				</li>
			</ul>
			<h2>{t('page.strategicAssessment.phases')}</h2>
			<ol>
				<li>
					<strong>Strategic focus:</strong> participatory definition of priorities, development of the Strategic
					Assessment Framework with CDFs, criteria and indicators, and identification of six key themes.
				</li>
				<li>
					<strong>Identification of strategic options:</strong> participatory definition of alternatives for
					budget allocation and strategic domains, integrating contributions from thematic roundtables and technical
					discussions.
				</li>
				<li>
					<strong>Assessment of opportunities and risks:</strong> analysis of trends, macro-policies, evolution
					of CDFs, impact evidence and international benchmarking.
				</li>
				<li>
					<strong>Monitoring and ex-post evaluation plan:</strong> system of performance, results and impact
					indicators, reporting frequency and monitoring mechanisms.
				</li>
			</ol>
			<h2>{t('page.strategicAssessment.participation')}</h2>
			<p>Participation by relevant stakeholders is continuous, combining:</p>
			<ul>
				<li>Online public consultation and contributions at thematic roundtables.</li>
				<li>Interaction with experts and stakeholders across the National Science, Technology and Innovation System and civil society.</li>
				<li>Decentralized sessions across the regions, including open conferences and workshops.</li>
			</ul>
		{/if}
		<div class="not-typography mt-10">
			<Button variant="outline" href="#" disabled>{t('page.strategicAssessment.viewDoc')}</Button>
		</div>
	</div>
</div>

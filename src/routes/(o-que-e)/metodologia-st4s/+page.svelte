<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.st4sMethodology.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A Avaliação Estratégica da AI² utiliza a metodologia ST4S - Strategic Thinking for
				Sustainability, desenvolvida pela Professora Maria do Rosário Partidário (Partidário, 2021)<sup
					>1</sup
				>. Esta abordagem combina pensamento sistémico, backcasting e participação pública ativa para
				apoiar decisões estratégicas de longo prazo.
			</p>
			<p>
				A metodologia começa por definir, de forma participada, o objetivo, a visão, os princípios e
				pilares estratégicos para o futuro da investigação e inovação em Portugal e, a partir daí,
				identifica caminhos estratégicos para os concretizar. Todo o processo decorre com envolvimento
				de peritos, atores relevantes e uma Comissão de Acompanhamento independente.
			</p>
			<h2>{t('page.st4s.threePhases')}</h2>
			<ol>
				<li>
					<strong>Focagem</strong>
					<p>
						Identificação do que é prioritário avaliar, definindo os Fatores Críticos para a Decisão
						(FCD) e o quadro de avaliação estratégica.
					</p>
				</li>
				<li>
					<strong>Avaliação de opções estratégicas</strong>
					<p>
						Análise das diferentes opções com base nas suas oportunidades e riscos, selecionando as
						que melhor contribuem para a visão e objetivos estabelecidos.
					</p>
				</li>
				<li>
					<strong>Diálogos contínuos</strong>
					<p>
						Interação permanente entre atores relevantes, garantindo aprendizagem, transparência e
						monitorização contínua ao longo das fases de decisão e implementação.
					</p>
				</li>
			</ol>
			<p>
				A metodologia integra uma abordagem participativa e híbrida, combinando contributos bottom-up
				com uma decisão final top-down, garantindo rigor técnico, envolvimento plural e orientação
				estratégica para a definição da alocação orçamental e dos domínios estratégicos da AI².
			</p>
			
			<hr />

			<p>
				<sup>1</sup>
				Partidário, M. R. (2021).
				<em>Strategic thinking for sustainability (ST4S) in strategic environmental assessment.</em>
				In <em>Handbook on strategic environmental assessment</em>
				(pp. 41-57). Edward Elgar Publishing.
			</p>
		{:else}
			<p>
				The AI² Strategic Assessment uses the ST4S methodology — Strategic Thinking for
				Sustainability — developed by Professor Maria do Rosário Partidário (Partidário, 2021)<sup
					>1</sup
				>. This approach combines systems thinking, backcasting and active public participation to
				support long-term strategic decisions.
			</p>
			<p>
				The methodology begins by defining, through a participatory process, the objective, vision,
				strategic principles and pillars for the future of research and innovation in Portugal, and
				from there identifies strategic pathways to achieve them. The entire process involves
				experts, relevant stakeholders and an independent Advisory Committee.
			</p>
			<h2>{t('page.st4s.threePhases')}</h2>
			<ol>
				<li>
					<strong>Focus</strong>
					<p>
						Identifying what is a priority to assess, defining the Critical Decision Factors (CDF) and
						the strategic assessment framework.
					</p>
				</li>
				<li>
					<strong>Assessment of strategic options</strong>
					<p>
						Analysis of the different options based on their opportunities and risks, selecting those
						that best contribute to the established vision and objectives.
					</p>
				</li>
				<li>
					<strong>Continuous dialogues</strong>
					<p>
						Permanent interaction among relevant stakeholders, ensuring learning, transparency and
						continuous monitoring throughout the decision-making and implementation phases.
					</p>
				</li>
			</ol>
			<p>
				The methodology integrates a participatory and hybrid approach, combining bottom-up
				contributions with a final top-down decision, ensuring technical rigour, plural involvement
				and strategic orientation for defining AI²'s budget allocation and strategic domains.
			</p>
			<hr />
			<p>
				<sup>1</sup>
				Partidário, M. R. (2021).
				<em>Strategic thinking for sustainability (ST4S) in strategic environmental assessment.</em>
				In <em>Handbook on strategic environmental assessment</em>
				(pp. 41-57). Edward Elgar Publishing.
			</p>
		{/if}
	</div>
</div>

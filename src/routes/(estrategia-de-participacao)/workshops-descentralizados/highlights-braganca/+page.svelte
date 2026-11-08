<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Highlights do workshop de Bragança' : 'Highlights from the Bragança workshop'} />
<div class="container my-12 md:my-24">
	<div class="typography">
		<p>
			<a href={resolve('/workshops-descentralizados/')}>
				{getLang() === 'pt'
					? '← Voltar aos workshops descentralizados'
					: '← Back to decentralised workshops'}
			</a>
		</p>
		<p>
			<em>
				{getLang() === 'pt'
					? 'síntese elaborada com recurso a uma ferramenta de inteligência artificial, com revisão posterior pela equipa'
					: 'summary prepared using an artificial intelligence tool, with subsequent review by the team'}
			</em>
		</p>
		{#if getLang() === 'pt'}
			<h4>Highlights do workshop de Bragança</h4>
						<p>Este workshop debruçou-se sobre o contexto da região de Trás-os-Montes e Alto Douro e teve quatro grupos de discussão.</p>
						<h5>1. Identificação de prioridades</h5>
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>Território forte em recursos naturais e endógenos (agro, biodiversidade, património natural e cultural), com potencial para cadeias de valor com maior valor acrescentado</li>
							<li>Existência de massa crítica científica e instituições de referência (UTAD, IPB), com capacidade de investigação relevante</li>
							<li>Proximidade entre atores e predisposição para cocriação entre academia, empresas e território</li>
							<li>Potencial de desenvolvimento de cadeias de valor associadas à bioeconomia, agroindústria e turismo de natureza</li>
							<li>Posição transfronteiriça, favorecendo cooperação com Espanha</li>
							<li>Qualidade de vida e características do território com potencial de atração de talento</li>
							<li>Capacidade de desenvolver abordagens experimentais, posicionando o território como “laboratório vivo do interior”</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>Dificuldade de atração e retenção de talento, apesar da base existente</li>
							<li>Subfinanciamento e inadequação dos instrumentos às especificidades do interior</li>
							<li>Fragmentação e fraca articulação entre atores, limitando a transferência de conhecimento</li>
							<li>Centralização das decisões e baixa capacidade de influência regional</li>
							<li>Fraca diversificação do tecido económico e reduzida capacidade de investimento em I&amp;D</li>
							<li>Déficits de planeamento estratégico e governação</li>
							<li>Condicionantes estruturais: despovoamento, envelhecimento, baixa densidade e custos de contexto associados à interioridade</li>
							<li>Limitações ao nível de infraestruturas e capacidade organizativa</li>
						</ul>
						<h5>2. Temas críticos</h5>
						<ul>
							<li>
								<strong>Recursos endógenos e desenvolvimento económico</strong>
								<p>
									Território com potencial para se afirmar como “laboratório vivo do interior”, embora com
									necessidade de valorizar ativos territoriais, potenciando cadeias de valor inovadoras
								</p>
							</li>
							<li>
								<strong>Recursos humanos e talento</strong>
								<p>
									Dificuldade de fixação e renovação de capital humano qualificado, mas potencial para atração de
									talento pelas características do território e qualidade de vida proporcionada
								</p>
							</li>
							<li>
								<strong>Financiamento e instrumentos de apoio</strong>
								<p>Necessidade de modelos adaptados ao interior, com maior continuidade e diferenciação</p>
							</li>
							<li>
								<strong>Transferência de conhecimento e articulação do ecossistema</strong>
								<p>Fragilidades na ligação entre ciência, empresas e território. Posição transfronteiriça favorece a cooperação com Espanha.</p>
							</li>
							<li>
								<strong>Governação e coesão territorial</strong>
								<p>Necessidade de maior descentralização, coordenação e planeamento estratégico</p>
							</li>
						</ul>
						<h5>3. Síntese</h5>
						<ul>
							<li>Existência de forte potencial baseado em recursos e conhecimento instalado, com capacidade de diferenciação territorial e vantagem pela posição transfronteiriça</li>
							<li>Persistência de bloqueios (talento, financiamento, articulação, governação)</li>
						</ul>
		{:else}
			<h4>Highlights from the Bragança workshop</h4>
						<p>This workshop focused on the Trás-os-Montes and Alto Douro region and included four discussion groups.</p>
						<h5>1. Identification of priorities</h5>
						<p><strong>Strengths</strong></p>
						<ul>
							<li>Territory strong in natural and endogenous resources (agriculture, biodiversity, natural and cultural heritage), with potential for higher value-added value chains</li>
							<li>Existence of scientific critical mass and reference institutions (UTAD, IPB), with relevant research capacity</li>
							<li>Proximity between actors and willingness for co-creation between academia, companies and the territory</li>
							<li>Potential to develop value chains linked to the bioeconomy, agroindustry and nature tourism</li>
							<li>Cross-border position, favouring cooperation with Spain</li>
							<li>Quality of life and territorial characteristics with potential to attract talent</li>
							<li>Capacity to develop experimental approaches, positioning the territory as an “interior living lab”</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>Difficulty attracting and retaining talent, despite the existing base</li>
							<li>Underfunding and inadequate instruments for the specificities of the interior</li>
							<li>Fragmentation and weak coordination between actors, limiting knowledge transfer</li>
							<li>Centralisation of decision-making and low regional influence capacity</li>
							<li>Low diversification of the economic fabric and limited capacity for R&amp;D investment</li>
							<li>Deficits in strategic planning and governance</li>
							<li>Structural constraints: depopulation, ageing, low density and context costs associated with interiority</li>
							<li>Limitations in infrastructure and organisational capacity</li>
						</ul>
						<h5>2. Critical themes</h5>
						<ul>
							<li>
								<strong>Endogenous resources and economic development</strong>
								<p>
									Territory with potential to position itself as an “interior living lab”, although it needs to
									valorise territorial assets and foster innovative value chains
								</p>
							</li>
							<li>
								<strong>Human resources and talent</strong>
								<p>
									Difficulty retaining and renewing qualified human capital, but potential to attract talent
									through the characteristics of the territory and the quality of life it provides
								</p>
							</li>
							<li>
								<strong>Funding and support instruments</strong>
								<p>Need for models adapted to the interior, with greater continuity and differentiation</p>
							</li>
							<li>
								<strong>Knowledge transfer and ecosystem coordination</strong>
								<p>Weak links between science, companies and the territory. The cross-border position favours cooperation with Spain.</p>
							</li>
							<li>
								<strong>Governance and territorial cohesion</strong>
								<p>Need for greater decentralisation, coordination and strategic planning</p>
							</li>
						</ul>
						<h5>3. Summary</h5>
						<ul>
							<li>Existence of strong potential based on resources and installed knowledge, with territorial differentiation capacity and an advantage from the cross-border position</li>
							<li>Persistent barriers (talent, funding, coordination, governance)</li>
						</ul>
		{/if}
	</div>
</div>

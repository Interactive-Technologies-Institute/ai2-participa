<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Highlights do workshop do Funchal' : 'Highlights from the Funchal workshop'} />
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
			<h4>Highlights do workshop do Funchal</h4>
						<p>Este workshop debruçou-se sobre o contexto da Região Autónoma da Madeira e teve três grupos de discussão.</p>
						<h5>1. Identificação de prioridades</h5>
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>Pequena dimensão e proximidade entre atores, facilitando articulação, cooperação e rápida transferência de conhecimento</li>
							<li>
								Condições para afirmação como “laboratório vivo”, permitindo testar soluções e projetos-piloto em
								pequena escala com potencial de replicação
							</li>
							<li>Forte base de recursos naturais e endógenos, com destaque para o mar, biodiversidade, património natural e cultural</li>
							<li>Potencial de desenvolvimento da economia azul, circular e bioeconomia, bem como valorização do património imaterial</li>
							<li>Existência de infraestruturas científicas relevantes e capacidade instalada em áreas como turismo, saúde e ambiente</li>
							<li>Multidisciplinaridade e sinergias intersectoriais (turismo, saúde, ambiente, cultura, digital)</li>
							<li>Possibilidade de acesso a fundos europeus específicos decorrentes do estatuto de região ultraperiférica</li>
							<li>Qualidade de vida e contexto territorial com potencial de atração de talento</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>Dificuldade de atração e retenção de talento, incluindo escassez e baixa diversidade de doutorados</li>
							<li>Limitações ao nível das carreiras científicas e condições de trabalho, incluindo habitação e estabilidade</li>
							<li>Fragmentação e fraca articulação entre academia, empresas e restantes atores, dificultando a transferência de conhecimento</li>
							<li>Subfinanciamento e inadequação dos instrumentos, com assimetrias face ao contexto nacional e pouca adaptação à realidade insular</li>
							<li>Dependência de financiamento concentrado em poucos domínios (“falta de diversificação”)</li>
							<li>Défices de planeamento e estratégia de médio/longo prazo</li>
							<li>Problemas de organização e gestão (infraestruturas dispersas, capacidade administrativa limitada)</li>
							<li>Falta de valorização e mapeamento de ativos intangíveis (ex. património imaterial)</li>
							<li>Condicionantes estruturais: insularidade, custos logísticos, baixa massa crítica e especialização económica limitada</li>
						</ul>
						<h5>2. Temas críticos</h5>
						<ul>
							<li>
								<strong>Recursos humanos e talento</strong>
								<p>Insuficiente massa crítica e dificuldade de retenção, apesar de existência de competências relevantes e potencial de atração</p>
							</li>
							<li>
								<strong>Financiamento e instrumentos de apoio</strong>
								<p>Necessidade de instrumentos adaptados à realidade ultraperiférica, com maior previsibilidade e diversificação</p>
							</li>
							<li>
								<strong>Transferência de conhecimento e articulação do ecossistema</strong>
								<p>
									Fragilidade nas ligações entre academia, empresas e sociedade limita o impacto do conhecimento
									produzido, embora a pequena dimensão e proximidade entre os atores possa potenciar a articulação
									e a transferência de conhecimento
								</p>
							</li>
							<li>
								<strong>Valorização dos recursos naturais e endógenos e “laboratório vivo”</strong>
								<p>
									Forte potencial de valorização do mar, da biodiversidade e do património natural e imaterial,
									associado ao desenvolvimento da economia azul/circular e da bioeconomia, com capacidade de
									experimentação no território
								</p>
							</li>
							<li>
								<strong>Governação e planeamento estratégico</strong>
								<p>Necessidade de reforço da coordenação, definição de estratégia integrada e melhoria da organização do sistema</p>
							</li>
						</ul>
						<h5>3. Síntese</h5>
						<ul>
							<li>Território com vantagens estruturais (escala, proximidade, recursos, laboratório vivo) e elevado potencial para investigação e inovação</li>
							<li>Persistência de bloqueios (talento, financiamento, coordenação) que limitam esse potencial</li>
						</ul>
		{:else}
			<h4>Highlights from the Funchal workshop</h4>
						<p>This workshop focused on the Autonomous Region of Madeira and included three discussion groups.</p>
						<h5>1. Identification of priorities</h5>
						<p><strong>Strengths</strong></p>
						<ul>
							<li>Small scale and proximity between actors, facilitating coordination, cooperation and rapid knowledge transfer</li>
							<li>Conditions to position the region as a “living lab”, allowing solutions and pilot projects to be tested at small scale with replication potential</li>
							<li>Strong base of natural and endogenous resources, particularly the sea, biodiversity, natural and cultural heritage</li>
							<li>Potential to develop the blue economy, circular economy and bioeconomy, as well as to valorise intangible heritage</li>
							<li>Existence of relevant scientific infrastructures and installed capacity in areas such as tourism, health and environment</li>
							<li>Multidisciplinarity and cross-sector synergies (tourism, health, environment, culture, digital)</li>
							<li>Possibility of accessing specific European funds due to the status of outermost region</li>
							<li>Quality of life and territorial context with potential to attract talent</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>Difficulty attracting and retaining talent, including scarcity and low diversity of PhD holders</li>
							<li>Limitations in scientific careers and working conditions, including housing and stability</li>
							<li>Fragmentation and weak coordination between academia, companies and other actors, hindering knowledge transfer</li>
							<li>Underfunding and inadequate instruments, with asymmetries compared with the national context and little adaptation to island realities</li>
							<li>Dependence on funding concentrated in a few domains (“lack of diversification”)</li>
							<li>Deficits in medium/long-term planning and strategy</li>
							<li>Organisation and management problems (dispersed infrastructures, limited administrative capacity)</li>
							<li>Lack of valorisation and mapping of intangible assets (e.g. intangible heritage)</li>
							<li>Structural constraints: insularity, logistics costs, low critical mass and limited economic specialisation</li>
						</ul>
						<h5>2. Critical themes</h5>
						<ul>
							<li>
								<strong>Human resources and talent</strong>
								<p>Insufficient critical mass and difficulty retaining talent, despite relevant competences and potential for attraction</p>
							</li>
							<li>
								<strong>Funding and support instruments</strong>
								<p>Need for instruments adapted to the outermost region reality, with greater predictability and diversification</p>
							</li>
							<li>
								<strong>Knowledge transfer and ecosystem coordination</strong>
								<p>
									Weak links between academia, companies and society limit the impact of the knowledge produced,
									although the small scale and proximity between actors may strengthen coordination and knowledge
									transfer
								</p>
							</li>
							<li>
								<strong>Valorisation of natural and endogenous resources and “living lab”</strong>
								<p>
									Strong potential to valorise the sea, biodiversity and natural and intangible heritage, linked
									to the development of the blue/circular economy and bioeconomy, with capacity for
									experimentation in the territory
								</p>
							</li>
							<li>
								<strong>Governance and strategic planning</strong>
								<p>Need to strengthen coordination, define an integrated strategy and improve system organisation</p>
							</li>
						</ul>
						<h5>3. Summary</h5>
						<ul>
							<li>Territory with structural advantages (scale, proximity, resources, living lab) and high potential for research and innovation</li>
							<li>Persistent barriers (talent, funding, coordination) limiting that potential</li>
						</ul>
		{/if}
	</div>
</div>

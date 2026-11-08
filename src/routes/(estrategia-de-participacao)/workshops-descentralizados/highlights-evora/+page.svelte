<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Highlights do workshop de Évora' : 'Highlights from the Évora workshop'} />
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
			<h4>Highlights do workshop de Évora</h4>
						<p>Este workshop debruçou-se sobre o contexto da região do Alentejo e teve quatro grupos de discussão.</p>
						<h5>1. Identificação de prioridades</h5>
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								Recursos naturais e endógenos (agro, montado, água, mar, energia, património cultural), com
								potencial de valorização científica e económica
							</li>
							<li>
								Potencial de afirmação do território como “laboratório vivo” para experimentação e projetos-piloto
								(transição climática, energia, saúde, inovação social)
							</li>
							<li>Massa crítica científica e infraestruturas de I&amp;D, incluindo em áreas de especialização relevantes</li>
							<li>
								Potencial de articulação e cooperação favorecido pela escala regional (proximidade entre atores,
								redes colaborativas)
							</li>
							<li>
								Oportunidades emergentes associadas a novas áreas tecnológicas (IA, digitalização, bioeconomia) e
								à valorização de cadeias de valor regionais
							</li>
							<li>Potencial de mobilização de fundos e instrumentos de financiamento para projetos estratégicos</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>
								Dificuldade de atração e retenção de talento, associada a carreiras precárias e condições
								territoriais pouco atrativas
							</li>
							<li>
								Fragmentação e fraca articulação entre academia, empresas, administração e sociedade, limitando a
								transferência de conhecimento
							</li>
							<li>
								Subfinanciamento estrutural e inadequação dos instrumentos às especificidades do tecido económico
								regional - forte dependência de ciclos curtos
							</li>
							<li>Fragilidades de governação/coordenação e ausência de estratégia regional integrada</li>
							<li>Baixa incorporação de conhecimento na economia, com reduzida inovação empresarial e poucas spinoffs</li>
							<li>Condicionantes estruturais do território: despovoamento, envelhecimento, baixa densidade e assimetrias internas</li>
							<li>Burocracia e complexidade administrativa, dificultando acesso a financiamento e implementação de projetos</li>
						</ul>
						<h5>2. Temas críticos</h5>
						<ul>
							<li>
								<strong>Recursos humanos e talento</strong>
								<p>
									Existência de massa crítica qualificada, mas com dificuldades de atração e retenção de talento,
									associada a carreiras precárias e condições territoriais pouco atrativas
								</p>
							</li>
							<li>
								<strong>Financiamento e instrumentos de apoio</strong>
								<p>
									Subfinanciamento estrutural e inadequação dos instrumentos às especificidades do tecido
									económico regional, apesar do potencial de mobilização de fundos e instrumentos de financiamento
									para projetos estratégicos
								</p>
							</li>
							<li>
								<strong>Transferência de conhecimento e cadeia de valor</strong>
								<p>
									Transferência de conhecimento limitada pela fragmentação e fraca articulação entre os
									diferentes atores, mas potencial para valorização de cadeias de valor por via de oportunidades
									emergentes associadas a áreas tecnológicas
								</p>
							</li>
							<li>
								<strong>Valorização dos recursos endógenos e “laboratório vivo”</strong>
								<p>
									Elevado potencial científico e económico para soluções inovadoras baseadas nos recursos
									naturais e endógenos e para a afirmação do território como “laboratório vivo”
								</p>
							</li>
							<li>
								<strong>Governação e articulação territorial</strong>
								<p>Necessidade de estratégia regional e de aproveitamento do potencial de redes colaborativas à escala regional</p>
							</li>
						</ul>
						<h5>3. Síntese</h5>
						<ul>
							<li>Recursos endógenos e capacidades posicionam o Alentejo como território com potencial para investigação e inovação</li>
							<li>
								Persistência de bloqueios estruturais (talento, financiamento, articulação e governação) e
								condicionantes territoriais (envelhecimento, desertificação e assimetrias) limitam esse potencial
							</li>
						</ul>
		{:else}
			<h4>Highlights from the Évora workshop</h4>
						<p>This workshop focused on the Alentejo region and included four discussion groups.</p>
						<h5>1. Identification of priorities</h5>
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								Natural and endogenous resources (agriculture, cork oak landscape, water, sea, energy, cultural
								heritage), with potential for scientific and economic valorisation
							</li>
							<li>
								Potential for the territory to position itself as a “living lab” for experimentation and pilot
								projects (climate transition, energy, health, social innovation)
							</li>
							<li>Scientific critical mass and R&amp;D infrastructures, including in relevant areas of specialisation</li>
							<li>Potential for coordination and cooperation supported by the regional scale (proximity between actors, collaborative networks)</li>
							<li>
								Emerging opportunities linked to new technological areas (AI, digitalisation, bioeconomy) and to
								the valorisation of regional value chains
							</li>
							<li>Potential to mobilise funds and funding instruments for strategic projects</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>Difficulty attracting and retaining talent, linked to precarious careers and less attractive territorial conditions</li>
							<li>
								Fragmentation and weak coordination between academia, companies, administration and society,
								limiting knowledge transfer
							</li>
							<li>Structural underfunding and instruments poorly suited to the regional economic fabric - strong dependence on short cycles</li>
							<li>Governance/coordination weaknesses and absence of an integrated regional strategy</li>
							<li>Low incorporation of knowledge into the economy, with limited business innovation and few spinoffs</li>
							<li>Structural territorial constraints: depopulation, ageing, low density and internal asymmetries</li>
							<li>Bureaucracy and administrative complexity, hindering access to funding and project implementation</li>
						</ul>
						<h5>2. Critical themes</h5>
						<ul>
							<li>
								<strong>Human resources and talent</strong>
								<p>
									Existence of qualified critical mass, but with difficulties attracting and retaining talent,
									linked to precarious careers and less attractive territorial conditions
								</p>
							</li>
							<li>
								<strong>Funding and support instruments</strong>
								<p>
									Structural underfunding and instruments poorly suited to the regional economic fabric, despite
									the potential to mobilise funds and funding instruments for strategic projects
								</p>
							</li>
							<li>
								<strong>Knowledge transfer and value chain</strong>
								<p>
									Knowledge transfer limited by fragmentation and weak coordination between the different actors,
									but with potential to valorise value chains through emerging opportunities linked to
									technological areas
								</p>
							</li>
							<li>
								<strong>Valorisation of endogenous resources and “living lab”</strong>
								<p>
									High scientific and economic potential for innovative solutions based on natural and endogenous
									resources and for positioning the territory as a “living lab”
								</p>
							</li>
							<li>
								<strong>Governance and territorial coordination</strong>
								<p>Need for a regional strategy and for making use of the potential of regional collaborative networks</p>
							</li>
						</ul>
						<h5>3. Summary</h5>
						<ul>
							<li>Endogenous resources and capacities position Alentejo as a territory with potential for research and innovation</li>
							<li>
								Persistent structural barriers (talent, funding, coordination and governance) and territorial
								constraints (ageing, desertification and asymmetries) limit that potential
							</li>
						</ul>
		{/if}
	</div>
</div>

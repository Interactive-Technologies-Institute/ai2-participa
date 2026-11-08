<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Highlights do workshop de Coimbra' : 'Highlights from the Coimbra workshop'} />
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
			<h4>Highlights do workshop de Coimbra</h4>
						<p>Este workshop debruçou-se sobre o contexto da região Centro e teve quatro grupos de discussão.</p>
						<h5>1. Identificação de prioridades</h5>
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>Forte base científica e académica, com produção de conhecimento relevante e capacidade em áreas emergentes e interdisciplinares</li>
							<li>Existência de ecossistemas e redes colaborativas em domínios específicos (ex. envelhecimento ativo) e potencial de cocriação</li>
							<li>Recursos humanos qualificados e capacidade de atração de talento, apoiada pela qualidade de programas doutorais</li>
							<li>Qualidade de vida e características territoriais com potencial de atratividade</li>
							<li>Presença de clusters e áreas estratégicas regionais, incluindo matérias-primas e valorização de recursos endógenos</li>
							<li>Centralidade geográfica e potencial de articulação inter-regional</li>
							<li>Capacidade para desenvolver “laboratórios vivos”, sobretudo em áreas como saúde e qualidade de vida</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>Fragmentação do sistema de I&amp;I e fraca articulação entre atores</li>
							<li>Dificuldades na transferência de conhecimento para o setor não académico</li>
							<li>Dificuldade de retenção de talento e fragilidade das carreiras científicas</li>
							<li>Excesso de burocracia e rigidez regulamentar</li>
							<li>Fraco tecido empresarial, com limitada capacidade de absorção de conhecimento</li>
							<li>Centralização das decisões e desalinhamento com políticas nacionais</li>
							<li>Baixo impacto da investigação, apesar da elevada produção científica</li>
							<li>Problemas de comunicação e articulação interna no ecossistema</li>
						</ul>
						<h5>2. Temas críticos</h5>
						<ul>
							<li>
								<strong>Ciência e investigação</strong>
								<p>Forte capacidade científica instalada, mas com dificuldades na transferência e impacto do conhecimento</p>
							</li>
							<li>
								<strong>Ecossistema colaborativo</strong>
								<p>
									Coexistem ecossistemas e redes colaborativas com a fragmentação institucional e a necessidade
									de reforçar articulação entre academia, empresas e sociedade
								</p>
							</li>
							<li>
								<strong>Recursos humanos e talento</strong>
								<p>Recursos humanos qualificados e capacidade de atração de talento, embora haja dificuldade de retenção e ausência de percursos de carreira atrativos</p>
							</li>
							<li>
								<strong>Financiamento e investimento estratégico</strong>
								<p>Necessidade de maior estabilidade, previsibilidade e adequação dos instrumentos</p>
							</li>
							<li>
								<strong>Governação e planeamento</strong>
								<p>Desalinhamento das políticas nacionais e excessiva centralização das decisões, não obstante o posicionamento geográfico estratégico para coordenação inter-regional</p>
							</li>
						</ul>
						<h5>3. Síntese</h5>
						<ul>
							<li>Forte capacidade científica, potencial de especialização e de valorização de recursos endógenos</li>
							<li>Persistência de bloqueios (fragmentação, financiamento, talento, articulação)</li>
						</ul>
		{:else}
			<h4>Highlights from the Coimbra workshop</h4>
						<p>This workshop focused on the Centre region and included four discussion groups.</p>
						<h5>1. Identification of priorities</h5>
						<p><strong>Strengths</strong></p>
						<ul>
							<li>Strong scientific and academic base, with relevant knowledge production and capacity in emerging and interdisciplinary areas</li>
							<li>Existence of collaborative ecosystems and networks in specific domains (e.g. active ageing) and potential for co-creation</li>
							<li>Qualified human resources and capacity to attract talent, supported by the quality of doctoral programmes</li>
							<li>Quality of life and territorial characteristics with potential for attractiveness</li>
							<li>Presence of clusters and regional strategic areas, including raw materials and valorisation of endogenous resources</li>
							<li>Geographical centrality and potential for interregional coordination</li>
							<li>Capacity to develop “living labs”, especially in areas such as health and quality of life</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>Fragmentation of the R&amp;I system and weak coordination between actors</li>
							<li>Difficulties in transferring knowledge to the non-academic sector</li>
							<li>Difficulty retaining talent and fragile scientific careers</li>
							<li>Excessive bureaucracy and regulatory rigidity</li>
							<li>Weak business fabric, with limited capacity to absorb knowledge</li>
							<li>Centralisation of decision-making and misalignment with national policies</li>
							<li>Low impact of research, despite high scientific output</li>
							<li>Problems of communication and internal coordination within the ecosystem</li>
						</ul>
						<h5>2. Critical themes</h5>
						<ul>
							<li>
								<strong>Science and research</strong>
								<p>Strong installed scientific capacity, but with difficulties in knowledge transfer and impact</p>
							</li>
							<li>
								<strong>Collaborative ecosystem</strong>
								<p>
									Collaborative ecosystems and networks coexist with institutional fragmentation and the need to
									strengthen coordination between academia, companies and society
								</p>
							</li>
							<li>
								<strong>Human resources and talent</strong>
								<p>Qualified human resources and capacity to attract talent, although there are difficulties retaining talent and a lack of attractive career paths</p>
							</li>
							<li>
								<strong>Funding and strategic investment</strong>
								<p>Need for greater stability, predictability and adequacy of instruments</p>
							</li>
							<li>
								<strong>Governance and planning</strong>
								<p>Misalignment of national policies and excessive centralisation of decision-making, despite the strategic geographical position for interregional coordination</p>
							</li>
						</ul>
						<h5>3. Summary</h5>
						<ul>
							<li>Strong scientific capacity, potential for specialisation and valorisation of endogenous resources</li>
							<li>Persistent barriers (fragmentation, funding, talent, coordination)</li>
						</ul>
		{/if}
	</div>
</div>

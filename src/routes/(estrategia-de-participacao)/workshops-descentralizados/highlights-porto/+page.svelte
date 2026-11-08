<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Highlights do workshop do Porto' : 'Highlights from the Porto workshop'} />
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
			<h4>Highlights do workshop do Porto</h4>
						<p>Este workshop debruçou-se sobre o contexto da região Norte e teve quatro grupos de discussão.</p>
						<h5>1. Identificação de prioridades</h5>
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>Forte massa crítica científica e tecnológica, com universidades e centros de I&amp;D de referência</li>
							<li>Ecossistema empresarial dinâmico, com tradição industrial, capacidade exportadora e emergência de start-ups</li>
							<li>Elevada proximidade e diversidade de atores, favorecendo cocriação e multidisciplinaridade</li>
							<li>Forte dotação de recursos endógenos (agro, mar, património cultural), com potencial de valorização económica</li>
							<li>Posicionamento geoestratégico atlântico e transfronteiriço, com ligações à Galiza e redes europeias</li>
							<li>Potencial em áreas emergentes: digitalização, IA, economia verde/circular, economia azul, saúde e indústrias criativas</li>
							<li>Capacidade instalada para atuar como “laboratório vivo” à escala regional, com condições para testar e escalar soluções</li>
							<li>Acesso a instrumentos de financiamento diversificados (nacionais, europeus e privados)</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>Fragmentação do ecossistema e insuficiente articulação entre atores</li>
							<li>Dificuldade de transferência de conhecimento para o tecido empresarial, sobretudo PME</li>
							<li>Subfinanciamento e inadequação dos instrumentos, pouco ajustados à realidade regional</li>
							<li>Excesso de burocracia e complexidade nos mecanismos de apoio</li>
							<li>Centralização das decisões, limitando a capacidade de definição estratégica regional</li>
							<li>Baixa incorporação de conhecimento na economia, com reduzido impacto de I&amp;D</li>
							<li>Falta de escala em alguns domínios estratégicos, dificultando competitividade internacional</li>
							<li>Desigualdades internas (litoral vs interior) e fraca coesão territorial</li>
							<li>Limitações na atração e retenção de talento, apesar da base existente</li>
						</ul>
						<h5>2. Temas críticos</h5>
						<ul>
							<li>
								<strong>Recursos endógenos e valorização económica</strong>
								<p>Necessidade de estruturar cadeias de valor baseadas nos ativos do território (agro, mar, cultura) que têm forte potencial de valorização económica</p>
							</li>
							<li>
								<strong>Recursos humanos e talento</strong>
								<p>Massa crítica científica forte, mas com desafios de fixação e valorização de capital humano qualificado</p>
							</li>
							<li>
								<strong>Financiamento e instrumentos de apoio</strong>
								<p>Necessidade de maior adequação, previsibilidade e diversificação, apesar do acesso a fontes diversificadas públicas e privadas, nacionais e europeias</p>
							</li>
							<li>
								<strong>Transferência de conhecimento e articulação do ecossistema</strong>
								<p>
									Fraca articulação entre diferentes atores e reduzido impacto I&amp;D na economia. A elevada
									proximidade e diversidade de atores favorece a cooperação e o posicionamento geoestratégico
									potencia participação em redes europeias
								</p>
							</li>
							<li>
								<strong>Governação e coesão territorial</strong>
								<p>Capacidade estratégica regional limitada por excessiva centralização</p>
							</li>
						</ul>
						<h5>3. Síntese</h5>
						<ul>
							<li>Elevado potencial suportado por capital humano, conhecimento e tecido empresarial</li>
							<li>Persistência de bloqueios (fragmentação, financiamento, governação, escala)</li>
						</ul>
		{:else}
			<h4>Highlights from the Porto workshop</h4>
						<p>This workshop focused on the North region and included four discussion groups.</p>
						<h5>1. Identification of priorities</h5>
						<p><strong>Strengths</strong></p>
						<ul>
							<li>Strong scientific and technological critical mass, with universities and reference R&amp;D centres</li>
							<li>Dynamic business ecosystem, with industrial tradition, export capacity and emerging start-ups</li>
							<li>High proximity and diversity of actors, favouring co-creation and multidisciplinarity</li>
							<li>Strong endowment of endogenous resources (agriculture, sea, cultural heritage), with potential for economic valorisation</li>
							<li>Atlantic and cross-border geostrategic positioning, with links to Galicia and European networks</li>
							<li>Potential in emerging areas: digitalisation, AI, green/circular economy, blue economy, health and creative industries</li>
							<li>Installed capacity to act as a regional “living lab”, with conditions to test and scale solutions</li>
							<li>Access to diversified funding instruments (national, European and private)</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>Fragmentation of the ecosystem and insufficient coordination between actors</li>
							<li>Difficulty transferring knowledge to the business fabric, especially SMEs</li>
							<li>Underfunding and inadequate instruments, poorly adjusted to the regional reality</li>
							<li>Excessive bureaucracy and complexity in support mechanisms</li>
							<li>Centralisation of decision-making, limiting regional strategic definition capacity</li>
							<li>Low incorporation of knowledge into the economy, with reduced R&amp;D impact</li>
							<li>Lack of scale in some strategic domains, hindering international competitiveness</li>
							<li>Internal inequalities (coast vs interior) and weak territorial cohesion</li>
							<li>Limitations in attracting and retaining talent, despite the existing base</li>
						</ul>
						<h5>2. Critical themes</h5>
						<ul>
							<li>
								<strong>Endogenous resources and economic valorisation</strong>
								<p>Need to structure value chains based on the territory's assets (agriculture, sea, culture), which have strong economic valorisation potential</p>
							</li>
							<li>
								<strong>Human resources and talent</strong>
								<p>Strong scientific critical mass, but challenges in retaining and valuing qualified human capital</p>
							</li>
							<li>
								<strong>Funding and support instruments</strong>
								<p>Need for greater adequacy, predictability and diversification, despite access to diversified public and private, national and European sources</p>
							</li>
							<li>
								<strong>Knowledge transfer and ecosystem coordination</strong>
								<p>
									Weak coordination between different actors and limited R&amp;D impact on the economy. The high
									proximity and diversity of actors favours cooperation and the geostrategic position strengthens
									participation in European networks
								</p>
							</li>
							<li>
								<strong>Governance and territorial cohesion</strong>
								<p>Regional strategic capacity limited by excessive centralisation</p>
							</li>
						</ul>
						<h5>3. Summary</h5>
						<ul>
							<li>High potential supported by human capital, knowledge and the business fabric</li>
							<li>Persistent barriers (fragmentation, funding, governance, scale)</li>
						</ul>
		{/if}
	</div>
</div>

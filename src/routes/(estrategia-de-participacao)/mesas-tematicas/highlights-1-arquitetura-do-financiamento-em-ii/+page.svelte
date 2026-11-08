<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Arquitetura do Financiamento em I&I' : 'Architecture of R&I Funding'} />
<div class="container my-12 md:my-24">
	<div class="typography">
		<p>
			<a href={resolve('/mesas-tematicas/')}>
				{getLang() === 'pt' ? '← Voltar às mesas temáticas' : '← Back to thematic tables'}
			</a>
		</p>
		<p>
			<em>
				{getLang() === 'pt'
					? 'elaborado com recurso a IA, com revisão posterior pelos peritos da equipa da Avaliação Estratégica'
					: 'prepared using AI, with subsequent review by the experts of the Strategic Assessment team'}
			</em>
		</p>
		{#if getLang() === 'pt'}
			<h3>Mesa temática “Arquitetura do financiamento em I&amp;I” (23 de abril, 10h)</h3>
			
						<p>
							<strong>Equilíbrio base-competitivo vs. instabilidade sistémica.</strong> Reconhecimento da necessidade
							de combinar financiamento estável e competitivo, coexistindo com imprevisibilidade, ciclos desalinhados
							e utilização recorrente do financiamento competitivo para cobrir custos estruturais, o que gera
							instabilidade sistémica e dificulta o planeamento estratégico.
						</p>
						<p>
							<strong>Integração do sistema vs. fragmentação de governação.</strong> Ambição de articulação
							entre ciência, inovação e financiamento público/privado, mas marcada por “três mundos paralelos”
							(ensino superior, investigação, inovação), instrumentos desconectados e em alguns casos, pouco
							conhecidos ou subutilizados pelos atores do sistema, contribuindo para uma fraca continuidade
							ao longo da cadeia de valor do conhecimento, com coordenação insuficiente entre lógicas e fontes
							de financiamento.
						</p>
						<p>
							<strong
								>Diversificação e mobilização de financiamento vs. baixa eficácia dos mecanismos.</strong
							>
							Potencial de alavancagem de financiamento privado e europeu, mas limitado por incentivos desalinhados,
							baixo compromisso e fraca participação efetiva das empresas e ineficiências operacionais.
						</p>
			
						<h4>1) Modelo de financiamento: equilíbrio necessário vs. instabilidade estrutural</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>Existe um consenso forte sobre a necessidade de um modelo que combine:</p>
						<ul>
							<li>
								financiamento base estável e plurianual, garantindo previsibilidade e capacidade
								institucional, mantendo ligação a avaliação e desempenho;
							</li>
							<li>financiamento competitivo, orientado para excelência, risco e diferenciação;</li>
							<li>modelos híbridos que articulem financiamento base e desempenho competitivo.</li>
						</ul>
						<p>É igualmente reconhecida a importância de:</p>
						<ul>
							<li>estabilidade para recursos humanos e infraestruturas;</li>
							<li>planeamento de médio prazo alinhado com ciclos plurianuais.</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>O sistema atual revela instabilidade e incoerência estrutural, nomeadamente:</p>
						<ul>
							<li>
								utilização do financiamento competitivo para cobrir custos estruturais (ex.: salários,
								funcionamento);
							</li>
							<li>
								imprevisibilidade, desfasamento e falta de articulação entre os ciclos (concursos,
								avaliação, resultados e contratualização);
							</li>
							<li>ausência de regras claras, consistentes e estáveis ao longo do tempo.</li>
						</ul>
						<p>Esta situação gera:</p>
						<ul>
							<li>dificuldades de planeamento institucional;</li>
							<li>incerteza para recursos humanos e infraestruturas;</li>
							<li>
								pressão contínua sobre as instituições associada a ciclos de avaliação sucessivos e
								sobrepostos.
							</li>
						</ul>
						<h4>2) Arquitetura do sistema: ambição de integração vs. fragmentação persistente</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>
							É amplamente reconhecida a necessidade de uma visão integrada do sistema de I&amp;I,
							incluindo:
						</p>
						<ul>
							<li>articulação ao longo da cadeia ciência–inovação;</li>
							<li>coordenação e coerência entre diferentes fontes de financiamento;</li>
							<li>papel potencial da AI2 como hub de articulação e alinhamento estratégico.</li>
						</ul>
						<p>Surge também uma proposta estruturante de:</p>
						<ul>
							<li>organização do financiamento em níveis distintos: base, competitivo e programático;</li>
							<li>maior coerência entre ensino superior, ciência e inovação.</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>Persistem fragmentações estruturais relevantes, designadamente:</p>
						<ul>
							<li>existência de “três mundos paralelos” (ensino superior, ciência e inovação);</li>
							<li>fraca articulação entre ministérios e fontes de financiamento público;</li>
							<li>
								instrumentos e programas com regras, lógicas e cronogramas pouco coordenados, e ausência
								de mecanismos eficazes de continuidade entre esses instrumentos ao longo da cadeia de
								valor.
							</li>
						</ul>
						<p>Acresce:</p>
						<ul>
							<li>tensão entre centralização e autonomia regional ou institucional;</li>
							<li>
								ausência de um mecanismo eficaz de coordenação transversal do sistema que assegure
								continuidade e coerência estratégica ao longo da cadeia de valor.
							</li>
						</ul>
						<h4>
							3) Mobilização de financiamento: potencial de alavancagem vs. limitações operacionais e de
							incentivos
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>É identificado potencial significativo para:</p>
						<ul>
							<li>diversificação de fontes de financiamento, incluindo privado e interministerial;</li>
							<li>maior captação de fundos europeus e internacionais;</li>
							<li>
								mecanismos de alinhamento de incentivos através de métricas de desempenho e impacto (ex.:
								ligação entre financiamento e capacidade de atração de recursos externos).
							</li>
						</ul>
						<p>Destaca-se também:</p>
						<ul>
							<li>relevância de modelos que incentivem compromisso efetivo das empresas;</li>
							<li>
								potencial de medir impacto (ex.: capacidade de “atrair financiamento por euro investido”).
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>A concretização deste potencial é limitada por:</p>
						<ul>
							<li>
								baixa participação efetiva das empresas, incluindo ausência ou pouca capacidade de
								cofinanciamento;
							</li>
							<li>
								fenómenos como “investigação por simpatia” ou projetos sem ligação ao core estratégico
								empresarial;
							</li>
							<li>dificuldades na transformação de financiamento em impacto económico.</li>
						</ul>
						<p>Adicionalmente, persistem:</p>
						<ul>
							<li>elevada carga burocrática na submissão e execução dos projetos;</li>
							<li>modelos de financiamento pouco adaptados às diferentes fases da cadeia de valor;</li>
							<li>ineficiências que reduzem a capacidade de mobilizar recursos adicionais.</li>
						</ul>
		{:else}
			<h3>Thematic Table “Architecture of R&amp;I funding” (23 April, 10:00)</h3>
			
						<p>
							<strong>Base-competitive balance vs. systemic instability.</strong> Recognition of the need to
							combine stable and competitive funding, coexisting with unpredictability, misaligned cycles and
							recurring use of competitive funding to cover structural costs, which generates systemic instability
							and makes strategic planning difficult.
						</p>
						<p>
							<strong>System integration vs. governance fragmentation.</strong> Ambition for coordination between
							science, innovation and public/private funding, but marked by “three parallel worlds” (higher
							education, research, innovation), disconnected instruments and, in some cases, instruments that
							are little known or underused by system actors, contributing to weak continuity along the knowledge
							value chain, with insufficient coordination between funding logics and sources.
						</p>
						<p>
							<strong>Diversification and mobilisation of funding vs. low mechanism effectiveness.</strong
							>
							Potential to leverage private and European funding, but limited by misaligned incentives, low
							commitment and weak effective participation by companies, as well as operational inefficiencies.
						</p>
			
						<h4>1) Funding model: necessary balance vs. structural instability</h4>
			
						<p><strong>Strengths</strong></p>
						<p>There is strong consensus on the need for a model that combines:</p>
						<ul>
							<li>
								stable and multiannual base funding, ensuring predictability and institutional capacity
								while maintaining a connection to evaluation and performance;
							</li>
							<li>competitive funding, oriented towards excellence, risk and differentiation;</li>
							<li>hybrid models that connect base funding and competitive performance.</li>
						</ul>
						<p>The importance of the following is also recognised:</p>
						<ul>
							<li>stability for human resources and infrastructures;</li>
							<li>medium-term planning aligned with multiannual cycles.</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>The current system reveals structural instability and incoherence, namely:</p>
						<ul>
							<li>use of competitive funding to cover structural costs (e.g. salaries, operations);</li>
							<li>
								unpredictability, misalignment and lack of coordination between cycles (calls, evaluation,
								results and contracting);
							</li>
							<li>absence of clear, consistent and stable rules over time.</li>
						</ul>
						<p>This situation generates:</p>
						<ul>
							<li>difficulties in institutional planning;</li>
							<li>uncertainty for human resources and infrastructures;</li>
							<li>
								continuous pressure on institutions associated with successive and overlapping evaluation
								cycles.
							</li>
						</ul>
						<h4>2) System architecture: ambition for integration vs. persistent fragmentation</h4>
			
						<p><strong>Strengths</strong></p>
						<p>
							The need for an integrated vision of the R&amp;I system is widely recognised, including:
						</p>
						<ul>
							<li>coordination along the science-innovation chain;</li>
							<li>coordination and coherence between different funding sources;</li>
							<li>AI2's potential role as a hub for coordination and strategic alignment.</li>
						</ul>
						<p>A structuring proposal also emerges for:</p>
						<ul>
							<li>organisation of funding into distinct levels: base, competitive and programmatic;</li>
							<li>greater coherence between higher education, science and innovation.</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>Relevant structural fragmentations persist, namely:</p>
						<ul>
							<li>existence of “three parallel worlds” (higher education, science and innovation);</li>
							<li>weak coordination between ministries and public funding sources;</li>
							<li>
								instruments and programmes with poorly coordinated rules, logics and schedules, and
								absence of effective continuity mechanisms between these instruments along the value
								chain.
							</li>
						</ul>
						<p>In addition:</p>
						<ul>
							<li>tension between centralisation and regional or institutional autonomy;</li>
							<li>
								absence of an effective cross-system coordination mechanism that ensures continuity and
								strategic coherence along the value chain.
							</li>
						</ul>
						<h4>3) Funding mobilisation: leverage potential vs. operational and incentive limitations</h4>
			
						<p><strong>Strengths</strong></p>
						<p>Significant potential is identified for:</p>
						<ul>
							<li>diversification of funding sources, including private and interministerial sources;</li>
							<li>greater attraction of European and international funds;</li>
							<li>
								incentive-alignment mechanisms through performance and impact metrics (e.g. connection
								between funding and capacity to attract external resources).
							</li>
						</ul>
						<p>Also highlighted:</p>
						<ul>
							<li>relevance of models that encourage effective company commitment;</li>
							<li>potential to measure impact (e.g. capacity to “attract funding per euro invested”).</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>Realising this potential is limited by:</p>
						<ul>
							<li>
								low effective participation by companies, including absence of or limited capacity for
								co-financing;
							</li>
							<li>
								phenomena such as “research out of sympathy” or projects with no connection to the
								company's strategic core;
							</li>
							<li>difficulties in transforming funding into economic impact.</li>
						</ul>
						<p>In addition, the following persist:</p>
						<ul>
							<li>high bureaucratic burden in project submission and execution;</li>
							<li>funding models poorly adapted to the different phases of the value chain;</li>
							<li>inefficiencies that reduce the capacity to mobilise additional resources.</li>
						</ul>
		{/if}
	</div>
</div>

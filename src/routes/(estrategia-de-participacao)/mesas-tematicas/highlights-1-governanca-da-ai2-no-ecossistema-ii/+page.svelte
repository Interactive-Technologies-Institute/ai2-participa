<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Governança da AI2 no Ecossistema I&I' : 'AI2 Governance in the R&I Ecosystem'} />
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
			<h3>MT Governança da AI2 no ecossistema de I&amp;I (30 de abril, 10h)</h3>
			
						<p>
							<strong
								>Centralidade sistémica da governança vs. fragmentação e vazio de coordenação.</strong
							>
							Consenso sobre necessidade de integração ao longo da cadeia de valor, mas persistência de ausência
							de responsabilidade e articulação estratégica efetiva.
						</p>
						<p>
							<strong>Integração institucional vs. fragilidades operacionais.</strong> Potencial da AI2 para
							atuar com coerência e visão estratégica, mas legado de baixa autonomia, capacidades limitadas
							e reduzida credibilidade.
						</p>
						<p>
							<strong>Orientação estratégica vs. dificuldade de concretização.</strong> Convergência na necessidade
							de prioridades, metas e indicadores claros, mas fragilidades na definição, estabilidade e tradução
							em decisões operacionais.
						</p>
			
						<h4>1) Centralidade sistémica da governança vs. fragmentação e vazio de coordenação</h4>
			
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								Existe um reconhecimento amplo da necessidade de uma abordagem sistémica da governança,
								orientada para a articulação e maior integração entre ciência, inovação, economia e
								políticas sectoriais.<br />
								Destaca-se o potencial da AI2 para ocupar o lugar sistémico de coordenação, incluindo intersectorial,
								estruturando o “pipeline” completo desde a produção de conhecimento até à sua aplicação e impacto,
								com integração de múltiplos atores e instrumentos, e fomentando maiores níveis de adicionalidade
								pelo tecido empresarial.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>
							Persiste um vazio de governação nas ligações e continuidades entre ciência e economia, sem
							um ator claramente responsável pela transformação do conhecimento em valor.<br />
							A fragmentação institucional (entre agências, ministérios e instrumentos) traduz-se em:
						</p>
						<ul>
							<li>Ausência de coordenação efetiva;</li>
							<li>Sobreposição e lacunas ao longo da cadeia de valor;</li>
							<li>Dificuldade em alinhar metas, políticas, financiamento e execução.</li>
						</ul>
						<h4>
							2) Potencial de integração institucional vs. limitações de autonomia, capacidade e
							credibilidade operacional
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>
							A criação da AI2 é percecionada como uma oportunidade para construir uma organização
							integrada, com:
						</p>
						<ul>
							<li>Mandato claro;</li>
							<li>Maior coerência entre instrumentos;</li>
							<li>Capacidade de decisão estratégica;</li>
							<li>Reforço de mecanismos de prestação de contas, avaliação e monitorização.</li>
							<li>
								Há também potencial para introduzir modelos de governação mais robustos (ex.: funções não
								executivas, maior escrutínio, separação entre níveis estratégico e operacional).
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>
							As instituições existentes são caracterizadas por fragilidades estruturais que podem
							persistir se não forem resolvidas:
						</p>
						<ul>
							<li>Autonomia limitada face à tutela;</li>
							<li>Capacidade operacional bastante insuficiente face às atribuições;</li>
							<li>Falta de financiamento previsível;</li>
							<li>
								Baixa credibilidade junto da comunidade de utilizadores (ex.: prazos, regras, execução).
							</li>
						</ul>
						<p>Acresce o risco de replicação de problemas num novo modelo, nomeadamente:</p>
						<ul>
							<li>Conselhos consultivos sem influência e autonomia efetiva;</li>
							<li>Excessiva dependência do ciclo político;</li>
							<li>Ausência de capacidade estratégica interna.</li>
						</ul>
						<h4>
							3) Reconhecimento da necessidade de orientação estratégica vs. dificuldades na definição e
							operacionalização
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>Verifica-se forte convergência quanto à necessidade de:</p>
						<ul>
							<li>Prioridades claras e partilhadas pela comunidade;</li>
							<li>Articulação sistémica entre objetivos científicos, económicos e societais;</li>
							<li>Programas e instrumentos ao serviço de uma estratégia integrada;</li>
							<li>Utilização de indicadores de desempenho e impacto multinível;</li>
							<li>
								Desenvolvimento de estratégias integradas (incluindo missões e abordagem orientada a
								objetivos), com alinhamento de modelos de avaliação e financiamento.
							</li>
							<li>
								Existe também abertura para modelos participativos na definição estratégica e maior
								alinhamento e sinergias com políticas e programas europeus e internacionais.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>
							A definição e implementação dessa orientação estratégica enfrenta limitações estruturais:
						</p>
						<ul>
							<li>Ausência de prioridades claras e aplicação coerente entre instrumentos;</li>
							<li>Descontinuidades e instabilidade associadas ao ciclo político;</li>
							<li>Risco de decisões top-down desajustadas das capacidades do sistema;</li>
							<li>Dificuldade de tradução dos diagnósticos em decisões operacionais.</li>
						</ul>
						<p>
							Adicionalmente, destacam-se desafios na mensuração de resultados e impacto, bem como no
							equilíbrio entre:
						</p>
						<ul>
							<li>Liberdade científica (bottom-up) e orientação estratégica (top-down);</li>
							<li>
								Longo prazo (investigação fundamental), a médio prazo (investigação aplicada) e
								necessidades e objetivos de curto prazo (mercado).
							</li>
						</ul>
		{:else}
			<h3>AI2 Governance in the R&amp;I ecosystem Thematic Table (30 April, 10:00)</h3>
			
						<p>
							<strong>Systemic centrality of governance vs. fragmentation and coordination gap.</strong>
							Consensus on the need for integration along the value chain, but persistence of an absence of
							responsibility and effective strategic coordination.
						</p>
						<p>
							<strong>Institutional integration vs. operational weaknesses.</strong> AI2's potential to act
							with coherence and strategic vision, but legacy of low autonomy, limited capacities and reduced
							credibility.
						</p>
						<p>
							<strong>Strategic orientation vs. difficulty of implementation.</strong> Convergence on the need
							for clear priorities, targets and indicators, but weaknesses in their definition, stability and
							translation into operational decisions.
						</p>
			
						<h4>1) Systemic centrality of governance vs. fragmentation and coordination gap</h4>
			
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								There is broad recognition of the need for a systemic approach to governance, oriented
								towards coordination and greater integration between science, innovation, economy and
								sectoral policies.<br />
								AI2's potential to occupy the systemic coordination role is highlighted, including intersectoral
								coordination, structuring the complete “pipeline” from knowledge production to its application
								and impact, integrating multiple actors and instruments, and fostering higher levels of additionality
								by the business fabric.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>
							A governance gap persists in the links and continuities between science and the economy,
							with no actor clearly responsible for transforming knowledge into value.<br />
							Institutional fragmentation (between agencies, ministries and instruments) translates into:
						</p>
						<ul>
							<li>Absence of effective coordination;</li>
							<li>Overlap and gaps along the value chain;</li>
							<li>Difficulty aligning targets, policies, funding and execution.</li>
						</ul>
						<h4>
							2) Potential for institutional integration vs. limitations in autonomy, capacity and
							operational credibility
						</h4>
			
						<p><strong>Strengths</strong></p>
						<p>
							The creation of AI2 is perceived as an opportunity to build an integrated organisation,
							with:
						</p>
						<ul>
							<li>Clear mandate;</li>
							<li>Greater coherence between instruments;</li>
							<li>Strategic decision-making capacity;</li>
							<li>Strengthening of accountability, evaluation and monitoring mechanisms.</li>
							<li>
								There is also potential to introduce more robust governance models (e.g. non-executive
								functions, greater scrutiny, separation between strategic and operational levels).
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>
							Existing institutions are characterised by structural weaknesses that may persist if
							unresolved:
						</p>
						<ul>
							<li>Limited autonomy from political oversight;</li>
							<li>
								Operational capacity that is quite insufficient in relation to their responsibilities;
							</li>
							<li>Lack of predictable funding;</li>
							<li>Low credibility among the user community (e.g. deadlines, rules, execution).</li>
						</ul>
						<p>There is also the risk of replicating problems in a new model, namely:</p>
						<ul>
							<li>Advisory boards without influence or effective autonomy;</li>
							<li>Excessive dependence on the political cycle;</li>
							<li>Absence of internal strategic capacity.</li>
						</ul>
						<h4>
							3) Recognition of the need for strategic orientation vs. difficulties in definition and
							operationalisation
						</h4>
			
						<p><strong>Strengths</strong></p>
						<p>There is strong convergence on the need for:</p>
						<ul>
							<li>Clear priorities shared by the community;</li>
							<li>Systemic coordination between scientific, economic and societal objectives;</li>
							<li>Programmes and instruments serving an integrated strategy;</li>
							<li>Use of multilevel performance and impact indicators;</li>
							<li>
								Development of integrated strategies (including missions and an objective-oriented
								approach), with alignment of evaluation and funding models.
							</li>
							<li>
								There is also openness to participatory models in strategic definition and greater
								alignment and synergies with European and international policies and programmes.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>
							The definition and implementation of this strategic orientation faces structural
							limitations:
						</p>
						<ul>
							<li>Absence of clear priorities and coherent application across instruments;</li>
							<li>Discontinuities and instability associated with the political cycle;</li>
							<li>Risk of top-down decisions misaligned with the system's capabilities;</li>
							<li>Difficulty translating diagnoses into operational decisions.</li>
						</ul>
						<p>
							In addition, challenges in measuring results and impact stand out, as does the balance
							between:
						</p>
						<ul>
							<li>Scientific freedom (bottom-up) and strategic orientation (top-down);</li>
							<li>
								Long term (fundamental research), medium term (applied research) and short-term needs and
								objectives (market).
							</li>
						</ul>
		{/if}
	</div>
</div>

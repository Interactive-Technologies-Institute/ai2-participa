<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Investigação e Inovação - com e para - a Sociedade' : 'Research and Innovation - with and for - Society'} />
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
			<h3>Mesa Temática “Investigação e inovação – com e para – a sociedade” (21 de abril, 15h)</h3>
			
						<p>
							<strong
								>Cocriação como princípio estruturante: consenso alargado vs. indefinição operacional.</strong
							>
							A cocriação é reconhecida como abordagem relevante para integrar conhecimento distribuído, reforçar
							a legitimidade das políticas e responder a desafios societais complexos, mas persistem indefinições
							sobre o seu âmbito, objetivos, outputs esperados e tradução em instrumentos efetivos de política.
						</p>
						<p>
							<strong
								>Inclusividade e qualidade da participação: potencial de legitimação vs. risco de
								superficialidade.</strong
							>
							O alargamento da participação a diferentes comunidades, territórios, cidadãos e utilizadores finais
							pode aumentar a robustez e aceitação das políticas, embora continue condicionado por participação
							episódica, assimetrias de poder, barreiras práticas e risco de processos sem tradução em decisões
							concretas.
						</p>
						<p>
							<strong
								>Implementação da cocriação nas políticas: potencial transformador vs. limitações
								institucionais e operacionais.</strong
							>
							A integração sistemática da cocriação pode melhorar a articulação entre ciência, inovação e necessidades
							societais, mas enfrenta limitações de capacidade institucional, priorização estratégica, burocracia,
							custos de participação e mecanismos insuficientes de incorporação dos contributos no processo
							decisório.
						</p>
			
						<h4>
							1) Cocriação como princípio estruturante: consenso alargado vs. indefinição operacional
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>
							Existe um consenso transversal sobre a relevância da cocriação como abordagem para políticas
							de I&amp;I, reconhecida pela sua capacidade de:
						</p>
						<ul>
							<li>integrar conhecimento distribuído entre múltiplos atores;</li>
							<li>reforçar a legitimidade e aceitação das políticas;</li>
							<li>melhorar a adequação das respostas a desafios societais complexos.</li>
							<li>
								A cocriação é também valorizada enquanto mecanismo de escuta ativa e aprendizagem
								coletiva, permitindo decisões mais informadas e alinhadas com necessidades reais.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>
							Verifica-se uma indefinição significativa quanto ao conceito e aplicação prática da
							cocriação, nomeadamente ao nível de:
						</p>
						<ul>
							<li>delimitação do seu âmbito (políticas vs. projetos vs. produção científica);</li>
							<li>ausência de enquadramento claro dos objetivos e outputs esperados;</li>
							<li>tendência para abordagens excessivamente genéricas e pouco operacionais.</li>
							<li>
								Esta falta de concretização dificulta a sua tradução em instrumentos efetivos de política.
							</li>
						</ul>
						<h4>
							2) Inclusividade e qualidade da participação: potencial de legitimação vs. risco de
							superficialidade
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>
							A cocriação é entendida como oportunidade para alargar e diversificar a participação,
							incluindo:
						</p>
						<ul>
							<li>diferentes comunidades científicas, empresariais e sociais;</li>
							<li>atores territoriais e grupos não representados;</li>
							<li>cidadãos e utilizadores finais.</li>
						</ul>
						<p>Este alargamento contribui para:</p>
						<ul>
							<li>maior robustez das soluções;</li>
							<li>reforço da cultura científica e do envolvimento social;</li>
							<li>aumento da probabilidade de implementação das políticas.</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>Persistem limitações à efetividade e profundidade da participação, nomeadamente:</p>
						<ul>
							<li>envolvimento frequentemente instrumental ou episódico;</li>
							<li>assimetrias de poder, linguagem e capacidade de influência;</li>
							<li>
								barreiras práticas (tempo, recursos, complexidade) que limitam a participação de alguns
								atores.
							</li>
							<li>
								Adicionalmente, a experiência acumulada aponta para o risco de processos que não se
								traduzem em decisões concretas, afetando a credibilidade institucional.
							</li>
						</ul>
						<h4>
							3) Implementação da cocriação nas políticas: potencial transformador vs. limitações
							institucionais e operacionais
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>
							A integração sistemática da cocriação nas políticas de I&amp;I é vista como um instrumento
							com potencial transformador, permitindo:
						</p>
						<ul>
							<li>melhor articulação entre ciência, inovação e necessidades societais;</li>
							<li>definição mais informada de prioridades estratégicas;</li>
							<li>mobilização de ecossistemas diversos para resposta a desafios complexos.</li>
							<li>
								Existem também referências a exemplos concretos (internacionais e nacionais) que
								demonstram a viabilidade de modelos cocriativos.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>
							A operacionalização da cocriação enfrenta constrangimentos estruturais importantes,
							incluindo:
						</p>
						<ul>
							<li>limitada capacidade das instituições públicas para coordenar processos complexos;</li>
							<li>ausência de priorização estratégica (dificuldade em fazer escolhas);</li>
							<li>burocracia e custos de participação elevados, especialmente para empresas;</li>
							<li>falta de mecanismos de integração dos contributos no processo decisório.</li>
							<li>
								Acresce o risco de descontinuidade (dependência de iniciativas pontuais) e de falta de
								alinhamento com incentivos e resultados concretos.
							</li>
						</ul>
		{:else}
			<h3>Thematic Table “Research and innovation - with and for - society” (21 April, 15:00)</h3>
			
						<p>
							<strong
								>Co-creation as a structuring principle: broad consensus vs. operational uncertainty.</strong
							>
							Co-creation is recognised as a relevant approach for integrating distributed knowledge, strengthening
							the legitimacy of policies and responding to complex societal challenges, but uncertainties persist
							regarding its scope, objectives, expected outputs and translation into effective policy instruments.
						</p>
						<p>
							<strong
								>Inclusiveness and quality of participation: potential for legitimation vs. risk of
								superficiality.</strong
							>
							Broadening participation to different communities, territories, citizens and end users can increase
							the robustness and acceptance of policies, although it remains constrained by episodic participation,
							power asymmetries, practical barriers and the risk of processes without translation into concrete
							decisions.
						</p>
						<p>
							<strong
								>Implementation of co-creation in policies: transformative potential vs. institutional and
								operational limitations.</strong
							>
							The systematic integration of co-creation can improve coordination between science, innovation
							and societal needs, but faces limitations in institutional capacity, strategic prioritisation,
							bureaucracy, participation costs and insufficient mechanisms for incorporating contributions into
							the decision-making process.
						</p>
			
						<h4>
							1) Co-creation as a structuring principle: broad consensus vs. operational uncertainty
						</h4>
			
						<p><strong>Strengths</strong></p>
						<p>
							There is cross-cutting consensus on the relevance of co-creation as an approach to R&amp;I
							policies, recognised for its capacity to:
						</p>
						<ul>
							<li>integrate distributed knowledge among multiple actors;</li>
							<li>strengthen policy legitimacy and acceptance;</li>
							<li>improve the adequacy of responses to complex societal challenges.</li>
							<li>
								Co-creation is also valued as a mechanism for active listening and collective learning,
								enabling more informed decisions aligned with real needs.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>
							There is significant uncertainty regarding the concept and practical application of
							co-creation, namely in terms of:
						</p>
						<ul>
							<li>delimitation of its scope (policies vs. projects vs. scientific production);</li>
							<li>absence of a clear framework for objectives and expected outputs;</li>
							<li>tendency towards overly generic and insufficiently operational approaches.</li>
							<li>
								This lack of specificity makes it difficult to translate co-creation into effective policy
								instruments.
							</li>
						</ul>
						<h4>
							2) Inclusiveness and quality of participation: potential for legitimation vs. risk of
							superficiality
						</h4>
			
						<p><strong>Strengths</strong></p>
						<p>
							Co-creation is understood as an opportunity to broaden and diversify participation,
							including:
						</p>
						<ul>
							<li>different scientific, business and social communities;</li>
							<li>territorial actors and under-represented groups;</li>
							<li>citizens and end users.</li>
						</ul>
						<p>This broadening contributes to:</p>
						<ul>
							<li>greater robustness of solutions;</li>
							<li>strengthening of scientific culture and social engagement;</li>
							<li>increased likelihood of policy implementation.</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>Limitations persist regarding the effectiveness and depth of participation, namely:</p>
						<ul>
							<li>frequently instrumental or episodic involvement;</li>
							<li>asymmetries of power, language and capacity to influence;</li>
							<li>
								practical barriers (time, resources, complexity) that limit the participation of some
								actors.
							</li>
							<li>
								In addition, accumulated experience points to the risk of processes that do not translate
								into concrete decisions, affecting institutional credibility.
							</li>
						</ul>
						<h4>
							3) Implementation of co-creation in policies: transformative potential vs. institutional and
							operational limitations
						</h4>
			
						<p><strong>Strengths</strong></p>
						<p>
							The systematic integration of co-creation into R&amp;I policies is seen as an instrument
							with transformative potential, enabling:
						</p>
						<ul>
							<li>better coordination between science, innovation and societal needs;</li>
							<li>more informed definition of strategic priorities;</li>
							<li>mobilisation of diverse ecosystems to respond to complex challenges.</li>
							<li>
								There are also references to concrete examples (international and national) that
								demonstrate the viability of co-creative models.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>
							The operationalisation of co-creation faces important structural constraints, including:
						</p>
						<ul>
							<li>limited capacity of public institutions to coordinate complex processes;</li>
							<li>absence of strategic prioritisation (difficulty making choices);</li>
							<li>high bureaucracy and participation costs, especially for companies;</li>
							<li>lack of mechanisms for integrating contributions into the decision-making process.</li>
							<li>
								This is compounded by the risk of discontinuity (dependence on one-off initiatives) and
								lack of alignment with incentives and concrete results.
							</li>
						</ul>
		{/if}
	</div>
</div>

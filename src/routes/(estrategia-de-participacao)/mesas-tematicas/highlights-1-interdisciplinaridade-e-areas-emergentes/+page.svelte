<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Interdisciplinaridade e Áreas emergentes' : 'Interdisciplinarity and Emerging Areas'} />
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
			<h3>Mesa temática “Interdisciplinaridade e áreas emergentes” (22 de abril, 10h)</h3>
			
						<p>
							A discussão evidenciou um reconhecimento amplo da relevância da interdisciplinaridade e das
							áreas emergentes para responder a desafios científicos, tecnológicos, económicos e societais
							complexos. Contudo, foi igualmente assinalada a dificuldade de traduzir essa relevância em
							instrumentos de financiamento, modelos de avaliação, sistemas de classificação de áreas
							científicas e mecanismos de governação adequados.
						</p>
						<p>
							<strong>Interdisciplinaridade reconhecida vs. dificuldades de operacionalização.</strong> Foi
							amplamente reconhecida a importância da interdisciplinaridade para responder a desafios complexos,
							embora tenham sido assinaladas limitações nos modelos de financiamento e avaliação, na organização
							dos painéis e na escala dos instrumentos disponíveis, que podem penalizar propostas verdadeiramente
							interdisciplinares.
						</p>
						<p>
							<strong>Dinâmica bottom up vs. tentativas de definição top down.</strong> Vários contributos defenderam
							a preservação da liberdade científica, da criatividade e da emergência espontânea de novas áreas.
							Em simultâneo, foi reconhecida a necessidade de identificar capacidades nacionais, áreas de vantagem
							competitiva e domínios onde Portugal possa posicionar-se de forma mais robusta.
						</p>
						<p>
							<strong>Alinhamento europeu vs. capacidade nacional.</strong> A articulação com instrumentos europeus
							foi considerada relevante, nomeadamente através de referências ao ERC, ao Horizonte Europa e a
							modelos como as ERC Synergy. Contudo, foi também sublinhado que a competitividade europeia depende
							de financiamento nacional continuado, de instrumentos preparatórios e de uma estratégia própria
							para reforçar capacidades nacionais.
						</p>
						<p>
							<strong
								>Valorização económica e social da ciência vs. preservação da liberdade científica.</strong
							>
							A ligação entre ciência, desenvolvimento tecnológico, translação e criação de valor foi considerada
							relevante, em particular em áreas deep tech e biotech. Foram igualmente expressas reservas quanto
							a uma orientação excessivamente prescritiva ou demasiado centrada na ideia de ciência ao serviço
							da economia.
						</p>
			
						<h4>1) Interdisciplinaridade: centralidade reconhecida vs. modelos inadequados</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>
							Existe um consenso alargado sobre a relevância da interdisciplinaridade para enfrentar
							desafios científicos e societais complexos, sendo identificada como:
						</p>
						<ul>
							<li>condição para gerar inovação e novas áreas de conhecimento;</li>
							<li>prática já presente em vários domínios e projetos;</li>
							<li>
								eixo fundamental para articulação entre ciência fundamental, desenvolvimento tecnológico e
								aplicação.
							</li>
							<li>
								mecanismo importante para aumentar competitividade internacional e capacidade de resposta
								a desafios complexos.
							</li>
							<li>
								Foram referidos modelos e práticas internacionais que podem servir de referência (ex.:
								painéis híbridos, revisores externos, concursos temáticos), sugerindo base sólida para
								evolução do sistema.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>
							Apesar deste reconhecimento, foram identificados vários obstáculos à operacionalização da
							interdisciplinaridade:
						</p>
						<ul>
							<li>
								modelos de avaliação que penalizam projetos interdisciplinares (dificuldade em satisfazer
								múltiplos painéis);
							</li>
							<li>
								ausência de critérios claros para avaliação da interdisciplinaridade (integração efetiva
								vs. mera agregação multidisciplinar);
							</li>
							<li>
								inadequação dos instrumentos de financiamento (escala reduzida dos projetos, pouco
								compatível com verdadeira interdisciplinaridade).
							</li>
							<li>
								Estas limitações traduzem-se numa baixa eficácia das políticas de promoção da
								interdisciplinaridade. Foi também sublinhado que a interdisciplinaridade e as
								configurações das suas colaborações não devem ser impostas artificialmente. Deve antes ser
								incentivada através de instrumentos simples, flexíveis e adequados à natureza dos
								projetos, permitindo que os promotores escolham os enquadramentos disciplinaresmais
								apropriados.
							</li>
						</ul>
						<h4>
							2) Orientação estratégica do sistema: maturidade no diagnóstico vs. falta de enquadramento
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								A discussão sobre interdisciplinaridade e áreas emergentes cruzou-se com a questão da
								classificação científica, nomeadamente com a utilização das áreas FORD para a AI2 e com a
								forma como esta pode condicionar as opções sobre modelos de avaliação.
							</li>
							<li>
								Foi sugerido que a identificação de áreas emergentes possa beneficiar de uma análise
								retrospetiva dos projetos FCT financiados, incluindo palavras-chave, áreas científicas
								principais e secundárias, padrões de combinação disciplinar e eventuais áreas que tenham
								ficado sem financiamento por não se enquadrarem adequadamente nos painéis existentes.
							</li>
							<li>
								Foi igualmente referida a possibilidade de permitir que os projetos indiquem uma área
								principal e uma área secundária, bem como o recurso a modelos de avaliação mais flexíveis,
								combinando painéis disciplinares, painéis híbridos, revisores externos e escolha informada
								do painel pelos candidatos.
							</li>
							<li>
								A questão central não será apenas criar painéis interdisciplinares, mas garantir que os
								critérios, avaliadores e modelos de classificação conseguem reconhecer a integração
								efetiva entre áreas, sem penalizar propostas que não correspondem aos enquadramentos
								disciplinares tradicionais ou já a enquadramentos interdisciplinares mas com definição
								top-down
							</li>
						</ul>
						<p>
							A discussão revela uma elevada convergência analítica, nomeadamente quanto à necessidade de:
						</p>
						<ul>
							<li>realizar um diagnóstico robusto das capacidades nacionais;</li>
							<li>identificar áreas de vantagem competitiva;</li>
							<li>
								compreender onde Portugal pode posicionar-se de forma mais robusta e articular
								investigação académica com tecido produtivo e impacto societal.
							</li>
							<li>
								Foi também reconhecida a importância de reforçar a ligação entre ciência, tecnologia,
								economia e sociedade, incluindo domínios onde a investigação possa contribuir para gerar
								valor, reforçar capacidades tecnológicas e apoiar processos de translação e maior impacto.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>
							Esta convergência contrasta com uma indefinição quanto ao quadro estratégico global,
							traduzida em:
						</p>
						<ul>
							<li>ausência de visão clara de longo prazo sobre o papel do sistema de I&amp;I;</li>
							<li>
								incerteza sobre objetivos prioritários (competitividade, impacto económico, avanço do
								conhecimento);
							</li>
							<li>
								dificuldade em enquadrar discussões operacionais (instrumentos, painéis, financiamento)
								sem esse referencial estratégico.
							</li>
							<li>
								Esta lacuna compromete a coerência e eficácia das decisões de política. Esta questão
								sugere a necessidade de um enquadramento estratégico claro, mas suficientemente flexível
								para acomodar dinâmicas emergentes.
							</li>
						</ul>
						<h4>3) Áreas emergentes: potencial de dinamismo vs. riscos de definição centralizada</h4>
			
						<p><strong>Potencialidades</strong></p>
						<p>As áreas emergentes são reconhecidas como resultado de:</p>
						<ul>
							<li>novas questões científicas, métodos ou combinações disciplinares;</li>
							<li>processos dinâmicos e evolutivos associados à liberdade científica;</li>
							<li>
								interações entre conhecimento científico, desenvolvimento tecnológico e desafios societais
								em transformação.
							</li>
							<li>
								Foi valorizada a necessidade de manter espaço para investigação e inovação bottom-up,
								permitindo o aparecimento espontâneo de novas áreas e ideias disruptivas, projetos de
								maior risco e propostas que ainda não encaixam claramente nas classificações ou painéis
								existentes.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<p>Identificam-se riscos significativos associados à sua governação, incluindo:</p>
						<ul>
							<li>
								dificuldade em definir áreas emergentes por via top-down, com risco de escolhas erradas ou
								desatualizadas;
							</li>
							<li>necessidade de horizontes temporais claros, previsibilidade e revisão periódica;</li>
							<li>
								ausência de mecanismos de revisão contínua e adaptação temporal;risco de concentrar
								recursos em áreas conjunturalmente valorizadas ou excessivamente dependentes de agendas
								externas, em detrimento de capacidades nacionais.
							</li>
							<li>
								Acresce a limitação dos instrumentos existentes, que nem sempre estão adaptados à natureza
								exploratória, incerta e evolutiva destas áreas.
							</li>
						</ul>
						<h4>4) Questões transversais</h4>
			
						<p>
							A discussão apontou ainda para quatro questões transversais: escala do financiamento,
							continuidade do investimento nacional, ligação aos programas europeus e reforço dos
							mecanismos de translação e criação de valor.
						</p>
			
						<p>A reunião apontou para a necessidade de uma abordagem equilibrada:</p>
			
						<p>
							preservar a liberdade científica e as dinâmicas bottom up, mas assegurar instrumentos
							capazes de identificar e apoiar áreas de potencial estratégico;
						</p>
			
						<p>promover a interdisciplinaridade, mas sem a transformar num requisito artificial;</p>
			
						<p>
							alinhar com oportunidades europeias, mas mantendo investimento nacional suficiente para
							desenvolver capacidades próprias;
						</p>
			
						<p>
							e criar mecanismos diferenciados para projetos exploratórios, interdisciplinares,
							tecnológicos e de translação.
						</p>
			
						<p>
							Foi destacada a necessidade de reforçar mecanismos que permitam transformar conhecimento
							científico em desenvolvimento tecnológico, capacidade empresarial e valor económico. Esta
							dimensão foi particularmente associada a áreas deep tech (como a biotecnologia), à criação
							de empresas a partir da academia e à necessidade de atores capazes de apoiar a passagem
							entre investigação, desenvolvimento e mercado.
						</p>
		{:else}
			<h3>Thematic Table “Interdisciplinarity and emerging areas” (22 April, 10:00)</h3>
			
						<p>
							The discussion highlighted broad recognition of the relevance of interdisciplinarity and
							emerging areas for responding to complex scientific, technological, economic and societal
							challenges. However, the difficulty of translating that relevance into appropriate funding
							instruments, evaluation models, scientific-area classification systems and governance
							mechanisms was also noted.
						</p>
						<p>
							<strong>Recognised interdisciplinarity vs. operationalisation difficulties.</strong>
							The importance of interdisciplinarity in responding to complex challenges was widely recognised,
							although limitations were noted in funding and evaluation models, panel organisation and the scale
							of available instruments, which may penalise truly interdisciplinary proposals.
						</p>
						<p>
							<strong>Bottom-up dynamics vs. attempts at top-down definition.</strong> Several contributions
							defended the preservation of scientific freedom, creativity and the spontaneous emergence of new
							areas. At the same time, the need to identify national capabilities, areas of competitive advantage
							and domains where Portugal can position itself more robustly was recognised.
						</p>
						<p>
							<strong>European alignment vs. national capacity.</strong> Coordination with European instruments
							was considered relevant, namely through references to the ERC, Horizon Europe and models such
							as ERC Synergy. However, it was also stressed that European competitiveness depends on continued
							national funding, preparatory instruments and a strategy of its own to strengthen national capabilities.
						</p>
						<p>
							<strong
								>Economic and social valorisation of science vs. preservation of scientific freedom.</strong
							>
							The connection between science, technological development, translation and value creation was
							considered relevant, particularly in deep tech and biotech areas. Reservations were also expressed
							about an excessively prescriptive orientation or one too centred on the idea of science serving
							the economy.
						</p>
			
						<h4>1) Interdisciplinarity: recognised centrality vs. inadequate models</h4>
			
						<p><strong>Strengths</strong></p>
						<p>
							There is broad consensus on the relevance of interdisciplinarity for addressing complex
							scientific and societal challenges, being identified as:
						</p>
						<ul>
							<li>a condition for generating innovation and new areas of knowledge;</li>
							<li>a practice already present in several domains and projects;</li>
							<li>
								a fundamental axis for coordination between fundamental science, technological development
								and application.
							</li>
							<li>
								an important mechanism for increasing international competitiveness and capacity to
								respond to complex challenges.
							</li>
							<li>
								International models and practices were mentioned as possible references (e.g. hybrid
								panels, external reviewers, thematic calls), suggesting a solid basis for the system's
								evolution.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>
							Despite this recognition, several obstacles to operationalising interdisciplinarity were
							identified:
						</p>
						<ul>
							<li>
								evaluation models that penalise interdisciplinary projects (difficulty satisfying multiple
								panels);
							</li>
							<li>
								absence of clear criteria for evaluating interdisciplinarity (effective integration vs.
								mere multidisciplinary aggregation);
							</li>
							<li>
								inadequacy of funding instruments (small project scale, not very compatible with true
								interdisciplinarity).
							</li>
							<li>
								These limitations translate into low effectiveness of policies promoting
								interdisciplinarity. It was also stressed that interdisciplinarity and the configurations
								of its collaborations should not be artificially imposed. Instead, it should be encouraged
								through simple, flexible instruments suited to the nature of the projects, allowing
								promoters to choose the most appropriate disciplinary frameworks.
							</li>
						</ul>
						<h4>
							2) Strategic orientation of the system: maturity in the diagnosis vs. lack of framework
						</h4>
			
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								The discussion on interdisciplinarity and emerging areas intersected with the question of
								scientific classification, namely with the use of FORD areas for AI2 and how this may
								shape options regarding evaluation models.
							</li>
							<li>
								It was suggested that identifying emerging areas could benefit from a retrospective
								analysis of FCT-funded projects, including keywords, main and secondary scientific areas,
								disciplinary-combination patterns and possible areas that may have gone unfunded because
								they did not fit adequately into existing panels.
							</li>
							<li>
								The possibility was also mentioned of allowing projects to indicate a main area and a
								secondary area, as well as using more flexible evaluation models combining disciplinary
								panels, hybrid panels, external reviewers and informed panel choice by applicants.
							</li>
							<li>
								The central issue will not only be to create interdisciplinary panels, but to ensure that
								criteria, evaluators and classification models can recognise effective integration between
								areas, without penalising proposals that do not correspond to traditional disciplinary
								frameworks or that already correspond to interdisciplinary frameworks but with a top-down
								definition.
							</li>
						</ul>
						<p>The discussion reveals a high level of analytical convergence, namely on the need to:</p>
						<ul>
							<li>carry out a robust diagnosis of national capabilities;</li>
							<li>identify areas of competitive advantage;</li>
							<li>
								understand where Portugal can position itself more robustly and connect academic research
								with the productive fabric and societal impact.
							</li>
							<li>
								The importance of strengthening the connection between science, technology, economy and
								society was also recognised, including domains where research can contribute to generating
								value, strengthening technological capabilities and supporting translation processes and
								greater impact.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>
							This convergence contrasts with uncertainty about the overall strategic framework, reflected
							in:
						</p>
						<ul>
							<li>absence of a clear long-term vision for the role of the R&amp;I system;</li>
							<li>
								uncertainty about priority objectives (competitiveness, economic impact, advancement of
								knowledge);
							</li>
							<li>
								difficulty framing operational discussions (instruments, panels, funding) without that
								strategic reference point.
							</li>
							<li>
								This gap compromises the coherence and effectiveness of policy decisions. This issue
								suggests the need for a clear strategic framework, but one flexible enough to accommodate
								emerging dynamics.
							</li>
						</ul>
						<h4>3) Emerging areas: potential for dynamism vs. risks of centralised definition</h4>
			
						<p><strong>Strengths</strong></p>
						<p>Emerging areas are recognised as the result of:</p>
						<ul>
							<li>new scientific questions, methods or disciplinary combinations;</li>
							<li>dynamic and evolving processes associated with scientific freedom;</li>
							<li>
								interactions between scientific knowledge, technological development and changing societal
								challenges.
							</li>
							<li>
								The need to maintain space for bottom-up research and innovation was valued, allowing the
								spontaneous emergence of new areas and disruptive ideas, higher-risk projects and
								proposals that do not yet clearly fit existing classifications or panels.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<p>Significant risks associated with their governance are identified, including:</p>
						<ul>
							<li>
								difficulty defining emerging areas through a top-down approach, with the risk of wrong or
								outdated choices;
							</li>
							<li>need for clear time horizons, predictability and periodic review;</li>
							<li>
								absence of mechanisms for continuous review and temporal adaptation; risk of concentrating
								resources in temporarily valued areas or areas excessively dependent on external agendas,
								to the detriment of national capabilities.
							</li>
							<li>
								This is compounded by the limitation of existing instruments, which are not always adapted
								to the exploratory, uncertain and evolving nature of these areas.
							</li>
						</ul>
						<h4>4) Cross-cutting issues</h4>
			
						<p>
							The discussion also pointed to four cross-cutting issues: scale of funding, continuity of
							national investment, connection to European programmes and strengthening of translation and
							value-creation mechanisms.
						</p>
			
						<p>The meeting pointed to the need for a balanced approach:</p>
			
						<p>
							preserve scientific freedom and bottom-up dynamics, while ensuring instruments capable of
							identifying and supporting areas of strategic potential;
						</p>
			
						<p>promote interdisciplinarity, but without turning it into an artificial requirement;</p>
			
						<p>
							align with European opportunities, while maintaining sufficient national investment to
							develop capabilities of its own;
						</p>
			
						<p>
							and create differentiated mechanisms for exploratory, interdisciplinary, technological and
							translation projects.
						</p>
			
						<p>
							The need to strengthen mechanisms that allow scientific knowledge to be transformed into
							technological development, business capacity and economic value was highlighted. This
							dimension was particularly associated with deep tech areas (such as biotechnology), the
							creation of companies from academia and the need for actors capable of supporting the
							transition between research, development and market.
						</p>
		{/if}
	</div>
</div>

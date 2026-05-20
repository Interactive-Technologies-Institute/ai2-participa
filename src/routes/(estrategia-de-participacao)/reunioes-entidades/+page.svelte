<script lang="ts">
	import { asset } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.stakeholderMeetings.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				As reuniões com entidades visam recolher perspetivas e contributos de entidades estratégicas
				identificadas no quadro de governança da Avaliação Estratégica (ver Anexo 2 do documento da
				<a href={asset('/docs/RelatMetod_PT.pdf')} target="_blank" rel="noreferrer">metodologia</a>).
				Entre 10 março e 8 abril de 2026, foram realizadas 17 reuniões em formato online, com 65 das
				95 entidades convidadas (lista abaixo). A moderação foi assegurada pela Coordenadora-geral da
				Avaliação Estratégica, Professora Maria do Rosário Partidário. Nestas reuniões participaram como
				observadores peritos da equipa da Avaliação Estratégica (FCT e ANI), o PLANAPP, a DGE, a
				DGEPA, elementos dos gabinetes da Secretária de Estado da Ciência e Inovação e do Secretário de
				Estado da Economia.
			</p>

			<p>
				<strong>Perguntas orientadoras do diálogo:</strong> Considerando a visão para 2050 definida para a
				avaliação estratégica (“Portugal afirma-se como um país que cria talento e conhecimento e os
				transforma em valor económico, social, cultural e ambiental, com um sistema de investigação e de
				inovação dinâmico, interligado em redes nacionais e internacionais, competitivo e orientado para a
				excelência, que conjuga um modelo de desenvolvimento sustentável e inclusivo, reforçando a sua
				posição na Europa e no mundo”), na perspetiva das entidades auscultadas:
			</p>
			<ol>
				<li>
					Quais são os <strong>grandes desafios a longo prazo</strong> que se colocam à organização e
					atividade da AI2, em particular em matéria de investimento em investigação e inovação.
				</li>
				<li>
					Quais são as <strong>grandes prioridades para a atuação da AI2</strong> para ir de encontro à
					visão estabelecida.
				</li>
			</ol>

			<h2>Síntese global dos contributos</h2>
			<p>
				<em
					>(construída a partir dos registos das 17 reuniões, organizados e analisados para preservar a
					diversidade dos contributos, depois estruturados numa matriz temática transversal e, por fim,
					consolidados numa síntese sistémica de desafios e prioridades estratégicas, com base em IA
					validada por revisão humana e suportada por notas e registos das reuniões)</em
				>
			</p>

			<h3>Desafios a longo prazo (Pergunta 1)</h3>
			<ul>
				<li>
					<strong>Instabilidade estratégica e descontinuidade institucional</strong>, resultantes da forte
					dependência de ciclos políticos, de reformas frequentes e da volatilidade das orientações,
					comprometendo a previsibilidade, o planeamento de longo prazo e a consolidação das políticas de
					I&amp;I.
				</li>
				<li>
					<strong>Limitações na previsibilidade e sustentabilidade do financiamento</strong> (plurianual,
					regular e basal/híbrido), mantendo uma dependência estrutural de fundos europeus e de
					instrumentos extraordinários.
				</li>
				<li>
					<strong>Dificuldades de integração efetiva entre investigação e inovação</strong> ao longo da
					cadeia de valor (incluindo transição “da ideia ao mercado”, TRL e translação), num ecossistema
					marcado por fragmentações e mediação intermédia insuficiente.
				</li>
				<li>
					<strong>Necessidade de maior simplificação e eficiência administrativa</strong> perante burocracia
					elevada e foco desproporcionado na despesa, com avaliação de resultados e impacto considerada
					frágil.
				</li>
				<li>
					<strong>Fragilidades na robustez e credibilidade dos modelos de avaliação e escrutínio</strong>,
					exigindo diversidade de métricas, painéis internacionais e controlo de qualidade a posteriori, e
					evitando leituras simplistas do impacto.
				</li>
				<li>
					<strong
						>Insuficiente proteção explícita da investigação fundamental e do seu equilíbrio com
						investigação orientada</strong
					>
					para impacto e inovação, evitando a subalternização ao retorno imediato e preservando a
					diversidade disciplinar.
				</li>
				<li>
					<strong>Baixa atratividade e sustentabilidade das carreiras e do emprego científico</strong>,
					incluindo precariedade, fraca previsibilidade, modelos contratuais limitados, mobilidade
					intersetorial reduzida e fraca integração de doutorados fora da academia.
				</li>
				<li>
					<strong>Constrangimentos no financiamento e na operacionalização das infraestruturas</strong>
					(científicas e de interface), incluindo manutenção e operação, avaliação regular e funcionamento em
					rede, após períodos prolongados de subfinanciamento.
				</li>
				<li>
					<strong>Fraca coesão territorial num sistema com assimetrias regionais</strong> (incluindo ilhas,
					territórios de baixa densidade e interior) em capacidade científica e de interface, acesso a
					financiamento, escala empresarial e intensidade de inovação.
				</li>
				<li>
					<strong>Necessidade de uma governança funcional e clara</strong> (“by design”) num sistema
					fragmentado, assegurando segmentação funcional com coordenação, regras de entrada/saída,
					proximidade ao terreno e orientação aos utilizadores.
				</li>
				<li>
					<strong>Dificuldades na definição de domínios estratégicos com portefólio adaptativo</strong>,
					evitando listas fechadas, assegurando critérios claros e diferenciando domínios por maturidade,
					risco e horizonte temporal, com proteção de áreas emergentes e margem para unknowns e para blue
					sky fora dos domínios.
				</li>
				<li>
					<strong>Fragilidades na articulação entre ciência e sociedade</strong>, incluindo literacia,
					atração para STEM, participação pública estruturada e gestão das tensões associadas à ciência
					aberta (segurança, dados e regulação).
				</li>
			</ul>

			<h3>Desafios setoriais</h3>
			<ul>
				<li>
					<strong>Limitações na sustentabilidade e autonomia organizacional na área da saúde</strong>,
					incluindo ao nível de carreiras (duais/tempo protegido), avaliação regular, rede e escala, e
					centralidade do impacto em saúde pública e em políticas públicas.
				</li>
				<li>
					<strong
						>Constrangimentos de autonomia, financiamento e infraestruturas nos Laboratórios do Estado</strong
					>, bem como de coordenação e governança para prioridades científicas (ex.: oceano, clima e
					desafios territoriais).
				</li>
				<li>
					<strong>Desigualdade de tratamento do ensino superior privado</strong> no acesso a financiamento
					público (ex.: PRR), apesar de exigências de qualidade semelhantes.
				</li>
				<li>
					<strong>Persistência de precariedade e elevada carga administrativa nos politécnicos</strong> (com
					impacto maior no interior), associada à perceção de enviesamentos na avaliação e à
					<strong>necessidade de clarificação de papéis institucionais</strong>.
				</li>
				<li>
					<strong>Subvalorização da inovação</strong> desenvolvida em Portugal quando a
					<strong>propriedade intelectual é registada noutros países</strong>, com efeitos adversos nos
					indicadores nacionais.
				</li>
			</ul>

			<h3>Prioridades para a atuação da AI² (Pergunta 2)</h3>
			<ul>
				<li>
					<strong
						>Governança estável/independente/plurianual e cultura organizacional integrada/horizontal</strong
					>, com processos claros de acompanhamento, reporte e articulação consultiva (incl. papel do CNCTI).
				</li>
				<li>
					<strong>Arquitetura funcional “em rede”</strong>, assente numa coordenação estratégica central com
					delegação operacional especializada; segmentação funcional com coordenação; proximidade ao terreno
					e orientação aos utilizadores; avaliação por impacto.
				</li>
				<li>
					<strong>Financiamento previsível/plurianual</strong> e, quando aplicável,
					<strong>modelos híbridos</strong> (base + competitivo por missões/serviços) para sustentabilidade
					institucional, planeamento e eficiência.
				</li>
				<li>
					<strong
						>Instrumentos integrados e contínuos ao longo da cadeia de valor, em programas multi-instrumento</strong
					>
					que assegurem progressão e escala, com mediação/cocriação e valorização do conhecimento, evitando
					ruturas entre fases (sobretudo iniciais e intermédias).
				</li>
				<li>
					<strong>Simplificação administrativa e melhoria na previsibilidade e no desenho dos concursos</strong>
					(incl. múltiplos momentos de candidatura e resubmissão), com foco em resultados/impacto e não
					apenas despesa.
				</li>
				<li>
					<strong>Avaliação e escrutínio reforçados</strong>: com painéis internacionais, diversidade de
					métricas, consideração de múltiplos tipos de impacto (científico, económico, social, cultural,
					ambiental e em políticas públicas) e controlo de qualidade a posteriori, suportados por
					monitorização sistemática para ajustamento de prioridades e instrumentos.
				</li>
				<li>
					<strong>Proteção explícita da investigação fundamental e modelo misto bottom-up/top-down</strong>
					(missões/temas-chave sem prescrição de trajetórias), assegurando adicionalidade.
				</li>
				<li>
					<strong>Domínios estratégicos definidos por critérios explícitos</strong> (soberania/interesse
					nacional, capacidade instalada, alinhamento europeu com especificidade nacional e potencial de
					valor), geridos por <strong>portefólio adaptativo</strong> (revisão periódica e não exclusividade),
					com proteção de <strong>emergentes/unknowns e espaço para blue sky</strong>.
				</li>
				<li>
					<strong>Valorização e transferência de conhecimento</strong>, ao nível da standardização de
					processos de Transferência de tecnologia (TT)/Propriedade Intelectual (PI); instrumentos claros de
					valorização (spinoffs, PI, métricas de impacto); programas multi-instrumento integrados.
				</li>
				<li>
					<strong>Mobilização de investimento privado</strong> (capital de risco; business angels; incentivos
					fiscais) com estabilidade e avaliação baseada em evidência; partilha de risco e instrumentos ágeis.
				</li>
				<li>
					<strong>Aposta nas carreiras e emprego científico</strong>, assegurando critérios de estabilidade
					laboral nos instrumentos; transição para modelos contratuais mais estáveis; mobilidade
					intersetorial; valorização de funções de gestão de ciência.
				</li>
				<li>
					<strong>Infraestruturas e redes: avaliação regular e financiamento sustentado</strong> (incl.
					operação/manutenção/pessoal especializado); gestão em rede; articulação interdisciplinar.
				</li>
				<li>
					<strong>Coesão territorial incorporada nos instrumentos</strong>, com critérios/métricas
					territoriais; abordagens diferenciadas para ilhas/baixa densidade/interior; financiamento orientado
					ao impacto territorial.
				</li>
				<li>
					<strong>Reforço da ligação ciência-sociedade</strong>, assente em mecanismos estruturados de
					participação pública e literacia; atração para STEM; ciência cidadã; atenção às tensões de ciência
					aberta.
				</li>
				<li>
					<strong>Promoção da internacionalização e diáspora</strong>, com mecanismos formais de envolvimento
					em consulta/avaliação/projetos e diplomacia científica.
				</li>
			</ul>

			<h3>Prioridades setoriais</h3>
			<ul>
				<li>
					<strong>Saúde</strong>: financiamento híbrido; autonomia efetiva com responsabilização; carreiras
					duais/tempo protegido; rede para escala; investigação clínica/translacional e impacto em saúde
					pública/políticas públicas.
				</li>
				<li>
					<strong>Laboratórios do Estado</strong>: reforço de autonomia e condições de
					financiamento/infraestruturas em coordenação com a agência, para responder a prioridades científicas
					setoriais (ex.: oceano/clima/território) e reforçar coordenação/governança.
				</li>
				<li>
					<strong>Ensino superior privado</strong> (equidade): regras claras e proporcionais que removam
					desigualdades no acesso a financiamento público, mantendo critérios de qualidade/impacto.
				</li>
				<li>
					<strong>Politécnicos</strong> (clarificação de papéis): clarificação de papéis institucionais e
					resposta a precariedade/encargos administrativos, em quadro de longo prazo.
				</li>
			</ul>

			<p>
				<strong>Lista de entidades participantes nas reuniões</strong> (por ordem alfabética):
				Agência de Investigação Clínica e Inovação Biomédica (AICIB), Agência para a Competitividade e
				Inovação, I.P. (IAPMEI), Agência para o Desenvolvimento e Coesão, I. P. (Ad&amp;C), Aliança
				Portuguesa de Centros de Tecnologia e Inovação (CTI Alliance), Associação de Pós-Graduados
				Portugueses na Alemanha (ASPPA), Associação dos Bolseiros de Investigação Científica (ABIC),
				Associação dos Graduados Portugueses na Suiça (AGRAPS), Associação Empresarial para a Inovação
				(COTEC), Associação Nacional de Investigadores em Ciência e Tecnologia (ANICT), Associação
				Nacional de Jovens Empresários (ANJE), Associação Portuguesa de Investidores Early Stage -
				Investors Portugal (APIES), Associação Portuguesa de Parques de Ciência e Tecnologia (TecParques),
				Associação Portuguesa do Ensino Superior Privado (APESP), Associação Portuguesa para a Gestão de
				Ciência (SCIGEST.PT), Atlantic International Research Centre (Air Centre), Centro Científico e
				Cultural de Macau (CCCM), CCDR Alentejo, CCDR Algarve, CCDR Norte, Ciência Viva (Agência Nacional
				para a Cultura Científica e Tecnológica), Comissão de Ética de Investigação Clínica (CEIC),
				Comunidade Intermunicipal da Região de Aveiro, Comunidade Intermunicipal da Região de Coimbra,
				Comunidade Intermunicipal do Alto Tâmega e Barroso, Comunidade Intermunicipal do Oeste, Comunidade
				Intermunicipal do Tâmega e Sousa, Confederação Empresarial de Portugal (CIP), Conselho Consultivo
				Estratégico (CNCTI), Conselho Coordenador do Roteiro Nacional de Infraestruturas de Investigação
				de Interesse Estratégico (CC-RNIE), Conselho Coordenador dos Institutos Superiores Politécnicos
				(CCISP), Conselho de Reitores das Universidades Portuguesas (CRUP), Conselho dos Laboratórios
				Associados (CLA), Conselho Nacional dos Centros Académicos Clínicos, Conselhos Científicos da FCT,
				I. P., Direção Regional da Ciência, Inovação e Desenvolvimento (Açores), FENPROF, FESAP, Fórum dos
				Conselhos Científicos dos Laboratórios do Estado (Fórum CCs LE), Fórum dos Laboratórios
				Colaborativos (FCoLAB), Gabinete da Secretária Regional de Educação, Ciência e Tecnologia (Madeira),
				Grupo Banco Português de Fomento, Grupo de Trabalho para a revisão da Lei da Ciência, Grupo de
				Trabalho para análise do Ecossistema Nacional de Investigação e Inovação, IdD Portugal Defence,
				IMPIC - Instituto dos Mercado Públicos, do Imobiliário e da Construção, Instituto Hidrográfico,
				Instituto Nacional da Propriedade Industrial, I. P. (INPI), Instituto Nacional de Investigação
				Agrária e Veterinária (INIAV), Instituto Nacional de Saúde Doutor Ricardo Jorge (INSA), Instituto
				Português da Qualidade (IPQ), Instituto Português do Mar e da Atmosfera, I. P. (IPMA), Investimento
				e Comércio Externo de Portugal, E.P.E. (AICEP), Laboratório Ibérico Internacional de Nanotecnologia
				(INL), Laboratório Nacional de Engenharia Civil (LNEC), Organização dos Trabalhadores Científicos
				(OTC), Portugal Ventures, Portuguese American Postgraduate Society (PAPS), Portuguese Association
				of Researchers and Students in the United Kingdom (PARSUK), Programa Regional Açores 2030 - Direção
				Regional do Planeamento e Fundos Estruturais, Programa Temático Inovação e Transição Digital -
				Compete 2030, PT Space (Agência Espacial Portuguesa), SNESUP, SPOT Nordic, Startup Portugal -
				Associação Portuguesa para a Promoção do Empreendedorismo, Venture Studios.
			</p>
		{:else}
			<p>
				Stakeholder meetings aim to gather perspectives and contributions from strategic entities
				identified in the Strategic Assessment governance framework (see Annex 2 of the
				<a href={asset('/docs/RelatMetod_PT.pdf')} target="_blank" rel="noreferrer"
					>methodology document</a
				> in Portuguese). Between 10 March and 8 April 2026, 17 online meetings were held with 65 of the
				95 invited entities (list below). Moderation was provided by the General Coordinator of the Strategic
				Assessment, Professor Maria do Rosário Partidário. Observers at these meetings included experts
				from the Strategic Assessment team (FCT and ANI), PLANAPP, DGE, DGEPA, and staff from the offices
				of the Secretary of State for Science and Innovation and the Secretary of State for the Economy.
			</p>

			<p>
				<strong>Guiding questions for the dialogue:</strong> Considering the 2050 vision defined for the
				strategic assessment (“Portugal asserts itself as a country that creates talent and knowledge and
				transforms them into economic, social, cultural and environmental value, with a dynamic research and
				innovation system, interconnected in national and international networks, competitive and oriented
				towards excellence, combining a sustainable and inclusive development model, strengthening its
				position in Europe and the world”), from the perspective of the entities consulted:
			</p>
			<ol>
				<li>
					What are the <strong>major long-term challenges</strong> facing the organisation and activity of
					AI2, particularly with regard to investment in research and innovation.
				</li>
				<li>
					What are the <strong>major priorities for AI2 action</strong> to meet the established vision.
				</li>
			</ol>

			<h2>Global synthesis of contributions</h2>
			<p>
				<em
					>(built from the records of the 17 meetings, organised and analysed to preserve the diversity
					of contributions, then structured in a cross-cutting thematic matrix and, finally,
					consolidated into a systemic synthesis of strategic challenges and priorities, based on AI
					validated by human review and supported by meeting notes and records)</em
				>
			</p>

			<h3>Long-term challenges (Question 1)</h3>
			<ul>
				<li>
					Strategic instability and institutional discontinuity, resulting from strong dependence on
					political cycles, frequent reforms and volatile orientations, undermining predictability,
					long-term planning and consolidation of R&amp;I policies.
				</li>
				<li>
					Limitations in the predictability and sustainability of funding (multi-year, regular and
					baseline/hybrid), maintaining structural dependence on European funds and extraordinary
					instruments.
				</li>
				<li>
					Difficulties in effective integration between research and innovation along the value chain
					(including the transition “from idea to market”, TRL and translation), in an ecosystem marked by
					fragmentation and insufficient intermediate mediation.
				</li>
				<li>
					Need for greater administrative simplification and efficiency in the face of high bureaucracy
					and disproportionate focus on expenditure, with evaluation of results and impact considered weak.
				</li>
				<li>
					Weaknesses in the robustness and credibility of evaluation and scrutiny models, requiring
					diversity of metrics, international panels and ex-post quality control, and avoiding simplistic
					readings of impact.
				</li>
				<li>
					Insufficient explicit protection of fundamental research and its balance with impact-oriented
					research and innovation, avoiding subordination to immediate returns and preserving disciplinary
					diversity.
				</li>
				<li>
					Low attractiveness and sustainability of scientific careers and employment, including
					precariousness, weak predictability, limited contractual models, reduced intersectoral mobility
					and weak integration of doctorates outside academia.
				</li>
				<li>
					Constraints on the funding and operationalisation of infrastructures (scientific and interface),
					including maintenance and operation, regular evaluation and networked operation, after prolonged
					periods of underfunding.
				</li>
				<li>
					Weak territorial cohesion in a system with regional asymmetries (including islands, low-density
					territories and inland areas) in scientific and interface capacity, access to funding, business
					scale and innovation intensity.
				</li>
				<li>
					Need for functional and clear governance (“by design”) in a fragmented system, ensuring functional
					segmentation with coordination, entry/exit rules, proximity to the field and user orientation.
				</li>
				<li>
					Difficulties in defining strategic domains with an adaptive portfolio, avoiding closed lists,
					ensuring clear criteria and differentiating domains by maturity, risk and time horizon, with
					protection of emerging areas and room for unknowns and blue sky outside the domains.
				</li>
				<li>
					Weaknesses in the articulation between science and society, including literacy, attraction to
					STEM, structured public participation and management of tensions associated with open science
					(security, data and regulation).
				</li>
			</ul>

			<h3>Sectoral challenges</h3>
			<ul>
				<li>
					Limitations in sustainability and organisational autonomy in health, including at career level
					(dual/protected time), regular evaluation, network and scale, and centrality of impact on public
					health and public policies.
				</li>
				<li>
					Constraints on autonomy, funding and infrastructures in State Laboratories, as well as
					coordination and governance for scientific priorities (e.g. ocean, climate and territorial
					challenges).
				</li>
				<li>
					Unequal treatment of private higher education in access to public funding (e.g. PRR), despite
					similar quality requirements.
				</li>
				<li>
					Persistence of precariousness and high administrative burden in polytechnics (with greater impact
					inland), associated with perceived biases in evaluation and the need to clarify institutional
					roles.
				</li>
				<li>
					Undervaluation of innovation developed in Portugal when intellectual property is registered in
					other countries, with adverse effects on national indicators.
				</li>
			</ul>

			<h3>Priorities for AI2 action (Question 2)</h3>
			<ul>
				<li>
					Stable/independent/multi-year governance and integrated/horizontal organisational culture, with
					clear monitoring, reporting and consultative articulation processes (incl. role of CNCTI).
				</li>
				<li>
					Functional “network” architecture, based on central strategic coordination with specialised
					operational delegation; functional segmentation with coordination; proximity to the field and
					user orientation; impact-based evaluation.
				</li>
				<li>
					Predictable/multi-year funding and, where applicable, hybrid models (base + competitive by
					missions/services) for institutional sustainability, planning and efficiency.
				</li>
				<li>
					Integrated and continuous instruments along the value chain, in multi-instrument programmes that
					ensure progression and scale, with mediation/co-creation and knowledge valorisation, avoiding
					breaks between phases (especially initial and intermediate).
				</li>
				<li>
					Administrative simplification and improved predictability and design of calls (incl. multiple
					application windows and resubmission), with focus on results/impact and not only expenditure.
				</li>
				<li>
					Strengthened evaluation and scrutiny: with international panels, diversity of metrics,
					consideration of multiple types of impact (scientific, economic, social, cultural, environmental
					and on public policies) and ex-post quality control, supported by systematic monitoring to adjust
					priorities and instruments.
				</li>
				<li>
					Explicit protection of fundamental research and mixed bottom-up/top-down model (missions/key
					themes without prescribing trajectories), ensuring additionality.
				</li>
				<li>
					Strategic domains defined by explicit criteria (sovereignty/national interest, installed
					capacity, European alignment with national specificity and value potential), managed by adaptive
					portfolio (periodic review and non-exclusivity), with protection of emergents/unknowns and space
					for blue sky.
				</li>
				<li>
					Knowledge valorisation and transfer, at the level of standardisation of Technology Transfer (TT)
					/ Intellectual Property (IP) processes; clear valorisation instruments (spinoffs, IP, impact
					metrics); integrated multi-instrument programmes.
				</li>
				<li>
					Mobilisation of private investment (venture capital; business angels; tax incentives) with
					stability and evidence-based evaluation; risk sharing and agile instruments.
				</li>
				<li>
					Commitment to careers and scientific employment, ensuring labour stability criteria in
					instruments; transition to more stable contractual models; intersectoral mobility; valorisation of
					science management functions.
				</li>
				<li>
					Infrastructures and networks: regular evaluation and sustained funding (incl.
					operation/maintenance/specialised staff); network management; interdisciplinary articulation.
				</li>
				<li>
					Territorial cohesion incorporated in instruments, with territorial criteria/metrics; differentiated
					approaches for islands/low density/inland; funding oriented to territorial impact.
				</li>
				<li>
					Strengthening the science-society link, based on structured public participation and literacy
					mechanisms; attraction to STEM; citizen science; attention to open science tensions.
				</li>
				<li>
					Promotion of internationalisation and diaspora, with formal mechanisms for involvement in
					consultation/evaluation/projects and science diplomacy.
				</li>
			</ul>

			<h3>Sectoral priorities</h3>
			<ul>
				<li>
					<strong>Health</strong>: hybrid funding; effective autonomy with accountability; dual careers/protected
					time; network for scale; clinical/translational research and impact on public health/public policies.
				</li>
				<li>
					<strong>State Laboratories</strong>: strengthening autonomy and funding/infrastructure conditions in
					coordination with the agency, to respond to sectoral scientific priorities (e.g.
					ocean/climate/territory) and strengthen coordination/governance.
				</li>
				<li>
					<strong>Private higher education</strong> (equity): clear and proportional rules that remove
					inequalities in access to public funding, maintaining quality/impact criteria.
				</li>
				<li>
					<strong>Polytechnics</strong> (role clarification): clarification of institutional roles and response
					to precariousness/administrative burdens, in a long-term framework.
				</li>
			</ul>

			<p>
				<strong>List of entities participating in the meetings</strong> (alphabetical order):
				Agência de Investigação Clínica e Inovação Biomédica (AICIB), Agência para a Competitividade e
				Inovação, I.P. (IAPMEI), Agência para o Desenvolvimento e Coesão, I. P. (Ad&amp;C), Aliança
				Portuguesa de Centros de Tecnologia e Inovação (CTI Alliance), Associação de Pós-Graduados
				Portugueses na Alemanha (ASPPA), Associação dos Bolseiros de Investigação Científica (ABIC),
				Associação dos Graduados Portugueses na Suiça (AGRAPS), Associação Empresarial para a Inovação
				(COTEC), Associação Nacional de Investigadores em Ciência e Tecnologia (ANICT), Associação
				Nacional de Jovens Empresários (ANJE), Associação Portuguesa de Investidores Early Stage -
				Investors Portugal (APIES), Associação Portuguesa de Parques de Ciência e Tecnologia (TecParques),
				Associação Portuguesa do Ensino Superior Privado (APESP), Associação Portuguesa para a Gestão de
				Ciência (SCIGEST.PT), Atlantic International Research Centre (Air Centre), Centro Científico e
				Cultural de Macau (CCCM), CCDR Alentejo, CCDR Algarve, CCDR Norte, Ciência Viva (Agência Nacional
				para a Cultura Científica e Tecnológica), Comissão de Ética de Investigação Clínica (CEIC),
				Comunidade Intermunicipal da Região de Aveiro, Comunidade Intermunicipal da Região de Coimbra,
				Comunidade Intermunicipal do Alto Tâmega e Barroso, Comunidade Intermunicipal do Oeste, Comunidade
				Intermunicipal do Tâmega e Sousa, Confederação Empresarial de Portugal (CIP), Conselho Consultivo
				Estratégico (CNCTI), Conselho Coordenador do Roteiro Nacional de Infraestruturas de Investigação
				de Interesse Estratégico (CC-RNIE), Conselho Coordenador dos Institutos Superiores Politécnicos
				(CCISP), Conselho de Reitores das Universidades Portuguesas (CRUP), Conselho dos Laboratórios
				Associados (CLA), Conselho Nacional dos Centros Académicos Clínicos, Conselhos Científicos da FCT,
				I. P., Direção Regional da Ciência, Inovação e Desenvolvimento (Açores), FENPROF, FESAP, Fórum dos
				Conselhos Científicos dos Laboratórios do Estado (Fórum CCs LE), Fórum dos Laboratórios
				Colaborativos (FCoLAB), Gabinete da Secretária Regional de Educação, Ciência e Tecnologia (Madeira),
				Grupo Banco Português de Fomento, Grupo de Trabalho para a revisão da Lei da Ciência, Grupo de
				Trabalho para análise do Ecossistema Nacional de Investigação e Inovação, IdD Portugal Defence,
				IMPIC - Instituto dos Mercado Públicos, do Imobiliário e da Construção, Instituto Hidrográfico,
				Instituto Nacional da Propriedade Industrial, I. P. (INPI), Instituto Nacional de Investigação
				Agrária e Veterinária (INIAV), Instituto Nacional de Saúde Doutor Ricardo Jorge (INSA), Instituto
				Português da Qualidade (IPQ), Instituto Português do Mar e da Atmosfera, I. P. (IPMA), Investimento
				e Comércio Externo de Portugal, E.P.E. (AICEP), Laboratório Ibérico Internacional de Nanotecnologia
				(INL), Laboratório Nacional de Engenharia Civil (LNEC), Organização dos Trabalhadores Científicos
				(OTC), Portugal Ventures, Portuguese American Postgraduate Society (PAPS), Portuguese Association
				of Researchers and Students in the United Kingdom (PARSUK), Programa Regional Açores 2030 - Direção
				Regional do Planeamento e Fundos Estruturais, Programa Temático Inovação e Transição Digital -
				Compete 2030, PT Space (Agência Espacial Portuguesa), SNESUP, SPOT Nordic, Startup Portugal -
				Associação Portuguesa para a Promoção do Empreendedorismo, Venture Studios.
			</p>
		{/if}
	</div>
</div>

<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Da Ideia ao Mercado (e do Mercado à Ideia)' : 'From Idea to Market (and from Market to Idea)'} />
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
			<h3>Mesa Temática “Da ideia ao mercado (e do mercado à ideia)” (15 de abril, 15h)</h3>
			
						<p>
							<strong
								>Valorização do conhecimento apresenta barreiras sistémicas, que vão para além dos
								desafios no setor da Ciência e Inovação.</strong
							>
							Existe capacidade de produção de conhecimento reconhecida, com massa crítica relevante no setor
							académico. No entanto, as instituições funcionam de forma pouco articulada, com fraca continuidade
							ao longo da cadeia de valor, comprometendo a transformação do conhecimento em impacto económico
							e societal. O percurso entre a descoberta e a sua transformação em valor é irregular e estruturalmente
							interrompido nas fases intermédias (validação, prototipagem e demonstração).
						</p>
						<p>
							<strong
								>Transferência tardia de resultados científicos para o mercado; a construção de
								ecossistemas colaborativos de I&amp;I é determinante.</strong
							>
							A ligação entre academia e o setor empresarial não é apenas um problema do lado da oferta. O tecido
							empresarial é dominado por micro e PME sem capacidade de escala nem qualificação interna dos recursos
							afetos à I&amp;D para absorver investigação, co-financiar validação, identificar oportunidades
							geradas pela produção científica, ou manter colaborações de longa duração. As linhas temporais
							da investigação e da inovação são estruturalmente diferentes.
						</p>
						<p>
							<strong
								>Definição de incentivos e mecanismos de financiamento que respondam às necessidades
								sistémicas, reforço das infraestruturas e governança articulada.</strong
							>
							As carreiras científicas e académicas não incentivam nem têm mecanismos de avaliação de percursos
							não-tradicionais. O modelo de governação e articulação entre os vários atores (Estado, empresas,
							universidades e entidades de intermediação) para definir políticas e gerir recursos terá de evoluir,
							por forma a assegurar coerência entre incentivos, instrumentos de financiamento e investimento
							em infraestruturas, para garantir que gera valor.
						</p>
			
						<h4>
							1) Valorização do conhecimento apresenta barreiras sistémicas, que vão para além dos
							desafios no setor da Ciência e Inovação
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								Existência de massa crítica científica e tecnológica. O sistema demonstra elevada
								capacidade de produção de conhecimento, reconhecida como ponto de partida sólido para a
								valorização económica.
							</li>
							<li>
								Diversidade de atores institucionais com competências complementares. Existência de uma
								base de entidades em várias áreas estratégicas e cobrindo os setores académico,
								empresarial, centros e infraestruturas de interface, sociedade civil e governança,
								potenciam um ecossistema mais integrado, com capacidade de estruturar consórcios completos
								ao longo da cadeia de valor.
							</li>
							<li>
								Oportunidade para reformas estruturais. O reconhecimento generalizado dos constrangimentos
								existentes cria condições favoráveis para reformas estruturais, representando uma
								oportunidade única para corrigir a fragmentação e fragilidade sistémica.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>
								Descontinuidade ao longo da cadeia de valor do conhecimento e inovação. A transição entre
								prova de conceito e demonstração em contexto real constitui uma barreira. Esta fase
								intermédia está sub-financiada e faltam mecanismos contínuos de articulação e progressão.
							</li>
							<li>
								Fragmentação institucional e fraca articulação entre atores. A cooperação é pouco
								estruturada e dependente de iniciativas individuais, frequentemente informal, dificultando
								trajetórias contínuas até ao mercado. O setor académico e o setor não-académico, em
								particular as empresas, revelam desconhecimento mútuo, representando uma debilidade
								permanente que afeta a eficiência sistémica.
							</li>
							<li>
								Governança e instrumentos de financiamento incoerente. Os instrumentos públicos não
								distinguem adequadamente entre investigação exploratória, validação e escala, e não
								estabelecem mecanismos ágeis ao longo do ciclo de vida dos projetos. Persistem
								desalinhamentos entre estratégias, programas de financiamento e necessidades reais do
								sistema.
							</li>
						</ul>
						<h4>
							2) Transferência tardia de resultados científicos para o mercado; a construção de
							ecossistemas colaborativos de I&amp;I é determinante
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								Casos de sucesso demonstram viabilidade dos ecossistemas colaborativos. O envolvimento
								precoce de empresas e utilizadores finais, aumenta a adequação tecnológica e a
								probabilidade de adoção.
							</li>
							<li>
								Estrutura das empresas e suas áreas de atuação como mapa estratégico. As empresas com
								I&amp;D formal e com demonstrada competitividade ao nível de infraestruturas e recursos
								humanos permitem identificar os domínios onde ecossistemas colaborativos poderão ser mais
								viáveis a curto prazo.
							</li>
							<li>
								Interesse real e disponibilidade em colaborar. O espírito colaborativo institucional
								existe, desde que os mecanismos sejam transparentes, o risco partilhado, e o timing de
								resposta do sistema científico compatível com o ritmo de decisão das empresas (e
								vice-versa). O sistema científico revela competência técnica para responder a problemas
								complexos, quando estes são bem definidos.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>
								Problema estrutural de escala empresarial. Tecido empresarial composto maioritariamente
								por micro e PME, com reduzida capacidade de escala. Dificuldade de as empresas absorverem
								doutorados, co-financiarem validação, ou manterem colaborações de longa duração.
							</li>
							<li>
								Qualificação empresarial insuficiente para a I&amp;D e fragilidade sistémica para a
								intermediação. As empresas têm escassez de trabalhadores com qualificações adequadas para
								a I&amp;D. Acrescenta-se a escassez de perfis especializados em desenvolvimento de negócio
								e inovação aplicada, capazes de traduzir conhecimento científico em oportunidades de
								mercado, principalmente no setor académico.
							</li>
							<li>
								Envolvimento do mercado e linhas temporais. Em muitos casos, a integração do mercado
								ocorre quando as soluções já estão “fechadas”, limitando ajustes, adaptação ao contexto
								real e viabilidade comercial. Persistem barreiras ao nível de tempos de decisão,
								expectativas de resultados, critérios de sucesso e formas de comunicação que afetam
								colaborações estáveis e duradoras.
							</li>
						</ul>
						<h4>
							3) Definição de incentivos e mecanismos de financiamento que respondam às necessidades
							sistémicas, reforço das infraestruturas e governança articulada
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								Reconhecimento de consensos alargados. É reconhecida a necessidade de rever carreiras,
								incentivos académicos e modelos de avaliação, e de reforçar as fases de validação,
								demonstração e prototipagem.
							</li>
							<li>
								Capacidade comprovada de gerar impacto quando os modelos são adequados. O sistema revela
								capacidade de produzir soluções adequadas ao mercado, desde que o enquadramento seja
								correto, o que reduz a incerteza da intervenção.
							</li>
							<li>
								Mecanismos operacionais estão identificados. Financiamento faseado ajustado ao risco e
								maturidade dos projetos, redes de infraestruturas de validação, métricas de impacto e
								modelos de governação orientada para valor.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>
								Carreiras académicas que não incentivam a inovação e percursos não-tradicionais. A
								progressão na carreira continua a depender da produção científica. A colaboração com
								empresas, a participação em validação comercial ou projetos com componente de mercado têm
								contributo marginal.
							</li>
							<li>
								Fragilidade e fragmentação das infraestruturas. As infraestruturas de validação,
								prototipagem e demonstração já existem parcialmente, mas estão insuficientemente mapeadas,
								articuladas e visíveis para os utilizadores do sistema.
							</li>
							<li>
								Governança e sistemas de avaliação pouco orientados para o impacto. A formação doutoral
								prepara, predominantemente, para o contexto académico. Os mecanismos de avaliação induzem
								comportamentos indesejados — patentes sem aplicação, spin-offs precoces, colaborações
								formais sem substância. Persistem modelos focados na execução administrativa de programas,
								em detrimento da criação efetiva de valor.
							</li>
						</ul>
		{:else}
			<h3>Thematic Table “From idea to market (and from market to idea)” (15 April, 15:00)</h3>
			
						<p>
							<strong
								>Knowledge valorisation presents systemic barriers that go beyond challenges in the
								Science and Innovation sector.</strong
							>
							There is recognised knowledge-production capacity, with relevant critical mass in the academic
							sector. However, institutions operate in a poorly coordinated way, with weak continuity along
							the value chain, compromising the transformation of knowledge into economic and societal impact.
							The path from discovery to its transformation into value is uneven and structurally interrupted
							in the intermediate phases (validation, prototyping and demonstration).
						</p>
						<p>
							<strong
								>Late transfer of scientific results to the market; building collaborative R&amp;I
								ecosystems is decisive.</strong
							>
							The connection between academia and the business sector is not only a supply-side problem. The
							business fabric is dominated by micro and SME companies without the scale or internal qualification
							of resources allocated to R&amp;D needed to absorb research, co-finance validation, identify opportunities
							generated by scientific production, or maintain long-term collaborations. Research and innovation
							timelines are structurally different.
						</p>
						<p>
							<strong
								>Definition of incentives and funding mechanisms that respond to systemic needs,
								strengthening of infrastructures and coordinated governance.</strong
							>
							Scientific and academic careers neither incentivise nor include evaluation mechanisms for non-traditional
							pathways. The governance and coordination model among the various actors (State, companies, universities
							and intermediary entities) for defining policies and managing resources will have to evolve in
							order to ensure coherence between incentives, funding instruments and investment in infrastructures,
							to ensure that value is generated.
						</p>
			
						<h4>
							1) Knowledge valorisation presents systemic barriers that go beyond challenges in the
							Science and Innovation sector
						</h4>
			
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								Existence of scientific and technological critical mass. The system demonstrates high
								knowledge-production capacity, recognised as a solid starting point for economic
								valorisation.
							</li>
							<li>
								Diversity of institutional actors with complementary skills. The existence of a base of
								entities in various strategic areas and covering the academic and business sectors,
								interface centres and infrastructures, civil society and governance fosters a more
								integrated ecosystem, with capacity to structure complete consortia along the value chain.
							</li>
							<li>
								Opportunity for structural reforms. The widespread recognition of existing constraints
								creates favourable conditions for structural reforms, representing a unique opportunity to
								correct fragmentation and systemic fragility.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>
								Discontinuity along the knowledge and innovation value chain. The transition between proof
								of concept and demonstration in a real-world context is a barrier. This intermediate phase
								is underfunded and continuous mechanisms for coordination and progression are lacking.
							</li>
							<li>
								Institutional fragmentation and weak coordination between actors. Cooperation is poorly
								structured and dependent on individual initiatives, often informal, making continuous
								paths to market difficult. The academic and non-academic sectors, particularly companies,
								show mutual lack of awareness, representing a persistent weakness that affects systemic
								efficiency.
							</li>
							<li>
								Incoherent governance and funding instruments. Public instruments do not adequately
								distinguish between exploratory research, validation and scaling, and do not establish
								agile mechanisms throughout the project life cycle. Misalignments persist between
								strategies, funding programmes and the system's real needs.
							</li>
						</ul>
						<h4>
							2) Late transfer of scientific results to the market; building collaborative R&amp;I
							ecosystems is decisive
						</h4>
			
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								Success stories demonstrate the viability of collaborative ecosystems. Early involvement
								of companies and end users increases technological adequacy and the likelihood of
								adoption.
							</li>
							<li>
								Company structure and areas of activity as a strategic map. Companies with formal R&amp;D
								and demonstrated competitiveness in terms of infrastructures and human resources make it
								possible to identify the domains where collaborative ecosystems may be most viable in the
								short term.
							</li>
							<li>
								Real interest and willingness to collaborate. Institutional collaborative spirit exists,
								provided that mechanisms are transparent, risk is shared, and the response timing of the
								scientific system is compatible with companies' decision-making pace (and vice versa). The
								scientific system shows technical competence to respond to complex problems when these are
								well defined.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>
								Structural problem of business scale. Business fabric made up mostly of micro and SME
								companies, with limited scale capacity. Difficulty for companies to absorb PhD holders,
								co-finance validation, or maintain long-term collaborations.
							</li>
							<li>
								Insufficient business qualification for R&amp;D and systemic fragility in intermediation.
								Companies have a shortage of workers with suitable qualifications for R&amp;D. Added to
								this is a shortage of profiles specialised in business development and applied innovation,
								capable of translating scientific knowledge into market opportunities, especially in the
								academic sector.
							</li>
							<li>
								Market involvement and timelines. In many cases, market integration occurs when solutions
								are already “closed”, limiting adjustments, adaptation to real-world context and
								commercial viability. Barriers persist in decision times, expectations about results,
								success criteria and forms of communication, affecting stable and lasting collaborations.
							</li>
						</ul>
						<h4>
							3) Definition of incentives and funding mechanisms that respond to systemic needs,
							strengthening of infrastructures and coordinated governance
						</h4>
			
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								Recognition of broad consensus. The need to review careers, academic incentives and
								evaluation models is recognised, as is the need to strengthen validation, demonstration
								and prototyping phases.
							</li>
							<li>
								Proven capacity to generate impact when models are appropriate. The system shows capacity
								to produce market-appropriate solutions, provided the framework is correct, reducing the
								uncertainty of intervention.
							</li>
							<li>
								Operational mechanisms are identified. Phased funding adjusted to project risk and
								maturity, networks of validation infrastructures, impact metrics and value-oriented
								governance models.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>
								Academic careers that do not incentivise innovation and non-traditional pathways. Career
								progression continues to depend on scientific production. Collaboration with companies,
								participation in commercial validation or projects with a market component have only a
								marginal contribution.
							</li>
							<li>
								Fragility and fragmentation of infrastructures. Validation, prototyping and demonstration
								infrastructures already exist in part, but are insufficiently mapped, coordinated and
								visible to system users.
							</li>
							<li>
								Governance and evaluation systems insufficiently oriented towards impact. Doctoral
								training prepares mostly for the academic context. Evaluation mechanisms induce
								undesirable behaviours - patents without application, premature spin-offs, formal
								collaborations without substance. Models focused on administrative execution of programmes
								persist, to the detriment of effective value creation.
							</li>
						</ul>
		{/if}
	</div>
</div>

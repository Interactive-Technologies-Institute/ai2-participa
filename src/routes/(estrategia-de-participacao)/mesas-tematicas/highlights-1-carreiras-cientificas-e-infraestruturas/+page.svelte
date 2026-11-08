<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Carreiras Científicas e Infraestruturas' : 'Scientific Careers and Infrastructures'} />
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
			<h3>Mesa Temática “Carreiras científicas e infraestruturas” (15 abril, 10h)</h3>
			
						<p>
							<strong
								>Carreiras científicas: precariedade e baixa previsibilidade vs. mobilidade e percursos
								diversificados.</strong
							>
							As carreiras continuam marcadas por instabilidade, dependência de instrumentos temporários e baixa
							previsibilidade, apesar do reconhecimento da mobilidade, das competências transversais e da diversificação
							de percursos como fatores importantes, ainda que não devidamente reconhecidos, para o sistema.
						</p>
						<p>
							<strong
								>Talento: retenção e integração frágeis vs. base qualificada e capacidade de atração.</strong
							>
							O sistema dispõe de uma base alargada de talento qualificado e alguma capacidade de atração internacional,
							sobretudo em fases iniciais, mas enfrenta dificuldades na retenção, integração e valorização de
							perfis em fases intermédias e avançadas.
						</p>
						<p>
							<strong
								>Infraestruturas científicas e tecnológicas: sustentabilidade e articulação insuficientes
								vs. capacidade instalada relevante.</strong
							>
							Existem investimentos, equipamentos e capacidades relevantes, mas persistem fragilidades no financiamento,
							nos recursos humanos, na visibilidade dos serviços e na articulação entre infraestruturas científicas,
							tecnológicas e o sistema de inovação.
						</p>
			
						<h4>
							1) Carreiras científicas: precariedade e baixa previsibilidade vs. mobilidade e percursos
							diversificados
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								Existência de múltiplos contextos de atuação científica – academia, entidades de
								interface, empresas, infraestruturas e administração pública – com potencial para
								diversificar percursos de carreira.
							</li>
							<li>
								Reconhecimento da importância da mobilidade entre academia, empresas, entidades de
								interface, administração pública e infraestruturas.
							</li>
							<li>
								Identificação de competências transversais críticas para percursos mais diversos,
								mobilidade entre setores e integração ao longo da cadeia de valor do conhecimento.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>
								Precariedade prolongada e forte dependência de bolsas, contratos curtos e instrumentos
								temporários.
							</li>
							<li>
								Baixa previsibilidade do financiamento, limitando compromissos institucionais de médio e
								longo prazo.
							</li>
							<li>
								Baixa atratividade dos percursos científicos para perfis em início de carreira, face à
								instabilidade e à falta de previsibilidade.
							</li>
							<li>
								Reconhecimento ainda insuficiente de percursos diversos nos modelos de carreira,
								progressão e avaliação, devido a modelos de avaliação demasiados centrados em indicadores
								de produção quantitativos, penalizando percursos não tradicionais, a mobilidade setorial e
								a interdisciplinaridade.
							</li>
						</ul>
						<h4>
							2) Talento: base qualificada e capacidade de formação vs dificuldade na retenção de talento
							nacional e internacional
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								Base alargada de talento qualificado, resultante do reforço da formação avançada e do
								aumento do número de doutorados e investigadores.
							</li>
							<li>Capacidade de atração internacional, sobretudo em fases iniciais da carreira.</li>
							<li>
								Existência de talento já formado no sistema nacional, com experiência científica acumulada
								e potencial de valorização.
							</li>
							<li>
								Circulação internacional como oportunidade para reforçar redes, aprendizagem e abertura do
								sistema científico nacional.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>
								Dificuldade de retenção de talento, em particular em fases intermédias e avançadas da
								carreira.
							</li>
							<li>
								Condições de integração pouco competitivas face a outros sistemas científicos e à
								iniciativa privada, incluindo remuneração, financiamento inicial e “pacotes de arranque”.
							</li>
							<li>
								Fragilidade dos mecanismos de integração e continuidade para talento já formado no sistema
								nacional, sobretudo em fases intermédias da carreira.
							</li>
							<li>
								Diferenças territoriais e setoriais que condicionam a atração e retenção de talento, em
								função da massa crítica, proximidade a empresas, acesso a redes, infraestruturas,
								condições de integração e oportunidades de carreira.
							</li>
						</ul>
						<h4>
							3) Infraestruturas científicas e tecnológicas: capacidade instalada relevante vs
							sustentabilidade e articulação insuficientes
						</h4>
			
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>
								Existência de investimento relevante em equipamentos, infraestruturas e capacidades
								científicas e tecnológicas.
							</li>
							<li>
								Reconhecimento das infraestruturas como elementos estruturantes para o sistema nacional de
								I&amp;I.
							</li>
							<li>
								Capacidade das infraestruturas para agregar recursos, serviços, competências, dados e
								conhecimento.
							</li>
							<li>
								Potencial de ligação entre investigação, desenvolvimento tecnológico, prestação de
								serviços especializados, empresas, administração pública e outros utilizadores.
							</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>
								Sustentabilidade financeira frágil: no caso das infraestruturas científicas, financiamento
								insuficiente para operação, manutenção, renovação tecnológica e continuidade; no caso das
								infraestruturas tecnológicas e dos CTI, modelos de financiamento voláteis.
							</li>
							<li>
								Desalinhamento entre investimento em equipamentos e investimento em recursos humanos
								qualificados.
							</li>
							<li>
								Deficiente valorização dos perfis técnico-científicos de apoio, operação, gestão,
								curadoria de dados e ligação a utilizadores.
							</li>
							<li>
								Visibilidade e mapeamento insuficientes dos serviços, equipamentos e competências
								disponíveis, limitando acesso, partilha e utilização por empresas e outros utilizadores.
							</li>
							<li>
								Necessidade de clarificar e reforçar a articulação entre infraestruturas científicas e
								tecnológicas, nomeadamente em termos de complementaridade, governação, acesso e ligação ao
								sistema de inovação.
							</li>
						</ul>
		{:else}
			<h3>Thematic Table “Scientific careers and infrastructures” (15 April, 10:00)</h3>
			
						<p>
							<strong
								>Scientific careers: precariousness and low predictability vs. mobility and diversified
								pathways.</strong
							>
							Careers continue to be marked by instability, dependence on temporary instruments and low predictability,
							despite recognition of mobility, transversal skills and pathway diversification as important factors
							for the system, although still not duly recognised.
						</p>
						<p>
							<strong
								>Talent: fragile retention and integration vs. a qualified base and attraction capacity.</strong
							>
							The system has a broad base of qualified talent and some international attraction capacity, especially
							at early stages, but faces difficulties in retaining, integrating and valuing profiles at intermediate
							and advanced stages.
						</p>
						<p>
							<strong
								>Scientific and technological infrastructures: insufficient sustainability and
								coordination vs. relevant installed capacity.</strong
							>
							There are relevant investments, equipment and capabilities, but weaknesses persist in funding,
							human resources, visibility of services and coordination between scientific and technological
							infrastructures and the innovation system.
						</p>
			
						<h4>
							1) Scientific careers: precariousness and low predictability vs. mobility and diversified
							pathways
						</h4>
			
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								Existence of multiple contexts for scientific activity - academia, interface entities,
								companies, infrastructures and public administration - with potential to diversify career
								pathways.
							</li>
							<li>
								Recognition of the importance of mobility between academia, companies, interface entities,
								public administration and infrastructures.
							</li>
							<li>
								Identification of critical transversal skills for more diverse pathways, mobility between
								sectors and integration throughout the knowledge value chain.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>
								Prolonged precariousness and strong dependence on grants, short contracts and temporary
								instruments.
							</li>
							<li>
								Low predictability of funding, limiting medium- and long-term institutional commitments.
							</li>
							<li>
								Low attractiveness of scientific pathways for early-career profiles, given instability and
								lack of predictability.
							</li>
							<li>
								Still insufficient recognition of diverse pathways in career, progression and evaluation
								models, due to evaluation models that are too focused on quantitative production
								indicators, penalising non-traditional pathways, sectoral mobility and
								interdisciplinarity.
							</li>
						</ul>
						<h4>
							2) Talent: qualified base and training capacity vs. difficulty retaining national and
							international talent
						</h4>
			
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								Broad base of qualified talent, resulting from the strengthening of advanced training and
								the increase in the number of PhD holders and researchers.
							</li>
							<li>Capacity to attract internationally, especially at early career stages.</li>
							<li>
								Existence of talent already trained in the national system, with accumulated scientific
								experience and potential for valorisation.
							</li>
							<li>
								International circulation as an opportunity to strengthen networks, learning and openness
								in the national scientific system.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>
								Difficulty retaining talent, particularly at intermediate and advanced career stages.
							</li>
							<li>
								Integration conditions that are not very competitive compared with other scientific
								systems and the private sector, including remuneration, initial funding and “start-up
								packages”.
							</li>
							<li>
								Fragility of integration and continuity mechanisms for talent already trained in the
								national system, especially at intermediate career stages.
							</li>
							<li>
								Territorial and sectoral differences that affect talent attraction and retention,
								depending on critical mass, proximity to companies, access to networks, infrastructures,
								integration conditions and career opportunities.
							</li>
						</ul>
						<h4>
							3) Scientific and technological infrastructures: relevant installed capacity vs.
							insufficient sustainability and coordination
						</h4>
			
						<p><strong>Strengths</strong></p>
						<ul>
							<li>
								Existence of relevant investment in equipment, infrastructures and scientific and
								technological capabilities.
							</li>
							<li>
								Recognition of infrastructures as structural elements for the national R&amp;I system.
							</li>
							<li>
								Capacity of infrastructures to aggregate resources, services, skills, data and knowledge.
							</li>
							<li>
								Potential connection between research, technological development, specialised service
								provision, companies, public administration and other users.
							</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>
								Fragile financial sustainability: in the case of scientific infrastructures, insufficient
								funding for operation, maintenance, technological renewal and continuity; in the case of
								technological infrastructures and CTI, volatile funding models.
							</li>
							<li>
								Misalignment between investment in equipment and investment in qualified human resources.
							</li>
							<li>
								Poor valorisation of technical-scientific support, operation, management, data curation
								and user liaison profiles.
							</li>
							<li>
								Insufficient visibility and mapping of available services, equipment and skills, limiting
								access, sharing and use by companies and other users.
							</li>
							<li>
								Need to clarify and strengthen coordination between scientific and technological
								infrastructures, namely in terms of complementarity, governance, access and connection to
								the innovation system.
							</li>
						</ul>
		{/if}
	</div>
</div>

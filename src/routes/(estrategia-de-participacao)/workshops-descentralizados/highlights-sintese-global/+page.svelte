<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang } from '$lib/i18n.svelte';
</script>

<PageHeader title={getLang() === 'pt' ? 'Síntese global dos workshops' : 'Overall summary of the workshops'} />
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
			<h3>Síntese global dos workshops</h3>
						<p>
							A síntese resulta da análise qualitativa agregada dos resultados dos cinco workshops, com base na
							identificação de padrões recorrentes nas potencialidades, debilidades e temas críticos emergentes.
						</p>
			
						<h4>1. Identificação de prioridades</h4>
						<p><strong>Potencialidades</strong></p>
						<ul>
							<li>Existência de massa crítica científica e capacidade instalada de I&amp;D em todas as regiões</li>
							<li>Recursos endógenos diferenciadores (naturais, culturais, territoriais)</li>
							<li>
								Potencial de afirmação dos territórios como “laboratórios vivos” para experimentação e
								demonstração
							</li>
							<li>Áreas de especialização diversas</li>
						</ul>
						<p><strong>Debilidades</strong></p>
						<ul>
							<li>Dificuldade transversal de atração e retenção de talento</li>
							<li>Fragmentação do sistema de I&amp;I e fraca articulação entre atores</li>
							<li>Baixa transferência de conhecimento para a economia e sociedade</li>
							<li>Subfinanciamento e inadequação dos instrumentos às realidades territoriais</li>
							<li>Burocracia e rigidez administrativa</li>
							<li>Fragilidades de governação e falta de visão estratégica integrada</li>
							<li>Assimetrias territoriais significativas (litoral/interior; regiões centrais/periféricas)</li>
						</ul>
			
						<h4>2. Temas críticos</h4>
						<ul>
							<li>
								<strong>Recursos humanos e talento</strong>
								<p>
									Tensão transversal: existência de massa crítica e capacidade de atração, mas forte dificuldade
									de retenção
								</p>
							</li>
							<li>
								<strong>Financiamento e instrumentos de apoio</strong>
								<p>
									Consenso sobre subfinanciamento, falta de previsibilidade e desadequação dos instrumentos às
									especificidades regionais
								</p>
							</li>
							<li>
								<strong>Transferência de conhecimento e cadeia de valor</strong>
								<p>
									Fraca articulação entre academia, empresas e sociedade, limitando o impacto económico e social
									da investigação
								</p>
							</li>
							<li>
								<strong>Valorização dos recursos endógenos e “laboratórios vivos”</strong>
								<p>
									Forte potencial dos territórios para desenvolver soluções inovadoras baseadas nos seus ativos
									específicos
								</p>
							</li>
							<li>
								<strong>Governação e articulação do sistema</strong>
								<p>Necessidade de maior coordenação, descentralização e estratégias territoriais integradas</p>
							</li>
						</ul>
			
						<h4>3. Síntese</h4>
						<p>
							O diagnóstico das potencialidades e debilidades do ecossistema de I&amp;I é semelhante nas várias
							regiões, não obstante as especificidades regionais. No geral, apesar da capacidade instalada,
							persistem dificuldades na transferência de conhecimento, de criação de valor económico ou de impacto
							social e territorial.
						</p>
						<p>
							Os maiores ativos para o ecossistema de I&amp;I são os recursos humanos qualificados, as
							infraestruturas de I&amp;D e os recursos endógenos (naturais e culturais). As oportunidades de
							cooperação são potenciadas por fatores de proximidade entre os atores e pelo aproveitamento do
							posicionamento geográfico.
						</p>
						<p>
							Os bloqueios identificados são, no geral, transversais, como a capacidade de reter talento, a
							articulação entre os atores do ecossistema, as desigualdades territoriais, a desadequação dos
							mecanismos de financiamento e os desajustes entre as políticas nacionais e as especificidades
							territoriais inibidores do desenvolvimento de estratégias territoriais.
						</p>
						<p>
							Os fatores de sucesso (temas críticos) são também convergentes. Nas várias regiões foram priorizados
							os recursos humanos, os recursos endógenos, a transferência e impacto do conhecimento, os mecanismos de
							coordenação e articulação entre os atores e territórios e a governação integrada.
						</p>
		{:else}
			<h3>Overall summary of the workshops</h3>
						<p>
							This summary is based on an aggregate qualitative analysis of the results of the five workshops,
							identifying recurring patterns in the strengths, weaknesses and emerging critical themes.
						</p>
			
						<h4>1. Identification of priorities</h4>
						<p><strong>Strengths</strong></p>
						<ul>
							<li>Existence of scientific critical mass and installed R&amp;D capacity in all regions</li>
							<li>Differentiating endogenous resources (natural, cultural and territorial)</li>
							<li>Potential for territories to position themselves as “living labs” for experimentation and demonstration</li>
							<li>Diverse areas of specialisation</li>
						</ul>
						<p><strong>Weaknesses</strong></p>
						<ul>
							<li>Cross-cutting difficulty in attracting and retaining talent</li>
							<li>Fragmentation of the R&amp;I system and weak coordination between actors</li>
							<li>Low transfer of knowledge to the economy and society</li>
							<li>Underfunding and inadequate instruments for territorial realities</li>
							<li>Bureaucracy and administrative rigidity</li>
							<li>Governance weaknesses and lack of an integrated strategic vision</li>
							<li>Significant territorial asymmetries (coast/interior; central/peripheral regions)</li>
						</ul>
			
						<h4>2. Critical themes</h4>
						<ul>
							<li>
								<strong>Human resources and talent</strong>
								<p>
									Cross-cutting tension: existence of critical mass and capacity to attract talent, but strong
									difficulty in retaining it
								</p>
							</li>
							<li>
								<strong>Funding and support instruments</strong>
								<p>
									Consensus around underfunding, lack of predictability and instruments that are poorly adapted
									to regional specificities
								</p>
							</li>
							<li>
								<strong>Knowledge transfer and value chain</strong>
								<p>
									Weak coordination between academia, companies and society, limiting the economic and social
									impact of research
								</p>
							</li>
							<li>
								<strong>Valorisation of endogenous resources and “living labs”</strong>
								<p>Strong potential for territories to develop innovative solutions based on their specific assets</p>
							</li>
							<li>
								<strong>Governance and coordination of the system</strong>
								<p>Need for greater coordination, decentralisation and integrated territorial strategies</p>
							</li>
						</ul>
			
						<h4>3. Summary</h4>
						<p>
							The diagnosis of the strengths and weaknesses of the R&amp;I ecosystem is similar across the
							different regions, despite regional specificities. Overall, despite installed capacity, difficulties
							persist in knowledge transfer, in creating economic value and in generating social and territorial
							impact.
						</p>
						<p>
							The main assets for the R&amp;I ecosystem are qualified human resources, R&amp;D infrastructures and
							endogenous resources (natural and cultural). Cooperation opportunities are strengthened by proximity
							between actors and by the use of geographical positioning.
						</p>
						<p>
							The barriers identified are, overall, cross-cutting: the capacity to retain talent, coordination
							between ecosystem actors, territorial inequalities, unsuitable funding mechanisms and mismatches
							between national policies and territorial specificities, which inhibit the development of territorial
							strategies.
						</p>
						<p>
							The success factors (critical themes) are also convergent. Across the different regions, human
							resources, endogenous resources, knowledge transfer and impact, coordination mechanisms between actors
							and territories, and integrated governance were prioritised.
						</p>
		{/if}
	</div>
</div>

<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.bottomUpInitiatives.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				As iniciativas bottom-up são de livre iniciativa da comunidade, e destinam-se a contribuir
				para o processo de avaliação estratégica em curso e para a definição de prioridades
				nacionais de investigação e inovação.
			</p>
			<p>
				O objetivo das iniciativas bottom-up é contribuir com uma reflexão estratégica sobre temas,
				prioridades e ambições em setores ou área de investigação estruturantes e emergentes numa
				perspetiva de longo prazo.
			</p>
			<p>
				Constituem iniciativas bottom-up reuniões, conferências, e outros eventos que configurem
				uma reflexão estratégica impulsionadora de investigação, criação de conhecimento científico
				e promoção da inovação, com potencial para melhorar a sociedade e se transformar em valor
				económico, social, cultural e ambiental.
			</p>
			<p>A fim de constituírem um contributo para a avaliação estratégica as iniciativas bottom-up:</p>
			<ol>
				<li>
					Protagonizam uma perspetiva estratégica num horizonte de longo prazo - desejavelmente 10
					anos ou mais
				</li>
				<li>
					Reconhecem a visão e os objetivos estabelecidos para a avaliação estratégica e definição
					de prioridades nacionais
				</li>
				<li>
					Estabelecem prioridades setoriais/temáticas de investigação e inovação e a sua
					importância ao longo da cadeia de valor
				</li>
				<li>
					São desejavelmente transversais no sistema científico, tecnológico e de inovação nacional
					e revelam comunidades dinâmicas de interesse partilhado.
				</li>
			</ol>
			<p>
				Os resultados das iniciativas bottom-up irão revelar a sua estratégia, prioridades e
				principais desafios, bem como o tema/área de investigação se pode tornar, ou consolidar,
				como uma área estruturante no Sistema Científico, Tecnológico e de Inovação Nacional,
				indicando:
			</p>
			<ol>
				<li>
					Que valor acrescentado irá gerar em termos de conhecimento científico, inovação e
					sustentabilidade
				</li>
				<li>
					Que contributos podem vir a dar ao desenvolvimento territorial, à sociedade e à economia
					nacional.
				</li>
				<li>
					Quais os seus planos para criar recursos e autonomia, se tornarem competitivos e menos
					dependentes de financiamento público depois dos próximos cinco anos.
				</li>
			</ol>
			<p>
				Os resultados das iniciativas bottom-up deverão ser enviados, entre a presente data e o dia
				30 de setembro 2026, para: <a href="mailto:ai2@planapp.gov.pt">ai2@planapp.gov.pt</a>
			</p>
		{:else}
			<p>
				Bottom-up initiatives are freely initiated by the community and are intended to contribute
				to the ongoing strategic assessment process and to the definition of national research and
				innovation priorities.
			</p>
			<p>
				The purpose of bottom-up initiatives is to contribute strategic reflection on themes,
				priorities and ambitions in structuring and emerging sectors or areas of research from a
				long-term perspective.
			</p>
			<p>
				Bottom-up initiatives include meetings, conferences and other events that constitute
				strategic reflection capable of driving research, the creation of scientific knowledge and
				the promotion of innovation, with the potential to improve society and generate economic,
				social, cultural and environmental value.
			</p>
			<p>To constitute a contribution to the strategic assessment, bottom-up initiatives:</p>
			<ol>
				<li>Present a strategic perspective over a long-term horizon - preferably 10 years or more</li>
				<li>
					Recognise the vision and objectives established for the strategic assessment and the
					definition of national priorities
				</li>
				<li>
					Establish sectoral/thematic research and innovation priorities and their importance
					along the value chain
				</li>
				<li>
					Are preferably cross-cutting within the national scientific, technological and innovation
					system and reveal dynamic communities of shared interest.
				</li>
			</ol>
			<p>
				The results of bottom-up initiatives will reveal their strategy, priorities and main
				challenges, as well as how the research theme/area can become, or consolidate itself as, a
				structuring area within the National Scientific, Technological and Innovation System,
				indicating:
			</p>
			<ol>
				<li>
					What added value it will generate in terms of scientific knowledge, innovation and
					sustainability
				</li>
				<li>
					What contributions it may make to territorial development, society and the national
					economy.
				</li>
				<li>
					What plans it has to create resources and autonomy, become competitive and less
					dependent on public funding after the next five years.
				</li>
			</ol>
			<p>
				The results of bottom-up initiatives should be sent, between the present date and 30
				September 2026, to: <a href="mailto:ai2@planapp.gov.pt">ai2@planapp.gov.pt</a>
			</p>
		{/if}
	</div>
</div>

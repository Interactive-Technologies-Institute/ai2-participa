<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.decentralizedWorkshops.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A metodologia prevê a realização de conferências e workshops descentralizados, abertos a
				todos os interessados mediante inscrição. Estas sessões têm como objetivo apresentar o
				processo, esclarecer dúvidas e recolher contributos em tempo real.
			</p>
			<p>
				Está previsto um workshop em cada região NUTS II do continente, em articulação com as CCDR,
				bem como nas Regiões Autónomas.
			</p>
			<p>
				Além da conferência de apresentação da metodologia, marcada para 24 de fevereiro de 2026 no
				Técnico Innovation Centre, estão previstas as seguintes iniciativas:
			</p>
			<ul>
				<li>
					Cinco workshops em maio de 2026 para abordar a focagem estratégica (Funchal, Évora,
					Coimbra, Bragança, Porto).
				</li>
				<li>
					Cinco workshops em junho-julho de 2026 para definir e discutir opções estratégicas e
					respetiva avaliação de oportunidades e riscos (Ponta Delgada, Aveiro, Covilhã, Braga,
					Faro).
				</li>
				<li>Apresentação preliminar de resultados (em outubro de 2026).</li>
				<li>Conferência final (em novembro/dezembro de 2026).</li>
			</ul>
			<p>
				Em breve será disponibilizada informação com as datas e local dos workshops, temas e lista
				de participantes.
			</p>
		{:else}
			<p>
				The methodology provides for conferences and decentralised workshops, open to all interested
				parties upon registration. These sessions aim to present the process, clarify doubts and
				gather contributions in real time.
			</p>
			<p>
				One workshop is planned for each NUTS II region on the mainland, in coordination with the
				CCDRs, as well as in the Autonomous Regions.
			</p>
			<p>
				In addition to the methodology presentation conference, scheduled for 24 February 2026 at
				the Técnico Innovation Centre, the following initiatives are planned:
			</p>
			<ul>
				<li>
					Five workshops in May 2026 to address strategic focus (Funchal, Évora, Coimbra, Bragança,
					Porto).
				</li>
				<li>
					Five workshops in June–July 2026 to define and discuss strategic options and assessment of
					their opportunities and risks (Ponta Delgada, Aveiro, Covilhã, Braga, Faro).
				</li>
				<li>Preliminary presentation of results (October 2026).</li>
				<li>Final conference (November/December 2026).</li>
			</ul>
			<p>
				Information on workshop dates, venues, themes and participant lists will be made available
				soon.
			</p>
		{/if}
	</div>
</div>

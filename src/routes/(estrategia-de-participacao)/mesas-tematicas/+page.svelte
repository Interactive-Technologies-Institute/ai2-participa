<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.thematicTables.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				As mesas temáticas têm como objetivo aprofundar temas críticos, identificar consensos e
				divergências e recolher propostas concretas. Participarão representantes dos diferentes
				universos a consultar: comunidade académica, sistema científico e tecnológico, setor
				empresarial, Administração Pública e sociedade civil.
			</p>
			<p>
				A composição será mista, garantindo diversidade de perspetivas, e as sessões decorrerão entre
				março e abril e entre final de junho e início de julho.
			</p>
			<p>Em breve serão divulgadas as datas, os temas e a lista de participantes.</p>
		{:else}
			<p>
				The thematic tables aim to deepen critical topics, identify areas of consensus and
				divergence, and gather concrete proposals. Representatives from the different communities to
				be consulted will participate: academic community, scientific and technological system,
				business sector, Public Administration and civil society.
			</p>
			<p>
				The composition will be mixed, ensuring diversity of perspectives, and sessions will take
				place between March and April and between late June and early July.
			</p>
			<p>Dates, themes and the list of participants will be announced soon.</p>
		{/if}
	</div>
</div>

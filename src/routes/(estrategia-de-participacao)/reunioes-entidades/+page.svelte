<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.stakeholderMeetings.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				Estas reuniões têm como objetivo recolher perspetivas e contributos das entidades estratégicas
				definidas no quadro de governança da Avaliação Estratégica (ver Anexo 2 do documento da
				metodologia). Estão previstas, pelo menos, oito sessões online, a realizar entre março e abril
				de 2026.
			</p>
			<p>Em breve serão divulgadas as datas e a lista completa de entidades participantes.</p>
		{:else}
			<p>
				These meetings aim to gather perspectives and contributions from strategic entities defined
				in the Strategic Assessment governance framework (see Annex 2 of the methodology document).
				At least eight online sessions are planned, to be held between March and April 2026.
			</p>
			<p>Dates and the full list of participating entities will be announced soon.</p>
		{/if}
	</div>
</div>

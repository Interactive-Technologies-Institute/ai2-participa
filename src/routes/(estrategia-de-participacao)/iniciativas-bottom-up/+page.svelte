<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.bottomUpInitiatives.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				As entidades do Sistema Nacional de Ciência, Tecnologia e Inovação são convidadas a dinamizar
				iniciativas próprias de diálogos e a partilhar nesta plataforma os seus resultados para que
				possam contribuir para a Avaliação Estratégica da AI².
			</p>
			<p>Em breve será disponibilizada uma proposta de guião orientador para estas iniciativas.</p>
		{:else}
			<p>
				Entities of the National Science, Technology and Innovation System are invited to organise
				their own dialogue initiatives and share their results on this platform so that they can
				contribute to the AI² Strategic Assessment.
			</p>
			<p>A proposed guiding script for these initiatives will be made available soon.</p>
		{/if}
	</div>
</div>

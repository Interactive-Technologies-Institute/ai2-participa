<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.nationalLegislation.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				O <a
					href="https://diariodarepublica.pt/dr/detalhe/decreto-lei/132-2025-992627244"
					target="_blank"
					rel="noopener">Decreto-Lei n.º 132/2025, de 24 de dezembro</a
				>, estabelece a criação da Agência para a Investigação e Inovação (AI²), E. P. E., resultante
				da transformação da Agência Nacional de Inovação, S. A., e da fusão com a Fundação para a
				Ciência e a Tecnologia, I. P., aprovando também o respetivo regime jurídico.
			</p>
		{:else}
			<p>
				<a
					href="https://diariodarepublica.pt/dr/detalhe/decreto-lei/132-2025-992627244"
					target="_blank"
					rel="noopener">Decree-Law No. 132/2025, of 24 December</a
				>, establishes the creation of the Agency for Research and Innovation (AI²), E. P. E.,
				resulting from the transformation of the National Innovation Agency, S. A., and its merger
				with the Foundation for Science and Technology, I. P., also approving the respective legal
				framework.
			</p>
		{/if}
	</div>
</div>

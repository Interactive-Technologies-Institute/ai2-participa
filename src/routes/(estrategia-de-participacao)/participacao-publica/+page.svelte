<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.publicParticipation.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A Avaliação Estratégica da AI² assenta numa participação pública ampla, contínua e informada,
				envolvendo atores de todo o ecossistema de investigação e inovação. O objetivo é assegurar um
				processo transparente e inclusivo, onde diferentes perspetivas sobre prioridades estratégicas
				são partilhadas e ponderadas.
			</p>
			<p>
				Este espaço de diálogo permite acompanhar a evolução do processo, aceder à informação
				disponibilizada e contribuir ativamente com opiniões e respostas às questões colocadas, de
				forma pública e transparente, reforçando a qualidade da avaliação e a legitimidade das
				decisões.
			</p>
		{:else}
			<p>
				The AI² Strategic Assessment is built on broad, continuous and informed public participation,
				involving actors from across the research and innovation ecosystem. The goal is to ensure a
				transparent and inclusive process, where different perspectives on strategic priorities are
				shared and considered.
			</p>
			<p>
				This dialogue space allows you to follow the evolution of the process, access available
				information and actively contribute with opinions and responses to the questions raised, in a
				public and transparent manner, reinforcing the quality of the assessment and the legitimacy
				of decisions.
			</p>
		{/if}
	</div>
</div>

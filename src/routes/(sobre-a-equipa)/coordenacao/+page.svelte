<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { asset } from '$app/paths';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.coordination.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				Conheça a equipa responsável pela coordenação da Avaliação Estratégica que apoia a definição
				das prioridades nacionais de investigação e inovação e a elaboração do contrato-programa
				plurianual da Agência para a Investigação e Inovação (AI²).
			</p>
		{:else}
			<p>
				Meet the team responsible for coordinating the Strategic Assessment that supports the
				definition of national research and innovation priorities and the preparation of the
				multi-annual programme contract for the Agency for Research and Innovation (AI²).
			</p>
		{/if}
		<h2>{t('page.coordination.scientificCoordination')}</h2>
		<div class="mt-4 flex flex-col gap-4 sm:flex-row sm:items-center">
			<img
				src={asset('/photos/MariaRosarioPartidario.jpg')}
				alt="Professora Doutora Maria do Rosário Partidário"
				class="h-28 w-28 shrink-0 rounded-full object-cover shadow-sm border border-slate-200 bg-slate-50"
				loading="lazy"
			/>
			<p class="large">
				Professora Doutora Maria do Rosário Partidário<br />
				<span class="muted">{t('page.coordination.scientificRole')}</span>
			</p>
		</div>
		{#if getLang() === 'pt'}
			<p>
				Professora Catedrática do Instituto Superior Técnico, especialista em Avaliação Estratégica e
				autora da metodologia ST4S - Strategic Thinking for Sustainability, que estrutura o presente
				processo de avaliação.
			</p>
		{:else}
			<p>
				Full Professor at Instituto Superior Técnico, specialist in Strategic Assessment and author
				of the ST4S methodology — Strategic Thinking for Sustainability — which structures the
				present assessment process.
			</p>
		{/if}
		<h2>{t('page.coordination.institutionalCoordination')}</h2>
		<p class="large">
			PLANAPP - Centro de Planeamento e de Avaliação de Políticas Públicas<br />
			<span class="muted">{t('page.coordination.institutionalRole')}</span>
		</p>
		{#if getLang() === 'pt'}
			<p>
				O PLANAPP coordena globalmente o processo de Avaliação Estratégica, em articulação com a
				Direção-Geral da Economia (DGE) e a Direção-Geral de Estudos, Planeamento e Avaliação (DGEPA),
				assegurando o desenho metodológico, a organização da participação pública e a consolidação
				técnica dos resultados.
			</p>
		{:else}
			<p>
				PLANAPP provides overall coordination of the Strategic Assessment process, in articulation with the
				Directorate-General for the Economy (DGE) and the Directorate-General for Studies, Planning
				and Evaluation (DGEPA), ensuring the methodological design, organisation of public
				participation and technical consolidation of results.
			</p>
		{/if}
	</div>
</div>

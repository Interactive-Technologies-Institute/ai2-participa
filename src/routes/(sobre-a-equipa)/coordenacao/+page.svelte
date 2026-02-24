<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { asset } from '$app/paths';
</script>

<PageHeader title="Coordenação" />
<div class="container my-12 md:my-24">
	<div class="typography">
		<p>
			Conheça a equipa responsável pela coordenação da Avaliação Estratégica que apoia a definição
			das prioridades nacionais de investigação e inovação e a elaboração do contrato-programa
			plurianual da Agência para a Investigação e Inovação (AI²).
		</p>
		<h2>Coordenação Científica</h2>
		<div class="mt-4 flex flex-col gap-4 sm:flex-row sm:items-center">
			<img
				src={asset('/photos/MariaRosarioPartidario.jpg')}
				alt="Professora Doutora Maria do Rosário Partidário"
				class="h-28 w-28 shrink-0 rounded-full object-cover shadow-sm border border-slate-200 bg-slate-50"
				loading="lazy"
			/>
			<p class="large">
				Professora Doutora Maria do Rosário Partidário<br />
				<span class="muted">Coordenação Científica da Metodologia ST4S</span>
			</p>
		</div>
		<p>
			Professora Catedrática do Instituto Superior Técnico, especialista em Avaliação Estratégica e
			autora da metodologia ST4S - Strategic Thinking for Sustainability, que estrutura o presente
			processo de avaliação.
		</p>
		<h2>Coordenação Institucional</h2>
		<p class="large">
			PLANAPP - Centro de Planeamento e de Avaliação de Políticas Públicas<br />
			<span class="muted">Coordenação global</span>
		</p>
		<p>
			O PLANAPP coordena globalmente o processo de Avaliação Estratégica, em articulação com a
			Direção-Geral da Economia (DGE) e a Direção-Geral de Estudos, Planeamento e Avaliação (DGEPA),
			assegurando o desenho metodológico, a organização da participação pública e a consolidação
			técnica dos resultados.
		</p>
	</div>
</div>

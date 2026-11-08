<script lang="ts">
	import { asset, resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.publicPresentation.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<ul>
				<li>
					<strong>24 de fevereiro de 2026:</strong> Apresentação pública da metodologia para a
					definição dos domínios estratégicos e para a alocação orçamental da AI² (<a
						href={resolve('/apresentacao-publica/24-fevereiro-2026/')}>programa e apresentações</a
					>)
				</li>
				<li>
					<strong>22 de junho de 2026:</strong> Definição das prioridades de Investigação e Inovação –
					Discussão sobre os Fatores Críticos de Decisão
				</li>
				<li>
					<strong>15-16 de julho de 2026:</strong> Encontro Ciência e Inovação 2026
					<ul>
						<li>
							site do Encontro Ciência e Inovação 2026 (<a
								href="https://www.cienciainovacao.pt/"
								target="_blank"
								rel="noopener noreferrer"
								>Encontro Ciência e Inovação 2026 • 15 e 16 de Julho • Lisboa</a
							>)
						</li>
						<li>
							vídeos das sessões plenárias (<a
								href="https://www.youtube.com/@ai2portugal"
								target="_blank"
								rel="noopener noreferrer">Agência para a Investigação e Inovação - YouTube</a
							>)
						</li>
						<li>
							apresentação da Professora Maria do Rosário Partidário (sessão plenária 1) (<a
								href={asset('/docs/20260715_APRESENTACAO_MARIA_ROSARIO_PARTIDARIO.pdf')}
								target="_blank"
								rel="noreferrer">link</a
							>)
						</li>
						<li>
							apresentação do Ministro da Educação, Ciência e Inovação, Fernando Alexandre (sessão
							plenária 5) (<a
								href={asset('/docs/20260715_APRESENTACAO_FERNANDO_ALEXANDRE.pdf')}
								target="_blank"
								rel="noreferrer">link</a
							>)
						</li>
					</ul>
				</li>
			</ul>
		{:else}
			<ul>
				<li>
					<strong>24 February 2026:</strong> Public presentation of the methodology for defining the
					strategic domains and the budget allocation of AI² (<a
						href={resolve('/apresentacao-publica/24-fevereiro-2026/')}
						>programme and presentations</a
					>)
				</li>
				<li>
					<strong>22 June 2026:</strong> Definition of Research and Innovation priorities – Discussion
					on the Critical Decision Factors
				</li>
				<li>
					<strong>15-16 July 2026:</strong> Encontro Ciência e Inovação 2026
					<ul>
						<li>
							Encontro Ciência e Inovação 2026 website (<a
								href="https://www.cienciainovacao.pt/en/"
								target="_blank"
								rel="noopener noreferrer"
								>Portuguese Science Summit Innovation 2026 • July 15 and 16 • Lisbon</a
							>)
						</li>
						<li>
							plenary session videos (<a
								href="https://www.youtube.com/@ai2portugal"
								target="_blank"
								rel="noopener noreferrer">Agência para a Investigação e Inovação - YouTube</a
							>)
						</li>
						<li>
							presentation by Professor Maria do Rosário Partidário (plenary session 1) (<a
								href={asset('/docs/20260715_APRESENTACAO_MARIA_ROSARIO_PARTIDARIO.pdf')}
								target="_blank"
								rel="noreferrer">link</a
							>)
						</li>
						<li>
							presentation by the Minister of Education, Science and Innovation, Fernando Alexandre
							(plenary session 5) (<a
								href={asset('/docs/20260715_APRESENTACAO_FERNANDO_ALEXANDRE.pdf')}
								target="_blank"
								rel="noreferrer">link</a
							>)
						</li>
					</ul>
				</li>
			</ul>
		{/if}
	</div>
</div>

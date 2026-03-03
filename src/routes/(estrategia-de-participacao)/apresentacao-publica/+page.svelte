<script lang="ts">
	import { asset } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.publicPresentation.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		<p>
			<strong
				>Apresentação pública da metodologia para a definição dos domínios estratégicos e para a
				alocação orçamental da AI²</strong
			>
			(<a href={asset('/docs/Apresentacao_ENG.pdf')} target="_blank" rel="noreferrer">link</a>);
		</p>
		<p>24 de fevereiro de 2026 | Técnico Innovation Center | Lisboa</p>
		<h2>Programa</h2>
		<p><strong>09h30</strong> – Welcome coffee</p>
		<p><strong>10h00</strong> – Sessão de Abertura</p>
		<ul>
			<li>
				Fernando Alexandre
				<ul>
					<li>Ministro da Educação, Ciência e Inovação</li>
				</ul>
			</li>
		</ul>
		<p>
			<strong>10h35</strong> – Science, Technology and Innovation Outlook 2025 – Driving change in a shifting
			landscape
		</p>
		<ul>
			<li>
				Alessandra Colecchia (<a
					href={asset('/docs/AI2_ALESSANDRA_COLECCHIA_OCDE.pdf')}
					target="_blank"
					rel="noreferrer">link</a
				>)
				<ul>
					<li>Chefe da Divisão de Política de Ciência e Tecnologia da OCDE</li>
				</ul>
			</li>
		</ul>
		<p><strong>11h00</strong> – Coffee break</p>
		<p><strong>11h20</strong> – O estado da Investigação e da Inovação em Portugal</p>
		<p>Instrumentos, mecanismos de financiamento e ecossistema de Investigação e Inovação</p>
		<ul>
			<li>
				Raúl Fangueiro (<a
					href={asset('/docs/AI2_RAUL_FANGUEIRO_CNCTI.pdf')}
					target="_blank"
					rel="noreferrer">link</a
				>) – Membro do Conselho Nacional de Ciência, Tecnologia e Inovação
				<ul>
					<li>Universidade do Minho</li>
				</ul>
			</li>
			<li>
				Adélio Mendes (<a
					href={asset('/docs/AI2_ADELIO_MENDES_CNCTI.pdf')}
					target="_blank"
					rel="noreferrer">link</a
				>) – Membro do Conselho Nacional de Ciência, Tecnologia e Inovação
				<ul>
					<li>Universidade do Porto</li>
				</ul>
			</li>
		</ul>
		<p>Análise do Ecossistema Científico, Tecnológico e de Inovação Nacional</p>
		<ul>
			<li>
				Eugénio Campos Ferreira (<a
					href={asset('/docs/AI2_EUGENIO_CAMPOS_FERREIRA_DIAGNOSTICO_QUANTITATIVO.pdf')}
					target="_blank"
					rel="noreferrer">link</a
				>) – Coordenador do Grupo de Trabalho de Análise do Ecossistema Nacional de Investigação e
				Inovação
				<ul>
					<li>Universidade do Minho</li>
				</ul>
			</li>
		</ul>
		<p><strong>12h10</strong> – Debate aberto ao público</p>
		<ul>
			<li>
				Hermínia Vilar
				<ul>
					<li>Vice-Presidente do CRUP e Reitora da Universidade de Évora</li>
				</ul>
			</li>
			<li>
				Orlando Rodrigues
				<ul>
					<li>Comissão Permanente do CCISP e Presidente do Instituto Politécnico de Bragança</li>
				</ul>
			</li>
			<li>
				Carlos Oliveira
				<ul>
					<li>Presidente do Conselho Nacional de Ciência, Tecnologia e Inovação</li>
				</ul>
			</li>
			<li>
				Jorge Portugal
				<ul>
					<li>Diretor-Geral da COTEC Portugal</li>
				</ul>
			</li>
			<li>
				Eugénio Campos Ferreira
				<ul>
					<li>
						Coordenador do Grupo de Trabalho de Análise do Ecossistema Nacional de Investigação e
						Inovação
					</li>
				</ul>
			</li>
		</ul>
		<p><strong>13h15</strong> – Almoço volante</p>
		<p><strong>14h30</strong> – Grandes tendências globais e desafios de Portugal e da Europa</p>
		<ul>
			<li>
				Ricardo Reis (<a href={asset('/docs/AI2_RICARDO_REIS.pdf')} target="_blank" rel="noreferrer"
					>link</a
				>) – Coordenador da Comissão de Acompanhamento
				<ul>
					<li>London School of Economics</li>
				</ul>
			</li>
		</ul>
		<p>
			<strong>15h00</strong> – Apresentação da metodologia para a definição dos domínios estratégicos
			e para a alocação orçamental da AI²
		</p>
		<ul>
			<li>
				Maria do Rosário Partidário (<a
					href={asset('/docs/AI2_ROSARIO_PARTIDARIO_ENG.pdf')}
					target="_blank"
					rel="noreferrer">link</a
				>) – Coordenadora da Equipa de Projeto
				<ul>
					<li>Instituto Superior Técnico</li>
				</ul>
			</li>
		</ul>
		<p><strong>15h30</strong> – Debate aberto ao público</p>
		<ul>
			<li>
				Helena Canhão
				<ul>
					<li>Secretária de Estado da Ciência e Inovação</li>
				</ul>
			</li>
			<li>
				João Rui Ferreira
				<ul>
					<li>Secretário de Estado da Economia</li>
				</ul>
			</li>
			<li>
				Maria do Rosário Partidário
				<ul>
					<li>Coordenadora da Equipa de Projeto</li>
				</ul>
			</li>
			<li>
				Madalena Alves
				<ul>
					<li>Presidente da Fundação para a Ciência e a Tecnologia</li>
				</ul>
			</li>
			<li>
				António Grilo
				<ul>
					<li>Presidente da Agência Nacional de Inovação</li>
				</ul>
			</li>
		</ul>
		<p><strong>17h00</strong> – Sessão de Encerramento</p>
		<ul>
			<li>
				Manuel Castro Almeida
				<ul>
					<li>Ministro da Economia e Coesão Territorial</li>
				</ul>
			</li>
		</ul>
	</div>
</div>

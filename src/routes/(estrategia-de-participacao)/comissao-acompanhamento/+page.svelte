<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.advisoryCommittee.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A <strong>Comissão de Acompanhamento (CA)</strong> da Avaliação Estratégica da AI² é constituída
				por elementos de referência da comunidade científica e de inovação, garantindo equilíbrio entre
				académicos e empreendedores de base tecnológica, e individualidades com experiência profissional
				internacional.
			</p>
			<h2>{t('page.advisoryCommittee.members')}</h2>
			<ul>
				<li>Ricardo Reis (London School of Economics) - <strong>Coordenador</strong>.</li>
				<li>Ana Casaca (Conselho Europeu de Inovação).</li>
				<li>Evelyn Wang (Massachusetts Institute of Technology - MIT).</li>
				<li>Fernanda Leite (University of Texas at Austin).</li>
				<li>Gonçalo Quadros (Critical Software SA).</li>
				<li>José Fonseca Moura (Carnegie Mellon University).</li>
				<li>Luís Portela (Fundação Bial).</li>
			</ul>
			<h2>{t('page.advisoryCommittee.missionFunctions')}</h2>
			<p>
				A CA atua de forma independente e com natureza consultiva, tendo como principais
				responsabilidades:
			</p>
			<ul>
				<li>
					Emitir pareceres sobre o desenho e implementação da metodologia de avaliação estratégica.
				</li>
				<li>Acompanhar a implementação do processo e emitir pareceres nas suas diferentes fases.</li>
			</ul>
			<p>
				A Comissão de Acompanhamento tem acesso a toda a informação e documentação necessária para o
				exercício das suas funções e pode participar em reuniões, sessões de trabalho e outras
				iniciativas sempre que necessário.
			</p>
			<h2>{t('page.advisoryCommittee.interaction')}</h2>
			<p>
				Para cumprir a sua missão, a CA pode consultar e solicitar a participação de membros do
				Conselho Nacional de Ciência, Tecnologia e Inovação, peritos, representantes do setor
				científico e de inovação, outras entidades públicas ou privadas, associações, académicos ou
				personalidades de reconhecido mérito. A colaboração com peritos da OCDE e com o Steering
				Committee que acompanha a reforma em curso no Ministério da Educação, Ciência e Inovação
				(MECI) constitui uma mais-valia para todo o Sistema Nacional de Ciência, Tecnologia e
				Inovação.
			</p>
		{:else}
			<p>
				The <strong>Advisory Committee (AC)</strong> of the AI² Strategic Assessment is made up of leading
				figures from the scientific and innovation community, ensuring a balance between academics and
				technology-based entrepreneurs, and individuals with international professional experience.
			</p>
			<h2>{t('page.advisoryCommittee.members')}</h2>
			<ul>
				<li>Ricardo Reis (London School of Economics) - <strong>Coordinator</strong>.</li>
				<li>Ana Casaca (European Innovation Council).</li>
				<li>Evelyn Wang (Massachusetts Institute of Technology - MIT).</li>
				<li>Fernanda Leite (University of Texas at Austin).</li>
				<li>Gonçalo Quadros (Critical Software SA).</li>
				<li>José Fonseca Moura (Carnegie Mellon University).</li>
				<li>Luís Portela (Fundação Bial).</li>
			</ul>
			<h2>{t('page.advisoryCommittee.missionFunctions')}</h2>
			<p>
				The AC operates independently and in an advisory capacity, with the following main
				responsibilities:
			</p>
			<ul>
				<li>
					Issuing opinions on the design and implementation of the strategic assessment methodology.
				</li>
				<li>
					Monitoring the implementation of the process and issuing opinions at its different phases.
				</li>
			</ul>
			<p>
				The Advisory Committee has access to all information and documentation necessary to carry out
				its functions and may participate in meetings, working sessions and other initiatives whenever
				necessary.
			</p>
			<h2>{t('page.advisoryCommittee.interaction')}</h2>
			<p>
				To fulfil its mission, the AC may consult and request the participation of members of the
				National Council for Science, Technology and Innovation, experts, representatives of the
				scientific and innovation sector, other public or private entities, associations, academics
				or individuals of recognised merit. Collaboration with OECD experts and the Steering
				Committee overseeing the ongoing reform at the Ministry of Education, Science and Innovation
				(MECI) represents an added value for the entire National Science, Technology and Innovation
				System.
			</p>
		{/if}
	</div>
</div>

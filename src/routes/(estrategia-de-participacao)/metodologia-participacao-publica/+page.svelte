<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.publicParticipationMethodology.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A participação pública na Avaliação Estratégica da AI² assenta numa metodologia estruturada,
				pensada para garantir um processo aberto, informado e inclusivo, envolvendo atores de todo o
				ecossistema de investigação e inovação.
			</p>
			<h2>Princípios que orientam a participação</h2>
			<ul>
				<li>
					<strong>Transparência e partilha de informação</strong> entre todos os grupos de atores-chave.
				</li>
				<li>
					<strong>Cobertura nacional</strong>, incluindo Regiões Autónomas, garantindo participação
					representativa.
				</li>
				<li>
					<strong>Combinação de sessões abertas e por convite</strong>, equilibrando diversidade de
					atores, interesses e territórios.
				</li>
				<li>
					<strong>Divulgação contínua</strong> do processo e dos seus resultados em portais oficiais, redes
					sociais, imprensa, no sítio do PLANAPP e na própria plataforma do projeto.
				</li>
				<li>
					<strong>Gestão de expetativas e feedback estruturado</strong> aos participantes ao longo de todo
					o processo.
				</li>
			</ul>
			<h2>Componentes da estratégia de participação</h2>
			<p>
				A metodologia integra um conjunto de instrumentos complementares que garantem
				<strong>diálogo permanente</strong>, recolha de contributos diversificados e envolvimento
				ativo dos atores-chave:
			</p>
			<ul>
				<li><strong>Página digital dedicada</strong>, atualizada ao longo de todo o processo.</li>
				<li>
					<strong>Plataforma interativa online</strong> para contributos contínuos, diálogos e aprendizagem
					coletiva.
				</li>
				<li>
					<strong>Comissão de Acompanhamento</strong> com elementos de referência da comunidade científica
					e inovação.
				</li>
				<li>
					<strong>Reuniões com entidades</strong> estratégicas para recolha de perspetivas e contributos.
				</li>
				<li>
					<strong>Mesas temáticas</strong> com participantes representativos da comunidade académica, sistema
					científico e tecnológico, setor empresarial, administração pública e sociedade civil.
				</li>
				<li>
					<strong>Conferências e workshops descentralizados</strong> em várias regiões para apresentar o
					processo e recolher contributos em tempo real.
				</li>
				<li>
					<strong>Iniciativas bottom-up</strong>, dinamizadas espontaneamente por agentes do SNCTI.
				</li>
			</ul>
		{:else}
			<p>
				Public participation in the AI² Strategic Assessment is based on a structured methodology,
				designed to ensure an open, informed and inclusive process, involving actors from across the
				research and innovation ecosystem.
			</p>
			<h2>Principles guiding participation</h2>
			<ul>
				<li>
					<strong>Transparency and information sharing</strong> among all key stakeholder groups.
				</li>
				<li>
					<strong>National coverage</strong>, including Autonomous Regions, ensuring representative
					participation.
				</li>
				<li>
					<strong>Combination of open and invitation-based sessions</strong>, balancing diversity of
					actors, interests and territories.
				</li>
				<li>
					<strong>Continuous dissemination</strong> of the process and its results through official portals,
					social media, press, the PLANAPP website and the project platform itself.
				</li>
				<li>
					<strong>Expectation management and structured feedback</strong> to participants throughout the
					entire process.
				</li>
			</ul>
			<h2>Components of the participation strategy</h2>
			<p>
				The methodology integrates a set of complementary instruments that ensure
				<strong>permanent dialogue</strong>, collection of diverse contributions and active involvement
				of key stakeholders:
			</p>
			<ul>
				<li><strong>Dedicated digital page</strong>, updated throughout the entire process.</li>
				<li>
					<strong>Online interactive platform</strong> for continuous contributions, dialogues and collective
					learning.
				</li>
				<li>
					<strong>Advisory Committee</strong> with leading figures from the scientific and innovation community.
				</li>
				<li>
					<strong>Meetings with strategic entities</strong> to gather perspectives and contributions.
				</li>
				<li>
					<strong>Thematic tables</strong> with representatives from the academic community, scientific and
					technological system, business sector, public administration and civil society.
				</li>
				<li>
					<strong>Decentralized conferences and workshops</strong> across various regions to present the
					process and gather contributions in real time.
				</li>
				<li>
					<strong>Bottom-up initiatives</strong>, spontaneously organised by SCTI actors.
				</li>
			</ul>
		{/if}
	</div>
</div>

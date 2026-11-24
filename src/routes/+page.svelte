<script lang="ts">
	import { asset } from '$app/paths';
	import Logo from '$lib/components/logo.svelte';
	import { Button } from '$lib/components/ui/button';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<svelte:head>
	<title>AI²Participa</title>
	<meta name="title" content="AI²Participa" />
	<meta property="og:title" content="AI²Participa" />
	<meta name="twitter:title" content="AI²Participa" />
</svelte:head>

<section class="relative overflow-hidden bg-background py-20 md:py-32">
	<div class="relative z-10 container">
		<div class="mx-auto flex max-w-5xl flex-col items-center gap-8 text-center">
			<Logo class="h-48 w-auto" />
			<h1 class="font-title text-4xl font-bold sm:text-5xl md:text-6xl">
				{t('home.heading')}
			</h1>
			<div class="flex flex-col items-center justify-center gap-3 sm:flex-row">
				<Button
					size="lg"
					href="https://ai2participa.eu.consider.it/"
					target="_blank"
					rel="noopener noreferrer"
				>
					{t('home.participateBtn')}
				</Button>
				<Button variant="outline" size="lg" href="mailto:ai2@planapp.gov.pt">
					{t('home.contributeBtn')}
				</Button>
			</div>
		</div>
	</div>
	<div class="absolute inset-0 -z-10 overflow-hidden">
		<div class="dotted-grid-bg absolute inset-0 opacity-70"></div>
	</div>
</section>

<section
	class="border-y border-primary-foreground/15 bg-primary py-12 text-primary-foreground md:py-16"
>
	<div class="container">
		<article class="mx-auto max-w-5xl">
			<p
				class="mb-4 inline-flex rounded-full bg-primary-foreground/15 px-3 py-1 text-sm font-semibold tracking-wide uppercase"
			>
				{getLang() === 'pt' ? 'Relatórios' : 'Reports'}
			</p>
			<h2 class="font-title text-3xl font-bold text-balance sm:text-4xl">
				{getLang() === 'pt'
					? 'Relatórios da Avaliação Estratégica'
					: 'Strategic Assessment reports'}
			</h2>
			<ul class="mt-6 space-y-3 text-lg leading-relaxed">
				<li>
					<a
						class="font-semibold underline underline-offset-4 hover:text-primary-foreground/80"
						href={asset('/docs/RelatorioFinalConsultaPublica.pdf')}
						target="_blank"
						rel="noreferrer"
					>
						{getLang() === 'pt'
							? 'Relatório Final da Avaliação Estratégica'
							: 'Final Strategic Assessment Report'}
					</a>
				</li>
				<li>
					<a
						class="font-semibold underline underline-offset-4 hover:text-primary-foreground/80"
						href={asset('/docs/RelatorioEnvolvimentoParticipacaoPublica.pdf')}
						target="_blank"
						rel="noreferrer"
					>
						{getLang() === 'pt'
							? 'Relatório Complementar - Relatório de Envolvimento e Participação Pública'
							: 'Complementary Report - Public Engagement and Participation Report'}
					</a>
				</li>
				<li>
					<a
						class="font-semibold underline underline-offset-4 hover:text-primary-foreground/80"
						href={asset('/docs/PropostaSistemaMonitorizacaoAvaliacao.pdf')}
						target="_blank"
						rel="noreferrer"
					>
						{getLang() === 'pt'
							? 'Relatório Complementar - Proposta de sistema de monitorização e avaliação da AI²'
							: 'Complementary Report - Proposal for a monitoring and evaluation system for AI²'}
					</a>
				</li>
			</ul>
			<p class="mt-6 text-lg leading-relaxed">
				{#if getLang() === 'pt'}
					Os documentos estão em consulta pública até 23 de novembro. Os contributos podem ser
					enviados para <a
						class="font-semibold underline underline-offset-4 hover:text-primary-foreground/80"
						href="mailto:ai2@planapp.gov.pt">ai2@planapp.gov.pt</a
					>.
				{:else}
					The documents are open for public consultation until 23 November. Contributions can be
					sent to <a
						class="font-semibold underline underline-offset-4 hover:text-primary-foreground/80"
						href="mailto:ai2@planapp.gov.pt">ai2@planapp.gov.pt</a
					>.
				{/if}
			</p>
		</article>
	</div>
</section>

<section class="border-b bg-background py-12 md:py-16">
	<div class="container">
		<article class="mx-auto max-w-5xl">
			<p
				class="mb-4 inline-flex rounded-full bg-primary px-3 py-1 text-sm font-semibold tracking-wide text-primary-foreground uppercase"
			>
				{t('home.event.eyebrow')}
			</p>
			<h2 class="font-title text-3xl font-bold text-balance sm:text-4xl">
				{t('home.event.title')}
			</h2>
			<div
				class="mt-5 flex flex-col gap-2 text-base font-semibold sm:flex-row sm:flex-wrap sm:gap-x-3"
			>
				<time datetime="2026-11-16">{t('home.event.date')}</time>
				<span class="hidden sm:inline" aria-hidden="true">·</span>
				<time datetime="2026-11-16T14:30:00+00:00">{t('home.event.time')}</time>
				<span class="hidden sm:inline" aria-hidden="true">·</span>
				<span>{t('home.event.location')}</span>
			</div>
			<div class="mt-5 space-y-4 text-lg leading-relaxed text-foreground/85">
				{#if getLang() === 'pt'}
					<p>
						As propostas de prioridades estratégicas para a Investigação e Inovação em Portugal,
						para o período 2027-2031, serão apresentadas a 16 de novembro, às 14h30, no Grande
						Auditório do Convento São Francisco, em Coimbra.
					</p>
					<p>
						O evento «Investigação e Inovação para transformar Portugal» apresenta as conclusões da
						Avaliação Estratégica das prioridades nacionais para a Investigação e Inovação,
						resultantes do processo AI²Participa, desenvolvido no âmbito da criação da Agência para
						a Investigação e Inovação (AI²). O encontro irá dar a conhecer os principais resultados
						da avaliação estratégica da Agência e apresentar as prioridades identificadas, os
						desafios societais a que procuram responder e o seu potencial contributo para o
						desenvolvimento do País.
					</p>
					<p>
						A iniciativa conta com a participação de responsáveis pela metodologia e pela
						coordenação do processo, dirigentes da AI² e do PLANAPP, bem como representantes de
						diferentes entidades e áreas de especialização.
					</p>
					<p>
						A sessão de abertura estará a cargo do Ministro da Educação, Ciência e Inovação,
						Fernando Alexandre. O encerramento estará a cargo da Secretária de Estado da Ciência e
						Inovação, Helena Canhão, e do Secretário de Estado da Economia, João Rui Ferreira. O
						programa contará ainda com a intervenção da Coordenadora Científica da Avaliação
						Estratégica, Professora Maria do Rosário Partidário, entre outros. O programa completo
						será divulgado em breve.
					</p>
					<p class="font-semibold text-foreground">
						A participação é gratuita, mas sujeita a inscrição prévia até 11 de novembro, ou até ao
						limite da lotação do espaço. O processo de acreditação no local terá início pelas 13h45.
					</p>
				{:else}
					<p>
						The proposed strategic priorities for Research and Innovation in Portugal for 2027–2031
						will be presented on 16 November at 14:30, in the Grande Auditório of Convento São
						Francisco, in Coimbra.
					</p>
					<p>
						The event “Investigação e Inovação para transformar Portugal” presents the conclusions
						of the Strategic Assessment of national Research and Innovation priorities, resulting
						from the AI²Participa process, developed in the context of creating the Agency for
						Research and Innovation (AI²). The meeting will share the main results of the Agency’s
						strategic assessment and present the priorities identified, the societal challenges they
						seek to address, and their potential contribution to the country’s development.
					</p>
					<p>
						The initiative includes those responsible for the methodology and coordination of the
						process, leaders of AI² and PLANAPP, and representatives of different organisations and
						areas of expertise.
					</p>
					<p>
						The opening session will be given by the Minister of Education, Science and Innovation,
						Fernando Alexandre. The closing session will be given by the Secretary of State for
						Science and Innovation, Helena Canhão, and the Secretary of State for the Economy, João
						Rui Ferreira. The programme will also include a contribution from the Scientific
						Coordinator of the Strategic Assessment, Professor Maria do Rosário Partidário, among
						others. The full programme will be announced shortly.
					</p>
					<p class="font-semibold text-foreground">
						Participation is free of charge, but requires prior registration by 11 November, or
						until the venue reaches capacity. Accreditation on site starts at 13:45.
					</p>
				{/if}
			</div>
			<Button
				size="lg"
				class="mt-6 w-full sm:w-auto"
				href="https://www.eventbrite.pt/e/bilhetes-investigacao-e-inovacao-para-transformar-portugal-2003463950608"
				target="_blank"
				rel="noopener noreferrer"
			>
				{t('home.event.button')}
			</Button>
		</article>
	</div>
</section>

<section class="bg-muted/30 py-16 md:py-20">
	<div class="typography container">
		<div class="large mx-auto max-w-5xl">
			{#if getLang() === 'pt'}
				<p>
					Portugal está a definir as suas <strong
						>prioridades nacionais de investigação e inovação</strong
					>
					no âmbito da criação da <strong>Agência para a Investigação e Inovação</strong> (AI²), E.P.E.
					Para apoiar decisões estratégicas que orientarão a atuação futura da agência, está em curso
					uma Avaliação Estratégica que abrange:
				</p>
				<ul>
					<li>
						Alocação orçamental às áreas de I&amp;D, aos domínios estratégicos e à Unidade de
						Promoção da Inovação (UPI);
					</li>
					<li>Definição dos domínios estratégicos da AI², incluindo possíveis subdomínios.</li>
				</ul>
				<p>
					Esta avaliação visa identificar opções estratégicas, analisar oportunidades e riscos, e
					sustentar a elaboração do contrato-programa plurianual da AI². Este processo centra-se em
					quatro questões essenciais:
				</p>
				<ul>
					<li>
						Que percentagem do orçamento deverá ser alocada às áreas de I&amp;D, domínios
						estratégicos e à UPI?
					</li>
					<li>
						Quantos e quais os domínios estratégicos devem integrar o contrato-programa entre o
						Governo e a AI²?
					</li>
					<li>Como deverá ser distribuído o orçamento entre os domínios estratégicos?</li>
					<li>Como deverá ser distribuído o orçamento entre as áreas de I&amp;D?</li>
				</ul>
			{:else}
				<p>
					Portugal is defining its <strong>national research and innovation priorities</strong>
					in the context of creating the <strong>Agency for Research and Innovation</strong> (AI²), E.P.E.
					To support strategic decisions that will guide the agency's future activities, a Strategic Assessment
					is currently underway covering:
				</p>
				<ul>
					<li>
						Budget allocation to R&amp;D areas, strategic domains and the Innovation Promotion Unit
						(UPI);
					</li>
					<li>Definition of AI²'s strategic domains, including possible sub-domains.</li>
				</ul>
				<p>
					This assessment aims to identify strategic options, analyse opportunities and risks, and
					support the preparation of AI²'s multi-annual programme contract. The process focuses on
					four key questions:
				</p>
				<ul>
					<li>
						What percentage of the budget should be allocated to R&amp;D areas, strategic domains
						and the UPI?
					</li>
					<li>
						How many and which strategic domains should be included in the programme contract
						between the Government and AI²?
					</li>
					<li>How should the budget be distributed among strategic domains?</li>
					<li>How should the budget be distributed among R&amp;D areas?</li>
				</ul>
			{/if}
		</div>
	</div>
</section>

<section class="py-20 md:py-24">
	<div class="container">
		<div class="mx-auto max-w-5xl text-center">
			<p class="text-lg leading-relaxed text-muted-foreground">
				{t('home.ctaText')}
			</p>
			<div class="mt-8 flex justify-center">
				<Button
					size="lg"
					href="https://ai2participa.eu.consider.it/"
					target="_blank"
					rel="noopener noreferrer"
				>
					{t('home.ctaBtn')}
				</Button>
			</div>
		</div>
	</div>
</section>

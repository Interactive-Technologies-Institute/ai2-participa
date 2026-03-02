<script lang="ts">
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
		<div class="mx-auto flex max-w-4xl flex-col items-center gap-8 text-center">
			<Logo class="h-48 w-auto" />
			<h1 class="font-title text-4xl font-bold sm:text-5xl md:text-6xl">
				{t('home.heading')}
			</h1>
			<div class="flex justify-center">
				<Button
					size="lg"
					href="https://ai2participa.eu.consider.it/"
					target="_blank"
					rel="noopener noreferrer"
				>
					{t('home.participateBtn')}
				</Button>
			</div>
		</div>
	</div>
	<div class="absolute inset-0 -z-10 overflow-hidden">
		<div class="dotted-grid-bg absolute inset-0 opacity-70"></div>
	</div>
</section>

<section class="bg-muted/30 py-16 md:py-20">
	<div class="typography container">
		<div class="large mx-auto max-w-4xl">
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

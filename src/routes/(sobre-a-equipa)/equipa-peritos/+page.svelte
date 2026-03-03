<script lang="ts">
	import { asset } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { Avatar, AvatarFallback, AvatarImage } from '$lib/components/ui/avatar';
	import { getLang, t } from '$lib/i18n.svelte';

	type Person = {
		name: string;
		image: string;
	};

	type Section = {
		titleKey: string;
		people: Person[];
	};

	const sections: Section[] = [
		{
			titleKey: 'expertTeam.s1',
			people: [
				{ name: 'Ana Quartin (FCT)', image: '/images/ana-quartin.jpg' },
				{ name: 'Artur Santoalha (ANI) - coordenador', image: '/images/artur-santoalha.jpg' },
				{ name: 'Dina Carrilho (FCT)', image: '/images/diana-carrilho.jpg' },
				{ name: 'Margarida Prado (FCT)', image: '/images/margarida-prado.jpg' },
				{ name: 'Marta Norton (FCT) - coordenadora', image: '/images/marta-norton.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s2',
			people: [
				{ name: 'António Bob Santos (FCT)', image: '/images/antonio-bob-santos.jpg' },
				{ name: 'Bruno Béu (FCT) - coordenador', image: '/images/bruno-beu.jpg' },
				{
					name: 'Cristiana Leandro (ANI) - coordenadora',
					image: '/images/cristiana-leandro.jpg'
				},
				{ name: 'Rui Munhá (FCT)', image: '/images/rui-munha.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s3',
			people: [
				{ name: 'Bruno Béu (FCT) - coordenador', image: '/images/bruno-beu.jpg' },
				{ name: 'João Ribau (ANI) - coordenador', image: '/images/joao-ricau.jpg' },
				{ name: 'Luís Ascenção (FCT)', image: '/images/luis-ascencao.jpg' },
				{ name: 'Nanete Sousa (FCT)', image: '/images/nanete-sousa.jpg' },
				{ name: 'Pedro Leite (FCT) - coordenador', image: '/images/pedro-leite.jpg' },
				{ name: 'Rui Munhá (FCT)', image: '/images/rui-munha.jpg' },
				{ name: 'Susana Dias (FCT)', image: '/images/susana-dias.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s4',
			people: [
				{ name: 'João Ferreira (ANI) - coordenador', image: '/images/joao-lobo-ferreira.jpg' },
				{
					name: 'António Bob Santos (FCT) - coordenador',
					image: '/images/antonio-bob-santos.jpg'
				},
				{ name: 'Bruno Béu (FCT)', image: '/images/bruno-beu.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s5',
			people: [
				{ name: 'Sofia Azevedo (ANI) - coordenadora', image: '/images/sofia-azevedo.jpg' },
				{ name: 'Bruno Béu (FCT) - coordenador', image: '/images/bruno-beu.jpg' },
				{ name: 'Madalena Alves (FCT)', image: '/images/madalena-alves.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s6',
			people: [
				{ name: 'Marisa Borges (ANI) - coordenadora', image: '/images/marisa-borges.jpg' },
				{ name: 'Daniel Carapau (FCT) - coordenador', image: '/images/daniel-carapau.jpg' },
				{ name: 'João Nuno Ferreira (FCT)', image: '/images/joao-nuno-ferreira.jpg' },
				{ name: 'Marta Abrantes (FCT)', image: '/images/marta-abrantes.jpg' },
				{ name: 'Sílvia Figueiras (FCT)', image: '/images/silvia-figueiras.jpg' }
			]
		}
	];
</script>

<PageHeader title={t('page.expertTeam.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A Avaliação Estratégica da AI² é apoiada por uma equipa de peritos provenientes da FCT e da
				ANI que irão contribuir para realizar diagnósticos estratégicos, análises de tendências e
				avaliação de opções estratégicas, bem como facilitação de mesas temáticas.
			</p>
			<p>
				coordenados pela Professora Maria do Rosário Partidário, os peritos estão organizados por
				temas-chave da Avaliação Estratégica:
			</p>
		{:else}
			<p>
				The AI² Strategic Assessment is supported by a team of experts from the National Innovation
				Agency, S. A. (ANI) and the Foundation for Science and Technology, I. P. (FCT) who will
				contribute to strategic diagnoses, trend analyses and assessment of strategic options, as
				well as facilitation of thematic roundtables.
			</p>
			<p>
				coordinated by Professor Maria do Rosário Partidário, the experts are organised by key
				themes of the Strategic Assessment:
			</p>
		{/if}
		{#each sections as section}
			<section class="mt-12">
				<h2>{t(section.titleKey)}</h2>
				<ul class="grid gap-4 sm:grid-cols-2">
					{#each section.people as person (section.titleKey + '|' + person.name + '|' + person.image)}
						<li class="not-typography flex items-center gap-4">
							<Avatar class="size-14">
								<AvatarImage
									src={asset(person.image)}
									alt={`${t('page.expertTeam.photoAlt')} ${person.name}`}
								/>
								<AvatarFallback>
									{person.name.slice(0, 1).toUpperCase()}
								</AvatarFallback>
							</Avatar>
							<span>{person.name}</span>
						</li>
					{/each}
				</ul>
			</section>
		{/each}
	</div>

	<div class="typography mt-10 space-y-10"></div>
</div>

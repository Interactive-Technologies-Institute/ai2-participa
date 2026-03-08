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
				{ name: 'Artur Santoalha (ANI) ', image: '/images/artur-santoalha.jpg' },
				{ name: 'Marta Norton (FCT) ', image: '/images/marta-norton.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s2',
			people: [
				{ name: 'Bruno Béu (FCT) ', image: '/images/bruno-beu.jpg' },
				{ name: 'Cristiana Leandro (ANI) ', image: '/images/cristiana-leandro.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s3',
			people: [
				{ name: 'João Ribau (ANI)', image: '/images/joao-ricau.jpg' },
				{ name: 'Pedro Leite (FCT)', image: '/images/pedro-leite.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s4',
			people: [
				{ name: 'João Ferreira (ANI)', image: '/images/joao-lobo-ferreira.jpg' },
				{ name: 'Rui Munhá (FCT)', image: '/images/rui-munha.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s5',
			people: [
				{ name: 'Sofia Azevedo (ANI) ', image: '/images/sofia-azevedo.jpg' },
				{ name: 'Bruno Béu (FCT) ', image: '/images/bruno-beu.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s6',
			people: [
				{ name: 'Marisa Borges (ANI) ', image: '/images/marisa-borges.jpg' },
				{ name: 'Daniel Carapau (FCT) ', image: '/images/daniel-carapau.jpg' }
			]
		}
	];
</script>

<PageHeader title={t('page.expertTeam.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A Avaliação Estratégica da AI² é apoiada por uma equipa de peritos da FCT e da ANI,
				coordenada pela Professora Maria do Rosário Partidário. Esta equipa irá contribuir para a
				realização de diagnósticos estratégicos, análises de tendências, avaliação de opções
				estratégicas, bem como para a facilitação de mesas temáticas.
			</p>
			<p>
				Os peritos estão organizados por temas-chave da Avaliação Estratégica, com os seguintes
				coordenadores:
			</p>
		{:else}
			<p>
				The AI² Strategic Assessment is supported by a team of experts from the National Innovation
				Agency, S. A. (ANI) and the Foundation for Science and Technology, I. P. (FCT), coordinated
				by Professor Maria do Rosário Partidário. They will contribute to strategic diagnoses, trend
				analyses and assessment of strategic options, as well as facilitation of thematic
				roundtables.
			</p>
			<p>The experts are organised by key themes of the Strategic Assessment:</p>
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

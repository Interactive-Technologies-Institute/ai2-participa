<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { asset } from '$app/paths';
	import { getLang, t } from '$lib/i18n.svelte';

	type Person = {
		name: string;
		org?: 'FCT' | 'ANI';
		role?: 'coordinator' | 'coordinatorf';
		photo?: string;
	};

	type Section = {
		titleKey: string;
		people: Person[];
	};

	const sections: Section[] = [
		{
			titleKey: 'expertTeam.s1',
			people: [
				{ name: 'Ana Quartin', org: 'FCT', photo: '/photos/AnaQuartin-FCT.jpg' },
				{ name: 'Artur Santoalha', org: 'ANI', role: 'coordinator', photo: '/photos/ArturSantoalha-ANI.jpg' },
				{ name: 'Dina Carrilho', org: 'FCT', photo: '/photos/DianaCarrilho-FCT.jpg' },
				{ name: 'Margarida Prado', org: 'FCT', photo: '/photos/MPrado.jpg' },
				{ name: 'Marta Norton', org: 'FCT', role: 'coordinatorf', photo: '/photos/MartaNorton.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s2',
			people: [
				{ name: 'António Bob Santos', org: 'FCT', photo: '/photos/AntonioBobSantos-FCT.jpg' },
				{ name: 'Bruno Béu', org: 'FCT', role: 'coordinator', photo: '/photos/BrunoBeu-RECT.jpg' },
				{ name: 'Cristiana Leandro', org: 'ANI', role: 'coordinatorf', photo: '/photos/CristianaLeadro-ANI.jpg' },
				{ name: 'Rui Munhá', org: 'FCT', photo: '/photos/RuiMunha.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s3',
			people: [
				{ name: 'Bruno Béu', org: 'FCT', role: 'coordinator', photo: '/photos/BrunoBeu-RECT.jpg' },
				{ name: 'João Ribau', org: 'ANI', role: 'coordinator', photo: '/photos/JoaoRicau.jpg' },
				{ name: 'Luís Ascenção', org: 'FCT', photo: '/photos/LuisAscencao-FCT.jpg' },
				{ name: 'Nanete Sousa', org: 'FCT', photo: '/photos/NaneteSousa.jpg' },
				{ name: 'Pedro Leite', org: 'FCT', role: 'coordinator', photo: '/photos/PedroLeite-FCT.jpg' },
				{ name: 'Rui Munhá', org: 'FCT', photo: '/photos/RuiMunha.jpg' },
				{ name: 'Susana Dias', org: 'FCT', photo: '/photos/SusanaDias-FCT.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s4',
			people: [
				{ name: 'João Ferreira', org: 'ANI', role: 'coordinator', photo: '/photos/JoaoLoboFerreira-ANI.jpg' },
				{ name: 'António Bob Santos', org: 'FCT', role: 'coordinator', photo: '/photos/AntonioBobSantos-FCT.jpg' },
				{ name: 'Bruno Béu', org: 'FCT', photo: '/photos/BrunoBeu-RECT.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s5',
			people: [
				{ name: 'Sofia Azevedo', org: 'ANI', role: 'coordinatorf', photo: '/photos/SofiaAzevedo-ANI.jpg' },
				{ name: 'Bruno Béu', org: 'FCT', role: 'coordinator', photo: '/photos/BrunoBeu-RECT.jpg' },
				{ name: 'Madalena Alves', org: 'FCT', photo: '/photos/MadalenaAlves-FCT.jpg' }
			]
		},
		{
			titleKey: 'expertTeam.s6',
			people: [
				{ name: 'Marisa Borges', org: 'ANI', role: 'coordinatorf', photo: '/photos/MarisaBorges.jpg' },
				{ name: 'Daniel Carapau', org: 'FCT', role: 'coordinator', photo: '/photos/DanielCarapau-FCT.jpg' },
				{ name: 'João Nuno Ferreira', org: 'FCT', photo: '/photos/JoaoNunoFerreira.jpg' },
				{ name: 'Marta Abrantes', org: 'FCT', photo: '/photos/MAbrantes-FCT.jpg' },
				{ name: 'Sílvia Figueiras', org: 'FCT', photo: '/photos/SilviaFigueiras-FCT.jpg' }
			]
		}
	];

	function label(person: Person): string {
		let s = person.name;
		if (person.org) s += ` (${person.org})`;
		if (person.role) s += ` - ${t(`page.expertTeam.role.${person.role}`)}`;
		return s;
	}
</script>

<PageHeader title={t('page.expertTeam.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				A Avaliação Estratégica da AI² é apoiada por uma equipa de peritos provenientes da FCT e da ANI
				que irão contribuir para realizar diagnósticos estratégicos, análises de tendências e avaliação
				de opções estratégicas, bem como facilitação de mesas temáticas.
			</p>
			<p>
				Coordenados pela Professora Maria do Rosário Partidário, os peritos estão organizados por
				temas-chave da Avaliação Estratégica:
			</p>
		{:else}
			<p>
				The AI² Strategic Assessment is supported by a team of experts from the National Innovation Agency, S. A. (ANI) and the Foundation for Science and Technology, I. P. (FCT) who will
				contribute to strategic diagnoses, trend analyses and assessment of strategic options, as
				well as facilitation of thematic roundtables.
			</p>
			<p>
				Coordinated by Professor Maria do Rosário Partidário, the experts are organised by key themes
				of the Strategic Assessment:
			</p>
		{/if}
	</div>

	<div class="mt-10 space-y-10">
		{#each sections as section}
			<section class="space-y-4">
				<h2 class="typography">{t(section.titleKey)}</h2>
				<ul class="grid gap-4 sm:grid-cols-2">
					{#each section.people as person (section.titleKey + '|' + person.name + '|' + (person.role ?? ''))}
						<li class="flex items-center gap-4">
							{#if person.photo}
								<img
									src={asset(person.photo)}
									alt={`${t('page.expertTeam.photoAlt')} ${person.name}`}
									class="h-14 w-14 shrink-0 rounded-full object-cover shadow-sm border border-slate-200 bg-slate-50"
									loading="lazy"
								/>
							{:else}
								<div class="h-14 w-14 shrink-0 rounded-full border border-slate-200 bg-slate-50"></div>
							{/if}
							<span>{label(person)}</span>
						</li>
					{/each}
				</ul>
			</section>
		{/each}
	</div>
</div>

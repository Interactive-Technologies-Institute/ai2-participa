<script lang="ts">
	import PageHeader from '$lib/components/page-header.svelte';
	import { asset } from '$app/paths';

	type Person = {
		name: string;
		org?: 'FCT' | 'ANI';
		role?: string;
		photo?: string;
	};

	type Section = {
		title: string;
		people: Person[];
	};

	const sections: Section[] = [
		{
			title: 'Desafios societais e necessidades de investigação e inovação',
			people: [
				{ name: 'Ana Quartin', org: 'FCT', photo: '/photos/AnaQuartin-FCT.jpg' },
				{ name: 'Artur Santoalha', org: 'ANI', role: 'coordenador', photo: '/photos/ArturSantoalha-ANI.jpg' },
				{ name: 'Dina Carrilho', org: 'FCT', photo: '/photos/DianaCarrilho-FCT.jpg' },
				{ name: 'Margarida Prado', org: 'FCT', photo: '/photos/MPrado.jpg' },
				{ name: 'Marta Norton', org: 'FCT', role: 'coordenadora', photo: '/photos/MartaNorton.jpg' }
			]
		},
		{
			title: 'Governança e ecossistema de investigação e inovação',
			people: [
				{ name: 'António Bob Santos', org: 'FCT', photo: '/photos/AntonioBobSantos-FCT.jpg' },
				{ name: 'Bruno Béu', org: 'FCT', role: 'coordenador', photo: '/photos/BrunoBeu-RECT.jpg' },
				{ name: 'Cristiana Leandro', org: 'ANI', role: 'coordenadora', photo: '/photos/CristianaLeadro-ANI.jpg' },
				{ name: 'Rui Munhá', org: 'FCT', photo: '/photos/RuiMunha.jpg' }
			]
		},
		{
			title: 'Modelo e fontes de financiamento',
			people: [
				{ name: 'Bruno Béu', org: 'FCT', role: 'coordenador', photo: '/photos/BrunoBeu-RECT.jpg' },
				{ name: 'João Ribau', org: 'ANI', role: 'coordenador', photo: '/photos/JoaoRicau.jpg' },
				{ name: 'Luís Ascenção', org: 'FCT', photo: '/photos/LuisAscencao-FCT.jpg' },
				{ name: 'Nanete Sousa', org: 'FCT', photo: '/photos/NaneteSousa.jpg' },
				{ name: 'Pedro Leite', org: 'FCT', role: 'coordenador', photo: '/photos/PedroLeite-FCT.jpg' },
				{ name: 'Rui Munhá', org: 'FCT', photo: '/photos/RuiMunha.jpg' },
				{ name: 'Susana Dias', org: 'FCT', photo: '/photos/SusanaDias-FCT.jpg' }
			]
		},
		{
			title: 'Relação entre investigação e inovação',
			people: [
				{ name: 'João Ferreira', org: 'ANI', role: 'coordenador', photo: '/photos/JoaoLoboFerreira-ANI.jpg' },
				{ name: 'António Bob Santos', org: 'FCT', role: 'coordenador', photo: '/photos/AntonioBobSantos-FCT.jpg' },
				{ name: 'Bruno Béu', org: 'FCT', photo: '/photos/BrunoBeu-RECT.jpg' }
			]
		},
		{
			title: 'Áreas de I&D',
			people: [
				{ name: 'Sofia Azevedo', org: 'ANI', role: 'coordenadora', photo: '/photos/SofiaAzevedo-ANI.jpg' },
				{ name: 'Bruno Béu', org: 'FCT', role: 'coordenador', photo: '/photos/BrunoBeu-RECT.jpg' },
				{ name: 'Madalena Alves', org: 'FCT', photo: '/photos/MadalenaAlves-FCT.jpg' }
			]
		},
		{
			title: 'Infraestruturas e emprego científico e tecnológico',
			people: [
				{ name: 'Marisa Borges', org: 'ANI', role: 'coordenadora', photo: '/photos/MarisaBorges.jpg' },
				{ name: 'Daniel Carapau', org: 'FCT', role: 'coordenador', photo: '/photos/DanielCarapau-FCT.jpg' },
				{ name: 'João Nuno Ferreira', org: 'FCT', photo: '/photos/JoaoNunoFerreira.jpg' },
				{ name: 'Marta Abrantes', org: 'FCT', photo: '/photos/MAbrantes-FCT.jpg' },
				{ name: 'Sílvia Figueiras', org: 'FCT', photo: '/photos/SilviaFigueiras-FCT.jpg' }
			]
		}
	];

	function label(person: Person) {
		let s = person.name;
		if (person.org) s += ` (${person.org})`;
		if (person.role) s += ` - ${person.role}`;
		return s;
	}
</script>

<PageHeader title="Equipa de Peritos" />
<div class="container my-12 md:my-24">
	<div class="typography">
		<p>
			A Avaliação Estratégica da AI² é apoiada por uma equipa de peritos provenientes da FCT e da ANI
			que irão contribuir para realizar diagnósticos estratégicos, análises de tendências e avaliação
			de opções estratégicas, bem como facilitação de mesas temáticas.
		</p>
		<p>
			Coordenados pela Professora Maria do Rosário Partidário, os peritos estão organizados por
			temas-chave da Avaliação Estratégica:
		</p>
	</div>

	<div class="mt-10 space-y-10">
		{#each sections as section}
			<section class="space-y-4">
				<h2 class="typography">{section.title}</h2>
				<ul class="grid gap-4 sm:grid-cols-2">
					{#each section.people as person (section.title + '|' + person.name + '|' + (person.role ?? ''))}
						<li class="flex items-center gap-4">
							{#if person.photo}
								<img
									src={asset(person.photo)}
									alt={`Foto de ${person.name}`}
									class="h-14 w-14 shrink-0 rounded-full object-cover shadow-sm border border-slate-200 bg-slate-50"
									loading="lazy"
								/>
							{:else}
								<div class="h-14 w-14 shrink-0 rounded-full border border-slate-200 bg-slate-50" />
							{/if}
							<span>{label(person)}</span>
						</li>
					{/each}
				</ul>
			</section>
		{/each}
	</div>
</div>

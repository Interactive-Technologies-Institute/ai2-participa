<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.thematicTables.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				As mesas temáticas criam um espaço de reflexão conjunta sobre temas relevantes para a
				alocação orçamental da AI2 e para a definição dos domínios estratégicos que constituem o
				problema de decisão na Avaliação Estratégica. O objetivo das mesas temáticas é construir
				conhecimento, explorando em profundidade aspetos críticos, consensos e divergências, e
				propostas concretas sobre os temas em discussão. As reflexões das mesas temáticas constituem
				contributos fundamentais para diferentes fases da metodologia da Avaliação Estratégica.
			</p>
			<p>São seis as mesas temáticas:</p>
			<ul>
				<li>
					Carreiras Científicas e Infraestruturas (<a
						href={resolve('/mesas-tematicas/highlights-1-carreiras-cientificas-e-infraestruturas/')}
						>highlights da 1.ª ronda</a
					>)
				</li>
				<li>
					Da Ideia ao Mercado (e do Mercado à Ideia) (<a
						href={resolve('/mesas-tematicas/highlights-1-da-ideia-ao-mercado/')}
						>highlights da 1.ª ronda</a
					>)
				</li>
				<li>
					Investigação e Inovação - com e para - a Sociedade (<a
						href={resolve(
							'/mesas-tematicas/highlights-1-investigacao-e-inovacao-com-e-para-a-sociedade/'
						)}>highlights da 1.ª ronda</a
					>)
				</li>
				<li>
					Interdisciplinaridade e Áreas emergentes (<a
						href={resolve('/mesas-tematicas/highlights-1-interdisciplinaridade-e-areas-emergentes/')}
						>highlights da 1.ª ronda</a
					>)
				</li>
				<li>
					Arquitetura do Financiamento em I&amp;I (<a
						href={resolve('/mesas-tematicas/highlights-1-arquitetura-do-financiamento-em-ii/')}
						>highlights da 1.ª ronda</a
					>)
				</li>
				<li>
					Governança da AI2 no Ecossistema I&amp;I (<a
						href={resolve('/mesas-tematicas/highlights-1-governanca-da-ai2-no-ecossistema-ii/')}
						>highlights da 1.ª ronda</a
					>)
				</li>
			</ul>
			<p>
				As mesas temáticas têm entre 16 e 23 especialistas, individualidades com experiência,
				conhecimento e perspetivas plurais que permitem alimentar um diálogo e uma discussão
				criativa, mantendo um olhar estratégico sobre o tema em discussão. Cobrem um amplo conjunto
				de perspetivas, desde a comunidade académica, ao sistema científico e tecnológico, setor
				empresarial, Administração Pública e sociedade civil. Cada mesa é co-moderada por um
				especialista convidado e por um ou dois peritos da equipa da Avaliação Estratégica.
				Participaram como observadores a Coordenadora-geral da Avaliação Estratégica, outros peritos
				da equipa da Avaliação Estratégica, o PLANAPP, a DGE, a DGEPA e elementos dos gabinetes da
				Secretária de Estado da Ciência e Inovação e do Secretário de Estado da Economia. Cada mesa
				temática decorre em três rondas: 1.ª ronda em abril já realizada entre 15 e 30 de abril; 2.ª
				ronda em junho/julho; 3.ª ronda em setembro.
			</p>

			<p>
				<strong>Lista de participantes nas mesas temáticas</strong> (por ordem alfabética): Adelino
				Canário, Alexandra Teodósio, Alexandra Vilela, Ana Casaca, Ana Delicado (moderadora), Ana
				Domingos, Ana Ferreira, Ana Justino, Anabela Carvalho, André Mão de Ferro, André Matos,
				António Braz Costa, António Candeias, António Cunha, António Jacinto, António Portela,
				Arlindo Oliveira, Artur Santoalha, Bárbara Gomes, Bruno Béu (co-moderador), Carla Branco
				Santos, Carlos Pascoal Neto, Cecília Roque, Cláudia Cavadas (moderadora), Cláudio Sunkel,
				Cristiana Leandro, Daniel Carapau (co-moderador), Daniel Matias, Daniela Braga, Delfim Leão,
				Duarte Alemão, Eduardo Rodrigues, Eloy Rodrigues, Filipe Natálio, Francisco Ruivo Rodrigues,
				Helena Freitas, Helena Maio, Helena Peres, Inês Lynce, Isabel Rocha, Ivo Vieira, Joana
				Branco, Joana Gonçalves Sá, Joana Lobo Antunes, João Claro, João Crespo (moderador), João
				Ferreira (co-moderador), João Gabriel Silva, João Mano, João Ribau (co-moderador), João
				Rocha, João Seixas, João Vilaça, Jorge Gomes, Jorge Portugal (moderador), José Carlos
				Caldeira, José Manuel Mendonça, Júlia Seixas, Liliana Ferreira, Luís Barbosa, Luis
				Carvalho, Luis Oliveira e Silva (moderador), Luísa Cortes, Manuela Pintado, Maria Custódia
				Correia, Maria Helena Godinho, Maria Mota, Maria João Leão, Marina Costa Lobo, Marisa Borges
				(co-moderadora), Marlos Silva, Marta Agostinho, Marta Norton (co-moderadora), Mónica Sousa,
				Nuno Araújo, Nuno Bento, Nuno Bicho, Nuno Cerca, Nuno Matos, Nuno Prego Ramos, Paulo
				Ferreira, Paulo Pereira, Pedro Alberto, Pedro Garret, Pedro Leite (co-moderador), Pedro Pita
				Barros (moderador), Ricardo Paes Mamede, Ricardo Rato, Ruben Branco, Rui Munhá
				(co-moderador), Rui Reis, Sandro Mendonça, Sara Falcão Casaca, Sara Magalhães, Sílvia
				Socorro, Sofia Azevedo, Sónia Ferreira, Susana Peralta, Susana Sargento, Telmo Morato,
				Teresa Ponce de Leão, Teresa Sumavielle, Tiago Santos Pereira, Vanessa Marcos, Vera
				Aldeias, Vitor Vasconcelos.
			</p>
		{:else}
			<p>
				The thematic tables create a space for joint reflection on topics relevant to AI2 budget
				allocation and to the definition of the strategic domains that make up the decision problem
				in the Strategic Assessment. The aim of the thematic tables is to build knowledge by
				exploring in depth the critical aspects, areas of consensus and divergence, and concrete
				proposals on the topics under discussion. The reflections from the thematic tables are
				fundamental contributions to different phases of the Strategic Assessment methodology.
			</p>
			<p>There are six thematic tables:</p>
			<ul>
				<li>
					Scientific Careers and Infrastructures (<a
						href={resolve('/mesas-tematicas/highlights-1-carreiras-cientificas-e-infraestruturas/')}
						>highlights from the 1st round</a
					>)
				</li>
				<li>
					From Idea to Market (and from Market to Idea) (<a
						href={resolve('/mesas-tematicas/highlights-1-da-ideia-ao-mercado/')}
						>highlights from the 1st round</a
					>)
				</li>
				<li>
					Research and Innovation - with and for - Society (<a
						href={resolve(
							'/mesas-tematicas/highlights-1-investigacao-e-inovacao-com-e-para-a-sociedade/'
						)}>highlights from the 1st round</a
					>)
				</li>
				<li>
					Interdisciplinarity and Emerging Areas (<a
						href={resolve('/mesas-tematicas/highlights-1-interdisciplinaridade-e-areas-emergentes/')}
						>highlights from the 1st round</a
					>)
				</li>
				<li>
					Architecture of R&amp;I Funding (<a
						href={resolve('/mesas-tematicas/highlights-1-arquitetura-do-financiamento-em-ii/')}
						>highlights from the 1st round</a
					>)
				</li>
				<li>
					AI2 Governance in the R&amp;I Ecosystem (<a
						href={resolve('/mesas-tematicas/highlights-1-governanca-da-ai2-no-ecossistema-ii/')}
						>highlights from the 1st round</a
					>)
				</li>
			</ul>
			<p>
				The thematic tables have between 16 and 23 experts, individuals with experience, knowledge
				and diverse perspectives that enable creative dialogue and discussion, while maintaining a
				strategic view of the topic under discussion. They cover a broad range of perspectives, from
				the academic community, the scientific and technological system, the business sector, Public
				Administration and civil society. Each table is co-moderated by an invited expert and one or
				two experts from the Strategic Assessment team. Observers included the General Coordinator
				of the Strategic Assessment, other experts from the Strategic Assessment team, PLANAPP, DGE,
				DGEPA and staff from the offices of the Secretary of State for Science and Innovation and
				the Secretary of State for the Economy. Each thematic table takes place in three rounds: 1st
				round in April already held between 15 and 30 April; 2nd round in June/July; 3rd round in
				September.
			</p>

			<p>
				<strong>List of participants in the thematic tables</strong> (alphabetical order): Adelino
				Canário, Alexandra Teodósio, Alexandra Vilela, Ana Casaca, Ana Delicado (moderator), Ana
				Domingos, Ana Ferreira, Ana Justino, Anabela Carvalho, André Mão de Ferro, André Matos,
				António Braz Costa, António Candeias, António Cunha, António Jacinto, António Portela,
				Arlindo Oliveira, Artur Santoalha, Bárbara Gomes, Bruno Béu (co-moderator), Carla Branco
				Santos, Carlos Pascoal Neto, Cecília Roque, Cláudia Cavadas (moderator), Cláudio Sunkel,
				Cristiana Leandro, Daniel Carapau (co-moderator), Daniel Matias, Daniela Braga, Delfim Leão,
				Duarte Alemão, Eduardo Rodrigues, Eloy Rodrigues, Filipe Natálio, Francisco Ruivo Rodrigues,
				Helena Freitas, Helena Maio, Helena Peres, Inês Lynce, Isabel Rocha, Ivo Vieira, Joana
				Branco, Joana Gonçalves Sá, Joana Lobo Antunes, João Claro, João Crespo (moderator), João
				Ferreira (co-moderator), João Gabriel Silva, João Mano, João Ribau (co-moderator), João
				Rocha, João Seixas, João Vilaça, Jorge Gomes, Jorge Portugal (moderator), José Carlos
				Caldeira, José Manuel Mendonça, Júlia Seixas, Liliana Ferreira, Luís Barbosa, Luis Carvalho,
				Luis Oliveira e Silva (moderator), Luísa Cortes, Manuela Pintado, Maria Custódia Correia,
				Maria Helena Godinho, Maria Mota, Maria João Leão, Marina Costa Lobo, Marisa Borges
				(co-moderator), Marlos Silva, Marta Agostinho, Marta Norton (co-moderator), Mónica Sousa,
				Nuno Araújo, Nuno Bento, Nuno Bicho, Nuno Cerca, Nuno Matos, Nuno Prego Ramos, Paulo
				Ferreira, Paulo Pereira, Pedro Alberto, Pedro Garret, Pedro Leite (co-moderator), Pedro Pita
				Barros (moderator), Ricardo Paes Mamede, Ricardo Rato, Ruben Branco, Rui Munhá
				(co-moderator), Rui Reis, Sandro Mendonça, Sara Falcão Casaca, Sara Magalhães, Sílvia
				Socorro, Sofia Azevedo, Sónia Ferreira, Susana Peralta, Susana Sargento, Telmo Morato,
				Teresa Ponce de Leão, Teresa Sumavielle, Tiago Santos Pereira, Vanessa Marcos, Vera
				Aldeias, Vitor Vasconcelos.
			</p>
		{/if}
	</div>
</div>

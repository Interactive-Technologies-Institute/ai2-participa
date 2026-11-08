<script lang="ts">
	import { resolve } from '$app/paths';
	import PageHeader from '$lib/components/page-header.svelte';
	import { getLang, t } from '$lib/i18n.svelte';
</script>

<PageHeader title={t('page.decentralizedWorkshops.title')} />
<div class="container my-12 md:my-24">
	<div class="typography">
		{#if getLang() === 'pt'}
			<p>
				Os workshops descentralizados têm como objetivo apresentar o processo, esclarecer dúvidas e
				recolher contributos em tempo real. Está previsto um workshop em cada região NUTS II do continente,
				bem como nas Regiões Autónomas, num total de dez ao longo da Avaliação Estratégica.
			</p>
			<p>
				Os workshops são dinamizados por atores locais, sob a forma de sessões semi-abertas. Participam
				líderes de opinião e representantes de entidades relevantes do ecossistema de investigação e
				inovação, procurando-se garantir um equilíbrio de perspetivas da academia, inovação, empresas,
				indústria e administração local e regional, com uma dimensão entre 20 e 60 participantes. Os
				participantes são organizados em grupos mistos, assegurando diversidade de perfis em cada grupo. As
				sessões assentam em dinâmicas participativas, centradas na discussão em grupo e na partilha de
				contributos com base em questões orientadoras previamente definidas, contando com facilitadores para
				apoiar a dinamização e a gestão do tempo.
			</p>
			<p>
				Na primeira fase de focagem, os workshops têm como objetivo apresentar o processo de Avaliação
				Estratégica e as suas prioridades políticas, discutir criticamente os principais problemas
				identificados, esclarecer dúvidas e recolher contributos dos participantes sobre a sua concretização
				a nível local e regional. Esta reflexão contribui para a identificação de fatores críticos para a
				decisão, no âmbito da avaliação de opções estratégicas relacionadas com a alocação de recursos
				financeiros e a definição de domínios prioritários de investigação e inovação, articulados com o
				território e o desenvolvimento regional.
			</p>
			<p>
				Já foram realizados os cinco workshops da primeira fase de focagem em Évora, Funchal, Bragança,
				Porto e Coimbra (ver abaixo). Estão ainda previstos cinco workshops a realizar em setembro de
				2026: Lagoa/Açores (8 de setembro), Covilhã (10 de setembro), Faro (14 de setembro), Braga (16
				de setembro) e Aveiro (17 de setembro). O tema destes workshops será a identificação das
				opções estratégicas e a sua avaliação.
			</p>

			<h2>WORKSHOPS DA FASE DE FOCAGEM:</h2>
			<p>
				Síntese global dos workshops (<a
					href={resolve('/workshops-descentralizados/highlights-sintese-global/')}
					>highlights da fase de focagem</a
				>)
			</p>

			<p>
				<strong>ÉVORA:</strong> workshop realizado a 5 de maio de 2026, no PACT - Parque do Alentejo de
				Ciência e Tecnologia, dinamizado localmente pelas Professoras Teresa Pinto Correia e Susana Filipe
				(Universidade de Évora, CHANGE). (<a
					href={resolve('/workshops-descentralizados/highlights-evora/')}>highlights da fase de focagem</a
				>)
			</p>
			<p>
				<strong>Lista de entidades participantes (por ordem alfabética):</strong> ACOS - Associação de
				Agricultores do Sul, AERNNova, Águas Públicas do Alentejo, APA, IP - AHR Alentejo, ARNET, Câmara
				Municipal de Évora, Câmara Municipal de Odemira, Cátedra UNESCO Património Cultural Imaterial, CEBAL,
				CHAIA – Universidade de Évora, CHANGE – Universidade de Évora, CHRC, CICS.NOVA – Universidade de
				Évora, CIDEHUS – Universidade de Évora, Cluster Mineral Resources, CREATE, ERA Arqueologia, Estação
				Biológica de Mértola, FCT, IHC – Universidade de Évora, InnovPlantProtect, Instituto Politécnico de
				Beja, Instituto Politécnico de Portalegre, NOVA LINCS – Universidade de Évora, Porto de Sines,
				Portugal Nuts, PRF, Sines Tecnopolo, SoilArray Lda., SOL4R, Terras Dentro, Universidade de Évora,
				VISTA Lab – Universidade de Évora.
			</p>

			<p>
				<strong>FUNCHAL:</strong> workshop realizado a 7 de maio de 2026, na Reitoria da Universidade da
				Madeira, dinamizado localmente pelo Professor José Câmara (Vice-Reitor para a Investigação, Inovação
				e Internacionalização da Universidade da Madeira) e Dra. Clementina Reis (Gabinete de Transferência de
				Conhecimento, Universidade da Madeira). (<a
					href={resolve('/workshops-descentralizados/highlights-funchal/')}>highlights da fase de focagem</a
				>)
			</p>
			<p>
				<strong>Lista de entidades participantes (por ordem alfabética):</strong> ACIN iCloud Solutions, Apus
				Trust, Centro de Investigação em Educação – Universidade da Madeira, CQM - Centro de Química da
				Madeira – Universidade da Madeira, Direção Regional da Saúde, Direção Regional de Competitividade,
				Inovação e Sustentabilidade, FCT, Frederico Mendes &amp; Associados, Grupo de Astronomia –
				Universidade da Madeira, Horários do Funchal, IDE - Instituto de Desenvolvimento Empresarial, INSC-
				Informática Serviços e Consultadoria, Lda., INSC, Lda., Instituto de Tecnologias Interativas – LARSyS
				– Universidade da Madeira, Invest Madeira, ISOPlexis – Centro em Agricultura Sustentável e Tecnologia
				Agroalimentar – Universidade da Madeira, Laboratório Genética Humana – Universidade da Madeira,
				Madeira Wine Company, SA, MARE-Madeira, Universidade da Madeira.
			</p>

			<p>
				<strong>BRAGANÇA:</strong> workshop realizado a 13 de maio de 2026, no Brigantia Ecopark - Parque de
				Ciência e Tecnologia, dinamizado localmente pela Dra Clotilde Nogueira (Diretora Executiva do Centro
				Ciência Viva de Bragança). (<a
					href={resolve('/workshops-descentralizados/highlights-braganca/')}>highlights da fase de focagem</a
				>)
			</p>
			<p>
				<strong>Lista de entidades participantes (por ordem alfabética):</strong> ADRAT, Aquavalor, Associação
				Douro Histórico, Bísaro - Salsicharia Tradicional, Lda., Boticas Hotel Art&amp;SPA, Câmara Municipal
				de Bragança, CATRAPORT, LDA., CeDRI – Instituto Politécnico de Bragança, Centro de Ciência Viva de
				Bragança, Centro de Estudos Transdisciplinares para o Desenvolvimento – UTAD, Centro de Investigação
				em Vida Ativa e Bem-Estar – Instituto Politécnico de Bragança, Centro de Investigação Transdiscipliar
				em Educação e Desenvolvimento, CoraNE - Associação de Desenvolvimento Local, DESTEQUE, Douro Superior -
				Associação de Desenvolvimento, Escola Agrária – Instituto Politécnico de Bragança, Escola Superior de
				Comunicação, Administração e Turismo – Instituto Politécnico de Bragança, Escola Superior de Educação
				– Instituto Politécnico de Bragança, Escola Superior de Tecnologia e Gestão – Instituto Politécnico de
				Bragança, GICoS - Grupo de Investigação em Construção Sustentável, HTQ, Instituto Politécnico de
				Bragança, Konig Modulo Portugal, Lda., MORE - Laboratório Colaborativo Montanhas de Investigação –
				Associação, Regia Douro Park, Termas de Chaves, UNIAG, Universidade de Trás-os-Montes e Alto Douro.
			</p>

			<p>
				<strong>PORTO:</strong> workshop realizado a 14 de maio de 2026, nas instalações da ANI no Porto,
				dinamizado localmente pelo Eng.º António Braz Costa (CITEVE, CeNTI). (<a
					href={resolve('/workshops-descentralizados/highlights-porto/')}>highlights da fase de focagem</a
				>)
			</p>
			<p>
				<strong>Lista de entidades participantes (por ordem alfabética):</strong> ADVID- Cluster da Vinha e do
				Vinho, AEP, AIMMAP, Amorim Cork Solutions, ANI, APICCAPS, Bial, Câmara Municipal de Matosinhos, CCDR
				Norte, CEiiA, Centro Tecnológico do Calçado de Portugal, CIIMAR, CITEVE / CeNTI, Corticeira Amorim,
				CTCP, FCT, FEP – Universidade do Porto, Fórum Oceano, Fórum Oceano, Health Cluster Portugal, i3S, INEGI - Instituto
				de Ciência e Inovação em Engenharia Mecânica e Engenharia Industrial, INESC TEC, Instituto Politécnico
				do Porto, LIPOR, MC Sonae, Next Generation Chemistry, PortugalFoods, PRODUTECH, Smartex.ai, Sogrape
				Vinhos SA, Super Bock Bebidas, SA, Super Bock Group, Teixeira Duarte - Engenharia e Construções, SA,
				Universidade Católica Portuguesa, Universidade do Porto.
			</p>

			<p>
				<strong>COIMBRA:</strong> workshop realizado a 14 de maio de 2026, no UC Exploratório - Centro Ciência
				Viva da Universidade de Coimbra, dinamizado localmente pelos Professores Paulo Trincão (Diretor do UC
				Exploratório) e Manuel Valença (Project Manager do UC Exploratório). (<a
					href={resolve('/workshops-descentralizados/highlights-coimbra/')}>highlights da fase de focagem</a
				>)
			</p>
			<p>
				<strong>Lista de entidades participantes (por ordem alfabética):</strong> AEMITEQ - Associação para a
				Inovação Tecnológica e Qualidade, AIBILI, Bluepharma, Câmara Municipal de Coimbra, CEAACP – Centro de
				Estudos em Arqueologia, Artes e Ciências do Património – UCoimbra, CeBER – Universidade de Coimbra,
				CEIS20 – UCoimbra, CELGA-ILTEC, CEMMPRE, Centro de Engenharia Mecânica, Materiais e Processos, Centro
				de Estudos Clássicos e Humanísticos – UCoimbra, Centro de Estudos Interdisciplinares – UCoimbra, Centro
				de Estudos Sociais - UCoimbra, Centro de Geociências - UCoimbra, Centro de Investigação do Território,
				Transportes e Ambiente - UCoimbra, Centro de Literatura Portuguesa – UCoimbra, Centro de Química de
				Coimbra, Centro Investigação em Antropologia e Saúde, CERES - Chemical Engineering and Renewable
				Resources for Sustainability, CERNAS - Centro de Estudos de Recursos Naturais, Ambiente e Sociedade,
				CFisUC – Centro de Física – UCoimbra, CINEICC – Centro de Investigação em Neuropsicologia e
				Intervenção Cognitivo-Comportamental – UCoimbra, CISUC – Centre for Informatics and Systems –
				UCoimbra, CITEUC - Centro de Investigação da Terra e do Espaço – UCoimbra, CIVG - Centro de
				Investigação Vasco da Gama, CNC – Centro de Neurociências e Biologia Celular – UCoimbra, CoLAB4Ageing,
				CTCV - Centro Tecnológico da Cerâmica e do Vidro, Escola de Enfermagem – UCoimbra, EUVG, FCT, ICNAS
				PHARMA, INESC Coimbra, Instituto de Astrofísica e Ciências do Espaço – UCoimbra, Instituto de Astrofísica e Ciências do Espaço – UCoimbra, Instituto de Estudos
				Filosóficos, Instituto de Investigação Aplicada, Instituto Dom Luiz, Instituto Jurídico - UCoimbra,
				Instituto Pedro Nunes, LIP – Laboratório de Instrumentação e Física Experimental de Partículas,
				MARE- Centro de Ciências do Mar e do Ambiente – UCoimbra, Open Cosmos, UC Business – UCoimbra, UC
				Exploratório, UICISA:E.
			</p>
		{:else}
			<p>
				Decentralised workshops aim to present the process, clarify questions and gather contributions in
				real time. One workshop is planned for each NUTS II region on the mainland, as well as in the
				Autonomous Regions, for a total of ten throughout the Strategic Assessment.
			</p>
			<p>
				Workshops are led by local actors, in the form of semi-open sessions. Opinion leaders and
				representatives of relevant entities in the research and innovation ecosystem participate, seeking to
				ensure a balance of perspectives from academia, innovation, companies, industry and local and
				regional administration, with between 20 and 60 participants. Participants are organised in mixed
				groups, ensuring diversity of profiles in each group. Sessions are based on participatory dynamics,
				focused on group discussion and sharing contributions based on previously defined guiding questions,
				with facilitators to support facilitation and time management.
			</p>
			<p>
				In the first focus phase, workshops aim to present the Strategic Assessment process and its political
				priorities, critically discuss the main problems identified, clarify questions and gather
				participants' contributions on their implementation at local and regional level. This reflection
				contributes to identifying critical factors for decision-making, within the assessment of strategic
				options related to the allocation of financial resources and the definition of priority research and
				innovation domains, articulated with the territory and regional development.
			</p>
			<p>
				The five workshops of the first focus phase have already been held in Évora, Funchal, Bragança, Porto
				and Coimbra (see below). Five further workshops are planned for September 2026: Lagoa/Azores (8
				September), Covilhã (10 September), Faro (14 September), Braga (16 September) and Aveiro (17
				September). The theme of these workshops will be the identification of strategic options and their
				assessment.
			</p>

			<h2>FOCUS PHASE WORKSHOPS:</h2>
			<p>
				Overall summary of the workshops (<a
					href={resolve('/workshops-descentralizados/highlights-sintese-global/')}
					>highlights from the focus phase</a
				>)
			</p>

			<p>
				<strong>ÉVORA:</strong> workshop held on 5 May 2026 at PACT - Parque do Alentejo de Ciência e
				Tecnologia, locally led by Professors Teresa Pinto Correia and Susana Filipe (University of Évora,
				CHANGE). (<a href={resolve('/workshops-descentralizados/highlights-evora/')}
					>highlights from the focus phase</a
				>)
			</p>
			<p>
				<strong>List of participating entities (alphabetical order):</strong> ACOS - Associação de
				Agricultores do Sul, AERNNova, Águas Públicas do Alentejo, APA, IP - AHR Alentejo, ARNET, Câmara
				Municipal de Évora, Câmara Municipal de Odemira, Cátedra UNESCO Património Cultural Imaterial, CEBAL,
				CHAIA – Universidade de Évora, CHANGE – Universidade de Évora, CHRC, CICS.NOVA – Universidade de
				Évora, CIDEHUS – Universidade de Évora, Cluster Mineral Resources, CREATE, ERA Arqueologia, Estação
				Biológica de Mértola, FCT, IHC – Universidade de Évora, InnovPlantProtect, Instituto Politécnico de
				Beja, Instituto Politécnico de Portalegre, NOVA LINCS – Universidade de Évora, Porto de Sines,
				Portugal Nuts, PRF, Sines Tecnopolo, SoilArray Lda., SOL4R, Terras Dentro, Universidade de Évora,
				VISTA Lab – Universidade de Évora.
			</p>

			<p>
				<strong>FUNCHAL:</strong> workshop held on 7 May 2026 at the Rectorate of the University of Madeira,
				locally led by Professor José Câmara (Vice-Rector for Research, Innovation and Internationalisation,
				University of Madeira) and Dr Clementina Reis (Knowledge Transfer Office, University of Madeira). (<a
					href={resolve('/workshops-descentralizados/highlights-funchal/')}
					>highlights from the focus phase</a
				>)
			</p>
			<p>
				<strong>List of participating entities (alphabetical order):</strong> ACIN iCloud Solutions, Apus
				Trust, Centro de Investigação em Educação – Universidade da Madeira, CQM - Centro de Química da
				Madeira – Universidade da Madeira, Direção Regional da Saúde, Direção Regional de Competitividade,
				Inovação e Sustentabilidade, FCT, Frederico Mendes &amp; Associados, Grupo de Astronomia –
				Universidade da Madeira, Horários do Funchal, IDE - Instituto de Desenvolvimento Empresarial, INSC-
				Informática Serviços e Consultadoria, Lda., INSC, Lda., Instituto de Tecnologias Interativas – LARSyS
				– Universidade da Madeira, Invest Madeira, ISOPlexis – Centro em Agricultura Sustentável e Tecnologia
				Agroalimentar – Universidade da Madeira, Laboratório Genética Humana – Universidade da Madeira,
				Madeira Wine Company, SA, MARE-Madeira, Universidade da Madeira.
			</p>

			<p>
				<strong>BRAGANÇA:</strong> workshop held on 13 May 2026 at Brigantia Ecopark - Parque de Ciência e
				Tecnologia, locally led by Dr Clotilde Nogueira (Executive Director, Centro Ciência Viva de Bragança).
				(<a href={resolve('/workshops-descentralizados/highlights-braganca/')}
					>highlights from the focus phase</a
				>)
			</p>
			<p>
				<strong>List of participating entities (alphabetical order):</strong> ADRAT, Aquavalor, Associação
				Douro Histórico, Bísaro - Salsicharia Tradicional, Lda., Boticas Hotel Art&amp;SPA, Câmara Municipal
				de Bragança, CATRAPORT, LDA., CeDRI – Instituto Politécnico de Bragança, Centro de Ciência Viva de
				Bragança, Centro de Estudos Transdisciplinares para o Desenvolvimento – UTAD, Centro de Investigação
				em Vida Ativa e Bem-Estar – Instituto Politécnico de Bragança, Centro de Investigação Transdiscipliar
				em Educação e Desenvolvimento, CoraNE - Associação de Desenvolvimento Local, DESTEQUE, Douro Superior -
				Associação de Desenvolvimento, Escola Agrária – Instituto Politécnico de Bragança, Escola Superior de
				Comunicação, Administração e Turismo – Instituto Politécnico de Bragança, Escola Superior de Educação
				– Instituto Politécnico de Bragança, Escola Superior de Tecnologia e Gestão – Instituto Politécnico de
				Bragança, GICoS - Grupo de Investigação em Construção Sustentável, HTQ, Instituto Politécnico de
				Bragança, Konig Modulo Portugal, Lda., MORE - Laboratório Colaborativo Montanhas de Investigação –
				Associação, Regia Douro Park, Termas de Chaves, UNIAG, Universidade de Trás-os-Montes e Alto Douro.
			</p>

			<p>
				<strong>PORTO:</strong> workshop held on 14 May 2026 at ANI premises in Porto, locally led by Eng.
				António Braz Costa (CITEVE, CeNTI). (<a
					href={resolve('/workshops-descentralizados/highlights-porto/')}
					>highlights from the focus phase</a
				>)
			</p>
			<p>
				<strong>List of participating entities (alphabetical order):</strong> ADVID- Cluster da Vinha e do
				Vinho, AEP, AIMMAP, Amorim Cork Solutions, ANI, APICCAPS, Bial, Câmara Municipal de Matosinhos, CCDR
				Norte, CEiiA, Centro Tecnológico do Calçado de Portugal, CIIMAR, CITEVE / CeNTI, Corticeira Amorim,
				CTCP, FCT, FEP – Universidade do Porto, Fórum Oceano, Fórum Oceano, Health Cluster Portugal, i3S, INEGI - Instituto
				de Ciência e Inovação em Engenharia Mecânica e Engenharia Industrial, INESC TEC, Instituto Politécnico
				do Porto, LIPOR, MC Sonae, Next Generation Chemistry, PortugalFoods, PRODUTECH, Smartex.ai, Sogrape
				Vinhos SA, Super Bock Bebidas, SA, Super Bock Group, Teixeira Duarte - Engenharia e Construções, SA,
				Universidade Católica Portuguesa, Universidade do Porto.
			</p>

			<p>
				<strong>COIMBRA:</strong> workshop held on 14 May 2026 at UC Exploratório - Centro Ciência Viva da
				Universidade de Coimbra, locally led by Professors Paulo Trincão (Director, UC Exploratório) and Manuel
				Valença (Project Manager, UC Exploratório). (<a
					href={resolve('/workshops-descentralizados/highlights-coimbra/')}
					>highlights from the focus phase</a
				>)
			</p>
			<p>
				<strong>List of participating entities (alphabetical order):</strong> AEMITEQ - Associação para a
				Inovação Tecnológica e Qualidade, AIBILI, Bluepharma, Câmara Municipal de Coimbra, CEAACP – Centro de
				Estudos em Arqueologia, Artes e Ciências do Património – UCoimbra, CeBER – Universidade de Coimbra,
				CEIS20 – UCoimbra, CELGA-ILTEC, CEMMPRE, Centro de Engenharia Mecânica, Materiais e Processos, Centro
				de Estudos Clássicos e Humanísticos – UCoimbra, Centro de Estudos Interdisciplinares – UCoimbra, Centro
				de Estudos Sociais - UCoimbra, Centro de Geociências - UCoimbra, Centro de Investigação do Território,
				Transportes e Ambiente - UCoimbra, Centro de Literatura Portuguesa – UCoimbra, Centro de Química de
				Coimbra, Centro Investigação em Antropologia e Saúde, CERES - Chemical Engineering and Renewable
				Resources for Sustainability, CERNAS - Centro de Estudos de Recursos Naturais, Ambiente e Sociedade,
				CFisUC – Centro de Física – UCoimbra, CINEICC – Centro de Investigação em Neuropsicologia e
				Intervenção Cognitivo-Comportamental – UCoimbra, CISUC – Centre for Informatics and Systems –
				UCoimbra, CITEUC - Centro de Investigação da Terra e do Espaço – UCoimbra, CIVG - Centro de
				Investigação Vasco da Gama, CNC – Centro de Neurociências e Biologia Celular – UCoimbra, CoLAB4Ageing,
				CTCV - Centro Tecnológico da Cerâmica e do Vidro, Escola de Enfermagem – UCoimbra, EUVG, FCT, ICNAS
				PHARMA, INESC Coimbra, Instituto de Astrofísica e Ciências do Espaço – UCoimbra, Instituto de Astrofísica e Ciências do Espaço – UCoimbra, Instituto de Estudos
				Filosóficos, Instituto de Investigação Aplicada, Instituto Dom Luiz, Instituto Jurídico - UCoimbra,
				Instituto Pedro Nunes, LIP – Laboratório de Instrumentação e Física Experimental de Partículas,
				MARE- Centro de Ciências do Mar e do Ambiente – UCoimbra, Open Cosmos, UC Business – UCoimbra, UC
				Exploratório, UICISA:E.
			</p>
		{/if}
	</div>
</div>

<script lang="ts">
	import { Button } from '$lib/components/ui/button';
	import { Separator } from '$lib/components/ui/separator';
</script>

<footer class="border-t bg-muted/50 py-12">
	<div class="container">
		<div class="grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-4">
			<div class="flex flex-col items-start gap-4">
				<p class="text-xl font-semibold text-foreground">AI²Participa</p>
				<p class="max-w-[24rem] text-sm text-muted-foreground">
					Espaço de participação sobre a Avaliação Estratégica para a definição das prioridades
					nacionais de investigação e inovação no âmbito da criação da AI².
				</p>
				<p class="text-sm text-muted-foreground">
					Dúvidas ou sugestões?
					<a
						href="mailto:ai2@planapp.gov.pt"
						class="transition-color text-primary hover:text-foreground"
					>
						Contacte-nos
					</a>
				</p>
			</div>
			<div>
				<div class="flex flex-col gap-4">
					<a href="https://www.planapp.gov.pt/" target="_blank" rel="noreferrer">
						<img
							src="/logo-planapp.svg"
							alt="Logo PLANAPP"
							class="h-24 w-auto transition-opacity hover:opacity-80"
						/>
					</a>
					<a
						href="https://www.gov.pt/entidades/ministerio-da-educacao-ciencia-e-inovacao"
						target="_blank"
						rel="noreferrer"
					>
						<img
							src="/logo-meic.svg"
							alt="Logo Ministério da Educação, Ciência e Inovação"
							class="h-24 w-auto transition-opacity hover:opacity-80"
						/>
					</a>
				</div>
			</div>
			<div>
				<p class="font-semibold">Estratégia de Participação</p>
				<ul class="mt-3 space-y-2 text-sm text-muted-foreground">
					<li>
						<a href="/participacao-publica/" class="hover:text-foreground">Participação Pública</a>
					</li>
					<li>
						<a href="/metodologia-participacao-publica/" class="hover:text-foreground">
							Metodologia de Participação Pública
						</a>
					</li>
					<li>
						<a href="/comissao-acompanhamento/" class="hover:text-foreground">
							Comissão de Acompanhamento
						</a>
					</li>
					<li>
						<a href="/reunioes-entidades/" class="hover:text-foreground">Reuniões com Entidades</a>
					</li>
					<li>
						<a href="/mesas-tematicas/" class="hover:text-foreground">Mesas Temáticas</a>
					</li>
					<li>
						<a href="/conferencias-reunioes-descentralizadas/" class="hover:text-foreground">
							Conferências e Reuniões Descentralizadas
						</a>
					</li>
					<li>
						<a href="/iniciativas-bottom-up/" class="hover:text-foreground">Iniciativas Bottom-up</a
						>
					</li>
				</ul>
			</div>
			<div>
				<a href="/relatorios/" class="hover:text-foreground">Relatórios</a>
				<p class="mt-4 font-semibold text-foreground">O que é</p>
				<ul class="mt-3 space-y-2 text-sm text-muted-foreground">
					<li>
						<a href="/metodologia-st4s/" class="hover:text-foreground">Metodologia ST4S</a>
					</li>
					<li>
						<a href="/metodologia-avaliacao-estrategica-ai2/" class="hover:text-foreground">
							Metodologia de Avaliação Estratégica da AI²
						</a>
					</li>
					<li>
						<a href="/legislacao-nacional/" class="hover:text-foreground">Legislação Nacional</a>
					</li>
				</ul>
				<p class="mt-4 font-semibold text-foreground">Sobre a Equipa</p>
				<ul class="mt-3 space-y-2 text-sm text-muted-foreground">
					<li><a href="/coordenacao/" class="hover:text-foreground">Coordenação</a></li>
					<li>
						<a href="/equipa-peritos/" class="hover:text-foreground">Equipa de Peritos</a>
					</li>
				</ul>
			</div>
		</div>
		<Separator class="my-8" />
		<div
			class="flex flex-col gap-4 text-center text-sm text-muted-foreground md:flex-row md:justify-between"
		>
			<p>
				&copy; 2026 PLANAPP. Processo promovido pelo Ministério da Educação, Ciência e Inovação.
				Todos os direitos reservados.
			</p>
			<div class="flex justify-center md:justify-end">
				<Button variant="ghost" size="sm" href="#top">Voltar ao topo ↑</Button>
			</div>
		</div>
	</div>
</footer>

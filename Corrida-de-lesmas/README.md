Este eh um programa para saber qual lesma venceu e qual seu nível de acordo com sua velocidade
	
	# # 
	algoritmo
	declare ql, vlm, vl numerico
	vlm <- 1
	escreva "Digite o número de Lesmas:"
	leia ql
	enquanto ql <> 0 faca
	inicio
		se ql >= 1 e ql <= 20 entao
			inicio
				para ql <- 1 ate ql faca passo 1
					inicio
						escreva "Digite a velocidade das lesmas:"
						leia vl
						
						se vl >= 1 e vl <= 50 entao
							inicio 
								se vl >= vlm entao
									inicio
										vlm <- vl
									fim
							fim
						senao
							inicio
								escreva "Não existem lesmas tão rápidas em nosso planeta!"
							fim
					fim
			fim
		senao
			inicio
				escreva "Valor inváliddo."
			fim
		escreva " "
		escreva "A lesma mais veloz tem a velocidade:", " ", vlm, "cm/h"
		escreva " "
		se vlm >= 1 e vlm < 10 entao
		inicio
			escreva "Lesma de Nível 1!"
		fim
		
		se vlm >= 10 e vlm < 20 entao
		inicio
			escreva "Lesma de Nível 2!"
		fim
		se vlm >= 20 entao
		inicio
			escreva "Lesma de Nível 3!"
		fim
		escreva " "
		escreva " "
		escreva "Se quiser continuar, digite o número de Lesmas, se não, digite 0:"
		leia ql
	fim
	
	escreva " "
	escreva "A lesma mais veloz tem a velocidade:", " ", vlm, "cm/h"
	escreva " "
	
	se vlm >= 1 e vlm < 10 entao
	inicio
		escreva "Lesma de Nível 1!"
	fim
	se vlm >= 10 e vlm < 20 entao
	inicio
		escreva "Lesma de Nível 2!"
	fim
	se vlm >= 20 entao
	inicio
		escreva "Lesma de Nível 3!"
	fim
	fim_algoritmo

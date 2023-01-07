# Calculadora-de-perimetro-
Este arquivo é uma calculadora de perímetro de triangulo em linguagem Portugol.

    Algoritmo
      declare A, B, C, Perimetro numerico
           A <- 1
              B <- 1
                 C <- 1
        Enquanto A <> 0 ou B <> 0 ou C <> 0 faca
          Inicio 
            Escreva "Este programa serve para calcular o perimetro do seu triangulo a partir de valores dos lados fornecidos pelo usuário."
            Escreva "Digite os lados do seu triangulo:"
            Escreva "Primeiro lado:"
              Leia A 
            Escreva "Segundo lado:"
              Leia B 
            Escreva "Terceiro lado:"
              Leia C 
            Se A + B < C ou A + C < B ou B + C < A ou A = 0 ou B = 0 ou C = 0 entao 
              inicio
                Escreva " Nao foi possivel formar um triangulo com esses valores e o programa foi encerrado."
              fim
          senao 
            inicio
              Perimetro <- A + B + C 
              Escreva "Seu perimetro é: ", Perimetro 
              Escreva "Para encerrar o programa, ensira 0 em todos os valores."
              Escreva " "
              Escreva " "
            fim
        Fim
    Fim_algoritmo	

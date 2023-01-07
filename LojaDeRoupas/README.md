# LojaDeRoupas
Este eh um sistema que dara desconto aos clientes que sao constantes compradores em determinada loja de roupas

     algoritmo
    declare NomeCliente, ClienteConsumista literal
         Valor, MaiorValor numerico
          Valor <- 1
          MaiorValor <- 1	   		    
            Escreva " Este Programa serve para bonificar clientes assiduos de acordo com o valor de suas compras anuais " 
            escreva " Insira o Nome do Cliente " 
            Enquanto NomeCliente <> "." faca
            inicio	   		
              leia NomeCliente		   		
              escreva " Insira os valores de suas compras do ano anterior " 	   				   				   			 			
              Leia Valor
              se NomeCliente = "."   entao
              inicio
                Valor <- 0
              fim
              se Valor > MaiorValor entao 
                inicio
                MaiorValor <- Valor
                ClienteConsumista <- NomeCliente		   			
                fim		   				   		   			   		
            se Valor >= 500 e Valor < 2000 entao
              escreva NomeCliente, " Ganhou 10% de desconto " 
              se valor >= 2000 entao
              escreva NomeCliente, " Ganhou 15% de desconto " 
              escreva " "	
              escreva " Insira o Nome do Proximo Cliente "	  		   				   				   		 			   		
               fim	   	     	   	    
               escreva ClienteConsumista, " receberá mais R$ 100,00 de bônus. "	   			   			   			   			   		
    fim_algoritmo

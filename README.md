Esse commit se trata de uma atividade sobre os temas de programação procedural e programação orientada a objetos. E um Algorítimo que descreve uma rotina do café da manhã pelo Portugol studio.


O que é uma programação procedural ?
<img src="![alt text](<PROGRAMAÇÃO PROCEDURAL.png>)">

O que é uma programação orientada a objetos ?
<img src="![alt text](<PROGRAMAÇÃO ORIENTADA A OBJETOS.png>)">

------------------------------------------------------------------------

Conteúdo do arquivo (Rotina de café.po) listado neste commit.
Link do Código https://portugol.dev/#share=5vrodgp

// Algorítimo que descreve uma rotina do café da manhã //

programa
{
    funcao inicio()
    {
            escreva("Rotina do café da Manhã")
              cadeia resposta
            
            //ao acordar
            escreva("\nAcordou ?") 
              leia(resposta)
                se (resposta == "sim")
                  escreva("Levante da cama!")
                    senao
                      escreva("Espere dormindo o despertador tocar e levanta!")
            
            //ao levantar
            escreva("\nLevantou ?") 
              leia(resposta)
                se (resposta == "sim")
                  escreva("Pegue a escova de dentes!")
                    senao
                      escreva("Levanta! e pega a escova de dentes.")
                        escreva("\nPegou a escova de dentes ?") 
                          leia(resposta)
                            se (resposta == "sim")
                              escreva("vai escovar os dentes!")
                                senao
                                  escreva("Pegue a escova de dentes e vai escovar os dentes!")

            // após escovar os dentes
            escreva("\nEscovou os dentes ?") 
              leia(resposta)
                se (resposta == "sim")
                  escreva("Vá para a cozinha!")
                    senao
                      escreva("vai escovar os dentes e vai pra cozinha!")
                        escreva("\nEstá na cozinha ?") 
                          leia(resposta)
                            se (resposta == "sim")
                              escreva("Pegue um sanduiche e coma!")
                                senao
                                  escreva("Vai para a cozinha, pegue um sanduiche e coma!")
                                
    }
}
algoritmo "semnome"
var
 M, A, IMC : REAL
Inicio
   Escreva("Massa (kg): ")
   Leia (M)
   Escreva ("Altura (m): ")
   Leia (A)
   IMC <- M / (A ^ 2)
   Escreval ("IMC: ", IMC:5:2)
   se (IMC <= 18.5) e (IMC<25) entao
      Escreval("Parabéns! você está no seu peso!")
   senao
      Escreva("Você não está no peso ideal")
      fimse
   


fimalgoritmo

# logica-de-programa
programa {
  funcao inicio() {
   inteiro idade, nascimento

   escreva("digite o ano de nascimento: ")
   leia(nascimento)

   idade= 2023- nascimento

   escreva("\n sua idade é: ", idade)

   se (idade >= 18){
    escreva("\n acesso permitido, maior de idade")
   } senao {
    escreva("\n acesso negado, menor de idade")
   }
  }
}

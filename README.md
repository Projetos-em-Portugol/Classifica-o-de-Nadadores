# Classifica-o-de-Nadadores
Um clube de natação precisa classificar seus atletas em categorias de acordo com a idade

    programa {
     funcao inicio() {
    
      inteiro idade

      escreva("Digite a sua idade: ")
      leia (idade)

      se (idade <= 10){
        escreva("Categoria: Infantil")
      }senao se (idade >= 11 e idade <= 15){
        escreva("Categoria: Juvenil")
      }senao se (idade >= 16 e idade <=19){
        escreva("Categoria: Júnior")
      }senao 
        escreva("Categoria: Sênior")

    }
  }

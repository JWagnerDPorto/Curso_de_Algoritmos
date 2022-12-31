algoritmo "Emprestimo"
var
     valor_emprestimo, numero_parcelas, valor_total, valor_parcelas: Real
inicio
      Escreva("Qual o valor do empréstimo? ")
      Leia(valor_emprestimo)
      Escreva("Quantas parcelas? ")
      Leia(numero_parcelas)
      valor_total <- ((valor_emprestimo * 20)/100)+ valor_emprestimo
      valor_parcelas <- valor_total / numero_parcelas
      Escreva("Vou pagar um total de R$", valor_total:5:2, " em", numero_parcelas, " vezes de R$", valor_parcelas:5:2)
fimalgoritmo
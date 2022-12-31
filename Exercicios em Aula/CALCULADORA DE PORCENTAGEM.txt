algoritmo "Calculadora de Porcentagem"
var
      preco, porcentagem, imposto: Real
inicio
      Escreva("Qual valor do produto? ")
      Leia(preco)
      Escreva("Qual a porcentagem de imposto? ")
      Leia(porcentagem)
      imposto <- (preco * porcentagem) / 100
      Escreva("O imposto será de US$",imposto:5:2)
fimalgoritmo
# gaaaaaaaaaaaaaaaaaa
Algoritmo "IMC"
// Disciplina   : [PA] 
// Professor   : cintia pinho 
// Descri��o   : calcula quanto a pessoa esta com seu peso,idade e altura do jogador 
// Autor(a)    : Luis Fernando Osuna Solda 
// Data atual  : 24/11/2021
Var 
altura,idade:real
pode,naopode:logico 


Inicio 
escreval("qual a sua altura?")
leia(altura)
escreval("qual sua idade?")
leia(idade) 
idade&lt;-(idade/(altura*altura)) 

pode&lt;-(idade>=18) e (altura>1.75)
naopode&lt;-(idade&lt;18) e (altura&lt;1.75) 
escreval("sua altura �:",altura) 
escreval("sua idade �",idade)  

Fimalgoritmo

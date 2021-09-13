# calculadora.media.alura
Calculadora em javascript para media das notas
var nome = "Rita"
var notaPB = 0
var notaSB = 10
var notaTB = 5
var notaQB = 7

var notaFinal = (notaPB + notaSB + notaTB + notaQB)/4
var notaFix= notaFinal.toFixed(1)

console.log ("Bem vindo/a " + nome)
if (notaFix >= 7)
{
  console.log("Você foi aprovado com a nota: " + notaFix + " Parabéns!")
}
else 
  {
    console.log("Sua nota foi: " + notaFix + ". Você não foi aprovado")
  }

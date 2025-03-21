# Correção da lista 1

## Exercício 1
let nome = "João"
let numero = 10
let boolean = true

console.log(typeof nome)
console.log(typeof numero)
console.log(typeof boolean)

## Exercício 2
let nota1 = 5
let nota2 = 2
let nota3 = 7

let media = (nota1 + nota2 + nota3)/3

if (media >= 7){
    console.log("Aprovado")
}else {
    console.log("Reprovado")
}

## Exercício 3
let estaChovendo = true

if (estaChovendo) {
    console.log("É preciso levar uum guarda-chuva")
}
else {
    console.log("Não é preciso levar um guarda-chuva")
}


## Exercício 4
function calcularDobro (numero) {
    return numero * 2
}

//let resultado = calcularDobro(2)
console.log(calcularDobro(5))


## Exercício 5
function verificarIdade(idade) {
    if (idade >= 18){
        console.log("Maior de idade")
    }else {
        console.log("Menor de idade")
    }
}

verificarIdade(17)

## Exercício 6
function saudacao(nome) {
   console.log(`Olá, ${nome}! Seja bem-vindo(a)`)
}

saudacao("Vinicius")
saudacao("Jennifer")

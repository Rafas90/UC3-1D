# Caderno virtual - Lógica da Programação e Algoritmos

## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.


## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

- String
conceito de string
Exemplos:
"==" "===" "const" "prompt" "else" "if" "console.log" "switch" "break;" "case" "break;" "var" "let" "parseInt" "array"

```
const nome = prompt('Qual o Seu nome?')
const nota1 = prompt('Insira a nota de portugues.')
const nota2 = prompt('Insira a nota de Matematica.')
const nota3 = prompt('Insira a nota de Historia.')
const nota4 = prompt('Insira a nota de Química.')
const nota5 = prompt('Insira a nota de Ingles')

const media = (parseInt(nota1) + parseInt(nota2) + parseInt(nota3) + parseInt(nota4) + parseInt(nota5)) /5

if(media >= 7){
 console.log(`Parabéns, ${nome}! Você está aprovado(a).`)
} else if (media < 7 && media >=4 ){
 console.log(`Atenção, ${nome}! Você está de recuperação`)
} else {
 console.log(`Olá, ${nome}. infelizmente você reprovou.smt`)
} 
```
```
const produto = prompt("Seja bem vindo(a) a nosa loja de mascaras ta enteressado nessas?")

switch(produto) { 
  case "Mascara do Heroi": 
  case "Majora Masck" : 
console.log ("A mascara do heroi e a majora masck custa R$100.000")
Break;
  case "Mascara do dicipolo" :
  case "Mascara das fadas" :
console.log("A Mascara do dicipolo e a mascara das fadas custam R$ 50.000")
}
```
```
const Amor = ['Eu','Te','Amo']
const string = Amor.join('-')

console.log(Amor)
console.log(string)
```
```
const produto = prompt("Seja bem vindo(a) a nosa loja de mascaras ta enteressado nessas?")

switch(produto) { 
  case "Mascara do Heroi": 
  case "Majora Masck" : 
console.log ("A mascara do heroi e a majora masck custa R$100.000")
Break;
  case "Mascara do dicipolo" :
  case "Mascara das fadas" :
console.log("A Mascara do dicipolo e a mascara das fadas custam R$ 50.000")
}
```

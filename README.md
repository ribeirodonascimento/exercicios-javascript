# exercicios-javascript

1)Escreva um programa que peça dois números e exiba a soma deles. 

var num1 = parseInt(prompt("Digite um número"))
var num2 = parseInt(prompt("Digite outro número"))
var soma = num1 + num2
document.write("A soma dos dois números é " + soma + ".")

2)Escreva um programa que peça dois números e exiba a subtração do primeiro pelo segundo.

var num1 = parseInt(prompt("Digite um número"))
var num2 = parseInt(prompt("Digite outro número"))
var subtracao = num1 - num2
document.write("A subtração do primeiro número pelo segundo é " + subtracao + ".")

3)Escreva um programa que peça dois números e exiba a multiplicação deles.

var num1 = parseInt(prompt("Digite um número"))
var num2 = parseInt(prompt("Digite outro número"))
var mult = num1 * num2
document.write("A multiplicação dos dois números é " + mult + ".")

4)Escreva um programa que peça dois números e exiba a divisão do primeiro pelo segundo.

var num1 = parseInt(prompt("Digite um número"))
var num2 = parseInt(prompt("Digite outro número"))
var divisao = num1 / num2
document.write("A divisão do primeiro número pelo segundo é " + divisao + ".")

5)Escreva um programa que peça dois números e exiba o resto da divisão do primeiro pelo segundo.

var num1 = parseFloat(prompt("Digite um número"))
var num2 = parseFloat(prompt("Digite outro número"))
if(num2 !== 0){
  var resto = num1 % num2
  document.write(`O resto da divisão de ${num1} por ${num2} é ${resto}`)
} else{
  document.write("Divisão por zero não é permitida")
}

6)Escreva um programa que incremente o valor de uma variável em 1 e exiba o resultado.

var num1 = parseInt(prompt("Digite um número"))
num1++
document.write("O número digitado incrementado é " + num1 + ".")

7)Escreva um programa que decremente o valor de uma variável em 1 e exiba o resultado.

var num1 = parseInt(prompt("Digite um número"))
num1--
document.write("O número digitado decrementado é " + num1 + ".")

8)Atribua o valor de uma variável a outra.

var a = 0
var b = a
document.write(`O valor de B é: ${b}`)

9)Some 10 a uma variável existente usando o operador +=.

var num = parseInt(prompt("Digite um número"))
num += 10
document.write("O número digitado mais dez é " + num + ".")

10)Subtraia 5 de uma variável existente usando o operador -=.

var num = parseInt(prompt("Digite um número"))
num -= 5
document.write("O número digitado menos cinco é " + num + ".")

11)Multiplique o valor de uma variável por 4 usando o operador *=.

var num = parseInt(prompt("Digite um número"))
num *= 4
document.write("O número digitado multiplicado por quatros é " + num + ".")

12)Divida o valor de uma variável por 2 usando o operador /=.

var num = parseInt(prompt("Digite um número"))
num /= 2
document.write("O número digitado dividido por dois é " + num + ".")

13)Obtenha o resto da divisão de uma variável por 3 usando o operador %=.

var num = parseInt(prompt("Digite um número"))
num %= 3
document.write("O resto da divisão por três do número digitado é " + num + ".")

14)Escreva um programa que verifique se um número é positivo ou negativo.

var num = parseInt(prompt("Digite um número"))
if(num >= 0 ){
  document.write("O número digitado é positivo.")
}else{
  document.write("O número digitado é negativo.")
}

15)Escreva um programa que verifique se um número é par ou ímpar.

var num = parseInt(prompt("Digite um número"))
if(num % 2 == 0 ){
  document.write("O número digitado é par.")
}else{
  document.write("O número digitado é ímpar.")
}

16)Escreva um programa que verifique qual dos dois números é maior.

var num = parseInt(prompt("Digite um número"))
var num2 = parseInt(prompt("Digite um número"))
if(num > num2){
  document.write(`O número ${num} é maior que o número ${num2}.`)
}else{
  document.write(`O número ${num2} é maior que o número ${num}.`)
}

17)Escreva um programa que verifique se uma pessoa tem mais de 18 anos.

var num = parseInt(prompt("Digite a sua idade"))
if(num > 18){
  document.write("Você tem mais de 18 anos.")
}else{
  document.write("Você tem menos de 18 anos.")
}

18)Escreva um programa que verifique se um número está no intervalo entre 0 e 100.

var num = parseInt(prompt("Digite um número"))
if(num < 0 || num > 100){
  document.write(`O número ${num} não está entre os números 0 e 100.`)
}else{
  document.write(`O número ${num} está entre os números 0 e 100.`)
}}

19)Escreva um programa que verifique se uma letra é uma vogal ou consoante.

var letra = prompt("Digite uma letra")
if(letra === 'a' || letra === 'e' || letra === 'i' || letra === 'o' || letra === 'u'){
  document.write(`A letra '${letra}' é uma vogal.`)
}else{
  document.write(`A letra '${letra}' é uma consoante.`)
}

20)Escreva um programa que verifique qual dos três números é o maior.

var n1 = prompt("Digite um número.")
var n2 = prompt("Digite outro número.")
var n3 = prompt("Agora digite mais um número.")

if (n1 > n2 && n1 > n3){
  document.write(" O número ",n1 ," é o maior número digitado.")
}else if (n2 > n1 && n2 > n3){
  document.write(" O número ",n2 ," é o maior número digitado.")
}else{ (n3 > n2 && n3 > n1)
  document.write(" O número ",n3 ," é o maior número digitado.")
}

21)Escreva um programa que verifique se um ano é bissexto.

var ano = prompt("Digite um ano.")
if(((ano % 4 === 0 && ano % 100 !== 0) || ano % 400 === 0)){
  document.write(`O ano de ${ano} é um ano bissexto.`)
}else{
  document.write(`O ano de ${ano} não é um ano bissexto.`)
}

22)Escreva um programa que verifique se dois números são positivos.

var num1 = parseFloat(prompt("Digite o primeiro número: "));
var num2 = parseFloat(prompt("Digite o segundo número: "));
if (num1 > 0 && num2 > 0) {
    document.write("Ambos números são positivos.");
} else {
    document.write("Pelo menos um número não é positivo.");

23)Escreva um programa que verifique se pelo menos um dos dois números é negativo.

var num1 = parseFloat(prompt("Digite o primeiro número: "));
var num2 = parseFloat(prompt("Digite o segundo número: "));
if (num1 < 0 || num2 < 0) {
    document.write("Pelo menos um número é negativo.");
} else {
    document.write("Ambos números são não negativos.");
}

24)Escreva um programa que verifique se um número é par e positivo.

var num = parseFloat(prompt("Digite um número: "));
if (num > 0 && num % 2 == 0) {
    document.write("O número é par e positivo.");
} else {
    document.write("O número não é par e positivo.");
}

25)Escreva um programa que verifique se um número não é múltiplo de 5.

var num = parseFloat(prompt("Digite um número: "));
if (num % 5 != 0) {
    document.write("O número não é múltiplo de 5.");
} else {
    document.write("O número é múltiplo de 5.");
}

26)Escreva um programa que verifique se um número está fora do intervalo de 1 a 10.

var num = parseFloat(prompt("Digite um número: "));
if (num < 1 || num > 10) {
    document.write("O número está fora do intervalo.");
} else {
    document.write("O número está no intervalo.");
}

27)Escreva um programa que verifique se dois números são pares.

var num1 = parseFloat(prompt("Digite o primeiro número: "));
var num2 = parseFloat(prompt("Digite o segundo número: "));
if (num1 % 2 == 0 && num2 % 2 == 0) {
    document.write("Ambos números são pares.");
} else {
    document.write("Pelo menos um número não é par.");
}

28)Escreva um programa que verifique se a soma de dois números é maior que 100.

var num1 = parseFloat(prompt("Digite o primeiro número: "));
FontFaceSetLoadEvent num2 = parseFloat(prompt("Digite o segundo número: "));
if (num1 + num2 > 100) {
    document.write("A soma é maior que 100.");
} else {
    document.write("A soma não é maior que 100.");
}

29)Escreva um programa que verifique se dois números são iguais ou diferentes.

var num1 = parseFloat(prompt("Digite o primeiro número: "));
var num2 = parseFloat(prompt("Digite o segundo número: "));

if (num1 == num2) {
document.write("Os números são iguais.");
} else {
document.write("Os números são diferentes.");
}

30)Escreva um programa que verifique se uma string não está vazia.

var texto = prompt("Digite um texto: ");

if (texto != "" && texto != null && texto.trim() != "") {
document.write("A string não está vazia.");
} else {
document.write("A string está vazia.");
}

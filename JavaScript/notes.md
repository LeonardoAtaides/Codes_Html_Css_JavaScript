# ANOTAÇÕES EM JAVA SCRIPT
_O JS PERMITE APLICAR DINÂMICA AOS ELEMENTOS DA PÁGINA WEB_

# VARIÁVEIS
Como e feita a declaração: sendo opcional mais importante utilizada-se 
o termo _var_ antes da variável, *não podem ser iniciados com números,apenas com letras com ou "_", não pode ser utilizado caracteres especiais como "ç" , "$" e nãopodeutilizar palavras reservadas da linguagem_*

Ex: var Soma = 10 + 10;

# TIPOS DE VARIÁVEIS
*Strings* -  Armazenagem os caracteres 
*Number* -  Armazenamento número inteiro, negativos, inteiros ou fracionados 
*Boolean* - Permite o valor de estado, False ou True


# Comandos:

*alert()* -  Mostra uma caixa com uma mensagem definida pelo dev, pode ser utilizar variáveis também para mostrar o valor da variável.
ex: alert("Olá, mundo!");

*document.write()* - Escreve algo na página, pode ser utilizar variáveis também para mostrar valores.
**É POSSIVEL CONCATENAR STRINGS COM O +**
Ex: 
var nome = 'Ataídes'; -> _define uma variável_

document.write('<h1> Olá ' + nome +'</h1>');
    |            |            |-> passa o nome da varoável
    |            |-> passa a tag em html
    |-> chama o comando

**PODE SE PEDIR OS DADOS DO USUARIO COM O PROMPT()**
Funciona como o input que recebe o valor digitado pelo usuário, pela caixa de mensagem exibida
pelo navegador,_estes dados são salvos como strings_
Ex: 
var nome = prompt("Qual é o seu nome?"); -  _"Ataídes"_
var idade = prompt("Qual é a sua idade?"); - _"19"_


*console.log()* - Utilizado no processo de debug, para testar os valores de variáveis, atravez do console do navegador.


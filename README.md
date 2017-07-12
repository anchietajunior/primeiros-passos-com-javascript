# Javascript.init();

Primeiros passos em programação/javascript.

## 0 - Init! ->

Vamos ao que interessa, só que antes precisamos saber um pouco de como surgiu o ***Javascript***.

***Javascript*** se tornou praticamente uma linguagem universal, presente nas mais conhecidas vertentes do desenvolvimento, front, back e mobile.
Criada por Brendan Eich, que na época estava a serviço da Netscape a linguagem ***Javascript*** foi influenciada por uma outra linguagem chamada Hypertalk, criada pela Apple. ***Javascript*** não foi o primeiro nome utilizado para a linguagem, ela nasceu como Mocha, logo depois virou Livrescript e depois veio o nome que conhecemos até hoje, uma jogada de marketing com o nome do Java que na época estava em alta. Sua primeira versão foi lançada em 1995.

Podemos até utilizar o nome ***Javascript*** pra tudo, mas o nome oficial da linguagem é ECMAScript, baseado no nome da ECMA International, organização responsável por manter os padrões da linguagem. Atualmente a versão mais utilizada é a ES5, mas já temos a versão ES6 (2015) disponível que pode ser utilizada através de algum "transpiler" e que trás grandes e significativas mudanças no core da linguagem.

Quando foi criada, a linguagem ***Javascript*** tinha a principal função de deixar as coisas mais dinâmicas, ou seja, reagir a determinados eventos e trazer um pouco mais de interação com o usuário, mas com o passar dos anos o ***Javascript*** tornou-se uma das linguagens de programação mais importantes no desenvolvimento de aplicações web.

## 1 - Variáveis ->

Variáveis são valores atribuídos a uma sequência de caractéres para que sejam memorizadas, reutilizadas e modificadas durante a execução do código.

Alguns exemplos de atribuição de valores a variáveis:

```javascript
var a = "Maria"
var b = 2
```

## 2 - Tipos de dados e Tipagem Fraca do *Javascript* ->

Cada linguagem de programação possui seus tipos dedos, sejam primitivos, compostos e etc, além disso as linguagens de programação podem ter tipagem forte ou fraca, por exemplo, quando vamos atribuir um valor a uma variável, não precisamos indicar ao interpretador Javascript qual o tipo de dado que estamos utilizando.

Pra identificar um certo tipo de dado, podemos utilizar a função **typeof** do Javascript.

### 2.1 Tipos Primitivos do Javascript

#### String

```javascript
var a = "Maria"

var b = "João"

var c = "cem"
```

#### Number

```javascript
var a = 20

var b = 300.23

var c = - 200
```
#### Boolean

```javascript
var a = true

var b = false
```

#### Object

```javascript
var pessoa = { nome: "Natan", idade: 23, profissao: "Desenvolvedor" }

var carro = { marca: "Volkswagen", modelo: "Fusca", cor: "Amarelo" }

var computador = { marca: "Dell", modelo: "XPI-200", processador: "i7" }
```
 
#### Array

```javascript
var a = [1, 2, 3, 4, 5]

var b = ["João", "Maria", "Antonio", "Rafaela"]
```

 > - Null
 > - Undefined

## 3 - Operadores ->

 Os cálculos e o controle da matemática que podemos ter durante a implementação do código são peças chave pra qualquer linguagem de programação, não seria diferente com o Javascript.

 Os principais tipos de operadores no Javascript que geralmente estão presentes em todas as linguagens de programação, são eles:

### 3.1 Operadores Aritméticos


#### 3.1.1 Soma

```javascript
a + b

b + a

```

#### 3.1.2 Subtração

```javascript
a - b

b - a

```

#### 3.1.3 Multiplicação

```javascript
a * b

b * a

```

#### 3.1.4 Divisão

```javascript
a - b

b - a

```

#### 3.1.5 Módulo

```javascript
a % b

b % a
```

### 3.2 Operadores de Comparação

#### 3.2.1 Igual

```javascript
a == b

a === b
```

#### 3.2.2 Diferente

```javascript
a != b

a !== b
```

#### 3.2.3 Maior/Menor

```javascript
a > b

b < a
```

#### 3.2.4 Maior Igual/Menor Igual

```javascript
a >= b

b <= a
```

#### 3.2.5 Ternário

```javascript
a == b ? true : false
```

### 3.3 Operadores Lógicos

#### 3.3.1 E

```javascript
a && b
```

#### 3.3.2 Ou

```javascript
a || b
```

#### 3.3.3 Diferente

```javascript
!a

!b
```
 
## 4 - Condicionais ->

De nada adiantaria ter tantas e boas opções de operadores se não pudéssemos aplicar condicionais aos mesmos, não acha?

Aqui também vamos começar a usar um cara bem legal chamado console.log() pra exibir nossos resultados.

### 4.1 If / Else

```javascript
if(a == b){
	console.log('a é igual a b');
}
else {
	console.log('a é diferente de b');
}
```

```javascript
if(a != b){
	console.log('a é diferente de b');
}
else {
	console.log('a é igual a b');
}
```

### 4.2 Elsif

```javascript
if(a == 10){
	//faça algo se for igual a 10
}
else if(a == 20) {
	//faça algo	se for igual a 20
}
else {
	//faça algo diferente se nao for igual a nenhum dos dois
}
```

### 4.3 Condicionais aninhadas

```javascript
if(a == b){
	if(a == 10){
		//faça algo
	}
}
```

```javascript
if(a == b){
	if(a == 10){
		//faça algo
	}
	else if(a == 20){
		//faça algo
	}
}
else {
	if(a == 100){
		//faça algo
	}
	else if(a == 200){
		//faça algo
	}	
}
```

### 4.4 Code Refactor nas Condicionais aninhadas

```javascript
if(a == b && a == 10){
	//faça algo
}
else(a != b && a == 100){
	//faça algo	
}
```

```javascript
if((a + b == 20) || (b + c == 30)){
	//faça algo
}
else{
	//faça algo	
}
```

```javascript
if(a > b || c < d){
	//faça algo
}
else{
	//faça algo	
}
```

## 5 - Estruturas de Repetição (laços) ->

Pra manter um código mais legível e não precisar repetir várias vezes a mesma condição, utilizamos laços de repetição baseados em parâmetros informadas ao programa que está sendo desenvolvido:

### 5.1 While

```javascript
while(1 < 10){
	//faça algo
}
```

Loop infinito...

```javascript
count = 0;

while(count < 10){
	//faça algo
	count++;
}
```

### 5.2 Do While

```javascript
count = 0;

do {
	console.log(count);
	count++;
} while(count <= 10)
```

### 5.3 For

```javascript
for(var count = 0; count < 10; count++){
	console.log(count);
}
```

## 6 - Funções ->

Funções são blocos de código que executam uma determinada tarefa ou calcula algo, além disso funções podem receber e retornar valores.

###6.1 Funções sem parâmetros e retornos.

Podemos dizer que esse tipo de função é um tipo simples que podemos chama-la para executar simples tarefas.

```javascript
function digaOi(){
	console.log('Oi pessoal, eu sou o Javascript.')
}
```
###6.2 Funções com parâmetros e sem retorno.

```javascript
function calculeUmNumeroMaisCem(numero){
	total = numero + 100;
	console.log(total)
}
```

###6.3 Funções com parâmetros e retorno.

```javascript
function verifiqueUmNumero(numero){
	if(numero % 2 == 0){
		return true;
	}else {
		return false;
	}
}
```

###6.4 Variáveis Globais x Variáveis Locais.

Variáveis globais são escritas no escopo principal, todos podem ver e podem ser reutilizadas em qualquer lugar do código.

Variáveis locais são escritas dentro de uma função e são reutilizadas apenas dentro da mesma.

```javascript
//Variável global
var linguagem = "Javascript";

function imprimeALinguagem(){
	//Reutilizada dentro de uma função
	console.log(linguagem);
}

imprimeALinguagem();
```

```javascript
function imprimeALinguagem(){
	//Declarada dentro da função -> Variável local
	var linguagem = "Javascript";
	console.log(linguagem);
}

imprimeALinguagem();
```

###6.5 Algumas funções disponíveis no Javascript.

```javascript
var cidades = ['Paulo Afonso', 'Delmiro Gouveia', 'Glória'];

cidades.push('Monte Alegre');
cidades.pop();
cidades.shift();
```

```javascript
var nome = 'Javascript';

nome.length
nome.toUpperCase();
nome.toLowerCase();
```

```javascript
var num = 198.87;
var numRounded = Math.round(num);
```

## 7 - Query Selectors (Front-End) ->

Passando a trabalhar com Javascript com foco mais no front-end, precisamos ter o básico de conhecimento do DOM (Domain Object Model) e como trabalhar com os elementos que pertencem ao mesmo. Pra isso, temos algumas opções para capturar elementos ou informações dos elementos HTML via Javascript.

###8.1 Click

## 8 - Eventos (Front-End) ->

Eventos são tarefas executadas em decorrência de alguma ação. Por exemplo, imprimir um número após clicar em um botão. Mudar a cor de uma div após passar o mouse por cima e etc...

Geralmente os eventos são tratados dentro de uma função para um determinado fim.

###8.1 Click

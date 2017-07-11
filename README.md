# Javascript.init();

Primeiros passos em programação/javascript.

## 0 - Init!

Javascript se tornou praticamente uma linguagem universal, presente nas mais conhecidas vertentes do desenvolvimento, front, back e mobile.


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

### 4.1 If / Else

```javascript
if(a == b){
	//faça algo
}
else {
	//faça algo diferente
}
```

```javascript
if(a != b){
	//faça algo
}
else {
	//faça algo diferente
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

### 5.2 Do While

```javascript
while(1 < 10){
	//faça algo
}
```

### 5.3 For

```javascript
while(1 < 10){
	//faça algo
}
```
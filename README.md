# Javascript.init();

Primeiros passos em programação/javascript.

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
 


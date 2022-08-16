<h1 align="center">
  <br>
  <img src="../github/assets/variavel.svg" alt="Variavel" height="145" width="145">
  <br>
</h1>

# Por que utilizar variáveis?
Variáveis são ferramentas indispensáveis na programação, são nelas que colocamos valores para podermos trabalhar com eles posteriormente, similar à álgebra da matemática. As variáveis são um dos fatores para mantermos o código dinâmico, fácil de ser lido, compreendido e escalável.

#
## 💣 Definindo variáveis com JS
Diferentemente de outras linguagens, como ``Java``, no ``JavaScript`` não há necessidade de declarar o tipo da variável, mas isso não significa que ela não tem tipo, na verdade o ``JS`` faz a tipagem dinamicamente, similar ao ``PHP``.

#
## 🤔 Por exemplo, na declaração da variável fruta, como pode-se ver abaixo:
```javascript
const fruta = "Banana";
```
Podemos perceber que não há uma declaração de tipo.

Vale lembrar que podemos fazer a declaração de uma variável no JavaScript com três operadores, são eles ``var``, ``let`` e ``const``. Tendo em mente que de acordo com o ``ECMA2015``, utilizar o operador var se tornou uma má pratica.

Já em ``Java`` ficaria algo como abaixo:
```java
String fruta = "Banana";
```
A diferença é pouca, porém é nítida. A tipagem do Java com a anotação acima não é dinâmica. Vale ressaltar que nas versões mais atuais do Java, conseguimos fazer declarações de variáveis com o operador ``var`` .

JavaScript é Case Sensitive
Case Sensitive significa algo como “sensível à caixa das letras” ou “sensível a maiúsculas e minúsculas”.

Exemplo:
```javascript
const Fruta = "Banana"
``` 
é diferente de:
```javascript
const fruta = "Maçã"
```
O JavaScript identifica que é outra variável, bastando um caractere da declaração ser diferente, no caso `F` é diferente de `f`, com isso, o ``JS`` interpreta como uma variável diferente.

## ⚡️ Tipos de variáveis em JavaScript
Os tipos de variáveis em JS são classificados em:
- <strong> Strings </strong>  - Uma String nada mais é que texto puro.
- <strong> Numbers </strong> - São os números, seja eles integer, float, double etc.
- <strong> Booleans </strong> - São os operadores booleanos (true ou false)
- <strong> Arrays </strong> - É uma estrutura de dado para armazenar uma coleção de valores, sendo eles de qualquer tipo.
- <strong> Objects </strong> - Conjunto de atributos aninhados a uma variável denomina-se um objeto.
- <strong> Functions </strong> - Em JavaScript é possível declarar uma variável como uma função, podendo fazer operações e retornando o valor para a variável de declaração. Obs: muito utilizado no paradigma de programação funcional.

## 💫 Tipagem dinâmica
Como eu havia falado anteriormente, o ``JavaScript``, diferentemente do ``Java``, possui sua tipagem dinâmica, ou seja, o próprio ``JS`` consegue saber que tipo é o valor atribuído à variável e fazer o casting automático.

Exemplo:
```javascript
const bananasAmount = 3
```
retorna:
```sh
3 to tipo number;
```

```javascript
const bananasAmount = "3"
```
retorna:
```sh
"3" to tipo string;
```
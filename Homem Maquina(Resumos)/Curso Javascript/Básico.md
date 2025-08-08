# Introdução ao JavaScript
- A Javascript é usada para deixar uma página web interativa.
- HTML e CSS: Marcação 
- Javascript: Lógica

# Variáveis

- Uma variável aponta para um endereço de memória específico que armazena um valor, elas recebem um nome, esse nome é usado para acessar o valor armazenado.
- Para criar uma variável usamos a palavra LET
```
let hello; //declaração de uma variavel que se chama hello
```
- Em JavaScript uma string pode ser declarada com aspas simples ou duplas.
```
let hello = 'Hello'
// iniciação e declaração da variável hello
```
- Para imprimir um valor em JavaScript usamos console.log(nome_variavel_que_sera_impressa). Equivale ao cout (c++) e ao println(Java)
```
console.log(hello); //código para imprimir o que está armazenado na variavel hello
```
- É possível reatribuir (mudar) o valor de uma variável em JavaScript, basta apenas escrever seu nome e o novo valor. Exemplo: (vamos mudar o valor da variável hello para world):
```
hello = "World"
//o novo valor atribuido para a variavel hello é World
```
- Uma boa prática na criação de variáveis com palavras compostas é escrever assim: segundaLetra
- Exercício do freeCodeCamp:
```
let character = 'Hello'; //Declaração de uma variavel chamada character com o valor Hello (string)

console.log(character); //imprimir o valor de character

character = "World"; //reatribuir o valor dessa variavel para World

let secondCharacter; //criação de outra variavel

secondCharacter = character; // essa variavel tera o valor World pois atribuimos a ela o conteudo da variavel character

console.log(secondCharacter); //imprimir o valor de secondCharacter
```
- Código envolvendo números: 
```
let character = 'Hello';

let count = 8; 

console.log(count +1); // vai ser impresso o valor de count mais uma unidade (nesse caso, será impresso 9), dá para fazer outras operações como divisão(/) e multiplicação (*)

```


# Arrays
- Os arrays são as estruturas de dados mais básicas, um array pode conter uma série de valores.
- Arrays são declarados com o uso de [\]
```
let rows = ["Naomi", "Quincy", "CamperChan"]; //criação de um array chamado rows com 3 elementos

console.log(rows[0]); //vai imprimir o primeiro elemento do array rows

rows[2] = 10; //vai mudar 

console.log(rows); //vai imprimir todos os elementos do array rows

```

- Para ver qual elemento está no último índice do array:
```
let rows = ["Naomi", "Quincy", "CamperChan"];

console.log(rows[0]); //primeiro elemento do array 

rows[2] = 10; //muda o valor do elemento de índice 2 (o último)

console.log(rows); // vai imprimir todos os elementos do array

let ver = rows[rows.length - 1]; //criamos uma variavel chamada "ver" nela armazenamos o elemento que está no último índice

console.log(ver) //vai imprimir o último elemento

```
![[Pasted image 20250808201451.png]]

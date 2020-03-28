---
nome: Tipagem de dados
layout: page
ordem: 3
---

## Introdução

O computador é uma calculadora. Todos os dados que o computador guarda são sequências de bits (dígitos que podem ser 1 ou zero: ver [ver sistema binário]()). Como trabalhar com dados da web (imagens, textos, símbolos, músicas, vídeos) se todos são “iguais”?

Nós adotamos duas estratégias: rotular e tipar. Damos nomes às nossas variáveis e dizemos de qual tipo elas são. Os nomes nos ajuda a organizar e saber qual é o sentido da existência daquela variável. Os tipos dizem… O tipo!

## Tipos de dados

Os tipos podem ser separados em *Tipos de Dados Primitivos* e *Tipos de Dados Abstratos*. Os tipos de dados primitivos , por exemplo, em Java são: *byte*, *short*, *int*, *long*, *float*, *double*, *boolean* e *char* (olhe a documentação da linguagem [aqui](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html) ) para mais detalhes e depois volte para o post). Os tipos *byte*, *short*, *int*, *long* são tipos de diferentes tamanhos para armazenar *números inteiros*. Os tipos *float*, *double*, para tratar de *números fracionários* (nunca monetários, devido à imprecisão de números binários fracionários que é explicada [aqui](https://medium.com/@vaibhav0109/choosing-data-type-for-monetary-calculation-in-java-float-double-or-bigdecimal-ac6f52e57740)). O tipo *boolean* para guardar informações lógicas (true ou false), e o tipo *char* para representar um caractere Unicode.

Mas como representamos um texto? E uma fração? Como representamos uma pessoa dentro de um sistema? Para isso, são utilizados os *Tipos de Dados Abstratos*. Estes tipos são criados através de classes, encapsulando seu funcionamento interno (como dito no último post) e expondo formas de trabalhar com eles. Um tipo de dado abstrato que é sem dúvidas o mais usado e vem por padrão na linguagem Java, é o tipo *String*.

O tipo String, é basicamente o tipo utilizado para trabalhar com cadeias de caracteres. Abstraindo, representa um array com vários caracteres. Este tipo de dado é definido pela classe de mesmo nome, que encapsula o funcionamento especial interno dele na JVM (que envolve reaproveitamento de memória e outras coisas avançadas que estão encapsuladas e não nos interessa no momento). A linguagem Java abstrai várias outros tipos de dados como *Calendar* (Para tratar de datas), *LocalTime* (para tratar de hora) e até estruturas de dados como *LinkedList*, mas estas não serão tratadas aqui por enquanto.

Resumindo: o tipo de uma variável é definida por uma classe ou por seu tipo de dado primitivo.

## Uso na linguagem

```java
int numero = 10;
char caractere = "a";
String nome = "joão";
```
Como é uma linguagem estaticamente tipada, é necessário declarar uma variável antes de poder usá-la no seguinte modelo:

```java
Tipo nomeVariavel;
```
O sinal de ‘=’ é o operador de atribuição, que atribui o valor da direita para a variável que está a esquerda. O próximo post irá tratar da atribuição e instanciação dos objetos e estruturas das classes. Até.

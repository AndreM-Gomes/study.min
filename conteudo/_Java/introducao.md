---
nome: Introdução
layout: page
ordem: 1
---
  A linguagem Java, é uma linguagem de uso geral, Orientada a Objetos, criada
  pela Sun Microsystems em 1995. A linguagem Java foi criada com o propóstio 
  "Write once, run anywhere" (Escreva uma vez, rode em qualquer lugar).

  Para que isso fosse posssível, os criadores da linguagem criaram a JVM. A JVM 
  (Java Virtual Machine - Máquina Virtual JAVA) é  uma camada
  de abstração do Sistema Operacional hospedeiro. Ela executa os chamados 
  _**bytecodes**_ (códigos java compilados para a código da JVM), enviando 
  as instruções a serem executadas para o sistema operacional. Sendo assim, qualquer
  dispositivo que execute a JVM, pode executar programas escritos em Java.

---

## Processo de Desenvolvimento

Para o desenvolvimento de programas em Java, popularmente, são usadas uma das várias
IDE's (Integrated Development Enviroment - Ambiente de Desenvolvimento Integrado) 
disponíveis (Eclipse e IntelliJ IDEA são as mais utilizadas). Para ilustrar de forma
mais evidente, será demonstrado um exemplo (no Linux, e é recomendado que você 
use Linux para desenvolvimento).

### Preparando o ambiente

Primeiramente, é necessário preparar o ambiente. Para preparar um ambiente no Ubuntu,
recomendo este <a target="_blank" href="https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04">tutorial da Digital Ocean</a>.

### Compilando seu olá mundo

Abra seu terminal e execute:
```shell
$ mkdir olamundo
```

Será criada uma pasta chamada olamundo. Entre nela e crie um arquivo onde será
escrito o código:
 
```shell
$ cd olamundo
$ touch Olamundo.java
```

Abra esse arquivo. Aqui você pode utilizar o editor de sua preferência, como por
exemplo, o Visual Studio Code, onde você abriria o arquivo da seguinte maneira:

```shell
$ code Olamundo.java
```

Assim que o editor for aberto, agora escreva o seguinte código:

```java
public class Olamundo{
  public static void main(String[] args){
    System.out.println("Olá mundo");
  }
}
```
O seguinte código cria uma classe chamada Olamundo e no método main (padrão do Java),
executa o método println com o argumento "Olá mundo". Os detalhes serão explicados 
em posts posteriores. Para compilar o código, execute o comando:

```shell
$ javac Olamundo.java
```

O código será compilado em um arquivo Olamundo.class, como pode ser visto se executar

```shell
$  ls -la
```
O resultado:

```terminal
total 16
drwxr-xr-x  2 ubuntu ubuntu 4096 fev  8 22:25 .
drwxr-xr-x 50 ubuntu ubuntu 4096 fev  8 22:30 ..
-rw-r--r--  1 ubuntu ubuntu  420 fev  8 22:25 Olamundo.class
-rw-r--r--  1 ubuntu ubuntu  108 fev  8 22:24 Olamundo.java

```

Se você executar

```shell
$  java Olamundo
```

O programa o arquivo .class será carregado na memória e o programa será executado,
 exibindo no terminal a mensagem "Olá Mundo".

Os próximos posts irão se começar a se aprofundar no estudo da linguagem, descrevendo
a declaração de variáveis, estruturas sintáticas e etc.

___

### Referências e Para saber mais:
DEITEL, Paul; DEITEL, Harvey. Java: como programar. 10. ed. São Paulo: Pearson, 2016

O livro possui uma sessão "Antes de começar" que auxilia na montagem do ambiente 
de desenvolvimento para linguagem Java e no capítulo 1, exibe um apanhado de informações
sobre a informática em geral e um pequeno guia do processo de desenvolvimento, similar
a este post.

<a target="_blank" href="https://plataforma.bvirtual.com.br/Acervo/Publicacao/39590">Link para Biblioteca Virtual</a>
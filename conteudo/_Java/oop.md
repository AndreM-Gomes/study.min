---
nome: Introdução à OO - Encapsulamento
layout: page
ordem: 2
---

## Introdução 

A programação orientada a objetos é um paradigma de programação onde o elemento básico é o objeto. Mas o que é este objeto? Um objeto na programação? Quando passamos a falar de orientação a objetos, começamos a pensar em termos de abstrações. Abstrair é considerar um elemento em separado, tirando a atenção daquilo que não é essencial. Agora podemos definir o que é o objeto.

O objeto é o elemento básico da programação orientada a objetos. Na linguagem Java, ele tem seu tipo definido pela classe. Um objeto possui atributos (suas características) e métodos (seus comportamentos), assim como os objetos da realidade. Uma máquina de café expresso por cápsulas, por exemplo, tem suas características (pode ser vermelha, ter capacidade de 750ml de água, possuir vaporizador e etc) e seus comportamentos (pode fazer chá, café filtrado, café expresso, capuccino). 

Para evitar erros, estabelecer condições e ter uma previsibilidade sobre o que é aquele objeto e o que se pode fazer com ele, a linguagem Java dispões de classes (como dito anteriormente). Nem todas as linguagens utilizam classes. Javascript por exemplo, tem o que chamamos de orientação a objetos baseada em protótipo. A construção de classes é somente o que chamamos de sugar syntax (açúcar sintático), algo que simplifica a escrita, mas não muda a parte interna da linguagem.

Uma classe define quais os atributos e métodos os objetos criados a partir dela terão. A criação do objeto é feita através de um método especial denominada método construtor. O método construtor define como aquele objeto será criado, quais serão os valores iniciais de seus atributos e até as validações desses valores.

Até a agora, já foi definido o conceito básico de objeto, método construtor e classes. Estes são os elementos básicos, porém, o poder da orientação a objetos vem de seus três pilares: encapsulamento, especialização/generalização e polimorfismo. Alguns autores definem mais pilares, mas aqui será definido somente três pilares.
Este post irá descrever o encapsulamento, e em futuros posts será mostrado exemplos práticos e descrito os outros dois princípios.  

## Encapsulamento

Eu quero um café, o que eu faço? Coloco uma cápsula do café que eu quero, aperto o botão para aquele tipo de café e aguardo o café sair pelo distribuidor. Simples não? Mas como funciona isso?

O processo para a extração do café expresso consiste no aquecimento da água à temperatura correta, a pressurização da água em 15 bar (aproximadamente a pressão de 15kg de massa em uma superfície de 1cm2), a escolha da moagem adequada do grão e da torragem de acordo com o sabor preferido, a quantidade de pó deve ser de aproximadamente 7 gramas para 50ml de café (café curto) ou 100ml (café longo). Após a extração, o copo deve ter a chamada crema, a espuma adocicada que conserva os aromas do café até ele ser servido.

Mas eu só quero meu café! Exato! Eu só quero tomar meu café, ou servir o café. Se eu tentar fazer todos estes processos, vou errar, então eu delego isso para um especialista em cafés. O especialista e o engenheiro então se uniram e criaram algo que encapsula-se seus conhecimentos, para que qualquer pessoa pudesse preparar um café de qualidade: a máquina e suas cápsulas.

Então aqui vai o conceito de encapsulamento: esconder os detalhes de implementação das funcionalidades de um objeto, provendo acessos públicos para o uso destas funcionalidades. A máquina de café esconde todos os detalhes da produção do expresso, exigindo somente o café  (que também está encapsulado, literalmente) que respeita a interface (encaixe da cápsula) e provê um acesso público para sua funcionalidade (o botão). E assim, temos um café rápido e delicioso :) .
No próximo post será apresentado os tipos da linguagem Java e os exemplos em código da orientação a objetos. Até.

### Referências e Para saber mais:
DEITEL, Paul; DEITEL, Harvey. Java: como programar. 10. ed. São Paulo: Pearson, 2016

<a target="_blank" href="https://plataforma.bvirtual.com.br/Acervo/Publicacao/39590">Link para Biblioteca Virtual (É necessário estar logado)</a>

O primeiro capítulo do livro "Introdução a computadores, internet e Java", possui uma introdução simples e concisa sobre orientação a objetos utilizando o exemplo de um carro.

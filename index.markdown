---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Bem-vindo ao study.min

  Este blog tem o intuito de fornecer além de conteúdos, um conjunto de referências
  para facilitar o estudo dos tópicos. Qualquer erro encontrado ou sugestão, enviar
  um e-mail para [André Monteiro](mailto:andre.montero702@gmail.com?subject=[study.min]Erros%20ou%20sugest%C3%B5es).

  Observação: Alguns assuntos serão **propositalmente** não explicadas (Exemplo: O 
  post de introdução a Java não detalha a maior parte das características da linguagem
  e nem ensina detalhadamente como preparar o ambiente ou usar uma IDE). Tomei esta
  decisão para estimular o leitor a pesquisar por si e conheça lugares onde seja 
  possível encontrar mais informações, tutoriais e possa experimentar os erros de 
  um uso real
   (erros este que são de grande valor para o aprendizado), 
  e não simplesmente provar de mais um ambiente super controlado comumente encontrado
   em cursos.

  ___

## Conteúdos

  <h2>
    Java
  </h2>
  <ul>
    {% assign paginas = site.Java | sort: "ordem" %}
    {% for pagina in paginas %}
      <li> <a href="{{pagina.url | relative_url}}">{{pagina.nome}}</a> </li>
    {% endfor %}
  </ul>



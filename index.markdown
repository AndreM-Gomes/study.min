---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Bem-vindo ao study.min

  Este blog tem o intuito de fornecer além de conteúdos, um conjunto de referências
  para facilitar o estudo dos tópicos. Qualquer erro encontrado ou sugestão, enviar
  um e-mail para [André Monteiro](mailto:andre.montero702@gmail.com?subject=[study.min]Erros%20ou%20sugest%C3%B5es).

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



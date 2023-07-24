# A Cascata (cascading)

A escolha do browser de qual regra aplicar, caso haja muitas regras para o elemento

* Seu estilo é lido de cima para baixo.

É levado em consideração 3 fatores

1. Origem do estilo
2. Especificidade
3. Importancia

### Origem do estilo

inline > tag style > tag link

### Especificidade

É um calculo matematico, onde, cada tipo de seletor e origem do estilo, possuem, valores a serem considerados.

0. Universal selector, combinators e negation pseudo=class (:not())
1. Element type selector e pseudo-elements (::before, ::after)
10. Classes e attribute selectors ([type='radio'])
100. ID selector
1000. Inline

```html
<h1 class="title" id="my-title">Titulo <strong> Ola</strong> </h1>
<p>paragrafo</p>
```
```css
#my-title,
#my-title strong{
  color: red;
}

.title{
  color: gray;
}

body h1 {
  color: blue;
}

*{
  color: green;
}
```

### A regra !important

* cuidado, evite o uso
* não é considerado uma boa pratica
* quebra o fluxo natural da cascata

```css
body h1  {
  color: blue !important;
}

```
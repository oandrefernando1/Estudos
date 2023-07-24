# Comentarios

* Não irá afetar o seu codigo
* Ajuda a lembrar blocos de códigos
* deixa dica para leitura
* Ajuda a entenderem
* Nunca esqueça de fechar um comentario aberto

Comentarios começam com `/*` e terminam com `*/`.

```css

/* Básico */

/* ----------------------------------------------- */
body {
  font: 1em/150% Helvetica, Arial, sans-serif;
  padding: 1em;
  margin: 0 auto;
  max-width: 33em;
}

@media (min-width: 70em) {
  /* Let`s special case the global font size. On large screen or window, we increase the font size for better readability */
  body{
    font-size: 130%
  }
}

h1 {font-size: 1.5em;}

/* Elementos especificos */
/* ----------------------------------------------- */
div p, #id:first-line {
  background-color: red;
  border-radius: 3px;
}

div p + p {
  padding-top: 0;
}

```

* Voce podera usar para desabilitar partes do seu codigo

```css

/*.special {
  color: red;
}*/

p {
  color: blue:
}

```
### Para mudar o tamanho da imagem do background usamos a propriedade background-size.

```css
{
  /* Values */
background-size: cover;
background-size: contain;

/* Podemos usar 2 valores, o primeiro é para a largura da imagem e o segundo é para a altura */
background-size: 40% auto;
background-size: 2em 25%;
background-size: auto 8px;
background-size: auto auto;
}
```

```HTML
<header>=
</header>
<main>
    <h1>Evolua rápido com a tecnologia</h1>
    <p>Junte-se a milhares de devs e acelere
    na direção dos seus objetivos</p>
</main>
```
```CSS
* {
    margin: 0;
}

header {
    height: 100px;
    border: 7px dashed red;
    background-color: rgb(55, 100, 50);
    background-image: url(https://app.rocketseat.com.br/_next/image?url=%2Fassets%2Ficons%2Fmember-get-member%2Fgift.png&w=32&q=75);
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain
}

```
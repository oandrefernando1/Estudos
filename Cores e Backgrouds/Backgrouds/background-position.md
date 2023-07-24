### Com a propriedade background-position podemos mudar a posição da imagem do background.


```css
{
/* Pricipais valores */
background-position: top;
background-position: bottom;
background-position: left;
background-position: right;
background-position: center;
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
}

```
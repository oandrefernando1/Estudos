### A propriedade background-origin é quem define o ponto de origem de uma imagem específica.


```css
{
  /* Principais valores */
    background-origin: border-box;
    background-origin: padding-box;
    background-origin: content-box;
}
```


### O background-clip define se a cor ou imagem do background iniciam debaixo de sua área de borda, preenchimento ou conteúdo.

```css
{
  /* Principais valores */
    background-clip: border-box;
    background-clip: padding-box;
    background-clip: content-box;
    background-clip: text;
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
    background-size: contain;
    background-origin: border-box;
    background-clip: content-box;
}

```
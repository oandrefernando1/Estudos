### A propriedade background-attachment determina se a posição da imagem vai ser fixa ou se vai rolar junto com o conteúdo.

```css
{
  /* Principais valores */
    background-attachment: scroll;
    background-attachment: fixed;
    background-attachment: local;
}

```
```HTML
<header>=
</header>
<main>
    <h1>Evolua rápido com a tecnologia</h1>
    <p>Junte-se a milhares de devs e acelere
    na direção dos seus objetivos</p>
    <h1>Evolua rápido com a tecnologia</h1>
    <p>Junte-se a milhares de devs e acelere
    na direção dos seus objetivos</p>
    <h1>Evolua rápido com a tecnologia</h1>
    <p>Junte-se a milhares de devs e acelere
    na direção dos seus objetivos</p>
    <h1>Evolua rápido com a tecnologia</h1>
    <p>Junte-se a milhares de devs e acelere
    na direção dos seus objetivos</p>
</main>
```
```CSS
* {
    margin: 0;
}

main {
    color: white;
    height: 100px;
    border: 7px dashed red;
    background-color: rgb(55, 100, 50);
    background-image: url(https://app.rocketseat.com.br/_next/image?url=%2Fassets%2Ficons%2Fmember-get-member%2Fgift.png&w=32&q=75);
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    background-origin: border-box;
    background-clip: content-box;
    background-attachment: fixed;
}

```
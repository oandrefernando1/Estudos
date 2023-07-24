### Para adicionar uma imagem como background podemos usar a propriedade background-image

### Por padrão a imagem vai se repetir e podemos modificar essa opção usando a propriedade background-repeat

```css
/* Values */
{
background-repeat: repeat-x;
background-repeat: repeat-y;
background-repeat: repeat;
background-repeat: space;
background-repeat: round;
background-repeat: no-repeat;

/* Podedmos usar 2 valores: horizontal | vertical */
background-repeat: repeat space;
background-repeat: repeat repeat;
background-repeat: round space;
background-repeat: no-repeat round;?
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
}

```
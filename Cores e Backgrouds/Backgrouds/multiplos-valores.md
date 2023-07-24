- Podemos aplicar múltiplos backgrounds em um mesmo elemento, podendo ter cor sólida, gradiente ou imagem. Para isso basta separar por vírgula cada background.

```CSS
* {
    margin: 0;
}

main {
    color: purple;
    background-color: rgb(55, 100, 50);
    background-image: url(https://app.rocketseat.com.br/_next/image?url=%2Fassets%2Ficons%2Fmember-get-member%2Fgift.png&w=32&q=75);
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    background-origin: border-box;
    background-clip: content-box;
    background-attachment: fixed;

    background: linear-gradient(rgba(255,255,255,0) ,rgba(255,0,0,0.2)) rgb(55, 100, 50) url(https://app.rocketseat.com.br/_next/image?url=%2Fassets%2Ficons%2Fmember-get-member%2Fgift/.png&w=32&q=75)
    no-repeat center top / 50px border-box content-box fixed;

    


}

```
### Podemos usar o shorthand background para definir todos os valores do background

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

    background: rgb(55, 100, 50)      url(https://app.rocketseat.com.br/_next/image?url=%2Fassets%2Ficons%2Fmember-get-member%2Fgift.png&w=32&q=75)
    no-repeat center top / 50px border-box content-box fixed;

}

```
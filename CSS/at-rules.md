# At-rules

* Está relacionado ao comportamento do CSS
* começa cp, p sinal de `@` seguindo do identificador e valor

## Exemplo

- @import       /* incluir um CSS externo */

- @media        /* regras condicionais para dispositivos */

- @font-face    /* fontes externas */

- @keyframes    /* Animation */

```css
@import "https://local.com/styles.css"; /* ou */ @import url("https://local.com/styles.css");


@media (min-width: 500px){
    /* rules here */
}

@font-face {
    /* rules here */
}

@keyframes nameofanimation {
    /* rules here */
}
```
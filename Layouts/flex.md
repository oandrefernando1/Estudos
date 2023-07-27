# Flexbox

* Nos permite posicionar os elementos dentro da caixa.
* Controle em uma dimensão (horizontal ou vertical)
* Alinhamento,direcionamento, ordernar e tamanhos

```css
div.parent {
  display: flex;
}
```
### flex-direction

* Qual a direçao do flex: horizontal ou vertical
* row | column

## Alinhamento

* justify-content
* align-items

```html
<div class="container">
  <div class="box blue"></div>
  <div class="box red"></div>
  <div class="box green"></div>
</div>
```

```css
.container {
    display: flex;
    justify-content: space-between;
}
.box {
  width: 50px;
  height: 50px;
  margin-bottom: 8px;
}

.blue {
  background-color: blue;
}

.red {
    background-color: red;
}

.green {
    background-color: green;
}
```
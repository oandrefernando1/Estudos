## Absolute

- Quando o position é absolute o elemento é deslocado saindo do fluxo normal. O elemento de position absolute é posicionado em relação ao seu parent element mais próximo. Se esse elemento "pai" não existir, ele será posicionando em relação ao bloco contendo a raiz do elemento.

```html
<main>
  <div class="box1 box"></div>
  <div class="box2 box"></div>
  <div class="box3 box"></div>
</main>
```

```css
.box{
  width:50px;
  height:50px;
  margin-bottom: 8px;
  
}

main {
  margin-top: 200px;
}

.box1{
  background-color: red;
  position: absolute;
  left: 0px;
  top: 0px
}

.box2{
  background-color: green;
  
}

.box3{
  background-color: blue;
}

```
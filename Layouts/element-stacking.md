## Element-Stacking

- É o empilhamento de elementos. Podemos usar o z-index para determinar a ordem da posição do elemento. Quanto maior o z-index, mais "acima" vai aparecer o elemento.

```html
<div class="box1 box"></div>
<div class="box2 box"></div>
<div class="box3 box"></div>
```

```css
.box{
  width:50px;
  height:50px;
  margin-bottom: 8px;
}

.box1{
  background-color: red;
  position: absolute;
  top: 5px;
  left: 5px;
  z-index: 3;
}

.box2{
  background-color: green;
  position: absolute;
  top: 10px;
  left: 10px;
}

.box3{
  background-color: blue;
  position: absolute;
  top: 15px;
  left: 15px;
}

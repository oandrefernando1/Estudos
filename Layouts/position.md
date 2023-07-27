## Posicionamentos

Controlar onde, na pagina, o elemento irá ficar,
alterando o fluxo normal dos elementos.

- Name: position
- Value: static|relative|absolute|fixed

Lembrando que o fluxo normal dos elementos é ficar um abaixo do outro, a não ser no caso de elementos inline, que ficam um ao lado do outro.


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
}

.box2{
  background-color: green;
}

.box3{
  background-color: blue;
}

```
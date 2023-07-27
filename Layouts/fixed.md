## Fixed

- Quando aplicado o position fixed é como se criasse um elemento flutuante que fica fixo na página, independente do scrolling feito.

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
  position: fixed;
}

.box2{
  background-color: green;
}

.box3{
  background-color: blue;
}

```
## Relative

-top, right, bottom, left, z-index

Quando o position é relative os elementos são deslocados do seu posicionamento normal, mas sem afetar o posicionamento de outros elementos da página.

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
  position: relative;
  left: 100px;
  top: 80px
}

.box2{
  background-color: green;
}

.box3{
  background-color: blue;
}

```
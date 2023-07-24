# Shorthand

* junção de propriedades
* resumido
* legivel

```css
{
  /* background properties */
  background-color: #000;
  background-image: url(images/bg.gif);
  background-repeat: no-repeat;
  background-position: left top;

  /* background shortland */
  background: #000 url(images/bg.gif) no-repeat left top;

  /* font properties */
  font-style: italic;
  font-weight: bold;
  font-size: .8em;
  line-height: 1.2; 
  font-family: Arial, sans-serif;

  /* font shorthand */
  font: italic  .8em/1.2 Arial, sans-serif;
}
```

## Detalhes

* não irá considerar propriedades anteriores
* valores não especificados irão assumir o valor padrão
* geralmente, a ordem descrita não importa, mas, se houver muitas propriedades com valores semelhantes, poderemos encontrar problemas

## Propriedades que aceitam shorthand

animation, backgorund, border, border-bottom, border-color, border-left,
border-radius, border-right, border-style, border-top, border-width,
column-rule, columns, flex, fles-flow, font, grid, grid-area, grid-column,
grid-row, grid-tamplate, list-style, margin, offset, outline, overflow, padding,
place-content, place-items, place-self, textt-decoration, transition

**https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties**
# Porcentagens %

* Em muitos casos é tratado da mesma maneira que as distancias <length>
* Sempre será relativo a algum valor

## Exemplo

```HTML
<ul>
  <li>One</li>
  <li>Two</li>
  <li>Threee
      <ul>
        <li>Three A</li>
        <li>Three B
          <ul>
            <li>Three B2</li>
          </ul>
        </li>
      </ul>
  </li>
</ul>
```

```CSS
li {
  font-size: 80%;
}
```
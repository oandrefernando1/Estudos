# Distancias absolutas <length>

São fixas e não alteram seu valor.

Unidade     Nome                  Equivalencia
cm          Centimetros           1cm = 96px/2.54
in          Inches (polegadas)    1in = 2.54cm = 96px
px          Pixels                 1px = 1/96th of 1in

* o mais comum e mais utilizado é o **px**
* não recomendado usar cm

# Distancias relativas

São relativas a algum outro valor, podem ser o elemento pai, ou root, ou o tamanho da tela.

* Beneficio: Maior adptação aos diferentes tipos de tela

Unidade         Relativos a
em              Tamanho da font do pai.
rem             Tamanho da font do elemento raiz (root/html)
vw              1% da viewport width
vh              1% da viewport heigth

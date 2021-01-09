# FRONTEND-ESSENTIALS

## FlexBox

## taak03 - Align Items

### Introductie

Oké. Je hebt geleerd hoe je de hoofdas van een flexbox-container kunt wijzigen:

![hoofdas](images/hoofd-as.png)

Maar bedenk eens dat je een streep kunt zetten, 90 graden, door de hoofdas heen. Dit noemen ze de kruisas (cross-axis). Dit is een denkbeeldige lijn die 90 graden staat op de hoofdas.

In andere woorden:

Als de `flex-direction: row;` is, dan loopt de  de __hoofdas__ van links naar rechts...
  
...en de __kruisas__ (cross-axis) loopt van boven naar beneden:

![Cross axis](images/cross-axis.png)

En andersom geldt natuurlijk ook: Als de hoofd-as van boven naar beneden loopt, dan loopt de kruis-as van links naar rechts.

![Cross axis column](images/cross-axis-column.png)

### Opdracht

1. Open eens align-items.html en bekijk eens wat je ziet. Je ziet dat de blokken de gehele ruimte in beslag nemen. Dit komt omdat we de container groter hebben gemaakt met `width:100vh;`.
2. Als je nu `align-items:center;` toevoegt aan de container, wat gebeurt er dan?
3. De blokken gaan naar het midden toe van de kruisas
4. Probeer het ook eens met de andere waarden:
   ![Align items](images/align-items.png)
5. Lees de bronnen nog eens door.

### Bronnen

- [CSS Flexbox Tutorial #10 - Align Items on the Cross Axis](https://www.youtube.com/watch?v=WY2itpeUK7Q)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Basic concepts of flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)

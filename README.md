# FrontendWebDevelopment

HTML- HyperText Markup Language, značkovací jazyk, popisuje strukturu stránky

Stránku tvoří prvky a jejich atributy

Prvky- jsou definovány počáteční značkou, obsahem a koncovou značkou

Atributy- poskytují další informace o prvcích, uvedeny v počáteční značce, název + hodnota

Syntax- ```<prvek atribut='hodnota'>obsah</prvek>```

Komentáře- ``` <!--komentář --> ```

Struktura webu:

```
<!DOCTYPE HTML>
<html lang="cs">
  <head>

    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1", shrink-to-fit='no' />
    <meta name="description" content="" />

    <title>title</title>
  
  </head>
   <body>

   </body>
</html>
```

Content:

Nadpisy- ```<h1> až <h6>, h1 největší```

Odstavce- ```<p>text<p>```

Odkazy- ```<a href=''>odkaz</a>    <a href='mailto:'>odkaz</a>    <a href='tel:'>odkaz</a>```

Seznamy- seřazený- ```<ol> <li> </li> <li> </li> </ol>```, neuspořádaný- ```<ul> <li> </li> <li> </li> </ul>```

Tabulky- <table><thead><tr><th>Name</th><th>Email</th><th>Age</th></tr></thead><tbody><tr><td>Brad</td><td>email@email.com</td><td>32</td></tr></tbody></table>

```<table><thead><tr><th>Name</th><th>Email</th><th>Age</th></tr></thead><tbody><tr><td>Brad</td><td>email@email.com</td><td>32</td></tr></tbody></table>```

Tlačítka- ```<button>tlacitko</button>```

Obrázek- ``` <img src='' alt=''>```

Tabulka- <form><label>First Name</label><input type='text'><label>Last Name</label><input type='text'><label>Email</label><input type='email'><label>Message</label><textarea></textarea><label>Gender</label><select><option>Male</option><option>Female</option></select><input type='checkbox'>C<input type='checkbox'>Java<input type='checkbox'>Python<input type='radio'>yes<input type='radio'>no<input type='submit'></form>

```<form><label>First Name</label><input type='text'><label>Last Name</label><input type='text'><label>Email</label><input type='email'><label>Message</label><textarea></teaxtarea><label>Gender</label><select><option>Male</option><option>Female</option></select><input type='checkbox'>C<input type='checkbox'>Java<input type='checkbox'>Python<input type='radio'>yes<input type='radio'>no<input type='submit'></form>```

Sémantické prvky- <img src='semantika.jpg' alt='semantika'> <br>

Základní atributy- class, id - ke stylu

Prvky pro definování částí webu- div a span, div- block= začíná a končí na novém řádku, span- inline= na stejném řádku


CSS- Cascading Stylesheets, popisuje, jak se mají prvky zobrazovat

Syntax- selektor {vlastnost: hodnota;}

Komentář-``` /* komentář */ ```

Metody přidání CSS na web: 

1. mezi prvky ```<style></style>```
2. odkazem ```<link rel='stylesheet' href=''>```

Selektory- 

.class- třída

#id- id

*- všechno

prvek- prvek

prvek.class- všechny určité prvky s určitou třídou

prvek,prvek- všechny určité prvky a jiné určité prvky

div p- všechny p v div

div > p- všechny p kde je rodič div

prvek[atribut='hodnota']- určitý prvek s atributem a jeho hodnotou



CSS Box Model- <img src='boxmodel.jpg' alt='boxmodel'>

Pozicování-

position: static- normálně v dokumentu, relative- posunuto z normálního umístění, fixed- při skrolování zůstává, absolute- vyjmut z toku dokumentu, umístěn na souřadnicích, sticky- drží pozici, dokud je vidět rodič

Display- block- zaplní celý řádek, inline- zaplní jen kolik potřebuje, inline-block- umožňuje

Opacity- určuje průhlednost, 0 - 1, 1- průhledná

Jednotky- absolutní a relativní, absoultní px- pixel, relativní rem- relative to font-size root prvku, %- relativní k rodičovskému prvku

Zarovnání prvků- float, hodnoty- right, left

Pseudotřídy- pro speciální události prvků, ```selector:pseudo-class { property: value;}``` např.: :hover, :link, :visited, :active

Pseudoprvky- pro stylování určitých čáastí prvků, ```selector::pseudo-class { property: value;}``` např.: ::after, ::before, ::first-letter, ::first-line

Media queries- ```@media screen and (vlastnost: hodnota) { }```, k responzivitě, vlastnosti- max-width, min-width

Box-sizing- border-box / content-box, border-box - padding a border jsou započítány do výšky a šířky

Flexbox-jednotlivé boxy musí být v kontejneru s display: flex, velikost boxů se určuje vlastností flex, pořadí vlastností order, flex-direction, justify-content, viz flexbox.html

Grid- boxy v kontejneru s display: grid, vlastnosti- grid-template-columns, grid-template-rows, grid-template-areas, grid-area, viz grid.html

Bootstrap- CSS framework, tip: kouknout na dokumentaci

containers- pro dání contentu v ně, .container- responsive fixed width container, .container-fluid- full width container, row pro horiyontální skupiny columns, columns- col-sm, col-md, col-lg, col-xl
grid- 12 columns, 
alerts, forms, inputs, buttons, badges, progress bars, pagination, cards, dropdowns, navbars, carousel


Sass-

Javascript-
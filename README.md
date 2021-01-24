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
  
  </head>
   <body>

   </body>
</html>
```

Content:

Nadpisy- ```<h1> až <h6>, h1 největší```

Odstavce- ```<p>text<p>```

Odkazy- ```<a href=''>odkaz</a>    <a href='mailto:'>odkaz</a>    <a href='tel:'>odkaz</a>```

Seznamy- seřazený- ```<ol> <li> </li> <li> </li> </ol>```, neuspořádaný- ```<ol> <li> </li> <li> </li> </ol>```

Tabulky- <table><thead><tr><th>Name</th><th>Email</th><th>Age</th></tr></thead><tbody><tr><td>Brad</td><td>email@email.com</td><td>32</td></tr></tbody></table>

```<table><thead><tr><th>Name</th><th>Email</th><th>Age</th></tr></thead><tbody><tr><td>Brad</td><td>email@email.com</td><td>32</td></tr></tbody></table>```

Tlačítka- ```<button>tlacitko</button>```

Obrázek- ``` <img src='' alt=''>```

Sémantické prvky- <img src='data:image/png;base64,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' alt='semntika'>
Základní atributy- class, id - ke stylu


CSS- Cascading Stylesheets, popisuje, jak se mají prvky zobrazovat

Syntax- selektor {vlastnost: hodnota;}

Komentář-``` /* komentář */ ```





# CSS ismeretek
## CSS Cascading Style Sheet
---
A HTML kezdetben nem egy professzionális megjelenítést lehetővé tévő nyelv volt, pusztán csak a tartalom egyszerű közlésére szolgált.
Az Internet fejlődésével a HTML nyelv tudásával kapcsolatos igények is nőttek. A HTML formázási lehetőségei segítettek ezen a problémán, azonban
bonyolultabbá is tették a HTML használatát. 

Felmerült az igény arra, hogy a HTML lehetőség szerint ne vagy csak minimális mértékben tartalmazzon formázást, valamint azt, hogy a formázás
a tartalom leírásától független legyen. 

Ezt biztosítják a stíluslapok.

## Alapvető HTML

### Egy egyszerű HTML oldal forrása a következőképpen néz ki

```HTML
<HTML>
  <HEAD>
    <TITLE>Az oldal címe</TITLE>
  </HEAD>
  <BODY>
    Ez a dokumentumtörzs
  </BODY>
</HTML>  
```
### A HTML leíró elemei

A HTML gyakorlatilag azt adja meg, hogy az adott tartalom az oldalon micsoda. 
A leggyakrabban megjelenő elemek:
 - szöveg típusú elemek (bekezdés, felsorolások,címsorok)
 - képek
 - hiperhivatkozások
 - táblázatok
 - form elemek
 
 ### HTML fájl meta információkkal, és stíluslap betöltéssel
 

 
 ```html
<HTML>

<Head>
    <title>Egyszerű html oldal</title>
    <meta lang="hu" charset="utf-8">
    <link rel="stylesheet" type="text/css" href="style.css">
</Head>

<body>
    Ez a dokumentumtörzs.


</body>

</HTML>
```
 
 ### CSS stílusok
 
  - kiválasztás HTML tag alapján
  ```css
  body {
    background-color: magenta;
    font-family: sans-serif;
  }
  ```
 

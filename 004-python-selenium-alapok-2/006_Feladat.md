## 006 Feladat: Űrlap automatizálás fájlból

A feladatokat külön python fileban oldd meg. Minden feladat tartalmazza az elvárt filenevet. Ezen a néven fogadható el a megoldás.

Adott az alábbi csv tartalom
```
Name,Email,DoB,Phone
Kiss Péter,peter.kiss@sel.hu,1988-12-12,06361 455899
Nagy Ervin,ervin.nagy@sel.hu,1977-01-01,06361 555555
Bella Eszter,eszter.bella@sel.hu,2003-07-07,06555 555555
Kis Franciska,franciska.kiss@sel.hu,1999-01-20,06666 666666
```
Metsd ezt el egy table_in.csv szöveges állományba. Ezzel fogsz dolgozni.

1) Készíts egy Python alkalmazást ami selenium-ot használ. Indítsd el lokálisan a selenium-py-peldatar alkalmazást. A program töltse be a példatárból az `http://localhost:9999/another_form.html` oldalt. A program segítségével olvassd be a csv tartalmat. A feladatod, hogy az oldalon található formanyomtatvány segítségével feltöltsd a táblázatot. Használd a Python CSV könyvtárát. A feltöltött táblázatot ellenőrizheted ha a probramod letölti a táblázat alatti gomb segítségével az aktuális tartalmat. Hasonlítsd össze python kódból a kapott file-t, hogy identikus-e az eredetivel.
    > A megoldást egy `csvfeltoltes.py` nevű fileban kell beadnod.

## Feladat beadása
A fent eméített python file-okat és benne a megoldásodat kérlek a saját `selenium-py-peldatar` github repo forkodban egy `selenium2-homework` nevű mappába helyezd el.

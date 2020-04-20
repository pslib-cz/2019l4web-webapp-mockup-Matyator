# Zábavná karetní hra ELEMENTS
## Pravidla hry
Hra se hraje v počtu dvou hráčů. Každý hráč má ze začítku k dipozici 5 karet. Ostatní karty ze sady jsou položeny lícem dolů. Z tohoto balíčku se během hry snímají karty. Na začátku hry je jedna startovací karta položena uprostřed lícem nahoru - na tuto kartu se v průběhu hry pokládají další karty. Hraje se postupným pokládáním karet se stejným symbolem nebo stejným čísle. Hráči střídají. Výjimnkou jsou speciální karty. Pokud hráč číslo jedna položí kartu s vyhovující barvou a symbolem +2, hráč číslo dva si musí ze snímacího balíčku vzít dvě karty, pokud tuto speciální kartu nemůže přebít svou kartou se symbolem +2. Druhým typem unikátních karet jsou "měniči". Tyto karty obsahují všechny čtyři barvy a použitím této karty si hráč zvolí barvu této karty podle libosti.

## Obsah (podklady)
Celkem 44 karet:

- 9 "ohnivých" karet
- 9 "vodních" karet
- 9 "přírodních" karet
- 9 "elektrických" karet
- 3 karty "měnič"
- 4 karty "+2"
- 1 líc karty

## Sada karet
![Sada-karet](/podklady/Sadakaret.PNG)

## Struktura
Celé hrací pole s kartami se nachází v `div class="pole"`
`"desk1"` = protihráčův stůl (hráč 2)
`"sada1"` = sada karet protihráče seřazených vedle sebe, obsahuje `img` jednotlivých karet *Card-Rub.svg* otočené lícem dolů
`"center"` = prostředek hracího stolu, obsahující akční část `"odhoz"` s položenými karty na stole, např. *Card-fire-5.svg*
a část `"balíček"` s lízacím balíčkem karet, otočenými lícem dolů *Card-Rub.svg*
`"desk2"` = hráčův stůl (hráč 1)
`"sada1"` = sada karet hráče seřazených vedle sebe, obsahuje `img` různých typů karet, např. *Card-water-2.svg*, *Menic-1.svg*

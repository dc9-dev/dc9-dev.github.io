# 1. Dodawanie nowego wpisu

hugo new posts/tytul_nowego_wpisu.md

## Redagowanie wpisu

Nalezy przejsc do katalogu posts i wyedytowac plik tytul_nowego_wpisu.md - nalezy odpowiednio uzupelnic pola

```
---
title: "Tytul_nowego_wpisu"
date: 2021-11-22T23:16:43+01:00
draft: true
alternativeUrl: 
summary: 
thumbnail: "i/europe.svg"
---
```

Pole alternativeUrl uzywane jest jezeli chcemy zeby zamiast do podstrony z trescia linki odnosily nas do zewnetrznej strony

Pole thumbnail uzywane jest do dodania obrazka miniaturki do wpisu - trzeba go wczesniej dodac do katalogu static a sciezka wpisywana w tym polu zaczyna sie wewnatrz katalogu static np. dla static/i/europe.svg wpisujemy jedynie i/europe.svg

Pole summary mozna uzywac skladni markdown np. zeby zrobic link

### WAZNE

Po skonczonej edycji trzeba zmienic draft na false - tak publikuje sie nowy wpis

## Poradnik uzywania [markdown](https://www.markdownguide.org/getting-started/)

# 2. Commitowanie zmian

Nalezy wykonac nastepujace operacje:

`git add .`

`git commit -a -m 'Informacja o dodaniu nowego wpisu'`

`git push`

### Strona po około minucie od wykonania powyzszej kombinacji polecen odswiezy sie samodzielnie na serwerze


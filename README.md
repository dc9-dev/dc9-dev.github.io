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
### WAZNE

Po skonczonej edycji trzeba zmienic draft na false - tak publikuje sie nowy wpis
W summary mozna uzywac skladni markdown np. zeby zrobic link

## Poradnik uzywania [markdown](https://www.markdownguide.org/getting-started/)

# 2. Commitowanie zmian

Nalezy wykonac nastepujace operacje:

`git add .`

`git commit -a -m 'Informacja o dodaniu nowego wpisu'`

`git push`

Strona po około minucie od wykonania powyzszej kombinacji polecen odswiezy sie zamodzielnie na serwerze


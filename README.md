PLANTING JS
====

[![Join the chat at https://gitter.im/komitywa/plantingjs](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/komitywa/plantingjs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Aby możliwe było uruchomienie źródeł zarówno w trybie developerskim, jak i builda na produkcje, wymagane są następujące pakiety:

    * NodeJS w wersji 0.10 lub nowszej
    * Manager pakietów node'a NPM najlepiej w wersji 2.6 lub nowszej


Odpalać wszsytkie komendy w roocie projektu

#### Instalacja wszystkich zaleznosci:

```shell
npm install
bower install
```

Windows miewa problemy ze ścieżkami unixowymi, więc warto także doinstalować Gulpa globalnie (na linuxie z sudo)

```shell
npm install -g gulp
```

#### Odpalanie produkcyjnego builda:

```shell
npm run build

lub

gulp build
```
> Generuje zminimalizowana apke w katalogu "dist" gotowa do deployu na produkcje.


#### Start servera developerskiego:

```shell
npm run server

lub

gulp serve
```
> Odpala lokalny server developerski na porcie 9000 z automatycznym wykrywaniem zmian i live reloadem.

<img src="https://glowspace.cz/wp-content/uploads/2020/10/gs-grad-transparent-2.png" alt="drawing" width="200" style="float:right"/>

# Křesťanské open-source projekty
Seznam křesťanských IT projektů. Projekty jsou open-source dostupné, pokud není uvedeno jinak.

:warning: **Seznam obsahuje i projekty, na kterých nepracují členové Glow Space,** ale stojí za to o nich vědět.

## Křesťanská hudba

### Projekt ProScholy.cz
| Repozitář                                                                  | Popis                                                          | Technologie                     |
| ------------- | ------------- | ------------- |
| [proscholy/regenschori-api](https://github.com/proscholy/regenschori-api)  | Databáze křesťanské hudby - centrální API server + admin       | GraphQL, Laravel, Elasticsearch |
| [proscholy/proscholy-web](https://github.com/proscholy/proscholy-web)      | FE aplikace [Zpěvník pro scholy](https://zpevnik.proscholy.cz) | Nuxt.js, Bit.dev |
| [proscholy/regenschori-web](https://github.com/proscholy/regenschori-web)    | FE aplikace [Regenschori.cz](https://regenschori.cz)         | Nuxt.js, Bit.dev |
| [proscholy/proscholy-android](https://github.com/proscholy/proscholy-android) | Android aplikace  [Zpěvník pro scholy](https://play.google.com/store/apps/details?id=jozkar.mladez)         | Java |
| [proscholy/proscholy-ios](https://github.com/proscholy/proscholy-ios)    | iOS aplikace [Regenschori.cz](https://apps.apple.com/us/app/zp%C4%9Bvn%C3%ADk-pro-scholy/id1475375453#?platform=iphone)         | Swift |
| [proscholy/proscholy-projekce](https://github.com/proscholy/proscholy-projekce)    | Webová projekce textu Projekce.proscholy.cz (alfa verze) | Laravel, WebSockets |

Repozitáře ProScholy jsou dockerizované a lze je spustit s docker-compose. GraphQL playground je dostupný na https://zpevnik.proscholy.cz/graphql-playground.

### LilyPond noty
https://github.com/jirihon/lilypond-scores

### Kancionál server
https://github.com/jridky/kancional-server

## Liturgický kalendář

### Igneus
| Repozitář | Popis | Technologie |
| ------------- | ------------- | ------------- |
| [igneus/church-calendar-api](https://github.com/igneus/church-calendar-api) ||| 
| [igneus/calendarium-romanum](https://github.com/igneus/calendarium-romanum) |||

## Bible
### Biblické souřadnice
| Repozitář | Popis | Technologie |
| ------------- | ------------- | ------------- |
| [proscholy/bible-reference](https://github.com/proscholy/bible-reference) | Parsování biblických souřadnic z plaintextu do strukturované podoby | Javascript |

## Organizace akcí
Aplikace pro plánování a organizaci akcí, táborů, duchovních obnov.

### Plánovací systémy
| Repozitář | Popis | Technologie |
| ------------- | ------------- | ------------- |
| [michaeldojcar/monkey-planner](https://github.com/michaeldojcar/monkey-planner) | Open source plánovač akcí, úkolů, zodpovědností, rolí | Laravel, MySQL |

### Přihlášování a evidence účastníků

#### Cidas (proprietární)
Sekce pro mládež ČBK a signály.cz. Systém pro přihlašování na akce, stravování, ubytování, statistiky, možnost přizpůsobení formulářů podle akce, wordpress a joomla plugin, aktuálně není veřejně dostupný, ale lze kontaktovat na webu https://cidas.cz/.

### Digitální táborové hry
| Repozitář | Popis | Technologie |
| ------------- | ------------- | ------------- |
| [michaeldojcar/live-rpg-game](https://github.com/michaeldojcar/live-rpg-game) | Živá RPG hra s questy - postavy mají mobilní rozhraní a udržují si informace o hráčích, jejich rozehrané questy, polohu hráčů atd. | Laravel, Vue.js, MySQL |


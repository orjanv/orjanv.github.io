---
layout: post
title: "Oppdagelsen av snøballtall"
date: 2016-02-15 20:28:15 
thumbnail: /assets/2014-12-28-snowball-numbers-11.png
category: programmering
tags: programmering matematikk tall kode språk
---

Jeg liker tall og språk og når jeg kommer over skjulte ikke-hensiktsmessige meninger i tekster blir det ofte spennende. For eksempel [å finne skjulte haikudikt i gamle bøker eller tekster](https://github.com/orjanv/hiddenhaikus) som ikke hadde til hensikt å skrive haikudikt. Jeg vet at jeg ikke er alene om dette og for eksempel The New York Times har en egen nettsideapplikasjon dedikert til å finne haikudikt i artikler de publiserer:

![](/assets/newyorktime-haiku.png "Haikudikt funnet i New York Times artikler")

For en god stund siden nå leste jeg [ett innlegg](http://www.futilitycloset.com/2014/12/28/snowball-numbers/) på en blogg jeg følger. Der tok de opp noe de kalte *snøballtall*. Snøball fordi om du ruller en snøball ned en bakke blir den jevnt større og større. 

> Snøballtallene. 
Skjulte tall i tallene.
Kan du finne de?

Det var forfriskende å lese om at noen har sett på tallord og funnet ut at noen tall inneholder en stigende fordeling av bokstaver brukt i tallordet. For eksempel det norske tallet **11**. Grunntallet skrives **elleve** og distribusjonen blir som følger 

e | l | v
---|---|---
3 | 2 | 1

Distribusjonen av bokstavene funnet i tallordet blir i ordnet rekkefølge: 1-2-3 og vi har et snøballtall. 

> Tallord som ruller ned en bakke

Blogginnlegget jeg leste var inspirert av en journal skrevet av Eric Harshbarger og Mike Keith og har tittelen: [*Number Names With A Snowball Letter Distribution*](http://digitalcommons.butler.edu/wordways/vol45/iss4/10/)

Jeg bestemte meg for å finne slike tall med python. Først på engelsk og så på norsk. Det viste seg at det ikke er så veldig mange tall på engelsk språk og at jeg må veldig høyt opp for å finne et slik snøballtall: **313.340.350.000.000.000.499**

![](/assets/2014-12-28-snowball-numbers-11.png "Snøballtall")

På norsk derimot var det som nevnt lengre opp et lavt tall: **elleve**, men etter det er det lenge til neste tall. Jeg har latt programmet kjøre i over en måned på min hjemmeserver uten hell. Jeg har gitt opp ettersom jeg ikke klarer å optimalisere programmet mer heller. Har du lyst å se på det, må du gjerne foreslå noe. Koden ligger på [GitHub](https://github.com/orjanv/snowball-numbers).


## Käyttötapaukset

* Määritä tänne järjestelmän loppukäyttäjät
* Käyttötapauskaavio, jossa järjestelmän keskeiset käyttötapaukset
* Kuvaile tärkeimmät käyttötapauksista käyttötapausskenaarioina mallipohjaan perustuen
  * mallipohja: määritä alkutila (initial state), normaali kulku (normal flow), lopputila (end state)
  * kerro myös kuinka normaali kulku voi mennä pieleen sekä
  * mahdolliset vaihtoehtoiset kulut (alternate flow)
  
---

#### Järjestelmän loppukäyttäjät

Metropolia ammattikorkeakoulun opiskelijat ovat WhereToGo:n loppukäyttäjiä. Vapaita luokkia opiskelijat yrittävät löytää usein koulupäivänsä aikana ja WhereToGo:n kaltainen sovellus nopeuttaisi vapaiden tilojen tarkistusta. Erityisesti uudet tai toisilla koulutaloilla vierailevat opiskelijat voivat hyödyntää reitin näyttävää sovellusta suunnistaessaan luokkatiloihin. Opettajan paikannusominaisuus helpottaa opettajien tavoittamista koulutalon sisällä.

#### Käyttötapauskaavio ja käyttäjäskenaariot

1. käyttötapaus: Opiskelijan tavoitteena on löytää vapaa luokka koulurakennuksessa - hän käynnistää sovelluksen, sovellus määrittää opiskelijan sijainnin - sovelluksen käynnistyttyä yleisnäkymänä on lista koulun luokista - luokkien nimet on kirjattu väreillä, joista selviää statukset (vihreä = vapaa luokka, keltainen = vapautumassa oleva luokka) - luokan nimeä painettaessa ilmestyy koulun kartta ja lyhin reitti luokkaan. Sovelluksessa on hakupalkki, jonka avulla käyttäjä voi hakea luokkaa tai opettajaa.
2. käyttötapus:  Opiskelijan tavoitteena on etsiä opettajaa - hän käynnistää sovelluksen, sovellus määrittää opiskelijan sijainnin - sovelluksen käynnistyttyä yleisnäkymänä on lista koulun luokista - hakupalkkiin opiskelija kirjottaa opettajan nimen - jos opettaja on läsnä ja hän on sallinut paikannuksen, näkyy hänen sijaintinsa kartalla.


[Next: Järjestelmäarkkitehtuuri](https://github.com/sannakas/ohjelmistotuotanto_2014_rakenne/blob/master/4_jarjestelmaarkkitehtuuri.md)



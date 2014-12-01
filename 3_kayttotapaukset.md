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
![kayttotapaus]()

1. käyttötapaus: Opiskelijan tavoitteena on löytää vapaa luokka koulurakennuksessa. Hän käynnistää sovelluksen, ja sovellus määrittää opiskelijan sijainnin. Sovelluksen käynnistyttyä yleisnäkymänä on lista koulun vapaista ja vapautuvista luokista. Luokkien nimet on kirjattu väreillä, joista selviää luokkien statukset (vihreä = vapaa luokka, keltainen = vapautumassa oleva luokka). Luokan nimeä painettaessa näkymä vaihtuu koulun karttaan, johon piirtyy lyhin reitti opiskelijan sijainnista valittuun luokkaan. Sovelluksessa on myös hakupalkki, jonka avulla käyttäjä voi hakea luokkaa tai opettajaa. Hakupalkkia on mahdollista käyttää kaikissa näkymissä.
2. käyttötapaus: Opiskelijan tavoitteena on etsiä opettaja koulurakennuksessa. Hän käynnistää sovelluksen, ja sovellus määrittää opiskelijan sijainnin. Sovelluksen käynnistyttyä yleisnäkymänä on lista koulun luokista. Näkymän alalaidassa on hakupalkki, johon opiskelija kirjoittaa haettavan opettajan nimen. Jos opettaja on läsnä ja hän on sallinut paikannuksen, näkyy hänen sijaintinsa kartalla. Näin opiskelija näkee opettajan sijainnin, ja hän voi lähteä tavoittelemaan opettajaa.
3. käyttötapaus: Opettaja määrittää itsensä paikallaolevaksi, jolloin opiskelijalla on mahdollisuus etsiä ja paikantaa hänet sovelluksen avulla.


[Next: Järjestelmäarkkitehtuuri](https://github.com/sannakas/ohjelmistotuotanto_2014_rakenne/blob/master/4_jarjestelmaarkkitehtuuri.md)



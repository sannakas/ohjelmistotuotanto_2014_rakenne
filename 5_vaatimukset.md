## Vaatimukset 

* Kuvaile tänne funktionaaliset ja ei-funktionaaliset vaatimukset
* Funktionaaliset vaatimukset
  * Tarkentavat käyttötapauksia
* Ei-funktionaaliset vaatimukset
  * Esim käytettävyyteen, tietoturvaan, tehokkuuteen, skaalautuvuuteen, hintaan ja prosessimalliin liittyvät vaatimukset
* **Muista esittää vaatimukset jäljitettävässä muodossa, yksiselitteisesti**
* Keskeinen tapa (erityisesti ei-funktionaalisiin vaatimuksiin) yksiselitteisille kuvauksille on vaatimusten **mitattavuus** (software metrics)


pohdittavaa
* kuinka taata järjestelmän helppokäyttöisyys?
* kuinka taata järjestelmän luotettavuus? Listaa mahdolliset 
järjestelmävirheet ja kuinka niistä toivutaan
* järjestelmälläsi on paljon käyttäjiä, kuinka taata että 
järjestelmässä on riittävästi tehoja? Millaisia metriikkoja 
käyttäisit?

Mitä muita ei-funktionaalisia vaatimuksia olisi syytä kuvata?
Millaisia metriikkoja käyttäisit, jotta vaatimukset ovat 
riittävän yksiselitteisiä?

--

#### Funktionaaliset vaatimukset

Seuraavissa taulukoissa on kuvattu toiminnalliset vaatimukset, jotka liittyvät jokaiseen käyttötapaukseen yleisesti. Lisäksi jokaiselle käyttötapaukselle on listattu omat toiminnalliset vaatimukset. Tavoitteena on ollut kuvata millaisia ominaisuuksia järjestelmältä odotetaan erilaisissa käyttötapauksissa, jotta sitä olisi mahdollisimman helppo käyttää ilman ongelmia.

|								1. Yleiset toiminnalliset vaatimukset														|
|-----------------------------------------------------------------------------------------------------------------------|
|		Järjstelmään on pystyttävä kirjautumaan koulun käyttäjätunnuksilla												|
|		Järjestelmästä poistutaan kirjautumalla ulos																	|
|		Kirjautuminen onnistuu ainoastaan koulun tunnuksilla 															|
|		Sovellus on ilmainen, ja se ladataan sovelluskaupasta															|
|		Järjestelmä toimii kaikilla yleisimmillä käyttöjärjestelmillä													|


|								2. Vapaiden luokkien etsiminen															|
|-----------------------------------------------------------------------------------------------------------------------|	
|		Järjestelmän on tunnistettava käyttäjä, sekä määritettävä hänen sijainti										|
|		Järjestelmän on tulostettava käyttäjälle lista vapaista ja vapautuvista luokista 								|
|		Järjestelmän on piirrettävä reitti käyttäjän sijainnista valittuun luokkaan										|
|		Hakupalkin avulla on oltava mahdollista etsiä opettajaa tai luokkaa nimen perusteella							|
|		Järjestelmässä on mahdollisuus palata yleisnäkymään nappia painamalla											|
|		Järjestelmän on myös osattava näyttää missä kerroksessa rakennuksessa liikutaan									|
|		Lisäksi järjestelmässä on mahdollisuus saada reitti näkyviin käyttäjän sijainnista varattuna olevaan luokkaan	|
										


|								3. Opettajan paikantaminen ja etsiminen koulurakennuksessa								|
|-----------------------------------------------------------------------------------------------------------------------|
|		Järjestelmään on voitava kirjautua opiskelijatunnuksilla														|
|		Järjestelmän on tunnistettava käyttäjä, sekä määritettävä hänen sijainti										|
|		Yleisnäkymässä (alkunäytössä) on oltava hakupalkki, johon käyttäjä voi kirjoittaa haettavan opettajan nimen		|
|		Opettajan sijainnin määritettyä, järjestelmän on piirrettävä reitti käyttäjän sijainnista opettajan sijaintiin	|
|		Järjestelmässä on mahdollisuus palata yleisnäkymään nappia painamalla											|



|								4. Opettaja sallii/estää paikannuksen													|
|-----------------------------------------------------------------------------------------------------------------------|
|		Opettajalla mahdollisuus kirjautua tunnuksillaan järjestelmään													|
|		Järjestelmän on tunnistettava käyttäjä, sekä määritettävä hänen sijainti										|
|		Alkunäkymässä opettajalla on mahdollisuus valita pystyykö hänet paikantamaan									|




																	
#### Ei-funktionaaliset vaatimukset

Tässä osassa kuvataan järjestelmän ei-funktionaaliset vaatimukset, jotka ovat yhteisiä kaikissa käyttötapauksissa

- Käyttäjällä tulee olla käytössä mobiililaite tai tablet, jossa on mahdollisuus wifi-yhteyteen
- Laitteessa tulee olla käyttöjärjestelmä, joka tukee sovellusta
- Koulun wifi-yhteyden tulee olla kokoajan päällä, jotta paikannus onnistuu
- Järjestelmän nappien tulee olla sopivan kokoisia, jotta helppokäyttöisyys on varmaa
- Luotettavuuden lisäämiseksi järjestelmä testataan kunnolla ennen julkaisua
- Jokaisen päivityksen jälkeen järjestelmä testataan ennen käyttöönottoa
- Ulkoasun tulee olla selkeä sekä miellyttävä

[Next: Käyttöliittymä](https://github.com/sannakas/ohjelmistotuotanto_2014_rakenne/blob/master/6_kayttoliittyma.md)
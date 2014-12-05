##  Järjestelmäarkkitehtuuri

* Pyri kuvailemaan tässä luvussa järjestelmäarkkitehtuuri yleisellä tasolla
= Korkean abstraktiotason yleiskuvaus
* Mitä komponentteja järjestelmään tarvitaan jotta se pystyy palvelemaan määritettyjä käyttötapauksia?
= Järjestelmän pääkomponentit ja niiden toiminnallisuuksien määrittely 

-- 

#### Yleisesti

Järjestelmäarkkitehtuurin kuvauksessa esitellään toimintoineen sellaiset sisäiset loogiset elementit, jotka sovellus tarvitsee toteuttaakseen vaatimusmäärittelyssä osoitetut vaatimukset. Alla olevassa kuvassa on nähtävissä yleiskatsaus WhereToGo-sovelluksen järjestelmäarkkitehtuurista.

![jarjestelma_arkkitehtuuri](j_arkkitehtuuri.png)

#### Tarvittavat komponentit tarkemmin

* Käyttöliittymä
* Karttakomponentti (karttakuvat, valitun tilan maalaus ym.. )
* Sisätilapaikannuskomponentti (tarvitsee puhelimen keräämät wlan-signaalivoimakkuudet ja antaa sijaintitiedot)
* Autentikointikomponentti (varmistetaan oikeudet, haetaan vapaat luokkatilat, ...)
* Kirjautumistiedot (opettajan näkyvyys-status tallennetaan)

[Next: Vaatimukset](https://github.com/sannakas/ohjelmistotuotanto_2014_rakenne/blob/master/5_vaatimukset.md)
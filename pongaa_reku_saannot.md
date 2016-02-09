## Pongaa Reku pelin säännöt V0.1

Ohessa kasa kortteja ja alla karkea selitys, mitä jokaisen kortin kohdalla on tarkoitus huomioida.

Peli on kehitysvaiheessa ja se ei edusta vielä täydellisyyttä. Pyrin kehittämään sitä kurssin aikana ja sen pohjalta.

PELIN TAVOITE:

* Oppia tunnistamaan tärkeitä ohjelmiston määrittelyyn liittyviä termejä/käsitteitä
* Oppia keskustelmaan oleellisista asioista, jotka vaikuttavat ohjelmiston/palvelun määrittelyyn & suunnitteluun
* Oppia tulkitsemaan olemassa olevia vaatimusmäärittelyjä ?


Kuva1: Tässä kokoelma erilaisia käsitteitä.


![](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/images/bongaa-reku-suomeksi1.jpg)

Kuva2: Tässä kokoelma erilaisia käsitteitä.

![](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/images/bongaa-reku-suomeksi2.jpg)


# Vaatimusten eri muotoja

* Mikä on vaatimus ?

Ohjelmistotekniikassa puhutaa yleisesti vaatimuksista (Requirements). Vaatimusten avulla tarkennetaan ohjelmistoon, ominaisuuteen tai palveluun liittyviä toimintoja tai rajoituksia.

* Millainen on vaatimus ?

Vaatimus on yleisesti muotoa esim. 

* _Käyttäjän on mahdollista kirjauta palveluun käyttäen Facebook-tunnusta_
* _Järjestelmän X käynnistyminen saa kestää maksimissaan 5 minuuttia_ 
* _Salasanassa on käytettävä vähintään MD5-tason salausta_
* _Palvelun X kaatuessa se palautetaan automaattisesti toimintaan vikaa edeltäneeseen tilaan_

Tärkeää on huomata, että vaatimus käsittelee vain yhtä asia kokonaisuutta! Alla olevassa vaatimuksessa on periaateessa kaksi erillistä. Usein ne myös johtavat useampaan uuteen

_Järjestelmän X sammuttaminen saa kestää 2 minuuttia ja sammuessaan palvelu lähettää tekstiviestin administraattorille_

voisi johtaaa useampaan vaatimukseen => 

* _Järjestelmän X sammuttaminen saa kestää 2 minuuttia_
* _Järjestelmän X sammuttamisesta voidaan lähettää tekstiviesti_
* _Järjestelmän X tilatieto voidaan lähettää tekstiviestinä_
* _Järjestelmän X tilatieto voidaan lähettää sähköpostina_
* _tilatieto palvelun vastaanottajan osoite voidaan asettaa käyttöliittymässä Y_

Tärkeä tarkistus tapa on miettiä mielessä testi, joka voisi tarkistaa onko kyseinen vaatimus toteutettu ohjelmistossa/palvelussa.

Pelkkä vaatimus lauseena ei aina riitä, vaan  vaatimus pyritään luokittelemaan eri vaatimustyypien avulla:


* toiminnalliset vaatimukset
* ei-toiminnaliset vaatimukset

Vaatimustyypeistä oleellisin on ehkä ns. _toiminnallinen vaatimus_, joka nimensä mukaisesti kuvaa haluttua toimintaa joka halutaan suunniteltuun ohjelmistoon/palveluun/järjestelmään.

Toiminnallisuus kannataa ajatella vain yksinkertaisena lauseena "Käyttäjä voi tarvitessaan generoida PDF-raportin viime kuun ostoksista", joka on siis toiminnallinen vaatimus.

Vaatimukseen liitettävä testi voisi olla esim. "Generoida raportti. Tarkista tuleeko ulos PDF tiedosto, joka sisältää todellisen ostoslistan" 

Ei-Toiminnallisen (eli laadullisen) vaatimuksen suhde toiminnalliseen vaatimukseen. Ei-toiminnallisen vaatimuksen suhde tuntuu hieman hankalalta ymmärtää, koska se sisältää useita eri tyyppejä:

* tehokkuus (Performance)
* Kuormitettavuus (Load)
* Laajennettavuus/skaalautuminen (Scalability)
* palautusmiskyky (Recovery)
* ylläpidettävyys (Maintainablity)
* tietoturvallisuus (Security)
* ja muitakin löytyy...


Mietitään vielä PDF-raportin generointia...

Tehokkuus näkökulmasta vaatimus voisi olla "Ostoslistan generointi PDF-muotoon saa kestää (esim. Mac Book Air-kannettavassa) koneessa minimissään 5 sekuntia"

Skaalautumis näkökulmasta:

"Ostoslistan generointi PDF muotoon täytyy onnistua yhtäaikaisesti 1500 käyttäjält"ä










Ominaisuuden suhde vaatimuksiin..

=> Aiemmin mainituista vaatimuksista voi osoittaa uusia ominaisuuksia/osa-alueita esim. "tilatieto-viestipalvelu" ja "palveluhallinta"

Näitä tunnistettuja osa-alueta voidaan nimet ominaisuuksina

Esim. 

_Ominaisuus "Tilatieto-viestipalvelu"_

Toiminnallisia vaatimuksia ovat: 

* _Järjestelmän X tilatieto voidaan lähettää tekstiviestinä_
* _Järjestelmän X tilatieto voidaan lähettää sähköpostina_
* _tilatieto palvelun vastaan ottajan osoite voidaan asettaa käyttöliittymässä Y_

Ominaisuus "Palvelunhallinta"

Toiminnallisia vaatimuksia:

* _Salasanassa on käytettävä vähintään MD5-tason salausta_
* _Palvelunhallinan tilatietoa voidaan lähettää viestinä palvelun valvojalle_
* _Palvelunhallinnan on hyödynnettävä tilatieto-palvelua_

Ei-Toiminnallisia vaatimuksia olisivat  

* _Järjestelmän X sammuttaminen saa kestää 2 minuuttia_
 





## Asiakkuus & tilaaja tason vaatimukset (Needs)

Asiakas voi esittää yleensä huomattavasti yleisempiä toiveita. Näitä kuvataa usein asiakkaan tarpeina (Needs)
On tärkeää kirjata asiakkaan tarpeet ja johtaa niistä virallisempia vaatimuksia esim.

Asiakkaan tarve/toive: _Asiakaan mielestä google tunnusten käyttö helpottaisi kirjautumista ko. palveluun_ -> Vaatimusmuodossa _ X on mahdollista kirjautua käyttäen google-käyttäjätunnusta.


### Asiakas vaatimus (Customer requirement)

* Mitä asiakas toivoo tuotteella tekevänsä ?

### Liiketoiminta vaatimus (Business requirement)

* Mikä on liiketoiminnan tavoite ?
* Miksi jokin ominaisuus on tärkeä ?

# Ominaisuus (Feature)

* 



# Toiminnalliset vaatimukset (Functional Requirements)

## Toiminnallinen vaatimus 

* Mitä toimintoja ohjelmistolla/palvelulla voidaan tehdä?
* Onko toiminto itse asiassa ominaisuus ? Kannattaa keskittyä ominaisuuden toiminnallisuuksiin

# Ei-Toiminnalliset (Laadulliset) vaatimukset


## Tehokkuus (Performance)

* sopivia kysymyksiä
 

## Kuormitettavuus (Load)

* Miten paljon palvelua on kyettävä kuormittamaan ja samalla säilyttämään riittävä palvelukapasiteetti?


 
## Käytettävyys (Usability)

* Millainen käytettävyys tuotteella/toiminnalla on oltava? 
* Onko jotain vertailukohtaa tarjolla?
* Millä kriteereillä käytettävyyttä on kehitettävä? Onko asiakasryhmiä, joille käytettävyys on huomioitava erikseen?


## Laajennettavuus (Scalability)

* Miten laajennettavuus on otettava huomioon? 
* millaista palvelun käyttö on ? Piikki kuormia? esim. joulumyynti ?
* Miten paljon asiakkaita voi olla tulevaisuudessa? 
* Onko tarve laajentaa palvelua?

## Palautuvuus (Recovery)

## Ylläpidettävyys (Maintainablity)

* Miten ohjelmisto on toteutettava, että se olisi ylläpidettävä? Miten dokumentoinnissa pitää huolehtia ylläpidettävyys?

## Tietoturva (Security)

* Onko joitain mitä tietoturvan näkökulmasta on huomioitava ? standardi ? Suojausluokat ? etc.

## Käyttöturvallisuus (Safety)

* sopivia kysymyksiä



# Agile /ketterä vaatimusmäärittely & muut 


## User Story

* sopivia kysymyksiä

## Käyttötapaus (Use Case)

* sopivia kysymyksiä




# Järjestelmä vaatimus (System Requirment)

*





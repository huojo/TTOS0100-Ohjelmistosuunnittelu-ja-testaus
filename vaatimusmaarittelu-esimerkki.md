
## XYZ-palvelun/ohjelmiston vaatimusmäärittely



Dokumentin versionumero - keksi sopiva



### Sisältö

Sisällysluettelo tähän





### Materiaalin luokittelu

Kuka saa nähdä ?

### Johdatus

Mikä on tämän dokumentin tehtävä? Mihin se liittyy ? 

## Tärkeää tietää

Oleellista lukijalle ?

### Oikeudet

Kuka omistaa dokumentin?

### Priorisointi 

Miten taulukoita luetaan

P1 = Erittäin tärkeä, 
P3 = Oleellinen 
P5 = Triviaali

### Lyhyt tuote/palvelukuvaus

Mitä määritetyltä palvelulta odotetaan? lyhyesti

### Tilaaja

Kuka on tilaaja, yhteistiedot ?



### Toimittaja

Kuka on toimittaja, yhteistiedot ?

### Aikataulu



| Etappi | Alkaa | Loppuu | | | 
|:-----:|:-----:|:-----:|:-----:|:-----:|
| Tutustuminen aiheeseen | Tapaaminen 1 | - |  | P3 |
| Sidosryhmien tunnistaminen | Tapaaminene 2 | - |  | P3 |
| Asiakkaan kokemuspolun määrittely | Tapaaminen 3 | - |  | P4 |
| Tärkeimpien käyttötapausten tunnistaminen | Tapaaminen 4 |  | P1 |
| Yleisten vaatimusten kerääminen | Tapaaminen 5 |  | P1 |
| Ominaisuuksien määrittely | Tapaaminen 6 |  | P1 |
| Ominaisuudet ja vaatimukset | Tapaaminen 7 |  | P1 |
| Käyttöliittymä mock |  Tapaaminen 8 |  | P1 |
| Testisuunnittelu | Tapaaminen 9  |  | P1 |
| Vaatimusmäärittelyn korjaukset | Tapaaminen 10  |  | P1 | 
| Vaatimusmäärittelyn luovutus | Tapaaminen 11  |  | P1 | 

## Palvelun/ohjelmiston sidosryhmät ja asiakkaat (Service and customers) 

Asiakasryhmiä tarkastellaan "persoonien" kautta. Jokainen persoona edustaa isompaa otosta kyseisestä ihmisryhmästä.

### Sidosryhmät/Persoonat (Stakeholders)

https://en.wikipedia.org/wiki/Stakeholder_analysis

Kuka on kiinnostunut tuotteesta tai kenellä on sanansa sanottavana liittyen tuotteen kehittämiseen ?

  * [Mungo consulting Oy](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/asiakasprofiilien_esimerkit.md), Palvelun tarjoaja
  * [RahoittajaA](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/asiakasprofiilien_esimerkit.md), yrityksen osakas, Bankoman Oy, osakkeen omistaja 55 %
  * [RahoittajaB](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/asiakasprofiilien_esimerkit.md), Yrityksen osakas, Mauri Bosse, omistaa 5 %
  * [TuotantotiimiA](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/asiakasprofiilien_esimerkit.md), em. yrityksen työntekijät, Kalle, Kille, Pelle ja Pöppö
  * [SuurAsiakasA](https://github.com/JAMK-IT/TT0S0100-software-desing-and-testing/blob/master/asiakasprofiilien_esimerkit.md), NordMan Oy, yritysasiakas
  * Asiakasprofiilit 1-4, kuvattu alla

### Sidosryhmäkartta (Stakeholder map)

![](https://www.lucidchart.com/publicSegments/view/afbaa205-0924-40f8-a0a1-96e281aafcf5/image.png)

### Yleinen palvelun asiakaspolku (General Customer Journey)

![](https://camo.githubusercontent.com/1429ec848bc406a1bc7f38874188e4af03d3ee46/68747470733a2f2f7777772e64726f70626f782e636f6d2f732f6c6f7076357a6a6a337076676261392f757365725f6a6f75726e6579732d30322e706e673f646c3d31)

Käydään läpi asiakaspolku, jossa käytetään nimettyjä sidosryhmien edustajia


### Asiakasprofiilit (Customer Profiles)

  * [Asiakas 1](), Mauno Mainio, 67, eläkeläinen, Vierumäki, kotosin Pohjois-Savosta (Matematiikan opettaja)
  * [Asiakas 2](), Riku Rikas, 30, IT Yrittäjä, asuinpaikka tuntematon, kotoisin nomands land 
  * [Asiakas 3](), Siiri Koikkalainen 99, suurmummo, Hankasalmi, (Sokea)
  * [Asiakas 4](), John Rambu, 55, tuntematon, Helsinki, (Bad Man)
  
### Asiakaspolku(Customer Journey Maps)

Millainen on yleinen asiakaspolku. Kuvaa esimerkiksi miten tuotetta käytetään?




## Palvelun osa-aluejako (Service Domain areas)

Millaisiin osa-alueiseiin voidaan suunniteltu palvelu jakaa. Alla esimerkkejä

Onko olemassa erilaisia tuoteversioita eri ympäristöihin, mitä?

Tuotteesta on saatavilla seuraavat versiot:


  * Työpöytäversio ?
  * Mobiiliversio ?
  * Kenttäversio  

ohjelmiston osa-alueita ?

  * Hallintapaneeli ?
  * Tietokanta-palvelut ?
  * Käyttöliittymät ?
  * Autentikointi ?
  * Laskutus ?


## Tärkeimmät piirteet/ominaisuudet (Features)

* [Ominaisuus 1 - linkki kuvaukseen]()
* [Ominaisuus 2 - linkki kuvaukseen]()
* [Ominaisuus 3 - linkki kuvaukseen]()
* [Ominaisuus 4 - linkki kuvaukseen]()
* [Ominaisuus 5 - linkki kuvaukseen]()


## Käyttötapaukset

### Tärkeimmät käyttötapaukset  (Yleiset käyttötapaukset)

Tässä vain kaksi tärkeintä. 

* [Palveluun rekisteröityminen](kayttotapaus-pohja)
* [Salasanan vaihto](kayttotapaus-pohja)


## Riskihallinta

## Tunnistetut riskit (Risks)

| Vaatimus ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti | 
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|RISK001| Käyttäjämäärän äkillinen lisääntyminen, esim poikkeustilanteen aikana | - | P1 |
|RISK002| Palvelun käytettävyys heikkenee kovan kuormituksen aikana | Toiminnnallinen |  | P5 |
|RISK003| Heikon verkkoyhteyden vaikutus palvelun käyttöön | Toiminnnallinen | - | P3 |

## Palveluun liittyvät yleiset toiminnnalliset vaatimukset (Functional Requirements)

| Vaatimus ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti | 
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|VAT0001| Palvelun täytyy toimia Android versiosssa 4.x alkaen | Toiminnnallinen | "ASAP"-tuotantotiimi | P1 |
|VAT0002| Palvelun täytyy toimia Windows Phonessa | Toiminnnallinen |  "ASAP"-tuotantotiimi | P5 |
|VAT0003| Palvelun täytyy toimia iPAD 3> | Toiminnnallinen |  "ASAP"-tuotantotiimi | P3 |

## Palveluun liittyvät laadulliset vaatimukset (Non-Functional Requirements)

| Vaatimus ID | Kuvaus | Tyyppi | Osa-alue | Vastuullinen | Prioriteetti | 
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|VAL0201| Palvelun pitää skaalatua hetkellisesti 1000 käyttäjälle | Skaalautuvuus | "ASAP"-tuotantotiimi | P1 |
|VAL0202| Palvelun saatavuus on oltava 99.1 % | Stabiilisuus |  "ASAP"-tuotantotiimi | P5 |
|VAL0203| Käyttäjän tiedot on salattavat | Tietoturva |  "ASAP"-tuotantotiimi | P3 |

  * [Esimerkkejä tietoturvavaatimuksista](https://confluence.csc.fi/display/oppija/10.+Tietoturvavaatimukset)

### Käytettävyys


## Käyttöliittymä prototyyppi

Palveluun liittyvä yleinen prototyyppi (ei ominaisuuskohtainen)

### Prototyypin esittely
### Tarvittavat tiedot prototyypin tarkasteluun
## Linkki prototyyppiin
## Yhteyshenkilö


### Palvelun karkea sijoittelunäkymä (Deployment diagram)

![](https://www.lucidchart.com/publicSegments/view/6f727a36-f880-4dca-b5ac-133f6f860697/image.png)

##  Julkaisusuunnitelma ja priorisointi
### Priorisointi 
### Toiminnallisuudet ja toteuttamisjärjestys

## Standardit ja lähteet
### Lähteet
### Standardit

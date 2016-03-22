### Testitapaus ID  : TCID1234

  * Testitapauksen suunnittelija: NarsuMan
  * Testitapauksen hyväksyjä: Tarhytti
  * Luontipvm : 26.06.2015

### Päivityshistoria

* versio 1.1 - 22.03.2016 - Tarhytti - pohjaan tehty kosmeettisia muutoksia
* versio 1.0 - 24.12.2015 - Tarhytti - testitapaus hyväksytty
* versio 0.1 - 26.06.2015 - Narsuman - testitapaus luotu

### Testin kuvaus

esim: Tarkista että kirjautumiseen kuluva aika ei ylitä 3 sekunnin rajaa alle palvelun ollessa kuormitettu alle 80 % 

### Testin tavoite

esim: Tarkistetaan, että palvelun kuormitusaste ei vaikuta liiaksi kirjautumiseen käytettävään aikaan. Kirjatuminen testataan palvelun ollessa eri kuormitusasteilla. Mittaus tehdään käyttäjärajapinnasta.

### Linkit

  * Vaatimus: [REQID10202]() Asiakkaan kirjautumispyyntö palveluun saa kestää normaalisti korkeintaan (3) sekuntia   
  * Käyttötapaus: [UC12345]()
  * Ominaisuus: [XXXXX]()

### Alkutilanne (Pre-state): 

esim: Palvelu saavutettavissa, Kuormitusgeneraattori asennettu, kirjautumistunnus luotu, ajanmittaus mahdollista

### Testiaskeleet (Test Steps)

esim
 1. Aseta palvelun kuormitus 30 prosenttiin
 2. Mittaa kirjaantumiseen kuluva aika
 3. Kirjaudu ulos palvelusta
 4. Toista testiaskeleet 1-3 kolme kertaa
 5. Laske kirjautumisaikojen keskiarvo

Toista testiaskeleet palvelun kuormituksilla 50% ja 80%.

## Huomioitava testin aikana

esim
 * *Huomioi:* esim. Kirjautumisen aikana näyttö ei välky
 * *Huomioi:* esim. Lokalisaatio ja kellon aika ovat samat kuin käyttäjän aiemin valitsemat.
 * *Huomioi:* esim. Tervetuloviesti ilmestyy välittömästi (alle 1s)

## Testin lopputilanne (End-State)

esim.
 - Kirjaantumisaikojen keskiarvo ei ylitä 3 sekuntia
 - jokainen kirjaantuminen onnistui

### Testin "tuomio"/tulos (Pass/Fail Criteria):

PASS Aikaa kului < 5 sekuntia
FAIL Aika > 5 sekuntia

 

Muita esimerkkejä:



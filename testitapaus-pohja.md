## Esimerkki perinteisestä testitapauksesta:



### Testitapaus ID  : TCID1234

  * Testitapauksen suunnittelija: NarsuMan
  * Date : 26.06.2015

### Testin kuvaus(Topic):  Tarkista kirjautumiseen kuluva aika palvelun ollessa kuormitettu 50 % 
  * Vaatimus/Syy: (VaatimusREQID10202)- Asiakkaan kirjautumispyyntö palveluun saa kestää normaalisti korkeintaan (5) sekuntia   
  * Alkutilanne (Pre-state): Palvelu saavutettavissa, Kuormitusgeneraattori asetettu 50 %iin. Testaajalla käytössä kello ajanottoa varten. 

### Testiaskeleet (Test Steps)

1. Avaa palvelun verkkosivu
1. Nollaa ajanotto (kello)
1. Kirjaudu sisään ja paina enter (käynnistä samalla ajanotto)
1. Odota kunnes palvelun etusivu aukeaa ja näet "Willkommeniah"-viestin
1. Pysäytä kello
1. Kirjaa kulunut aika
1. Kirjaudu ulos palvelusta


## Huomioitava testin aikana

1. *Huomioi:* Kirjautumisen aikana näyttö ei välky
1. *Huomioi:* Lokalisaatio ja kellon aika ovat samat kuin käyttäjän aiemin valitsemat.
1. *Huomioi:* Tervetuloviesti ilmestyy välittömästi


## Testin lopputilanne (End-State)

1. Kirjatumissivu näkyvissä ja uusi käyttäjä voi kirjautua palveluun.

### Testin "tuomio"/tulos (Pass/Fail Criteria):

PASS Aikaa kului < 5 sekuntia
FAIL Aika > 5 sekuntia

 

Muita esimerkkejä:



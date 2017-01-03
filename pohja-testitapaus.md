### Testitapaus ID  : TCID1234

  * Testitapauksen suunnittelija: xxxx
  * Testitapauksen hyväksyjä: xx
  * Luontipvm : 26.0x.20xx

### Päivityshistoria

* versio 0.1 - 26.0x.20xx - Narsuman - testitapaus luotu

### Testitapauksen kuvaus

Mitä pyritään tarkistamaan/testaamaan?

### Lähde testille

Minkä pohjalta testi on suunniteltu?

* Vaatimus: [REQID10202]()  
* Käyttötapaus: [UC12345]()
* Ominaisuus: [Feature00012]()

### Alkutilanne (Pre-state): 

* Mitä pitää olla valmiina ennen testin suorittamista?

### Testiaskeleet (Test Steps)



 1. Aseta palvelun kuormitus | Kuormitus muuttuu asetetuksi |
 1. Mittaa kirjaantumiseen kuluva aika | |
 1. Kirjaudu ulos palvelusta | Palvelusta uloskirjautuminen onnistuu |

esim 2:

| Testiaskel | Odotettu tulos |
| ---------- | -------------- |
| 1. Aseta kosteuden hälytysraja 50%:iin | Hälytysraja muuttuu näytöllä |
| 2. Nosta kosteus yli 50%:in | Järjestelmä lähettää hälytyksen käyttäjälle |
| 3. Laske kosteus alle 50%:in | Järjesteläm lähettää hälytyksen peruutuksen |


### Huomioitava testin aikana

esim
 * *Huomioi:* esim. Kirjautumisen aikana näyttö ei välky
 * *Huomioi:* esim. Tervetuloviesti ilmestyy välittömästi (alle 1s)

### Testin lopputilanne (End-State)

esim 1:
 - Jokainen kirjaantuminen onnistui

esim 2:
 - Järjestelmässä ei ole päällä kosteushälytystä

### Testin "tuomio"/tulos (Pass/Fail Criteria):

esim 1:

PASS Kirjaantumiseen kului aikaa =< 3 sekuntia

FAIL Kirjaantumiseen kului aikaa  > 3 sekuntia

esim 2:

PASS: hälytysrajan pystyi asettamaan ja hälytys lähetettiin määriteltyyn numeroon rajan ylittyessä

FAIL: hälytystä ei lähetetty

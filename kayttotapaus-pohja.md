Käyttötapauskuvaus-pohja

## KÄYTTÖTAPAUKSEN NIMI esim. Asiakastietojen muutos

Yleiskuvaus	Kuvataan lyhyesti mikä on käyttötapauksen tarkoitus/ tehtävä. 
Esim. Käyttäjä lisää, muuttaa tai poistaa tietoja

###Laatija	Kirjataan laatijan nimi.

  * Päiväys / Versio	Kirjataan laatimispäivä ja versio.
  * Prosessi	Kuvataan mihin prosessiin käyttötapaus kuuluu.
  * Esim. Asiakastietojen käsittelyprosessi.
	
### Käyttäjäroolit	Kuvataan käyttötapauksen käyttäjäroolit	Roolin oikeudet

  * rooli 1	esim. käsittelijä	Luku- ja kirjoitusoikeudet
  * rooli 2	esim. toinen järjestelmä	Luku- ja kirjoitusoikeudet
  * rooli 3	esim. pääkäyttäjä	Kaikki oikeudet

### Esitiedot/ehdot	

  * Kuvataan käyttötapauksen esiehdot, kuten esim. mitä järjestelmä tietää, mitä tietoja järjestelmä tarvitsee, mitä pitää olla tehtynä, mitä käyttötapaus olettaa, missä tilassa järjestelmä on, jotta käyttötapaus voidaan suorittaa. 	
  * Esim. Käsittelijä on kirjautunut järjestelmään omilla tunnuksillaan. Käsittelijä on syöttänyt asiakasnumeron järjestelmään. Järjestelmä on hakenut asiakkaan tiedot asiakastietokannasta ja avannut ne käsittelijälle.

### Käyttötapauksen kuvaus

  * 1	Esim. Käsittelijä syöttää ja tallentaa asiakkaan uudet osoitetiedot järjestelmään.
  * 2	Esim. Järjestelmä tarkistaa osoitetietojen oikeellisuuden (muodollinen tarkistus).
  * 3	Esim.Järjestelmä hakee yleisrekisterijärjestelmästä (esim VTJ) asiakkaan osoitetiedot. Järjestelmä vertailee osoitetietoja.
(P1)
  * 4	Esim. Järjestelmä tallentaa hyväksytyt osoitetiedot kantaan ja ilmoittaa käyttäjälle tietojen tallennuksen onnistumisesta.
  * 5	

### Poikkeukset
 
   * P1	

Esim. P1 Järjestelmä ilmoittaa käyttäjälle, että tiedoissa on eroja. Järjestelmä näyttää käyttäjän syöttämät ja yleisrekisterijärjestelmästä saadut tiedot rinnakkain käsittelijän ruudulla.
HUOM! Poikkeukset numeroidaan ja kukin sijoitetaan omaan ”lokeroon” ”, jotta niihin voidaan viitata tekstikuvauksesta.(Esim. P1) 
Poikkeukseen kirjoitetaan vain poikkeus, ei tilannetta/käsittelysääntöä, joka johtaa poikkeukseen, ne on kirjoitettu tekstikuvaukseen tai tarvittaessa käsittelysääntöön. 

Oletusarvoisesti käyttötapauksen suoritus keskeytyy poikkeukseen. Jos ei, siitä on mainittava.

  * P2	
	
### Lopputulos	

Kuvataan mikä on käyttötapauksen lopputulos. Esim. Asiakkaan tietoja on päivitetty. Tiedot on tallennettu tietokantaan. Asiakkaalle on lähetetty vahvistus tietojen päivittämisestä.
Muut vaatimukset v1	Kuvataan mitä muita vaatimuksia käyttötapaukselle asetetaan toiminnallisten vaatimusten lisäksi.
Esim. Asiakastietojen haku perustietorekisteristä ei saa kestää yli 25sek.
v2	
v3	

### Käyttötiheys	Kuvataan, kuinka usein käyttötapausta suoritetaan..

Esim. Muutoksia tehdään n.100/päivässä

### Muuta	Kuvataan muita käyttötapaukseen liittyviä oleellisia tietoja, kuten avoimia asioita, viittauksia käytettäviin koodistoihin jne.

# htmx-projekti
Käyttöohjeet:
  1. Lataa git repo koneellesi.
  2. Lisää kansio VS Codeen.
  3. Kirjoita NPM install
  4. Nyt moduulit pitäisi olla ladattu. Voit kokeilla käynnistää serverin komennolla "npm run dev"

Nyt voit testata ohjelmia selaimessa. Osoite on http://localhost:3000/, jonka myös VS Code ilmoittaa.
Sivu koostuu seuraavista toiminallisuuksista: 
  1. Käyttäjät haetaan rajapinnasta. Listan maksimimäärä on yhteensä 5 henkilöä.
  2. Haetaan sää (staattisesti). Sivu hakee tällä hetkellä Tornion sään.
  3. Haetaan käyttäjät rajapinnasta. Tulostetaan nimi, sekä sähköposti. Sivulla on oma hakutoimintonsa, jolla voi käyttäjiä hakea.
  4. Muunnetaan lämpötila fahrenheitistä celsiukseen.
  5. Tarkistaa, että onko sähköpostiosoite varmasti kirjoitettu oikein (vaatii siis @-merkin)
  6. Lisätään taskilistalle asioita. Koostuu otsikosta, kuvauksesta ja deadlinesta.

Tehtävän tekeminen on mielenkiintoinen. HTMX-kirjastolla on selkeästi potentiaalia kilpailla Javavscriptin kanssa, vaikka serverin puolella JS:ää on käytetty täysin. En osaa arvioida, että voisiko HTMX-projektin kaltaiset sivut olla resurssiensäästön kannalta tehokkaampia, mutta ainakin tämä on helpompi tapa lähteä opetteleen webohjelmointia aloittelijan (kuten allekirjoittaneen) näkökulmasta. HTMX on myös yksinkertainen käytettävän kielen vuoksi. Pienelläkin vaivalla voidaan saada aikaan todella vaikuttavia, dynaamisia verkkosivuja. Uskoisin, että voisi olla käytössä hyvinkin API:en puolella. HTMX ei kuitenkaan ole täydellinen, sillä todellakin on varjopuolia. Lähinnä, miksi HTMX ei vältämättä tule menestymään, johtuu siitä, että koodia on todella vaikea ylläpitää, ja se johtuu yksinomaan HTML-kielen ulkoasusta. On  diviä, headia, bodya sekä kaikkia muita luokkia. Näiden paljous voi aiheuttaa sekaannusta ja itselleni tekee koodista vaikealukuista. 

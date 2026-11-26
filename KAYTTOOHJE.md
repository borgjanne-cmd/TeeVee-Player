# TeeVee Player – Käyttöönotto- ja pikaopas

Yksinkertainen opas oman IPTV-soittolistan lisäämiseen, hallintaan ja TeeVee Playerin käyttöön.

---

## 1. Sovelluksen käynnistäminen

1. Kaksoisnapsauta työpöydällä olevaa **TeeVee Player** -kuvaketta (tai etsi ja avaa **TeeVee Player** Windowsin Käynnistä-valikosta).
2. Sovellus avautuu suoraan päänäkymään ja lataa aiemmin tallennetun soittolistasi.

---

## 2. Soittolistan lisääminen ja tallentaminen

1. **Avaa lisäysikkuna:**
   - Napsauta vasemman yläkulman sinistä **`+`** -painiketta (*Lisää soittolista*).

2. **Valitse soittolistan lähde (välilehti):**
   - **M3U URL:** Valitse tämä, jos sait palveluntarjoajaltasi linkin (esim. `http://.../get.php?...` tai `.m3u8`). Liitä linkki kenttään.
   - **Tiedosto (.m3u):** Valitse tämä, jos latasit soittolistatiedoston koneellesi. Paina **Selaa...** ja valitse tietokoneeltasi löytyvä `.m3u`- tai `.m3u8`-tiedosto.
   - **Xtream Codes:** Valitse tämä, jos sinulla on palvelimen osoite, käyttäjätunnus ja salasana. Syötä tiedot niille varattuihin kenttiin. (Mukana on älykäs Xtream API -tuki, joka toimii suoraan myös palvelimilla, jotka estävät tavallisen M3U-latauksen).

3. **Viimeistele asetukset:**
   - Anna soittolistalle haluamasi nimi (esim. *Oma IPTV*).
   - Valitse mitä sisältöjä tuodaan: **Live-TV**, **Elokuvat** ja/tai **Sarjat**.
   - (Halutessasi voit syöttää myös erillisen XMLTV/EPG-ohjelmaoppaan verkko-osoitteen).

4. **Tallenna:**
   - Paina ikkunan alareunasta **"Tallenna ja tuo kanavat"**.
   - Sovellus lataa kanavat, luo kategoriat ja tallentaa ne paikalliseen SQLite-tietokantaan. Latauksen jälkeen kanavalistasi avautuu heti käyttöön!

---

## 3. Soittolistojen ja asetusten hallinta

Yläpalkin luettelokuvakkeesta (**Soittolistat ja asetukset**) aukeaa hallintakeskus:
- **Aktiivisen listan valinta:** Voit tallentaa useita soittolistoja ja vaihtaa katseltavaa listaa lennosta yhdellä klikkauksella.
- **Päivitä kanavat:** Voit päivittää soittolistan ja kanavat uudelleen palvelimelta milloin vain.
- **Poista soittolista:** Voit siivota vanhentuneet soittolistat pois.

### Kanavien ja ryhmien muokkaus (Järjestely, piilotus ja lapsilukko)
Hallintaikkunan toiselta välilehdeltä (**Kanavien ja ryhmien muokkaus**) voit räätälöidä kanavalistasi juuri mieleiseksesi:
- **Järjestyksen muuttaminen:** 
  - **Raahaamalla hiirellä:** Ota kiinni rivin vasemmassa reunassa olevasta 6-pisteen kahvasta (⠿) ja vedä kohde haluamaasi kohtaan. Kun viet kohteen listan ylä- tai alareunaan, lista rullaa automaattisesti mukana.
  - **Siirtopainikkeilla:** Voit käyttää käteviä pikanappeja:
    - **`⇤`**: Siirrä suoraan listan kärkeen (ensimmäiseksi)
    - **`▲`**: Siirrä yksi pykälä ylöspäin
    - **`▼`**: Siirrä yksi pykälä alaspäin
    - **`⇥`**: Siirrä suoraan listan loppuun (viimeiseksi)
  - **Vierityspalkki ("hissi"):** Pitkillä tuhansien kanavien listoilla voit tarttua oikean reunan hissiin ja vetää suoraan haluamaasi kohtaan.
- **Uudelleennimeäminen:** Napsauta rivin oikean reunan **kynäkuvaketta** antaaksesi kanavalle tai ryhmälle oman selkeän nimen.
- **Piilottaminen:** Napsauta **silmäkuvaketta** piilottaaksesi turhat kanavat tai ryhmät päänäkymästä. Piilotetut kohteet saa esiin "Näytä vain piilotetut" -valinnalla.
- **Lapsilukko (PIN-koodi):**
  - Aseta 4-numeroinen koodi välilehdellä **Lapsilukko (PIN)**.
  - Napsauta minkä tahansa kanavan tai ryhmän **lukkokuvaketta** asettaaksesi lapsilukon. Lukitun kanavan katselu vaatii PIN-koodin syöttämisen.
- **Oletusten palautus:** "Palauta oletukset" -painike palauttaa alkuperäiset nimet, järjestyksen ja näkyvyyden.
- *Huom! Kaikki tekemäsi mukautukset tallennetaan paikalliseen tietokantaan, ja ne säilyvät täysin ennallaan myös soittolistan taustapäivitysten yhteydessä.*

---

## 4. Sovelluksen käyttö ja katselu

### A. Sisällön selaaminen ja kanavan valinta
- **Sisältötyypit:** Valitse vasemman palkin yläreunasta katsottava tyyppi:
  - **Live TV** (suorat tv-kanavat)
  - **Elokuvat** (VOD-elokuvat)
  - **Sarjat** (sarjat kausittain ja jaksoittain)
  - **Arkisto** (Catchup-lähetykset taaksepäin, mikäli palveluntarjoajasi tukee tätä)
- **Kategoriat:** Napsauta kategoriaa (esim. *Urheilu*, *Uutiset*, *Suomi*) rajataksesi näkyviä kanavia.
- **Haku:** Kirjoita hakukenttään kanavan, ohjelman tai elokuvan nimi – hakutulos päivittyy heti reaaliajassa.
- **Toiston aloitus:** Napsauta haluamaasi kanavaa listasta. Lähetys käynnistyy oikeanpuoleisessa toistoikkunassa.

### B. Suosikkikanavat
- Lisää kanava suosikkeihin napsauttamalla kanavan nimen vieressä olevaa **tähtikuvaketta**.
- Paina yläpalkin **tähtipainiketta** nähdäksesi vain suosikiksi merkitsemäsi kanavat.

### C. Toisto ja kuvan säätö
- **Koko ruutu (Full Screen):**
  - Paina **`F11`** tai kaksoisnapsauta videokuvaa siirtyäksesi reunattomaan koko ruudun tilaan.
  - Poistu koko ruudun tilasta painamalla **`Esc`** tai **`F11`**.
- **Äänenvoimakkuus:**
  - Säädä liukusäätimestä tai näppäimillä **`Nuoli ylös`** / **`Nuoli alas`**.
  - Pikamykistys: Napsauta kaiutinkuvaketta tai paina **`M`**.
- **Kuvasuhde:** Voit avata kuvasuhdevalikon toistopalkin painikkeesta (*Oletus*, *16:9*, *4:3*, *16:10*, *21:9*, *Sovita ruutuun*) tai vaihtaa kuvasuhdetta suoraan näppäimellä **`C`**.
- **Live-kanavien vaihto (Edellinen / Seuraava):**
  - Kun katsot suoraa lähetystä (Live TV), toistopalkin kelausnappien paikalla näkyvät **Edellinen kanava** (`|◄`) ja **Seuraava kanava** (`►|`) -painikkeet.
  - Painikkeet selaavat kanavia juuri siinä järjestyksessä kuin olet ne järjestänyt, ja kanavalista rullaa toiston mukana.
  - Elokuvissa ja sarjoissa painikkeet toimivat normaalisti 10 sekunnin pikakelauksena.

### D. Tekstitykset ja ääniraidat
- **Kieliraidat:** Paina toistopalkin **Ääni**-painiketta tai paina **`A`** vaihtaaksesi selostuskieltä.
- **Tekstitykset:** Paina **Tekstitys**-painiketta tai paina **`S`**:
  - **Lähetyksen raidat & Oletuskieli (Oletus):** Valitse lähetyksen oma sisäinen DVB/tekstitysraita tai oletuskieli.
  - **OpenSubtitles-haku:** Jos lähetyksessä ei ole valmista tekstitystä, hae tekstitykset toissijaisella välilehdellä automaattisesti suomeksi tai englanniksi.
  - Säädä tarvittaessa tekstityksen ajoitusta painikkeilla `[-0.5s]` ... `[+0.5s]`.

### E. Monikanavainen ohjelmaopas (Grid EPG)
- **Oppaan avaaminen:** Kun valitset Live TV -näkymässä jonkin kanavaryhmän (esim. *Suomi* tai *Urheilu*), ryhmän otsikkoriville kappalemäärän (esim. *210 kpl*) viereen ilmestyy sininen **kalenterikuvake**. Napsauttamalla sitä ohjelmaopas aukeaa omaan erilliseen työpöytäikkunaansa.
- **Rinnakkainen selaus ja aikataulut:**
  - Yläpalkista voit valita haluamasi viikonpäivän (Tänään sekä seuraavat 6 vuorokautta).
  - Ryhmän kaikki kanavat esitetään rinnakkaisina sarakkeina aikajärjestyksessä.
  - **"Nyt"-pikanappi:** Rullaa näkymän välittömästi parhaillaan meneillään olevien ohjelmien kohdalle.
  - **Esikatselukuvat:** Kuluvan ohjelman kortissa näytetään visuaalinen ohjelmakuva.
  - **Ohjelman lisätiedot (i):** Klikkaamalla ohjelman info-kuvaketta avautuu popup-ikkuna, josta näet koko ohjelmakuvauksen (synopsis) ja tarkat kellonajat.
  - **Kanavan vaihto taustalla:** Kaksoisnapsauttamalla ohjelmaa tai painamalla kanavan otsikon toistopainiketta pääikkuna siirtyy toistamaan kanavaa sulkematta opasikkunaa.
  - **Sujuva selaus:** Voit siirtyä kanavissa sivusuunnassa reunan pikanuolilla (`<` ja `>`), hiiren rullalla tai alalaidan vierityspalkilla.

### F. Kuva kuvassa (Picture-in-Picture) ja kahden lähetyksen rinnakkaistoisto
- **Sivuikkunan avaaminen:** Voit siirtää katseltavan lähetyksen kelluvaan kuva kuvassa -ikkunaan toistopalkin **Kuva kuvassa** -kuvakkeesta. Pääikkuna vapautuu samalla toisen kanavan tai soittolistan katseluun.
- **Aina päällimmäisenä työpöydällä:** Sivuikkuna pysyy muiden ikkunoiden päällä ja sitä voi vapaasti raahata hiirellä yläpalkista minne tahansa työpöydällä tai toiselle näytölle.
- **Koon muuttaminen:**
  - **Hiirellä venyttämällä:** Ota kiinni sivuikkunan oikean alakulman koonmuutoskahvasta (`///`) ja vedä ikkuna haluamaasi kokoon (`360×240` – `1280×800` px).
  - **Pikakoon säädin:** Yläpalkin pikanappi (`⛶`) vaihtaa ikkunan koon yhdellä klikkauksella pienen (`480×330` px) ja kookkaamman (`720×480` px) välillä.
- **Itsenäinen äänenhallinta:** Pääikkunalla ja sivuikkunalla on omat erilliset äänenvoimakkuuden ja mykistyksen säätimet. Sivuikkuna avautuu aina oletuksena mykistettynä, jolloin pääikkunan ääni kuuluu normaalisti ilman sekoittumista.
- **Vaihda päittäin (Swap):** Klikkaamalla sivuikkunan tai pääikkunan yläpalkin **Vaihda päittäin** -painiketta (`⇄` tai näppäin **`S`**) pää- ja sivuikkunan lähetykset vaihtavat paikkaa keskenään saumattomasti ilman katselukohdan keskeytymistä.
- **Pikanäppäimet sivuikkunalle (kun sivuikkuna on aktiivinen):**
  - **`Välilyönti`**: Toisto / Tauko
  - **`M`**: Mykistys päälle / pois
  - **`S`**: Vaihda päittäin pääikkunan kanssa (Swap)
  - **`Esc`**: Sulje sivuikkuna

### G. Google Cast ja Chromecast (Lähetä televisioon)
- **Laitteiden etsintä:** Kun toistat kanavaa, elokuvaa tai sarjaa, napsauta toistopalkin oikeassa yläkulmassa olevaa **Cast-kuvaketta** (lähettimen kuva). Sovellus etsii automaattisesti lähiverkostasi löytyvät Google Cast -laitteet (Chromecast, Android TV, Google TV, Nest Hub).
- **Toiston siirto televisioon:** Napsauta haluamaasi laitetta listasta. Lähetys siirtyy toistumaan suoraan televisioruudulle.
- **Tekstitykset:** Chromecast-suoratoistossa tekstityksen näkyminen vaatii tekstitystiedoston lataamisen OpenSubtitles-palvelusta (toistopalkin **Tekstitys**-painikkeesta). Sovelluksen sisäänrakennettu mediapalvelin muuntaa ladatun tekstityksen automaattisesti Chromecast-yhteensopivaksi (WebVTT) ja synkronoi sen suoraan televisioon viive- ja kokosäätöineen.
- **Toiston ohjaus ja palautus:** Voit säätää äänenvoimakkuutta, keskeyttää toiston tai kelata suoraan TeeVee Playerista. Toiston voi palauttaa takaisin tietokoneelle napsauttamalla Cast-valikosta *"Katkaise yhteys"*.

### H. Paikallinen DVR-tallennus ja ajastus (valinnainen)
- **Tallennuskansion määritys:** Valitse asetuksista kansio tallenteille ja halutessasi automaattinen lisäaika (0–10 min). Jos kansiota ei ole valittu, kaikki tallennuspainikkeet pysyvät piilossa.
- **Pikakäynnistys ja samanaikainen katselu:** Aloita suoran lähetyksen tallennus yhdellä klikkauksella soittimen alapalkista, kanavan tiedoista tai TV-oppaasta. Voit katsoa ja tallentaa samaa kanavaa samanaikaisesti ilman katkoksia myös yhden yhteyden IPTV-tileillä.
- **Ajastukset ja tallenteet:** Ajasta tulevia ohjelmia monikanavaisesta TV-oppaasta (`REC`-merkintä) ja katso valmiit tallenteet ryhmälistan kärjestä löytyvästä *Tallenteet*-näkymästä.

---

## 5. Ohje, diagnostiikka ja lokitiedostot

Jos kohtaat ongelmia toistossa tai soittolistan tuonnissa:
1. Paina yläpalkin kysymysmerkkipainiketta (**`?`**).
2. Valitse osio **Diagnostiikka ja tuki**:
   - **Kansiokuvake**: Avaa Windowsin lokikansion (`%LOCALAPPDATA%\IPTV_windows\logs\`).
   - **"Vie ZIP"**: Luo automaattisesti pakatun diagnostiikkaraportin tuelle toimitettavaksi. Tunnuksesi ja salasanasi on suojattu ja maskattu automaattisesti.

---

## 6. Ohjelmistopäivitykset

TeeVee Player sisältää helpon sisäänrakennetun päivitystoiminnon:
1. **Päivitysten tarkistus:**
   - Paina yläpalkin pilvipainiketta tai avaa Ohje-ikkunasta **Tarkista päivitykset**.
   - Sovellus tarkistaa virallisesta julkaisukanavasta, onko uudempaa versiota saatavilla.
   - Voit myös avata virallisen lataussivun selaimessa painikkeesta **Lataussivu**.
2. **Päivityksen asentaminen:**
   - Jos uusi versio löytyy, näet muutoslokin ja voit valita:
     - **Lataa ja asenna nyt**: Sovellus lataa asennuspaketin ja asentaa sen automaattisesti käynnistäen sovelluksen uudelleen.
     - **Päivitä myöhemmin**: Voit jatkaa katselua ja päivittää halutessasi vasta myöhemmin.
3. **Automaattinen tarkistus:**
   - Päivitysikkunassa voit kytkeä päälle tai pois asetuksen *"Tarkista päivitykset automaattisesti käynnistyksen yhteydessä"*.
   - Kun asetus on päällä, yläpalkkiin ilmestyy hienovarainen ilmoitusbadge vain silloin, kun uusi versio on oikeasti saatavilla.

---

## 7. Tärkeimmät pikanäppäimet

| Näppäin | Toiminto |
| :--- | :--- |
| **`F11`** / Kaksoisklikkaus | Koko ruudun tila päälle / pois |
| **`Esc`** | Poistu koko ruudun tilasta tai sulje sivuikkuna |
| **`Välilyönti`** / **`K`** | Toista / Tauko |
| **`Nuoli vasen / oikea`** (tai **`J`** / **`L`**) | Kelaa 10 sekuntia taaksepäin / eteenpäin |
| **`Nuoli ylös / alas`** | Äänenvoimakkuus +5 % / -5 % |
| **`M`** | Mykistys päälle / pois |
| **`C`** | Vaihda kuvasuhdetta (*Oletus* ➔ *16:9* ➔ *4:3* ➔ *16:10* ➔ *21:9* ➔ *Sovita ruutuun*) |
| **`A`** | Vaihda ääniraitaa |
| **`S`** | Tekstitysvalikko (pääikkunassa) tai vaihda pää- ja sivuikkuna päittäin (sivuikkunassa) |

# Muutosloki (Changelog)

Tämä tiedosto sisältää TeeVee Player -sovelluksen käyttäjälle näkyvät muutokset ja parannukset versiosta 1.0.1 alkaen.

## [1.4.1] - 2026-11-26

### 🛡️ VirusTotal Clean Scan Report
- **SHA-256:** `ac4dca6fe5d50ab11f5848d706621d7af9910f292380b5b64cb9352b0611bc47`
- **Security Analysis:** [View VirusTotal Report](https://www.virustotal.com/gui/file/ac4dca6fe5d50ab11f5848d706621d7af9910f292380b5b64cb9352b0611bc47)

### 🇫🇮 Suomi
- **Sujuvampi suoran lähetyksen katselu tallennuksen aikana:**
  - Korjattu ongelma, jossa suoran TV-lähetyksen toisto katkesi noin 20 sekunnin kuluttua tallennuksen aloittamisesta yhden samanaikaisen yhteyden IPTV-tileillä.
  - Voit nyt katsoa ja tallentaa samaa kanavaa samanaikaisesti ilman katkoja – kun tallennus päättyy, toisto jatkuu saumattomasti suoraan lähetyksestä.

### 🇸🇪 Svenska
- **Smidigare visning av direktsändning under inspelning:**
  - Åtgärdat ett problem där uppspelningen av direktsänd TV bröts cirka 20 sekunder efter att en inspelning startats på IPTV-konton med en samtidig anslutning.
  - Du kan nu titta på och spela in samma kanal samtidigt utan avbrott – när inspelningen avslutas återgår uppspelningen sömlöst till direktsändningen.

### 🇬🇧 English
- **Seamless live TV playback while recording:**
  - Fixed an issue where live TV playback disconnected roughly 20 seconds after starting a recording on single-connection IPTV accounts.
  - You can now watch and record the same channel simultaneously without interruptions, and playback smoothly returns to the live stream once recording stops.

## [1.4.0] - 2026-11-25

### 🛡️ VirusTotal Clean Scan Report
- **SHA-256:** `55ae5c311f05701d1abd97b8ee06ccb75eeb3abcc3e2cef854389727126c4a9c`
- **Security Analysis:** [View VirusTotal Report](https://www.virustotal.com/gui/file/55ae5c311f05701d1abd97b8ee06ccb75eeb3abcc3e2cef854389727126c4a9c)

### 🇫🇮 Suomi
- **Paikallinen DVR-tallennus ja ajastus (valinnainen toiminto):**
  - Tallenna suoria TV-lähetyksiä tietokoneellesi yhdellä klikkauksella suoraan soittimen alapalkista, kanavan tiedoista tai ohjelmaoppaasta.
  - Ajasta tulevia ohjelmia tallennettavaksi monikanavaisesta TV-oppaasta. Ajastetut ohjelmat erottuvat oppaassa selkeällä REC-merkinnällä, ja ajastukset toimivat luotettavasti myös eri soittolistojen välillä.
  - Valmiit tallenteet löytyvät omasta *Tallenteet*-näkymästä ryhmälistan kärjestä, ja asetuksista voi määrittää tallennusten automaattisen lisäajan (0–10 min). Paikalliset tallenteet pysyvät erillään elokuvien "Viimeksi katsotut" -historiasta.
  - **Täysin valinnainen:** Jos tallennuskansiota ei ole määritetty asetuksissa, kaikki tallennukseen liittyvät painikkeet ja valikot pysyvät piilossa pitäen käyttöliittymän yksinkertaisena.
  - Sovellus pitää tietokoneen hereillä tallennusten ja ajastusten aikana sekä varoittaa ohjelmaa suljettaessa, jos tallennus on kesken tai ajastettu.
- **Vakaampi toisto ja tarkempi tekstityksen valinta:**
  - Parannettu äänen ja kuvan vakautta kanavanvaihtojen aikana estämällä äänilähdön aiheuttama toiston pätkiminen ja hyppiminen.
  - Pidennetty automaattisen uudelleenyhdistyksen kestoa yhteyskatkosten jälkeen.
  - Korjattu automaattinen tekstityskielen valinta, jotta oletuskieli (esim. suomi) valikoituu tarkasti eikä sekoitu muihin kieliraitoihin, ja suositaan normaalia tekstitystä pakotetun sijaan.
- **Sarjojen suosikit ja käyttöliittymän parannukset:**
  - Korjattu sarjojen suosikiksi merkitseminen myös jo aiemmin avatuille sarjoille sekä estetty yksittäisten katseluhistorian jaksojen ilmestyminen ylimääräisinä riveinä suosikkilistalle.
  - Korjattu sarja- ja suosikkinäkymien kappalemäärälaskuri näyttämään tismalleen oikea sarjojen määrä.
  - Korjattu listojen oikean reunan työkaluvihjeet (tooltipit) avautumaan aina siististi vasemmalle, jotta ne eivät jää videoikkunan alle.
  - Parannettu soittolistojen päivityksen vikasietoisuutta.

### 🇸🇪 Svenska
- **Lokal DVR-inspelning och schemaläggning (valfri funktion):**
  - Spela in direktsända TV-program till din dator med ett klick från spelarens nederkant, kanalinformationen eller TV-guiden.
  - Schemalägg kommande program i den flerkanaliga TV-guiden. Schemalagda program markeras tydligt med en REC-symbol och fungerar tillförlitligt även över olika spellistor.
  - Färdiga inspelningar visas i en egen *Inspelningar*-vy överst i grupplistan, med valbar automatisk marginaltid (0–10 min) i inställningarna. Lokala inspelningar hålls separerade från filmernas "Senast spelade"-lista.
  - **Helt valfri:** Om ingen inspelningsmapp är vald i inställningarna döljs alla inspelningsknappar och vyer automatiskt.
  - Programmet förhindrar att datorn går i viloläge under inspelning eller inför kommande scheman och varnar vid stängning om en inspelning pågår eller är schemalagd.
- **Stabilare uppspelning och exaktare undertextval:**
  - Förbättrad ljud- och bildstabilitet vid kanalbyten för att förhindra hackande och hoppande uppspelning.
  - Förlängt fönster för automatisk återanslutning efter nätverks- eller serveravbrott.
  - Åtgärdat automatiskt val av undertextspråk så att valt standardspråk matchas exakt utan att blandas ihop med andra språk, samt prioriterar fullständiga undertexter framför tvingade (Forced).
- **Seriefavoriter och gränssnittsförbättringar:**
  - Åtgärdat favoritmarkering för redan öppnade serier och förhindrat att enskilda visade avsnitt dyker upp som extra rader i favoritlistan.
  - Korrigerat antalsräknaren i serie- och favoritvyn så att den alltid visar exakt antal serier.
  - Korrigerat verktygstipsen (tooltips) på högerkanten så att de alltid öppnas åt vänster och inte hamnar bakom videorutan.
  - Förbättrat skyddet vid uppdatering av spellistor.

### 🇬🇧 English
- **Local DVR Recording & Scheduling (Optional Feature):**
  - Record live TV broadcasts directly to your computer with one click from the player bar, channel info dialog, or TV guide.
  - Schedule upcoming shows from the Multi-Channel TV Guide, clearly marked with a REC badge and working reliably across multiple playlists.
  - Completed recordings are shown in a dedicated *Recordings* view at the top of the group list, with configurable end-padding (0–10 min) in Settings. Local recordings stay separate from the Movies "Recently Watched" list.
  - **Fully Optional (Opt-In):** If no recording folder is configured in Settings, all DVR buttons and sections remain hidden to keep the interface clean.
  - Automatically prevents the PC from sleeping during active recordings or upcoming schedules, and warns on exit if a recording is active or scheduled.
- **Smoother Playback & Accurate Subtitle Selection:**
  - Improved audio output fallback handling during channel switches to prevent playback stuttering and frame drops.
  - Extended automatic reconnection window after stream or server interruptions.
  - Fixed automatic subtitle language matching so the preferred default language (e.g. Finnish) is matched accurately without false matches, preferring full subtitles over Forced tracks.
- **Series Favorites & UI Refinements:**
  - Fixed favoriting for previously opened series and prevented individual watch-history episodes from appearing as extra duplicate entries in the Favorites list.
  - Fixed item counters in Series and Favorites views to always display the exact number of visible series.
  - Fixed right-edge list tooltips to always anchor and open inward to the left so they never clip behind the video surface.
  - Strengthened playlist sync reliability against interrupted updates.

## [1.3.0] - 2026-11-21

### 🛡️ VirusTotal Clean Scan Report
- **SHA-256:** `039d818ee1036cfad42ed4e18126f028f3719a7c1eceaae8230d4842c4faad9e`
- **Security Analysis:** [View VirusTotal Report](https://www.virustotal.com/gui/file/039d818ee1036cfad42ed4e18126f028f3719a7c1eceaae8230d4842c4faad9e)

### 🇫🇮 Suomi
- **Kuva kuvassa (PiP) ja kaksoistoisto:**
  - Avaa mikä tahansa toinen suora kanava kelluvaan pikkuruutuun ja seuraa kahta lähetystä samanaikaisesti.
  - Pikkuruudun kokoa voi muuttaa ja sen paikkaa näytöllä voi siirtää vapaasti.
  - Vaihda pääikkunan ja pikkuruudun kanavat sekä äänet keskenään saumattomasti yhdellä klikkauksella.
  - Itsenäiset äänenvoimakkuussäädöt molemmille ikkunoille ilman äänilähteiden sekoittumista.
- **Google Cast / Chromecast -suoratoisto:**
  - Suoratoista suorat TV-lähetykset, elokuvat ja sarjat suoraan televisioon tai Chromecast-laitteeseen lähiverkon yli.
  - Täysi tekstitystuki myös OpenSubtitles-palvelusta ladatuille tekstityksille reaaliaikaisella synkronoinnilla, viivesäädöllä ja tekstikoon valinnalla.
  - Toiston, tauon, äänenvoimakkuuden ja kelauksen hallinta suoraan soittimesta.
- **Nopeampi käynnistyminen ja tasaisempi toisto:**
  - Sovelluksen käynnistysaika on merkittävästi lyhyempi rinnakkaisen tietokanta-alustuksen ansiosta.
  - Korjattu suorien lähetysten alussa esiintynyt lyhyt toiston pätkiminen, jolloin lähetys käynnistyy heti vakaasti ja pehmeästi.
- **Monikanavaisen TV-oppaan parannus:**
  - Korjattu viikonpäivälyhenteiden näyttö laajan ohjelmaoppaan päivämäärävalitsimessa kaikilla tuetuilla kielillä.

### 🇸🇪 Svenska
- **Bild-i-bild (PiP) och dubbeluppspelning:**
  - Öppna valfri direktsänd kanal i ett flytande miniatyrfönster och titta på två kanaler samtidigt.
  - Fönstret kan fritt storleksändras och flyttas runt på skärmen.
  - Växla kanaler och ljud smidigt mellan huvudfönstret och miniatyrfönstret med ett klick.
  - Helt oberoende volymkontroll för båda fönstren utan ljudkonflikter.
- **Google Cast / Chromecast-stöd:**
  - Strömma direktsända TV-kanaler, filmer och serier direkt till din TV eller Chromecast via det lokala nätverket.
  - Fullt undertextstöd även för undertexter hämtade från OpenSubtitles med synkronisering i realtid, fördröjningsjustering och storleksval.
  - Styr uppspelning, paus, spolning och volym direkt från datorn.
- **Snabbare uppstart och jämnare uppspelning:**
  - Applikationen startar betydligt snabbare tack vare parallell databasinitiering.
  - Åtgärdat det korta hackandet i bild och ljud vid start av direktsändningar.
- **Förbättring av flerkanalig TV-guide:**
  - Korrigerat visningen av veckodagsförkortningar i guidefönstrets datumväljare för alla språk.

### 🇬🇧 English
- **Picture-in-Picture (PiP) & Dual-Stream:**
  - Watch two live channels simultaneously with a floating, resizable and draggable secondary window.
  - Swap channels and audio between main and PiP windows seamlessly with a single click.
  - Independent volume controls for both windows without audio cross-talk.
- **Google Cast / Chromecast Streaming:**
  - Cast live TV channels, movies, and TV series directly to your TV or Chromecast device over local Wi-Fi.
  - Full subtitle support including OpenSubtitles integration with live synchronization, delay adjustment, and font sizing.
  - Full playback, pause, seek, and volume control directly from the player.
- **Faster Startup & Smoother Live Playback:**
  - Significantly faster application launch via parallelized background database initialization.
  - Eliminated initial stuttering when starting live TV streams for immediate smooth playback.
- **Multi-Channel TV Guide Refinement:**
  - Fixed weekday abbreviation display in the TV guide date picker across all languages.

## [1.2.6] - 2026-11-08

### 🛡️ VirusTotal Clean Scan Report
- **SHA-256:** `ae430ede49cf91b05e7613985013464c15eccb858fae82d79b203461a0bb513e`
- **Security Analysis:** [View VirusTotal Report](https://www.virustotal.com/gui/file/ae430ede49cf91b05e7613985013464c15eccb858fae82d79b203461a0bb513e)

### 🇫🇮 Suomi
- **Uusi monikanavainen ohjelmaopas (TV Guide):**
  - Avaa yläpalkista suuri, useamman kanavan rinnakkainen ohjelmaopasikkuna, josta näet yhdellä silmäyksellä kaikkien ryhmän kanavien aikataulut.
  - Opas kohdistuu automaattisesti kuluvaan lähetykseen ja esittää tulevat ohjelmat heti selkeässä järjestyksessä.
  - Menneet ohjelmat erottuvat himmennettyinä, ja hiirellä voi rullata vapaasti aamun ja illan välillä.
  - Päivämäärävalitsin mahdollistaa tulevien päivien selailun sekä nopean siirtymisen eilisen arkisto-ohjelmiin yhdellä klikkauksella.
  - Kanavakohtaiset ohjelmakuvat ja tarkemmat ohjelmakuvaukset avattavissa info-painikkeella.
- **Käyttöliittymän työkaluvihjeet:**
  - Kaikkiin sivupalkin kuvakkeisiin ja toimintoihin on lisätty selkeät työkaluvihjeet (tooltipit), jotka näkyvät myös videotoiston aikana toistokuvan päällä.
- **Soittolistojen ja oppaan luotettavuus:**
  - Soittolistojen hallinta näyttää heti selkeän ilmoituksen, mikäli kanavaoppaan (EPG) lataus tai verkko-osoite kohtaa virheen.
  - Parempi EPG-ohjelmatietojen kohdistuminen kanaviin ja parannettu suosikkien luotettavuus.

### 🇸🇪 Svenska
- **Ny flerkanalig TV-guide (Multi-Channel EPG):**
  - Öppna ett stort och överskådligt guidefönster som visar tablån för alla kanaler i gruppen sida vid sida.
  - Guiden fokuserar automatiskt på det pågående programmet och visar direkt alla kommande sändningar.
  - Avslutade program visas nedtonade och du kan enkelt rulla med musen mellan morgon och kväll.
  - Datumväljare med snabb åtkomst till gårdagens arkivprogram (Catchup) och kommande veckodagar med ett klick.
  - Programbilder och utförliga beskrivningar via info-knappen.
- **Verktygstips (Tooltips):**
  - Tydliga hjälpbubblor för alla sidofältets knappar och flikar som alltid visas även över videouppspelningen.
- **Förbättrad tillförlitlighet för spellistor och tablå:**
  - Spellistehanteraren meddelar tydligt om EPG-nedladdningen stöter på ett fel eller nätverksavbrott.
  - Förbättrad matchning av programdata och stabilare favoritlista.

### 🇬🇧 English
- **New Multi-Channel TV Guide:**
  - Open a dedicated, large guide window viewing side-by-side schedules for all channels in the current category.
  - The guide automatically focuses on currently airing programs with upcoming shows visible right below.
  - Past programs are subtly dimmed for clarity, allowing easy mouse wheel scrolling across morning and evening lineups.
  - Date selector with one-click access to yesterday's catch-up archive and upcoming days.
  - Program thumbnails and detailed synopsis dialog via the info button.
- **User Interface Tooltips:**
  - Clear tooltips added for all sidebar buttons and tabs, designed to reliably render over active video playback.
- **Playlist & EPG Reliability:**
  - Clear visual notifications in Playlist Manager if an EPG source encounters network or sync errors.
  - Enhanced channel matching and improved favorites list deduplication.

## [1.2.5] - 2026-11-07

### 🛡️ VirusTotal Clean Scan Report
- **SHA-256:** `94a3c47ca7a94bcd3ef3e13e4c051563572877356024af2893b4127f3ae308d9`
- **Security Analysis:** [View VirusTotal Report](https://www.virustotal.com/gui/file/94a3c47ca7a94bcd3ef3e13e4c051563572877356024af2893b4127f3ae308d9)

### 🇫🇮 Suomi
- **Kanavien ja ryhmien massamuokkaus (Asetukset):**
  - Monivalinta valintaruuduilla sekä nopea Shift-klikkaus laajojen alueiden valitsemiseksi kerralla.
  - Uusi massatoimintopalkki: kaikkien näkyvien valinta, valintojen tyhjennys, eräpiilotus tai -näyttö sekä erälukitus lapsilukolla yhdellä klikkauksella.
  - Valittujen kohteiden massasiirto ja raahaus: siirrä valitut kohteet pikanäppäimillä kärkeen/pohjalle tai raahaa ne yhtenäisenä lohkona suoraan haluttuun kohtaan listalla.
  - Parannettu listan automaattirullaus ja ankkurointi: raahattava kohde pysyy aina vakaasti kursorin mukana pitkilläkin listoilla yläreunaan asti ilman raahauksen katkeamista.
- **Elokuvien trailerit (Tiedot-ikkuna):**
  - Uusi "Katso traileri" -painike elokuvan tieto- ja kuvausikkunassa avaa virallisen esittelyvideon selaimessa parhaalla saatavilla olevalla laadulla.

### 🇸🇪 Svenska
- **Massredigering av kanaler och grupper (Inställningar):**
  - Flervalsläge med kryssrutor och snabb Shift-klickning för att markera större områden samtidigt.
  - Nytt massåtgärdsfält: markera alla synliga, rensa markering, dölj/visa samt lås/lås upp med föräldralås med ett klick.
  - Massflytt och dra & släpp: flytta markerade objekt med snabbknappar till början/slutet eller dra dem som ett sammanhållet block direkt till önskad plats i listan.
  - Förbättrad automatisk rullning och förankring: det dragna objektet hålls alltid synligt även i långa listor hela vägen till toppen utan att dragningen avbryts.
- **Filmtrailers (Informationsfönster):**
  - Ny knapp "Se trailer" i filmens informationsfönster öppnar den officiella trailern i webbläsaren i högsta tillgängliga upplösning.

### 🇬🇧 English
- **Batch Operations for Channels & Groups (Settings):**
  - Multi-selection checkboxes with Shift-click support for selecting large ranges in one go.
  - New Batch Action Bar: select all visible, clear selection, batch hide/show, and batch lock/unlock with parental PIN in a single click.
  - Batch reordering and drag & drop: move selected items directly to top/bottom with quick buttons or drag and drop them as a single cohesive batch directly to your desired spot.
  - Enhanced auto-scrolling and viewport anchoring: dragged items stay firmly in view all the way to the top boundary of long lists without dropping unexpectedly.
- **Movie Trailers (Info Dialog):**
  - New "Watch Trailer" button in the movie info dialog opens the official trailer in your default browser in highest available quality.

## [1.2.4] - 2026-10-31

### 🇫🇮 Suomi
- **Kanavien ja ryhmien muokkaus & järjestely (Asetukset):**
  - Ryhmien ja kanavien mukautettu järjestäminen: raahaa suoraan hiirellä (drag & drop) tai käytä siirtopainikkeita (`⤒` kärkeen, `▲` ylös, `▼` alas, `⤓` loppuun).
  - Automaattinen ja sulava listan rullaus raahattaessa kanavaa listan ylä- tai alareunaan.
  - Pitkien listojen vierityspalkki ("hissi") ryhmien ja kanavien muokkausikkunassa nopeaan navigointiin.
  - Ryhmien ja kanavien uudelleennimeäminen omilla mukautetuilla nimillä.
  - Ryhmien ja kanavien piilottaminen ja näyttäminen (turhat kanavat tai ryhmät voidaan piilottaa päänäkymästä).
  - Alkuperäisten nimien ja järjestyksen palauttaminen yhdellä klikkauksella.
- **Edellinen / Seuraava kanava (|◄ / ►|) Live-toistossa:**
  - Suorien lähetysten toistopalkin kelauspainikkeet on korvattu suorilla kanavanvaihtopainikkeilla, jotka selaavat kanavia mukautetussa järjestyksessä ja vierittävät kanavalistan mukana.
- **Tekstitykset ja Teletext-parannus:**
  - Estetty Teletext- ja Teksti-TV -tekstityksen automaattinen päällekytkeytyminen DVB-lähetyksissä (tekstitv-sivu 100 ei enää peitä kuvaa oletuksena). Aito DVB-tekstitys valitaan edelleen automaattisesti.
- **Lapsilukko (PIN-koodi):**
  - Mahdollisuus asettaa 4-numeroinen PIN-koodi suoraan asetuksista.
  - Yksittäisiä kanavia tai kokonaisia ryhmiä voidaan lukita PIN-koodin taakse; toiston aloittaminen vaatii koodin syöttämisen.
- **Mukautusten säilyminen soittolistapäivityksissä:**
  - Kaikki omat mukautukset tallennetaan käyttäjätilatauluihin, joten ne säilyvät 100% koskemattomina palvelimen taustapäivitysten yli.
- **Entistä nopeampi käynnistyminen ja suorituskyky:**
  - Sovelluksen käynnistysnopeutta ja tietokantaa on optimoitu edelleen: kanavalistat ja soittolistat latautuvat päänäkymään välittömästi myös satojen tuhansien kanavien kokoelmilla.

### 🇸🇪 Svenska
- **Anpassning och ordning av kanaler och grupper (Inställningar):**
  - Anpassa ordning genom att dra med musen (drag & drop) eller använda flyttknappar (`⤒` till början, `▲` upp, `▼` ner, `⤓` till slutet).
  - Mjuk och automatisk rullning när ett objekt dras mot listans övre eller nedre kant.
  - Rullningslist ("hiss") för långa listor i anpassningsfönstret för snabb navigering.
  - Byt namn på grupper och kanaler till egna visningsnamn.
  - Dölj och visa grupper och kanaler från huvudlistorna.
  - Återställ standardinställningar med ett klick.
- **Föregående / Nästa kanal (|◄ / ►|) under Live TV:**
  - Spolningsknapparna fungerar som direkta kanalväxlingsknappar under livesändningar och bläddrar i din anpassade kanallista.
- **Undertexter och Teletext-förbättring:**
  - Förhindrat automatisk aktivering av Teletext/Text-TV vid start av sändningar.
- **Föräldralås (PIN-kod):**
  - Ställ in en 4-siffrig PIN-kod under Inställningar och lås känsliga kanaler eller grupper.
- **Beständiga anpassningar:**
  - Alla ändringar bevaras automatiskt även när spellistan uppdateras från servern.
- **Ännu snabbare uppstart och prestanda:**
  - Applikationens uppstartstid och databasfrågor har optimerats ytterligare: kanallistor och spellistor läses in omedelbart i huvudvyn även med hundratusentals kanaler.

### 🇬🇧 English
- **Channel & Group Customization & Reordering (Settings):**
  - Custom ordering of groups and channels: drag directly with mouse or use quick move buttons (`⤒` to top, `▲` up, `▼` down, `⤓` to bottom).
  - Smooth and continuous auto-scrolling when dragging near top or bottom list boundaries.
  - Scrollbar thumb ("elevator") added to group and channel customization lists for fast long-list scrolling.
  - Rename groups and channels to custom display names.
  - Hide and show unwanted groups and channels.
  - One-click reset to restore default ordering and visibility.
- **Previous / Next Channel (|◄ / ►|) in Live TV:**
  - Fast channel switching directly from the bottom player bar during live streams, respecting your customized channel order and auto-scrolling the list.
- **Subtitles & Teletext Safeguard:**
  - Prevents Teletext/Tele-text pages (such as page 100) from popping up by default over the video. Clean DVB subtitles are preferred automatically.
- **Parental Control (PIN Lock):**
  - Set up a 4-digit PIN code in Settings to lock sensitive channels or groups.
- **Sync-Proof Persistence:**
  - All customizations survive playlist background refreshes intact.
- **Faster Startup & Performance Optimization:**
  - Application launch time and database queries have been further optimized: channel lists and playlists load instantaneously in the main view even with collections of hundreds of thousands of items.

---

## [1.2.3] - 2026-10-09

### 🇫🇮 Suomi

- **Päivitetty toistomoottori:** Videotoistin on päivitetty tuoreimpaan LibVLC 3.0.24 -versioon, joka tarjoaa parannetun laitteistokiihdytyksen sekä entistä vakaamman ja nykimättömän toiston kaikille suoratoistomuodoille.
- **Näyttö pysyy päällä toiston aikana:** Windowsin virransäästö ja näytönsäästäjä eivät enää sammuta näyttöä tai vie tietokonetta lepotilaan videota katseltaessa. Normaali virranhallinta palautuu heti, kun toisto pysäytetään.
- **Sujuvampi elokuvien ja sarjojen jatkaminen:** Elokuvien ja sarjojen katselun jatkaminen aiemmasta katselukohdasta toimii nyt varmasti ja luotettavasti myös raskaammilla etätiedostoilla ilman ennenaikaisia yhteyskatkosilmoituksia.
- **Arkiston katseluhistorian parannukset:**
  - Vanhentuneiden tallenteiden tilalle tarjotaan nyt suora painike: *Avaa kanavan arkisto*, jolla pääset heti katsomaan kanavan voimassa olevia lähetyksiä.
  - Katseluhistoriasta siivotaan taustalla automaattisesti pois tallenteet, joiden säilytysaika palvelimelta on jo päättynyt.
- **Entistä nopeampi käynnistyminen:** Sovelluksen avautuminen ja kanavavalikon latautuminen käynnistyksessä on nyt huomattavasti aiempaa ripeämpää.
- **Kevyempi asennuspaketti:** Asennuspaketin koko on pienentynyt merkittävästi uuden optimoidun kuvakejärjestelmän ansiosta.
- **Suuret ryhmät kokonaisuudessaan:** Kaikki yli 1 000 kanavan tai elokuvan ryhmät näkyvät nyt kokonaisuudessaan ilman keinotekoisia rajoituksia.

---

### 🇸🇪 Svenska

- **Uppdaterad uppspelningsmotor:** Videospelaren har uppdaterats till senaste LibVLC 3.0.24, vilket ger förbättrad hårdvaruacceleration samt en mer stabil och jämn uppspelning för alla strömningsformat.
- **Skärmen förblir aktiv under uppspelning:** Windows energisparläge och skärmsläckare stänger inte längre av skärmen när du tittar på video. Normal energisparfunktion återställs omedelbart när uppspelningen pausas eller stoppas.
- **Smidigare återupptagning av filmer och serier:** Att fortsätta titta på filmer och serier från en sparad position fungerar nu stabilt och tillförlitligt även för stora mediefiler utan falska avbrottsmeddelanden.
- **Förbättrad arkivhistorik:**
  - Om en arkivinspelning har löpt ut erbjuds nu knappen *Öppna kanalens arkiv* för att direkt bläddra bland kanalens aktiva sändningar.
  - Utgångna arkivinspelningar rensas automatiskt från historiken vid uppstart.
- **Snabbare uppstart:** Applikationen och kanallistorna startar nu märkbart snabbare.
- **Mindre installationsfil:** Installationspaketets storlek har minskats avsevärt tack vare optimerade systemikoner.
- **Stora kanalgrupper i sin helhet:** Alla grupper med över 1 000 kanaler eller filmer visas nu fullständigt utan begränsningar.

---

### 🇬🇧 English

- **Upgraded Playback Engine:** The video player has been upgraded to the latest LibVLC 3.0.24 engine, delivering enhanced hardware acceleration and smoother, more stable playback across all streaming formats.
- **Keep Screen Awake During Playback:** Windows sleep mode and screen saver will no longer turn off your screen while watching video. Normal power management restores immediately when playback stops.
- **Seamless Resume for Movies & Series:** Resuming movies and series from a saved timestamp is now smooth and reliable, preventing premature timeout alerts on heavy remote streams.
- **Archive History Improvements:**
  - Expired catchup recordings now provide a direct *Open Channel Archive* action to quickly browse currently available programs for that channel.
  - Expired timeshift links are automatically purged in the background on startup.
- **Faster Startup Performance:** Application startup and channel menu initialization are significantly faster.
- **Lighter Installer Package:** Installer download size has been greatly reduced through optimized lightweight vector icons.
- **Full Display for Large Categories:** Large categories exceeding 1,000 channels or movies are now displayed completely without cutoffs.

🛡️ **VirusTotal Scan:** [Clean Report (392fbd6...)](https://www.virustotal.com/gui/file/392fbd6bef5ce87dd8dbf9746147d2721947125b9e849c9f7b8654b572710bd5)

---

## [1.2.2] - 2026-10-05

### 🇫🇮 Suomi

#### Uudet ominaisuudet:
- **Soittolistan kaikkien tietojen muokkaus:** Voit nyt muokata tallennetun soittolistan kaikkia tietoja suoraan asetuksista: soittolistan nimeä, lähdetyyppiä (M3U-verkko-osoite, paikallinen tiedosto tai Xtream Codes -palvelin, käyttäjätunnus ja salasana), EPG-ohjelmaopasosoitetta sekä sallittuja sisältötyyppejä (Live TV, Elokuvat, Sarjat). Lisäksi voit valita päivitetäänkö kanavalista heti tallennuksen yhteydessä.

#### Käyttökokemus- ja toistoparannukset:
- **Luotettava suoratoiston uudelleenyhdistyksen peruutus:** Uudelleenyhdistysikkunan "Peruuta"-painikkeen painaminen pysäyttää toiston nyt välittömästi ja palaa kanavanvalintaan ilman, että soitin jatkaisi taustalla uusia yhdistämisyrityksiä.
- **Sujuva ja vakaa kanavanvaihto ilman jumiutumista:** Nopeat kanavanvaihdot ja verkkokatkokset käsitellään nyt viiveettä erillisessä toistosäikeessä, mikä estää käyttöliittymän jumiutumisen ja "ei vastaa" -tilanteet.
- **Selkeä virheilmoitus toimimattomille elokuville ja sarjoille:** Jos valittu elokuva tai sarjan jakso ei ole saatavilla palvelimelta, tiedosto puuttuu tai toisto ei ala, soitin näyttää ruudulla välittömästi selkeän virheilmoituksen ja uudelleenyrityspainikkeen sen sijaan, että ruutu jäisi passiivisesti mustaksi.
- **Selkeä tilannebanneri soittolistan päivitykseen:** Kun päivität kanavalistan yläpalkista tai asetuksista, sovellus ilmoittaa ruudun yläreunassa selkeällä bannerilla päivityksen onnistumisesta tai tarkasta virheestä (esim. jos palveluntarjoajan palvelin ei vastaa tai yhteys hylättiin).
- **Välitön ilmoitus palvelinkatkoksesta toistossa:** Jos palveluntarjoajan suoratoistopalvelin on alhaalla tai hylkää yhteyden (*Connection refused*), soitin ilmoittaa siitä nyt heti selkeällä ilmoituksella sen sijaan, että se yrittäisi turhaan yhdistää toistuvasti uudelleen.
- **Suosikkien ja katseluhistorian luotettavampi kohdistus:** Suosikit ja katseluhistoria kohdistetaan nyt tarkasti oikeaan kanavaan, mikä estää samannimisten ulkomaisten kanavien tai haamukanavien sekaantumisen suosikkilistallesi.
- **Sarjojen eri laatuversioiden (esim. HD ja 4K) tarkka erottelu:** Jos samasta sarjasta on useampi julkaisu eri ryhmissä tai eri tarkkuuksilla (kuten HD ja 4K), sovellus avaa nyt aina tarkasti valitun version jaksot ja tiedot ilman, että toinen versio korvaisi toisen välimuistissa.

---

### 🇸🇪 Svenska

#### Nya funktioner:
- **Fullständig redigering av spellistans uppgifter:** Du kan nu redigera samtliga fält för en befintlig spellista direkt i inställningarna: namn, källtyp (M3U-länk, lokal fil eller Xtream Codes med server, användarnamn och lösenord), EPG-adress samt valda innehållstyper (Live TV, Filmer, Serier). Du kan även välja att uppdatera kanalerna automatiskt direkt när du sparar.

#### Förbättringar av användarupplevelse och uppspelning:
- **Pålitlig avbrytning av återanslutning:** Om du klickar på "Avbryt" i återanslutningsrutan avbryts uppspelningen omedelbart och spelaren återgår till kanalvalet utan att fortsätta i bakgrunden.
- **Stabil och smidig kanalväxling utan frysningar:** Snabb kanalväxling och nätverksavbrott hanteras nu asynkront i en dedikerad uppspelningstråd, vilket förhindrar att applikationen fryser eller slutar svara.
- **Tydligt felmeddelande för filmer och serier som inte kan spelas:** Om en vald film eller ett serieavsnitt saknas på servern, länken är bruten eller uppspelningen inte startar, visar spelaren direkt ett tydligt felmeddelande med möjlighet att försöka igen istället för att lämna skärmen tom och svart.
- **Tydlig statusbanner för spellisteuppdatering:** När du uppdaterar kanallistan visas en tydlig banner i överkant som bekräftar att uppdateringen lyckades eller förklarar det exakta felet (t.ex. om leverantörens server inte svarar eller avvisar anslutningen).
- **Omedelbart felmeddelande vid serveravbrott:** Om strömningsservern är nere eller avvisar anslutningen (*Connection refused*) visar spelaren direkt ett tydligt meddelande istället för att fastna i upprepade återanslutningsförsök.
- **Pålitligare hantering av favoriter och historik:** Favoriter och visningshistorik kopplas nu exakt till rätt kanal, vilket förhindrar att dubblettkanaler eller kanaler med samma namn felaktigt dyker upp bland dina favoriter.
- **Tydlig åtskillnad mellan serieversioner (HD och 4K):** Om samma serie finns i flera upplagor eller upplösningar (t.ex. HD och 4K) öppnar spelaren nu alltid exakt rätt version med dess egna avsnitt och metadata utan att de blandas samman i minnet.

---

### 🇬🇧 English

#### New Features:
- **Comprehensive Playlist Editing:** You can now edit every property of an existing playlist directly in settings: playlist name, source type (M3U URL, local file, or Xtream Codes server, username, and password), EPG guide URL, and permitted stream types (Live TV, Movies, Series). You can also choose to immediately refresh playlist contents upon saving.

#### User Experience & Playback Improvements:
- **Reliable Stream Reconnect Cancellation:** Clicking "Cancel" on the reconnecting dialog now cleanly aborts playback and returns to the channel selection view without triggering further background reconnection loops.
- **Smooth and Stable Channel Switching without Freezes:** Rapid channel changes and network disconnects are now handled asynchronously in a dedicated worker thread, preventing application UI freezes and unresponsive states.
- **Clear Error Alert for Unplayable Movies and Series:** If a selected movie or series episode is missing from the server, corrupted, or fails to start, the player immediately displays a clear diagnostic error notice with a retry option instead of silently leaving the screen black.
- **Clear Status Banner for Playlist Refreshes:** Refreshing playlists now displays an animated notification banner at the top of the screen confirming success or detailing the exact error (e.g., if the provider server is unreachable or refused the connection).
- **Immediate Server Outage Alerts:** When a streaming server is down or actively rejecting connections (*Connection refused*), the player instantly presents a helpful diagnostic notice instead of looping through prolonged reconnect attempts.
- **Accurate Favorite & History Matching:** Favorites and watch history now bind strictly to their respective streams, eliminating phantom channel duplicates and name-collision bugs in your favorites list.
- **Accurate Separation of Series Quality Releases (HD & 4K):** If a series exists in multiple categories or resolutions (such as HD and 4K), selecting a version now reliably opens that exact release and its specific episodes without cross-contaminating cache entries.

---

## [1.2.1] - 2026-10-02

### 🇫🇮 Suomi

#### Uudet ominaisuudet:
- **Kompakti ikkunatila (Vain video) [F10]:** Voit nyt katsoa lähetystä puhtaassa ikkunatilassa ilman häiriötekijöitä. Kanavalista ja toistosäätimet piilotetaan kokonaan pois näkyvistä, jolloin video täyttää ikkunan 100-prosenttisesti. Tila kytketään päälle pikanäppäimellä **`F10`** tai soittimen uudella painikkeella, ja normaalitilaan palataan painamalla **`F10`** tai **`Esc`**. Erinomainen useamman kanavan rinnakkaiseen katseluun tai työpöydän nurkkaan!
- **Tiivistetty ja avarampi ohjelmatietoikkuna:** Elokuvien, sarjojen ja lähetysten kuvausikkunan asettelua on tehostettu merkittävästi. Kansikuvan ja marginaalien tiivistämisen ansiosta pitkätkin juonikuvaukset ja ohjelmatiedot mahtuvat ruudulle kokonaisuudessaan ilman tarpeetonta vieritystä.
- **Aloita puhtaalta pöydältä (Asetusten ja tietokannan nollaus):** Asetukset-valikon Yleiset asetukset -välilehdelle on lisätty turvallinen toiminto, jolla voit yhdellä klikkauksella tyhjentää kaikki soittolistat, välimuistit ja katseluhistorian ja palauttaa sovelluksen puhtaaseen alkutilaan.

#### Käyttökokemus- ja toistoparannukset:
- **Saumattomat soittolistapäivitykset ilman välkkymistä:** Soittolistan päivittyessä taustalla kanavalista pysyy koko ajan ehjänä ja näkyvissä, eikä toisto tai kanavien selaus katkea päivityksen aikana.
- **"Viimeksi katsotut" -pikasuodatin ryhmänäkymään:** Voit nyt suodattaa ja avata viimeksi katsotut kanavat ja ohjelmat suoraan päänäkymästä ilman erillistä ryhmän valintaa.
- **Kattavampi arkiston katseluhistoria:** Katsotut arkistolähetykset ja suorat kanavat tallentuvat nyt välittömästi ja luotettavasti *Viimeksi katsotut* -listalle.
- **Arkistokanavien älykkäämpi valinta:** Arkistokanavaa klikattaessa sovellus avaa suoraan kyseisen kanavan ohjelma-arkiston ja menneet lähetykset vanhentuneen suoran linkin sijaan.
- **Suosikkikategorioiden säilyvyys:** Omat merkityt suosikkiryhmät ja niiden tilat säilyvät luotettavasti soittolistojen päivitysten yhteydessä.
- **Automaattinen soittolistan palautus:** Jos kaikki soittolistat poistetaan, sovellus osaa palauttaa toimivan oletuskanavalistan virhetilaan juuttumisen sijaan.

---

### 🇸🇪 Svenska

#### Nya funktioner:
- **Kompakt fönsterläge (Endast video) [F10]:** Titta på sändningar i ett rent och ostört fönsterläge där både kanallistan och alla kontroller döljs helt, så att videon fyller hela fönstret. Växla läget med snabbtangenten **`F10`** eller den nya knappen i spelaren, och återgå med **`F10`** eller **`Esc`**. Perfekt för att ha flera sändningar öppna bredvid varandra!
- **Rymligare och kompakt informationsruta:** Rutan för program- och videoinformation har optimerats så att även långa handlingar och beskrivningar syns tydligt utan onödig rullning.
- **Börja om från början (Databasåterställning):** En ny säker funktion under Allmänna inställningar gör det enkelt att rensa alla spellistor, historik och cachade data och återställa appen till ett rent utgångsläge.

#### Förbättringar av användarupplevelse och uppspelning:
- **Flimmerfri uppdatering av spellistor:** När spellistor uppdateras i bakgrunden förblir kanallistan intakt och uppspelningen fortsätter helt utan avbrott.
- **Snabbfilter för "Senast visade":** Du kan nu filtrera fram dina senast visade kanaler och program direkt i huvudvyn utan att behöva välja en specifik grupp först.
- **Pålitlig historik för arkivprogram:** Sedda arkivprogram och kanaler sparas nu direkt och tillförlitligt under *Senast visade*.
- **Smidigare arkivval:** Klick på en arkivkanal öppnar direkt kanalens sändningsarkiv och tidigare program.
- **Behåll favoritkategorier:** Dina markerade favoritgrupper bevaras säkert även när spellistor uppdateras.
- **Automatisk återställning av spellista:** Om alla spellistor raderas återställs en fungerande standardlista automatiskt så att appen inte fastnar i ett tomt läge.

---

### 🇬🇧 English

#### New Features:
- **Compact Window Mode (Video Only) [F10]:** Enjoy distraction-free viewing in a clean window mode where the channel sidebar and playback controls are completely hidden, letting the video fill 100% of the window. Toggle instantly with hotkey **`F10`** or the new player button, and exit with **`F10`** or **`Esc`**. Ideal for multitasking and watching multiple streams side by side!
- **Optimized Video & Program Details Dialog:** The info popup layout has been streamlined, allowing full plot summaries and extended show descriptions to fit on screen with significantly less scrolling.
- **Start Fresh (Database & Cache Reset):** Added a safe reset tool under General Settings to purge all playlists, history, and cached data in one click, restoring the app to a clean initial state.

#### User Experience & Playback Improvements:
- **Seamless & Flicker-Free Playlist Refreshes:** Background playlist updates now complete silently without clearing the channel list or interrupting your active stream.
- **"Recently Watched" Filter in Group View:** Quickly filter and jump into your recently watched channels and shows directly from the main view.
- **Reliable Catchup History:** Watched archive broadcasts and live channels now register immediately and reliably in the *Recently Watched* section.
- **Smarter Catchup Navigation:** Selecting a catchup channel takes you straight to its program archive instead of attempting an expired live link.
- **Persistent Category Favorites:** Your starred category groups and states are fully preserved across playlist refreshes.
- **Automatic Fallback Playlist:** If all playlists are deleted, the player automatically restores a working default playlist rather than getting stuck in an empty state.

---

## [1.2.0] - 2026-09-28

### 🇫🇮 Suomi

#### Uudet ominaisuudet:
- **Täysi monikielisyystuki:** Sovelluksen koko käyttöliittymä, haku, ohjelmaopas, dialogit ja pikaohjeet ovat nyt käytettävissä suomeksi, ruotsiksi ja englanniksi.
- **Kielivalinta asetuksissa:** Käyttöliittymän kielen voi vaihtaa suoraan Asetukset-valikon Yleiset asetukset -välilehdeltä, ja valinta astuu voimaan heti ilman sovelluksen uudelleenkäynnistystä.
- **Automaattiset tekstitysasetukset:** Tekstitysten oletuskieli seuraa automaattisesti sovelluksen ja käyttöjärjestelmän aktiivista kieltä.

#### Käyttökokemus- ja vakausparannukset:
- **Selkeytetty Asetukset-valikko:** Yläpalkki on siistitty ja kaikki toiminnot on koottu yhteen moderniin 2-välilehtiseen näkymään (*Yleiset asetukset* ja *Soittolistat*).
- **Soittolistakohtainen EPG-hallinta:** Ohjelmaoppaan osoitteen ja päivityksen asetukset säädetään nyt kätevästi suoraan kunkin soittolistan omista tiedoista.
- **Tarkempi arkistotoisto (Catchup):** Menneiden lähetysten ohjelmatiedot ja toiston aloitus vastaavat entistä luotettavammin todellisia lähetysaikoja.

---

### 🇸🇪 Svenska

#### Nya funktioner:
- **Fullt flerspråksstöd:** Hela användargränssnittet, sökningen, programguiden, dialogrutorna och snabbhjälpen är nu tillgängliga på svenska, finska och engelska.
- **Språkval i inställningarna:** Gränssnittsspråket kan enkelt bytas direkt under Allmänna inställningar, och ändringen slår igenom omedelbart utan att appen behöver startas om.
- **Smarta undertextval:** Undertexternas standardspråk anpassas automatiskt efter appens och systemets aktiva språk.

#### Användarupplevelse och stabilitetsförbättringar:
- **Förenklad inställningsmeny:** Toppmenyn har rensats och alla inställningar har samlats i en modern vy med två flikar (*Allmänna inställningar* och *Spellistor*).
- **Spellistebaserad EPG-hantering:** Programguidens länkar och uppdateringsinställningar hanteras nu smidigt direkt under respektive spellista.
- **Mer exakt arkivuppspelning (Catchup):** Tidigare sändningar matchas med högre precision mot sändningstiderna och startar direkt vid rätt tidpunkt.

---

### 🇬🇧 English

#### New Features:
- **Full Trilingual Localization:** The entire interface, search, electronic program guide (EPG), dialogs, and built-in help are now available in English, Finnish, and Swedish.
- **In-App Language Selection:** Easily switch the interface language from the General Settings tab, taking effect immediately with zero app restarts required.
- **Smart Subtitle Preferences:** Subtitles automatically default to the active application and operating system language.

#### User Experience & Stability Improvements:
- **Streamlined Settings Menu:** The top bar has been decluttered, uniting all settings and playlist tools into a clean 2-tab dialog (*General Settings* & *Playlists*).
- **Per-Playlist EPG Management:** Program guide URLs and sync settings are now conveniently managed per individual playlist.
- **Enhanced Archive Playback (Catchup):** Past broadcast listings now match actual airing schedules more accurately, launching catchup streams at the exact right timestamp.

---

## [1.1.11] - 2026-09-25

### Korjaukset ja parannukset:
- **Arkistokanavien toisto (Catchup / Timeshift):** Korjattu arkistotoiston käynnistyminen ja aikavyöhykkeen sovitus Xtream-palvelimilta. Kaikki saatavilla olevat menneet lähetykset (kuten urheilu-, uutis- ja viihdekanavat) toistuvat nyt luotettavasti.
- **Arkistopäivien selaus:** Eilisen päivän ohjelmat ovat nyt aina selattavissa myös kanavilla, joilla on lyhyempi (1 päivän) arkisto.
- **Suorat lähetykset arkisto-oppaasta:** Jos ohjelma on parhaillaan käynnissä, sen voi käynnistää suoraan reaaliaikaiseen lähetykseen selkeällä "Suorana"-painikkeella.
- **Käynnistyksen latausikkuna (Splash Screen):** Sovelluksen avaamisen yhteydessä esitettävä latausikkuna ja tilatiedot näkyvät taas välittömästi sovellusta käynnistettäessä.
- **Hissipalkki (Scrollbar) kanava- ja ryhmälistoihin:** Sivupalkin listoihin on lisätty moderni, huomaamaton hissipalkki, joka helpottaa listan koon ja oman sijainnin hahmottamista sekä mahdollistaa nopean siirtymisen suoraan listan alkuun tai loppuun vetämällä.
- **Ohjelmatietojen kattavuus:** Ohjelmaoppaan arkistotiedot noudetaan nyt automaattisesti myös silloin, kun kanavalla ei ole erillistä XMLTV-opasta.
- **Selkeät virheilmoitukset EPG-päivityksissä:** Ohjelmaoppaan latauksen epäonnistuessa tai palvelimen katkaistessa yhteyden sovellus näyttää nyt ymmärrettävän suomenkielisen opastustekstin kryptisten XML-koodivirheiden sijaan.

## [1.1.10] - 2026-09-24

### Korjaukset ja parannukset:
- **Hakukentän aktivointi heti käynnistyksessä:** Hakukenttä on heti kirjoitettavissa sovelluksen avauduttua ilman tarvetta toiston aloittamiseen tai näkymän vaihtamiseen.
- **Sarjojen "Viimeksi katsotut" -lista:** Korjattu katseltujen jaksojen tallentuminen ja näkyminen sarjojen Viimeksi katsotut -listalla, jolloin sarjojen toistoon palaaminen toimii taas saumattomasti.
- **Sarjojen jaksojen latauksen vakaus:** Korjattu virhetilanne, jossa sarjan jaksojen lataaminen epäonnistui tietyillä palvelimilla tai puuttuvilla jakso-/esittelytiedoilla. Jaksot ja kaudet avautuvat nyt luotettavasti.

## [1.1.9] - 2026-09-24

### Uudet ominaisuudet: Usean soittolistan tuki
- **Rinnakkaiset soittolistat:** Mahdollisuus tallentaa ja käyttää useita soittolistoja (M3U, Xtream Codes, paikallinen tiedosto) rinnakkain.
- **Soittolistakohtaiset tiedot:** Suosikkikanavat, katseluhistoria, toistokohdat ja kategoriat säilyvät erillään kullekin soittolistalle.
- **Pikavaihto yläpalkista:** Soittolistan voi vaihtaa lennosta suoraan yläpalkin pudotusvalikosta yhdellä painalluksella.
- **Uudistettu soittolistojen hallinta:** Selkeä korttinäkymä soittolistojen järjestämiseen, uudelleennimeämiseen, taustapäivitykseen ja poistoon.

### Käyttökokemus- ja vakausparannukset:
- **Sarjojen jaksokohtaiset kuvaukset ja kuvat:** Jaksonäkymässä näytetään sarjan yleisesittelyn sijaan kunkin jakson oma juonitiivistelmä ja esikatselukuva.
- **Kuvien esikatselu:** Kanava-, elokuva- ja sarjalistoilla kuvan päälle osoitettaessa näytetään suurempi esikatselukortti.
- **Koko ruudun palautus (Windows):** Korjattu toistosäädinten ja ikkunan alareunan peittyminen Windowsin tehtäväpalkin taakse koko ruudun tilasta poistuttaessa.
- **Soittolistakohtainen ja nopeampi EPG:** Ohjelmaoppaan osoite ja asetukset määräytyvät nyt soittolistakohtaisesti. Ohjelmatiedot latautuvat huomattavasti nopeammin ilman turhaa odotusta tai tuplamerkintöjä.

## [1.1.8] - 2026-09-23

### Uudet ominaisuudet ja päivitystoiminnot
- **Sisäänrakennettu ohjelmistopäivitysten hallinta:**
  - Sovellus tarkistaa viralliset päivitykset suoraan GitHub Releases REST API:sta.
  - Uuden version tunnistus, julkaisupäivämäärä sekä suora muutosloki sovelluksen sisällä.
  - **Suora lataus ja asennus:** Lataa uuden `.msi`-asennuspaketin reaaliaikaisella edistymisseurannalla ja asentaa sen automaattisesti taustaeräajolla uudelleenkäynnistäen sovelluksen.
  - **Päivitä myöhemmin -valinta:** Käyttäjä voi kieltäytyä tai lykätä päivitystä jatkaakseen katselua keskeytyksettä.
  - **Automaattinen tarkistus käynnistyksessä:** Valinnainen asetus, joka ilmoittaa uudesta versiosta huomaamattomalla huomiomerkillä yläpalkissa ilman että katselua häiritään.
  - **Pikalinkit:** Suorat painikkeet viralliselle esittelysivustolle (*Kotisivut*) sekä asennuspakettien jakelusivulle (*GitHub-julkaisut*).

## [1.1.7] - 2026-09-19

### Korjaukset ja vakausparannukset
- **Tietokannan säielukitus ja SQLite_BUSY -korjaus:**
  - Keskitetty coroutine-kirjoituslukko (`dbWriteMutex`), joka serialisoi kaikki taustasäikeiden ja käyttöliittymän kirjoitustoiminnot (toistokohdan tallennus, EPG-päivitykset, suosikit, soittolistojen muutokset).
  - Korjattu virhe `[SQLITE_BUSY] The database file is locked (database is locked)` ja sovelluksen odottamaton sulkeutuminen suosikkikanavia tai -sarjoja lisättäessä.
  - SQLiten `busy_timeout` kasvatettu 30 sekuntiin konfiguraatiossa ja yhteyksien alustuksessa.
  - Lisätty kattava virheensieto ja lokitus kaikkiin suosikkipainikkeisiin ja taustaprosesseihin, estäen poikkeusten nousemisen käyttöliittymään.

- **Salamannopea sarjojen suosikkien massapäivitys (`setFavoriteForChannels`):**
  - Sarjan lisääminen suosikiksi päivittää nyt kaikki sarjan jaksot kerralla yhdessä SQLite-erätransaktiossa kymmenien erillisten SQL-kyselyiden sijaan.

- **Xtream-sarjojen On-demand -lataus ja suorituskykyloikka:**
  - Korjattu valtavien sarjakirjastojen (kymmeniätuhansia sarjoja) tuonnin äärimmäinen hitaus ja jumittuminen.
  - Sarjojen jaksotietojen nouto siirretty on-demand -malliin: jaksot ladataan ja välimuistitetaan verkosta vasta sarjan avaamisen yhteydessä (`SeriesEpisodeLoader`).
  - Sarjanäkymään lisätty käyttäjäystävällinen latausanimaatio ("Ladataan jaksoja...") ja virhetilanteiden "Yritä uudelleen" -painike.

- **Live- ja arkistokanavien info-ikkunan (`VideoInfoDialog`) korjaus:**
  - Estetty automaattinen elokuvatietokantahaku (TheMovieDB / IMDb) TV-kanavien nimillä. Aiemmin TV-kanavan nimi (kuten "TV 7 News Heaven FI") aiheutti haun elokuvatietokannasta ja toi ruudulle satunnaisia, asiaankuulumattomia elokuvia tai sarjoja.
  - Live- ja arkistokanaville näytetään nyt siisti kanavakortti: oikea kanavalogo, LIVE TV / ARKISTO -tunniste sekä ohjelmaoppaan (EPG) tila selkeällä ilmoituksella ("Ei ohjelmatietoja saatavilla"), jos EPG-tietoja ei ole lähteessä.
  - Mahdollisuus hakea parhaillaan esitettävän ohjelman tietoja elokuvatietokannasta säilytetty manuaalisena hakutoimintona hakukentän kautta.

- **Soittimen virhe- ja uudelleenyhdistysilmoitusten vakaus:**
  - Eriytytty soittimen tilailmoitukset (`ReconnectingOverlay`, `PlaybackErrorOverlay`, `BufferingOverlay`) erillisiksi composable-komponenteiksi, mikä eliminoi JVM-luokannoutovirheet (`NoClassDefFoundError`) striimin yhteyskatkoksissa.
  - Live-kanavien suora käynnistys ilman tarpeetonta "Jatka katselua / Aloita alusta" -kyselyä.

- **Katseluhistorian yksittäisten kohteiden poisto:**
  - "Viimeksi katsotut" -näkymän kanavakortteihin lisätty roskakoripainike (`DeleteOutline`), jolla yksittäisen ohjelman, elokuvan tai kanavan voi poistaa katseluhistoriasta ilman, että koko katseluhistoriaa tarvitsee tyhjentää kerralla.
  - Poisto päivittää tietokannan toistohistorian ja käyttöliittymän välittömästi.

## [1.1.6] - 2026-09-19

### Uudet ominaisuudet ja parannukset
- **Soittolistojen hallintakeskus (Playlist Management):**
  - Lisätty yläpalkkiin uusi soittolistojen hallintapainike ja -ikkuna (`PlaylistManagerDialog`).
  - Näyttää kaikki tallennetut soittolistat, niiden nimet, kanavamäärät ja sisältötyypit (Live TV, VOD, Sarjat).
  - Mahdollisuus vaihtaa aktiivista soittolistaa lennosta yhdellä klikkauksella.
  - Olemassa olevan soittolistan ja kanavien nopea uudelleenpäivitys suoraan hallintanäkymästä.
  - Vanhentuneiden soittolistojen poistomahdollisuus vahvistuskyselyllä.

- **Kattava lokitus ja tukiraportin vienti (AppLogger & Support Diagnostics):**
  - Sisäänrakennettu kierrätettävä tiedostoloki polussa `%LOCALAPPDATA%\IPTV_windows\logs\teevee.log`.
  - **Täysi tietoturva ja yksityisyydensuoja:** Kaikki salasanat, tokenit, Xtream Codes -kirjautumiset ja URL-tunnisteet maskataan automaattisesti (`****`) ennen lokiin tallentamista.
  - **Ohje-ikkunasta (`?`):**
    - Suora kansion avaus Windowsin Resurssienhallinnassa (kansiokuvake).
    - **"Vie ZIP"** -toiminto, joka pakkaa lokit ja järjestelmätiedot (laite, resoluutio, muisti, kanavamäärä) helposti jaettavaksi diagnostiikkapaketiksi ongelmatilanteiden selvittämistä varten.

- **Xtream Codes API -integraatio ja virheen 884 korjaus:**
  - Korjattu virhe `Verkkovirhe: 884 <none>`, joka ilmeni kun Xtream-palveluntarjoaja (kuten Strong IPTV) estää perinteisen M3U `/get.php` -soittolistan lataamisen.
  - Automaattinen ja huomaamaton fallback suoraan viralliseen Xtream Codes JSON APIin (`/player_api.php`) Live TV-, VOD- ja sarjasisällöille rinnakkaisella jaksohaulla ja erätallennuksella.
  - Päivitetty HTTP User-Agentiksi IPTV-standardi `IPTVSmartersPro/1.0.0 (Linux;Android 11)` soittolistojen ja EPG-ohjelmaoppaiden noutoon.

- **Tekstitysten hallinnan parannukset ja ensisijaisuus:**
  - Lähetyksen sisäänrakennetut DVB-/tekstitysraidat asetettu oletusvälilehdeksi (`selectedTab = 0`), ja OpenSubtitles-haku toimii toissijaisena vaihtoehtona.
  - Korjattu tekstityksen "Pois päältä" -tilan tunnistus (`selectedSubtitleTrack == -1`).
  - Ladatun ulkoisen tekstityksen voi poistaa toistimesta suoraan `[✕]`-painikkeella.
  - Toistopalkin `[ Teksti: ON ]` -tilan ilmaisin näyttää nyt totuudenmukaisesti vain silloin, kun jokin tekstitysraita on toistimessa kytkettynä päälle.

## [1.1.5] - 2026-09-18

### Korjaukset ja parannukset
- **Täydellinen reunaton koko ruudun tila Windowsilla (Win32 Borderless Fullscreen):**
  - Korvattu aiempi Java AWT:n `GraphicsDevice.fullScreenWindow` natiivilla Windows Win32 API -tason ohjauksella (`WindowsFullscreenHelper`).
  - Poistaa Windowsin natiivin otsikkopalkin ja reunukset 100 % luotettavasti myös Compose Multiplatformissa.
  - Peittää näytön reunasta reunaan ilman pikselirakoja tai työpöydän taustakuvan pilkistämistä riippumatta näytön resoluutiosta (erityisesti 2880 × 1800, 4K, 16:10) tai Windowsin DPI-skaalauksesta (125 %, 150 %, 175 %, 200 %).
- **Korjattu sarjalistan kaatuminen kaksoisavaimeen (LazyColumn Key Collision Fix):**
  - Korjattu virhe `Key "series_..." was already used`, joka kaatoi sarjanäkymän, jos soittolistassa oli sarjoja tai jaksoja samalla nimellä mutta eri erottimilla/välimerkeillä (esim. kaksoispiste `:` vs viiva `-`).
  - Sarjojen ryhmittelyavain normalisoidaan nyt älykkäästi, jolloin eri tavoin nimetyt jaksot ryhmittyvät siististi saman sarjan alle.
  - Kaikille sarjoille ja jaksoille taataan nyt 100 % uniikki ja törmäysvapaa tunniste, joka estää käyttöliittymän kaatumisen.


## [1.1.4] - 2026-09-18

### Uudet ominaisuudet ja parannukset
- **Natiivi käynnistysloaderi (Splash Screen):**
  - Lisätty välittömästi käynnistyksen alussa (< 100 ms) avautuva tyylikäs, pyöristetty ja tummateemainen käynnistysikkuna sovelluslogolla, animoidulla latauspalkilla ja reaaliaikaisella tilatiedolla (*"Alustetaan toistoympäristöä..."*, *"Ladataan tietokantaa ja kanavia..."*, *"Valmistellaan toistomoottoria..."*).
  - Poistaa aiemman tyhjän odotushetken asennetun sovelluksen käynnistyessä ja sulkeutuu automaattisesti pääikkunan avautuessa.
- **Avoimen lähdekoodin lisenssit ja vastuuvapauslauseke sovelluksessa:**
  - Lisätty Ohje-ikkunaan (`?`) uusi osio **"5. Avoimen lähdekoodin lisenssit ja oikeudelliset tiedot"**, joka listaa kaikki käytetyt avoimen lähdekoodin komponentit (LibVLC, VLCJ, Kotlin/Compose Desktop, OkHttp, SQLite, JNA) lisensseineen sekä selkeän juridisen vastuuvapauslausekkeen.
- **Uudistettu käyttökokemuskeskeinen verkkosivusto:**
  - Esittely- ja lataussivusto uusittu kokonaan keskittymään televisionkatselun helppouteen, sujuvuuteen ja nautintoon teknisen jargonin sijaan.
  - Mukana myös uusi FAQ-osio *"Mitä siellä on konepellin alla?"* tekniikasta kiinnostuneille.

## [1.1.3] - 2026-09-18

### Korjaukset ja parannukset
- **EPG-ohjelmatietojen haku ja näkyvyys kanavalistassa:**
  - Korjattu kriittinen virhe, jonka vuoksi EPG-ohjelmatiedot eivät tulleet näkyviin kanavalistassa tai videosoittimen yläpalkissa, vaikka XMLTV-tiedot oli ladattu tietokantaan. Haku käyttää nyt kanavan sisäistä tunnistetta (`channel.id`), jolloin kaikki tallennetut ohjelmatiedot, alkamis-/päättymisajat ja etenemispalkit näkyvät heti.
  - Älykäs kanavatunnisteiden normalisointi: kanavanimistä siivotaan automaattisesti tekniset laatumääreet (`FHD`, `HD`, `SD`, `FI`, `[Multi-Sub]`) ja ohjelmatietoja etsitään useilla rinnakkaisilla ehdokasavaimilla (kuten `jim.fi`, `yletv1.fi`).
  - Parannettu ohjelmatietojen löytymistä myös kanavatietodialogissa (`Video Info`) ja ohjelma-arkistossa (`Catch-up`).
- **Äänen mykistyksen (Mute) ja pikanäppäimen korjaus:**
  - Lisätty puuttunut **`M`**-pikanäppäin äänen mykistämiseen ja palauttamiseen.
  - Korjattu LibVLC:n asynkronisen tilanvaihdoksen aiheuttama kilpatilanne, jossa mykistystila kääntyi ristiin (ääni kuului vaikka käyttöliittymä näytti mykistettyä ja päinvastoin). Tila hallitaan nyt sovelluksen tilakoneessa suoralla `setMute`-kutsulla, eikä tila voi enää kääntyä ristiin.
  - Mykistystila ja valittu äänenvoimakkuus säilyvät nyt aina kanavaa vaihdettaessa tai tekstityskokoa lennosta säädettäessä.
  - Äänenvoimakkuuden nostaminen poistaa automaattisesti mykistyksen ja nollaan vetäminen kytkee mykistyksen päälle.
  - Äänenvoimakkuusilmaisin näyttää mykistettynä selkeästi punaisella `0%` aiemman hämäävän `100%`:n sijaan ja säädin saa mykistysteeman.

## [1.1.2] - 2026-09-18

### Uudet ominaisuudet ja parannukset
- **Vaivaton OpenSubtitles-haku (Sisäänrakennettu yleisavain):**
  - Tekstitysten haku ja lataus toimii nyt suoraan ilman, että käyttäjän tarvitsee rekisteröityä tai luoda omaa API-avainta.
  - Asetuksista voi halutessaan edelleen syöttää oman henkilökohtaisen avaimensa (tai VIP-avaimen) laajempia latauskiintiöitä varten.
- **Sisäänrakennettu Käyttöönotto- ja pikaopas (Ohje-painike `?`):**
  - Lisätty yläpalkkiin kysymysmerkkipainike `(?)`, jota klikkaamalla aukeaa kattava ja selkeä opas.
  - Opas neuvoo oman soittolistan lisäämisen (M3U URL, tiedosto, Xtream Codes), kanavien selauksen, suosikit, kuvasuhteen ja tekstitysten käytön sekä kaikki pikanäppäimet.
- **Kuvasuhteen valinta (Aspect Ratio Fix):**
  - Korjattu ongelma, jossa toistopalkin kuvasuhdevalikko leikkautui videopinnan (AWT Canvas) alle ja näytti vain viipaleen "Fill".
  - Korvattu leikkautuva popup uudella luotettavalla `AspectRatioDialog`-ikkunalla, joka on aina näkyvissä eikä peity videon alle.
  - Korjattu LibVLC-kuvasuhdelogiikka: "Sovita ruutuun" poistaa mustat palkit luotettavasti crop-geometrialla.
  - Lisätty pikanäppäin **`C`** kuvasuhteen nopeaan vaihtamiseen lennossa (*Oletus* ➔ *16:9* ➔ *4:3* ➔ *16:10* ➔ *21:9* ➔ *Sovita ruutuun*).
  - Kuvasuhdeasetus säilyy nyt voimassa myös kanavaa tai striimiä vaihdettaessa.

## [1.1.1] - 2026-09-17

### Korjaukset ja parannukset
- **Aito koko ruudun tila Windowsilla (Fullscreen Fix):**
  - Korjattu ongelma, jossa F11- tai koko ruutu -painike jätti soittimen kellumaan ikkunaan ja näytti Windowsin otsikkopalkin erityisesti suuriresoluutioisilla näytöillä (kuten 2880 × 1800, High-DPI).
  - Korvattu puutteellinen Compose Multiplatform -toteutus suoralla näyttölaitetason koko ruudun ohjauksella (`GraphicsDevice.fullScreenWindow`), joka peittää 100 % näytöstä reunattomasti.
  - Koko ruudun tilasta poistuminen (Esc / F11) palauttaa ikkunan siististi aiempaan kokoon ja sijaintiin.
- **Käyttöliittymän selkeytys:**
  - Poistettu ylimääräinen/toisteinen EPG-osoitekenttä soittolistan lisäysikkunasta (EPG tunnistetaan automaattisesti Xtream-tunnuksista ja soittolistan tiedoista).

## [1.1.0] - 2026-09-17

### Merkittävät uudet ominaisuudet (Feature Release)
- **EPG-ohjelmaopas (Electronic Program Guide):**
  - XMLTV-tuki ja automaattinen EPG-osoitteen tunnistus soittolistasta.
  - Reaaliaikainen meneillään olevien ohjelmien näyttö suorien kanavien listassa etenemispalkkeineen.
  - Avaa ohjelmaopas -dialogi kanavakohtaisten ohjelmatietojen ja aikataulujen selaamiseen.
- **Sarjojen kausi- ja jaksonäkymä (Series / Seasons / Episodes):**
  - Kattava sarjojen esittelynäkymä: Hero-kortti, kuvaus, kausipainikkeet ja jaksojen lista.
  - "Jatka katselua" -ehdotus ja jaksojen toistohistoria/edistymisen seuranta.
- **Arkistotoisto (Catch-up / Timeshift):**
  - Uusi `⏪ Arkisto` -pääosio suorien lähetysten menneiden ohjelmien katseluun.
  - Suora Xtream Codes -arkistorajapinnan integrointi (`player_api.php`): vain todelliset tallennetut kanavat näkyvät arkistossa ryhmäkohtaisine määrineen (mm. Ruotsi 53 kpl, Saksa 41 kpl jne.).
  - Luotettava aikajanatoisto suoraan palvelimelta ilman toistomoottorin kaatumisia.
- **Soittolistojen automaattinen taustapäivitys:**
  - Taustapäivitys suoritetaan automaattisesti käynnistyksen yhteydessä ja 12 tunnin välein häiritsemättä katselua.
  - Yläpalkissa manuaalinen 🔄 **Päivitä** -painike.

### Korjaukset ja parannukset
- **Kanavatunnisteiden uniikkius:** Korjattu ongelma, jossa saman `tvg-id`-tunnisteen jakavat alukanavat (esim. alueradiot tai -televisiot) ylikirjoittivat toisensa tietokannassa.
- **Soittimen vakaus:** Korjattu Compose Sliderin `NaN`-poikkeus, joka saattoi kaataa toiston arkistovirtaa puskuroidessa.

---

## [1.0.7] - 2026-09-17

### Korjaukset ja parannukset
- **Koko ruudun ja ikkunatilan palautus:**
  - Korjattu ongelma, jossa toisto-ohjaimet katosivat tai leikkautuivat alareunasta palattaessa täyden ruudun tilasta ikkunaan. Kontrollit palautuvat nyt välittömästi ilman tarvetta muuttaa ikkunan kokoa käsin.
  - Korjattu ikkunan koon ja maksimointitilan palautuminen: ikkuna palaa täydestä ruudusta täsmälleen siihen kokoon ja sijaintiin, jossa se oli ennen koko ruutuun siirtymistä.
- **Tekstityksen näkyvyys koko ruudussa:**
  - Korjattu tekstityksen leikkautuminen näytön ulkopuolelle täyden ruudun tilassa näyttöskaalausta (DPI-skaalaus, esim. 125 % / 150 %) käyttävillä näytöillä.
- **Päivityspaketti:**
  - Mukana uusi kevyt ZIP-päivitysmuoto (`IPTV-Stream-TV-update-1.0.7.zip`), joka mahdollistaa sovelluksen nopean päivittämisen ilman raskasta uudelleenasennusta.

---

## [1.0.6] - 2026-09-17

### Uudet ominaisuudet
- **Tekstityksen koon valinta:**
  - Tekstitysvalikkoon lisätty selkeä koon valitsin: **Pieni**, **Keskikokoinen** ja **Suuri**.
  - Valittu tekstityskoko tallentuu automaattisesti muistiin ja pysyy voimassa myös kanavan tai ohjelman vaihtuessa ja sovelluksen uudelleenkäynnistyksissä.
- **Kevyt päivitystuki:**
  - Lisätty mahdollisuus luoda kevyt ZIP-päivityspaketti olemassa olevan asennuskansion päälle purettavaksi.

---

## [1.0.5] - 2026-09-16

### Uudet ominaisuudet ja parannukset
- **Sisäänrakennettu toistomoottori:**
  - Sovelluksen asennuspakettiin integroitu suoraan tarvittavat LibVLC-ajokirjastot, jolloin erillistä VLC Media Player -asennusta ei enää välttämättä vaadita järjestelmään.
- **Katselutietojen ja kanavatietojen tarkastelu:**
  - Kanavan ja toistettavan ohjelman lisätietodialogi (Info), josta näkee suoratoiston tekniset tiedot ja kuvaresoluution.
- **Vikasietoisuus:**
  - Sovelluksen vakauden parannuksia ja automaattinen virheiden kirjaus ongelmatilanteissa (`crash.log`).

---

## [1.0.4] - 2026-09-15

### Uudet ominaisuudet ja ulkoasu
- **Sivupalkin leveyden säätö:**
  - Kanavalistan ja toistonäkymän väliin lisätty hiirellä vedettävä jakopalkki (splitter). Sivupalkin kokoa voi säätää vapaasti omien mieltymysten mukaan.
- **Kanavien ja katseluhistorian järjestely:**
  - Lisätty kanavien lajittelumahdollisuus nimen (A-Z) tai lisäysjärjestyksen mukaan.
- **Tyyppikohtaiset tilastot:**
  - Yläpalkki näyttää nyt selkeät laskurit Live-lähetyksille, Elokuville ja Sarjoille.

---

## [1.0.3] - 2026-09-14

### Uudet ominaisuudet
- **Toiston jatkaminen (Resume Playback):**
  - Jos aiemmin katsottu elokuva tai ohjelma avataan uudelleen, sovellus kysyy halutaanko toistoa jatkaa suoraan aiemmasta kohdasta vai aloittaa alusta.
- **Viimeksi katsotut:**
  - Uusi pikavalinta viimeksi katsotuille kanaville ja ohjelmille sekä mahdollisuus tyhjentää katseluhistoria yhdellä painikkeella.
- **Edistymispalkki kanavakorteissa:**
  - Kanavalistassa näytetään visuaalinen etenemispalkki ja katseluaika kesken jääneille sisällöille.

---

## [1.0.2] - 2026-09-13

### Uudet ominaisuudet
- **Xtream Codes API -tuki:**
  - Soittolistan lisäysikkunassa voi nyt tuoda kanavat suoraan Xtream-palvelimen osoitteella, käyttäjätunnuksella ja salasanalla perinteisen M3U-tiedoston lisäksi.
- **Sisältötyyppien suodatus:**
  - Kanavat jaettu omiin päänäkymiinsä: **Live-TV**, **Elokuvat** ja **Sarjat**.
- **Soittolistan hallinta:**
  - Mahdollisuus korvata aiempi kanavalista uudella tai yhdistää uusia kanavia olemassa olevaan listaan.

---

## [1.0.1] - 2026-09-12

### Perustoiminnot
- **Ensimmäinen työpöytäversio:**
  - Kaksipalstainen käyttöliittymä: kanavaselain ja katseluruutu rinnakkain.
  - Haku ja suosikkien merkintä (tähtipainike).
  - OpenSubtitles-tekstitysten haku ja synkronointiviiveen hienosäätö (`[-0.5s]` ... `[+0.5s]`).
  - Kuvasuhteen vaihto (16:9, 4:3, Fill jne.) ja ääniraitojen vaihto lennosta.
  - Pikanäppäintuki (F11 koko ruutu, välilyönti tauko/toisto, Esc poistu, A ääni, S tekstitys).

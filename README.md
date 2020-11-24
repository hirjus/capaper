Tutkielma R Markdownilla ja **bookdown** - paketilla. (https://github.com/rstudio/bookdown). Bookdownin ohjeet löytyvät täältä  (https://bookdown.org/). Oma testidokumentti on (https://hirjus.github.io/test1/).

**31.7.2018**

Tutkielman lopullinen versio bookdown-paketilla, pohjana esimerkkiprojekti.

Kopioidaan suoraan testi-projektin asetustiedostot tähän projektiin.

**1.8.2018** pieniä korjailuja, lukujen otsikoita.

- Rmd-tiedostot luetellaan _bookdown.yml-tiedostossa
- kasitteet1.Rmd - df käsitteistä

## Hakemistot - GitHub

**docs** pdf- ja htlm-tulosteet

**bddefaults** bookdown-paketin oletuskonfiguraatiot (YAML- front matter index.
Rmd-tiedostossa, _output.yml, 		_bookdown.yml)

## Muut hakemistot RStudion projektissa

**data** 	SPSS-tiedosto, tekstitiedosto muuttujakuvauksista
**ark**		arkisto
**test**	yksittäisiä Rmd-sivuja, joilla saan yhden Rmd-tiedoston tulostuksen
toimimaan. preview_chapter() ei toimi		odotetulla tavalla projektin juuressa,
eikä RStudion knit-nappi, vaan aina tulostuu koko dokumentti.

**3.8.2018**

Lisäsin test-hakemiston, jossa voi rakennella r-koodia. Siellä toimii yhden
Rmd-tiedoston tulostus. output.yml - tiedostoon output-optioksi myös html_book.

**8.8.2018**

Lähdeviitteet toimivat, johdantoon hieman jäsentelyä. Tulostusvaihtoehtona on
myös html-book, siinä saa tarvittaessa koodin piilotuksen toimimaan. Ei onnistu
gitbook-formaatissa, vaatii teeman käyttöä.

Versio 0.02 : lisättty lähdeviiteitä ja päivitetty bibtex-viitetiedosto.

**9.8.2018 Versio 0.03**

Jäsentelyä data-lukuun. Lisäsin ISSP-viitteitä RefWorksiin, ja ne rikkoivat
PDF-version viitteidenhallinnan, nyt vain gitbook-tuloste. Korjaillaan,tai
poistetaan, ISSP-dokumentaatioon on hankalaa viitata. www.gesis.org on sekava
sivusto!

**11.8.2018**

Pieniä lisäyksiä tekstiin, lähdeviitteitä, skandien aiheuttamia ongelmia
kummasteltu bibtex - viitekannan pdf-käsittelyssä. PDF ja gitbook toimivat,
tallennetaan ark-hakemistoon nämä.

Versio 0.05, pieniä lisäyksiä (viitteitä, pari artiikelin abstraktia kopsattu).
Versionnin idea: 0.0n alustavaa hahmottelua, 0.n koko paperin jäsentelyjä, 1.n.n
valmiimpaa tekstiä.

**12.8.2018** Pieniä korjailuja sisällysluetteloon. Kolmas tulostusvaihtoehto
html_book(), yhteen html-tiedostoon (/docs/JH_ca.html), helpompi printata.
 output.yml - tiedostossa asetus code_folding: show, voi muuttaa 'hide'
 (jolloin koodi piilossa "napin alla").

**3.9.2018** Lisättiin asetus 'doc-depth: 2' YAML-headeriin (index.Rdm).
Dokumentointi on tässä hyvin hämärää, mutta toimii.

**24.10.2018** Aloitetaan sisällön lisääminen, kehyityshaara **dev**.
Ensin sisällysluettelo ajan tasalle jäsentelydokumentin (word) pohjalta.
Docs-hakemiston pdf- ja html- tulosteista arkistoversiot hakemistossa **ark**.

**25.10.2018** PDF-tulostus lakkasi toimimasta. Syy on luultavasti omalle
koneelle paikallisesti asennetun MikTeX:hin ja tinytex- r-paketin "lennossa"
asentamien (user-hakemistoon, Appdata-roaming - haaraan) tex-pakettien
yhteensovittamisessa. Käytetään html-tulostetta (yksi tiedosto).
**Korjattu, pientä editointia.** Lisätty muutama kuva.

**26.10.2019** R-paketti rgl ei toimi, ei suostu latautumaan. Kolmiulotteista
grafiikkaa, tuskin tarvitaan. Pientä editointia test-hakemiston kaavat1.Rmd - tiedostossa.

**14.12.2019** Testataan toiminta R- ja MikTeX - päivitysten jälkeen.
 Tarkistettiin ja korjailtiin test-hakemiston kasitteet1.Rmd ja kaavat1.Rmd,
 tulostettiin pdf- ja html-muodossa. Kaavoissa korjattavaa.

**13.10.2020**
simple_preamble.tex - luvun otsikko pois sivun yläreunasta.

**18.10.2020** Päivitettiin jhca2020.bib, tarkistettiin index.Rmd-tiedoston paketit.
Samat kuin Galku-projektissa, käyttämättömät poistettu. Lisätty datan
peruskäsittelyn R-koodilohkot. Versionumero 0.08. PDF-tulostus ei toimi.

**18.10.2020** Kommentoitiin pois muunnosten laveita ristiintaulkointeja,
 testauskoodilohko jätetiin. PDF-tulostus toimii.

 **21.10.2020 Versio 0.10** Johdatteleva esimerkin koodia, datan luonti ja profiilikuvat.
 Lisätty muuttujataulukko kysymyksistä ja suomenkielisen lomakkeen kuva. R- koodi
 liitteksi.
 Rivi- ja sarakeprofiilikuvien tekstit korjattu.
 Kaksi ensimmäistä karttaa.

 **23.20.2020** Ikäluokat syntmävuosina, ca-numeerisia tuloksia tekstiin.

 **23.10.2020 Versio 0.20** Karkea sisällysluettelo, hieman **k**appaleiden
 sisältöjä ja muistiinpanoja rakenteesta.

 **23.10.2020 Versio 0.30**  Karttoja yksinkertaisen ca-esimerkin loppuun asti.
 Muutettiin pdf-dokumentin nimi JH_ca.pdf -> JH_capaper.

 **24.10.2020** Belgian ja saksan jako, symmetrinen ja kontribuutiokartta. Uusi
  bib-tiedosto (RefWorks-lähteet). PDF-tulostus kaatuu aluejako-taulukkoon tai
	sitä edeltävään koodilohkoon. CA-numeeriset tulokset ja kolmiulotteinen ratkaisu.
	summary() - funktio ei toimi 3d-ca-objektilla jostain syystä.

	Ikä-sukupuoli ja ikä-sukupuoli-maa yhdysvaikutusmuuttujat luotu, molemmilla
	yksi kartta.

	**25.10.2020** PDF-tulostus ei toimi, julkaistan myös "html_book" yhtenä
	tiedostona, voi tulostaa selaimella pdf-muotoon.

	**26.10.2020**

	PDF-tulostus ei toimi, ei välitetä tästä. Lokitiedot ja tex-tiedosto, josta saan
	"suoraan" renderöityä jonkinlaisen pdf-tulosteen, mutta ilman lähdeviitteitä jne.
	Editointia, jäsentelyä loppulukuihin.

**26.10.2020**
	Analyysi ja kommenteja lisätty subsetCA-jakson loppuun. Muutama tulostus mukana
	CA:n numerisista tuloksista, poistetaan niistä suurin osa kun teksti on valmis.

**26.10.2020 Versio 0.4**
Koodi siirretty capaperiin, jonkin verran kommentteja lisäilty. Outo ilmiö,
koodiliitteeseen tulostuu myös koodilohkojen output?

**27.10.2020** R-koodi tulostuu ok.

**6.11.2020** Lisättiin koodia johdattelevaan esimerkkiin ja teorialiite, kopiotu
Galkusta. Pientä editointia.

**7.11.2020** Lisättiin MCA-lukuun kuva taulukoiden yhdistelyn periaatteesta,
ja asymmetrinen MCA-kuva.

**7.11.2020** Paljon kokeiluja, mutta pdf-tulostusta ei saatu toimimaan. TinyTeX
käyttöön latex-enginenä.

**8.11.2020** Siistittiin data-luvusta väliotsikoita pois, lisättiin viitteitä ja
muutama tekstipätkä.

**9.11.2020 Versio 0.5** Lukujen otsikot lyhyemmiksi, tarkistettu että koodilohkot päättyvät tyhjään riviin ("newline"),
maltillisesti kappalekuvauksia (**k**), lisäilty viitteitä hiotavaksi.

**9.11.2020** Muutama viite lisää. Taulukko ISSP-dokumenteista, muutama viite.

**11.11.2020** Teorialiitteeseen yksi kuva, yksi kartta lisää johdattelevan
 esimerkin massa-lukuun. Pieni tekstimuutoksia ja lisäyksiä, viitteitä lisää.

 **12.11.2020** Viitetietoja, pientä editointia.

 **12.11.2020** Teorialiitteen pientä täydennystä ja siistimistä, turhia alalukuja pois
 johdannosta.

 **12.11.2020 Versio 0.6** Johdanto ja yhteenvetoluku jätetään viimeisiksi,
  muihin valmista tekstiä. Dataluku lisätty.

**13.11.2020** Editointia data-analyysiluvuissa, pieniä lisäyksiä.

**14.11.2020** Korjattiin koodia täydäntävien pisteiden lisäämisessä taulukkoon.
Kokeiluja pdf-tulostuksen kanssa, ei vieläkään toimi mutta virheilmoitukset muuttuneet.
Korjailtiin teorialiitteen kaavoja, poistettiin toiset kaava-labelit sieltä
 missä niitä oli. Kommentoitiin pois testitulostuksia MCA-luvussa.

 **15.11.2020** Vaihdettu latex MikTeX -> TinyTeX, ja latex-kääntäjä pdflatex->
 xelatex. Index.Rmd - tiedostossa "korkeimman tason" YAML-asetusksissa
 margin = 0.9in jotta dokumenttitaulukko mahtuisi pdf-tulostuksessa sivulle.
 PDF-tulostus kaatuu koodiliitteeseen, lokit ja tex-tiedosto luettavissa. PDF
 saadaan "melkein", mutta sisällysluettelo puuttuu.

 **16.11.2020** Teksti johdattelevaan esimerkkiin (3.1 - 3.3).

 **16.11.2020 Versio 0.65** Tekstiä lukuun 3, asymmetriset kartat.

 **16.11.2020** Luku 3 tehty, on vielä editoitavaa.

 **17.11.2020** Kokeiluja pdf-tulostuksella, vailla ratkaisua.

 **17.11.2020** Luku neljä lähes valmis, numeeriset tulokset selitetty. Github Desktop päivitys.

**18.11.2020** Pieniä korjauksia ja editointeja. Tarkistettiin koodilohkot, kaikissa viimeisenä tyhjä rivi (newline). Tekstistä
ei löydy inline R - koodin aloitusmerkintöjä (`r). PDF-virheilmoitus tuttu "Dimenison too large", näyttäisi viittaavan
r-koodin automaattitulostukseen teknisessä liitteessä. TUlostus kaatuu, viitetiedot yms. jää pois.

**18.11.2020** Pieniä korjauksia, muutama muistiinpano tekstin
 tarkistuksen tueksi (määritelmiä jne), uusi viite yhteenvetolukuun. Kokeillaan uutta
 tex-preamble-tiedostoa.

 **19.11.2020 versio 0.7** Luku 5 kirjoitettu, pieniä korjauksia ja editointeja
 muualla. Viitetietokantaa korjattu (erikoismerkit).

 **21.11.2020** Pieniä lisäyksiä, muutama viite. Korjasin R-pakettien bibtex-tiedostossa
 Mullerin nimen "saksalaisen y-kirjaimen" kelvolliseksi. Lähdeluettelo ennen liitteitä,
 voi vaihtaa takaisin tarvittaessa.

 **21.11.2020 versio 0.8** Subset-analyysit valmiit, liikaa numeeristen tulosten listauksia. Tekstiä viimeisteltävä, muutama
 kappale teoriasta lisättävä.

 **22.11.2020** Lisättiin kolme pdf-tiedostoa: kansilehti, sisällysluettelo ja tiivistelmä.
 Kansilehti ja tiivistelmä OverLeafissa, sisällysluettelo tehty MS Wordillä.

**22.11.2020** Pieniä muutoksia rakenteeseen, tekstin editointia ja korjailua.

**23.11.2020** Johdatantokappale lukuun 6, pieniä korjauksia ja editointeja.

**23.11.2020** Tekstin editointia, viitteiden lisäyksiä ja tarkistuksia.

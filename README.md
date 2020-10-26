Tutkielma R Markdownilla ja **bookdown** - paketilla. (https://github.com/rstudio/bookdown). Bookdownin ohjeet löytyvät täältä  (https://bookdown.org/). Oma testidokumentti on (https://hirjus.github.io/test1/).

**31.7.2018**

Tutkielman lopullinen versio bookdown-paketilla, pohjana esimerkkiprojekti.

Kopioidaan suoraan testi-projektin asetustiedostot tähän projektiin.

**1.8.2018** pieniä korjailuja, lukujen otsikoita.

- Rmd-tiedostot luetellaan _bookdown.yml-tiedostossa
- kasitteet1.Rmd - df käsitteistä

## Hakemistot - GitHub

**docs** pdf- ja htlm-tulosteet

**bddefaults** bookdown-paketin oletuskonfiguraatiot (YAML- front matter index.Rmd-tiedostossa, _output.yml, 		_bookdown.yml)

## Muut hakemistot RStudion projektissa

**data** 	SPSS-tiedosto, tekstitiedosto muuttujakuvauksista
**ark**		arkisto
**test**	yksittäisiä Rmd-sivuja, joilla saan yhden Rmd-tiedoston tulostuksen toimimaan. preview_chapter() ei toimi
		odotetulla tavalla projektin juuressa, eikä RStudion knit-nappi, vaan aina tulostuu koko dokumentti.

**3.8.2018**

Lisäsin test-hakemiston, jossa voi rakennella r-koodia. Siellä toimii yhden Rmd-tiedoston tulostus. output.yml - tiedostoon output-optioksi myös html_book.

**8.8.2018**

Lähdeviitteet toimivat, johdantoon hieman jäsentelyä. Tulostusvaihtoehtona on myös html-book, siinä saa tarvittaessa koodin piilotuksen toimimaan. Ei onnistu gitbook-formaatissa, vaatii teeman käyttöä.

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

 **23.10.2020 Versio 0.20** Karkea sisällysluettelo, hieman **k**appaleiden sisältöjä ja muistiinpanoja rakenteesta.

 **23.10.2020 Versio 0.30**  Karttoja yksinkertaisen ca-esimerkin loppuun asti. Muutettiin pdf-dokumentin nimi JH_ca.pdf -> JH_capaper.

 **24.10.2020** Belgian ja saksan jako, symmetrinen ja kontribuutiokartta. Uusi
  bib-tiedosto (RefWorks-lähteet). PDF-tulostus kaatuu aluejako-taulukkoon tai
	sitä edeltävään koodilohkoon. CA-numeeriset tulokset ja kolmiulotteinen ratkaisu.
	summary() - funktio ei toimi 3d-ca-objektilla jostain syystä.

	Ikä-sukupuoli ja ikä-sukupuoli-maa yhdysvaikutusmuuttujat luotu, molemmilla
	yksi kartta.

	**25.10.2020** PDF-tulostus ei toimi, julkaistan myös "html_book" yhtenä tiedostona, voi tulostaa selaimella pdf-muotoon.

	**26.10.2020**

	PDF-tulostus ei toimi, ei välitetä tästä. Lokitiedot ja tex-tiedosto, josta saan
	"suoraan" renderöityä jonkinlaisen pdf-tulosteen, mutta ilman lähdeviitteitä jne.
	Editointia, jäsentelyä loppulukuihin.
	**26.10.2020**
	Analyysi ja kommenteja lisätty subsetCA-jakson loppuun. Muutama tulostus mukana
	CA:n numerisista tuloksista, poistetaan niistä suurin osa kun teksti on valmis.

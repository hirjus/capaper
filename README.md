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

Jäsentelyä data-lukuun. Lisäsin ISSP-viitteitä RefWorksiin, ja ne rikkoivat PDF-version viitteidenhallinnan, nyt vain gitbook-tuloste. Korjaillaan,
tai poistetaan, ISSP-dokumentaatioon on hankalaa viitata. www.gesis.org on sekava sivusto!

**11.8.2018**

Pieniä lisäyksiä tekstiin, lähdeviitteitä, skandien aiheuttamia ongelmia kummasteltu bibtex - viitekannan pdf-käsittelyssä. PDF ja gitbook toimivat, tallennetaan ark-hakemistoon nämä.

********************************************************************************************************************************
README
********************************************************************************************************************************
MIAULXRAFFE Projekti(Movie Information APP Using Live XML-REST API from Finnkino (Easy))
R0331 - Web sovellusten kehitt�minen JavaScriptill� 

Tekij�t: Huotari Valtteri ja Kainuulainen Otto


********************************************************************************************************************************

Sis�llys:

-Etusivu_VALMIS.html- Lopullinen ja valmis versio sovelluksesta
-Etusivu.html- Sovelluksen ty�st�mis-versio
-style.css - sovelluksen k�ytt�m� tyylitiedosto
-Mockup.png - konseptikuva sovelluksesta
-background.jpg - sovelluksen k�ytt�m� bannerikuva
-filmi.jpg - Sovelluksen k�ytt�m� kuva valikoiden yl� ja alapuolella.


********************************************************************************************************************************

SOVELLUS JA SEN K�YTT�:

Sovellus on yksinkertainen web-sovellus, jolla k�yt�tj� voi tarkistaa Suomen Finnkinon ohjelmiston realiajassa. Sovellus hakee
Finnkinon ohjelmistotiedot Finnkinon omalta REST API datasta. N�in sovellus pysyy ajantasalla Finnkinolla tapahtuvitsa
muutoksista, kunhan Finnkino pit�� datansa ajantasalla. 


Valikot
 
 -Sovelluksella on kolme vierekk�sit� valikkoa:
 	-teattereille/aluelle, josta k�ytt�j� voi valita mink� tahansa Suomen Finnkino teattereista
	-p�iv�m��r�lle, josta k�ytt�j� voi etsi� tietyn p�iv�n ohjelmiston
	-elokuvalle, josta k�ytt�j� voi etsi� tietty� elokuvaa, joka Finnkinolla on ohjelmistossa.

"N�yt� ohjelmisto" -nappi

 -Napin kautta ohjelma tarkistaa valikoihin asetetut hakukriteerit ja tuo esiin kriteerien perusteella
  ohjelmiston listaksi. HUOM! jos teatteria tai aluetta ei valita, tuo ohjelma kaikki Suomen Finnkinon elokuvat.
 -Ohjelmisto tiedoissa on elokuva nimi, n�yt�s aika ja n�yt�ksen teatteri/alue.
 
Ohjelmisto

 -Ohjelmisto tulee n�kyviin ensimm�ist� kertaa, kun "N�yt� ohjelmisto" -nappia painetaan.
 -Ohjelmisto p�ivitt�� listan, kun hakukriteerit muuttuvat ja nappia painetaan uudestaan.
 -Ohjelmisto n�ytt�� elokuvan nimen, n�yt�sajan ja n�yt�ksen teatterin/alueen.



********************************************************************************************************************************

HUOMATUS!

Sovellus k�ytt�� JavaScripti� ja jQuery:�, joten jotkin selaimet ja palomuurit est�v�n sovelluksen toiminnan.
 
********************************************************************************************************************************
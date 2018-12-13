********************************************************************************************************************************
README
********************************************************************************************************************************
MIAULXRAFFE Projekti(Movie Information APP Using Live XML-REST API from Finnkino (Easy))
R0331 - Web sovellusten kehittäminen JavaScriptillä 

Tekijät: Huotari Valtteri ja Kainuulainen Otto


********************************************************************************************************************************

Sisällys:

-Etusivu_VALMIS.html- Lopullinen ja valmis versio sovelluksesta
-Etusivu.html- Sovelluksen työstämis-versio
-style.css - sovelluksen käyttämä tyylitiedosto
-Mockup.png - konseptikuva sovelluksesta
-background.jpg - sovelluksen käyttämä bannerikuva
-filmi.jpg - Sovelluksen käyttämä kuva valikoiden ylä ja alapuolella.


********************************************************************************************************************************

SOVELLUS JA SEN KÄYTTÖ:

Sovellus on yksinkertainen web-sovellus, jolla käytätjä voi tarkistaa Suomen Finnkinon ohjelmiston realiajassa. Sovellus hakee
Finnkinon ohjelmistotiedot Finnkinon omalta REST API datasta. Näin sovellus pysyy ajantasalla Finnkinolla tapahtuvitsa
muutoksista, kunhan Finnkino pitää datansa ajantasalla. 


Valikot
 
 -Sovelluksella on kolme vierekkäsitä valikkoa:
 	-teattereille/aluelle, josta käyttäjä voi valita minkä tahansa Suomen Finnkino teattereista
	-päivämäärälle, josta käyttäjä voi etsiä tietyn päivän ohjelmiston
	-elokuvalle, josta käyttäjä voi etsiä tiettyä elokuvaa, joka Finnkinolla on ohjelmistossa.

"Näytä ohjelmisto" -nappi

 -Napin kautta ohjelma tarkistaa valikoihin asetetut hakukriteerit ja tuo esiin kriteerien perusteella
  ohjelmiston listaksi. HUOM! jos teatteria tai aluetta ei valita, tuo ohjelma kaikki Suomen Finnkinon elokuvat.
 -Ohjelmisto tiedoissa on elokuva nimi, näytös aika ja näytöksen teatteri/alue.
 
Ohjelmisto

 -Ohjelmisto tulee näkyviin ensimmäistä kertaa, kun "Näytä ohjelmisto" -nappia painetaan.
 -Ohjelmisto päivittää listan, kun hakukriteerit muuttuvat ja nappia painetaan uudestaan.
 -Ohjelmisto näyttää elokuvan nimen, näytösajan ja näytöksen teatterin/alueen.



********************************************************************************************************************************

HUOMATUS!

Sovellus käyttää JavaScriptiä ja jQuery:ä, joten jotkin selaimet ja palomuurit estävän sovelluksen toiminnan.
 
********************************************************************************************************************************
# Procesverslag
Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door *open* toe te voegen aan een *details* element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.





## Jij

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Auteur:
  Matthew Tangkilissan 

  #### Je startniveau:
  startniveau: rood

  #### Je focus:
  focus: responsive
 
</details>





## Je website

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Je opdracht:
  https://professor-e.com/

  #### Screenshot(s) van de eerste pagina (small screen): 
  hoofdpagina
  <img src="readme-images/smallscreen_hoofdpagina.png" width="375px" alt="mobiele versie van de homepagina">

  #### Screenshot(s) van de tweede pagina (small screen):
  detailpagina
  <img src="readme-images/smallscreen_detailpagina.jpg" width="375px" alt="mobiele versie van de detailpagina">
 
</details>



## Toegankelijkheidstest 1/2 (week 1)

<details>
  <summary>uitwerken na test in 1e werkgroep</summary>

  ### Bevindingen
  - Een screenreader is bijna niet te gebruiken op de echte website van professor E.
  - Tabben werkt heel primitief en laat ook key details eruit.
  - Vanwege de simplistische lay-out is de site wel te gebruiken met eventuele motorische beperkingen.
  - Site is nog steeds te gebruiken met visuele beperkingen behalve met blurred vision. Tekst in buttons zijn lastig te lezen.


  #### Screenreader
  Dropdown menu wordt niet uitgelezen
  Afbeeldingen zijn niet goed beschreven
  Er missen links bij het bestellen
  Prijs niet zichtbaar bij bestellen
  Voorpagina link tekst klopt niet 

 
  Pas de alt aan voor alle afbeeldingen. Is op dit moment nog te veel herhaling van de titel in de screenreader.
  Geef buttons een beschrijving van functie i.p.v "button 1, button 2, button 3" etc.
  Logo aanpassen zodat het niet alleen maar wordt voorgelezen als link.



  #### Muis en Toetsenbord 
  met tabben heb je drie links op categorie scherm: 
    -Afbeelding
    -Naam
    -Prijs
  Met tabben in winkelwagen prijs niet zichtbaar

  
  Tabben werkt over het algemeen naar behoren. Alleen is het nu niet te zien waar de focus zich bevind als de caroussel buttons worden geselecteerd. Ook gaat tabt hij de colom verticaal i.p.v de rij met opties horizontaal af te gaan. Pas grid aan zodat er van links naar rechts gelezen wordt. Vergroot border van focus state en geef een scherpere kleur als je door de caroussel tabt.

  #### Motoriek (shocks, elastiekjes)
  
  De website was te navigeren met het shock apparaat. Het scrollen en klikken verloopt redelijk normaal. Hetzelfde geldt bij het gebruik van de elastiekjes. Als je wilt bestellen ontstaan er problemen. Een formulier selecteren en typen verloopt heel lastig.

  Al het scroll en klikwerk gaat prima. Detail werk als iets moeten typen verloopt nog moeizaam maar dit is een hardware probleem en ligt niet aan de site.


  #### Visueel (brillen, contrast, kleurenblind, dark/light). 
  Met de brillen was de site nog steeds goed leesbaar. De enige kleuren die gebruikt worden door de site zijn zwart en wit. Alleen als je het scherm op blurred zet wordt het lastig. Tekst is dan soms niet te onderscheiden van de achtergrond.

  Dit is makkelijk aan te passen door de kleur van de tekst te veranderen.

</details>



## Breakdownschets (week 1)

<details>
  <summary>uitwerken na afloop 2e werkgroep</summary>

  ### de hele pagina: 
  <img src="readme-images/breakdownschets1.png" width="375px" alt="breakdown van de hele pagina">

  ### dynamisch deel (bijv menu): 
  <img src="readme-images/breakdownschets2.png" width="375px" alt="breakdown van een dynamisch deel">

 

</details>





## Voortgang 1 (week 2)

<details>
  <summary>uitwerken voor 1e voortgang</summary>

  ### Stand van zaken
  Wat goed ging:
  -Het opstellen van de HTML
  -Het verbinden met de CSS
  -Het verbinden met de JS

  Wat ging lastig:
  -Al het andere
  -Images importeren in HD
  -Files de juiste naam geven zodat ze daadwerkelijk op je website verschijnen


  ### Agenda voor meeting
  samen met je groepje opstellen

  | Ryan      | Charity         | Quinty  | Matthew       
  | ---            | ---                | ---          
  | dit bespreken  | en dit             | -Moet je ook alle animaties overnemen?         
  | en dat ook nog | dit als er tijd is | -Wordt jouw site naast de echte site gezet en vergeleken
  | ...            | ...                |           


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - Je site hoeft geen complete kopie te zijn van de echte website.
  - Vermijd divs en classes zoveel mogelijk.
  

</details>





## Voortgang 2 (week 3)

<details>
  <summary>uitwerken voor 2e voortgang</summary>

  ### Stand van zaken
  Dit ging goed:
  -Alle elementen staan nu op volgorde op de website en keurig in de HTML
  -De basis lay-out is gelegde met CSS

  Dit ging lastig:
  -Hamburger menu begreep ik niet en wou niet meewerken.
  -Grid weigerde te luisteren.
  



  ### Agenda voor meeting
  samen met je groepje opstellen

  | Ryan     | Quinty         | Charity   | Matthew       
  | ---            | ---                | ---          
  | dit bespreken  | en dit             |  Hoe kan ik individuele elementen selecteren in css zonder classes? 
  | en dat ook nog | dit als er tijd is |  Wat doe ik verkeerd bij mijn hamburger menu?
  | ...            | ...                |  


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - Breng je hamburgermenu button buiten de nav.
  - Gebruik direct-child selectors and attribute selectors
  


</details>





## Toegankelijkheidstest 2/2 (week 4)

<details>
  <summary>uitwerken na test in 8e werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen (geef ook aan wat er verbeterd is):

  #### Screenreader
  Hier korte omschrijving (met indien nodig afbeeldingen)

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)


  #### Muis en Toetsenbord 
  Hier korte omschrijving (met indien nodig afbeeldingen)

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)


  #### Motoriek (shocks, elastiekjes)
  Hier korte omschrijving (met indien nodig afbeeldingen)

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)


  #### Visueel (brillen, contrast, kleurenblind, dark/light). 
  Hier korte omschrijving (met indien nodig afbeeldingen)

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)

</details>





## Voortgang 3 (week 4)

<details>
  <summary>uitwerken voor 3e voortgang</summary>

  Ik was ziek deze week en dus ook niet aanwezig

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
  - ...

</details>





## Eindgesprek (week 5)

<details>
  <summary>uitwerken voor eindgesprek</summary>

  ### Je uitkomst - karakteristiek screenshots:
  <img src="readme-images/karakter.png" width="375px" alt="uitomst opdracht 1">


  ### Dit ging goed/Heb ik geleerd: 
  Korte omschrijving met plaatjes

  <img src="./readme-images/responsive.png" width="375px" alt="top">


  ### Dit was lastig/Is niet gelukt:
  Korte omschrijving met plaatjes

  <img src="./readme-images/jammer.png" width="375px" alt="bummer">
</details>





## Bronnenlijst

<details open>
  <summary>continu bijhouden terwijl je werkt</summary>

  Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg).

  1. bron 1
  2. bron 2
  3. ...

</details>
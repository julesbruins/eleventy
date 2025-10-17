# Eleventy
My first try outs with 11ty. 

## USER EXPERIENCE (UX)
De doelgroep vanuit UX gezien, de eindgebruikers, zijn de mensen die vooral kijken naar informatieve websites. Het zijn geen grote ingewikkelde websites met allerlei dynamische data of een webshop bijvoorbeeld. Voorbeelden van de doelgroep kunnen bijvoorbeeld de wat kleinere bedrijven zijn, die gewoon informatie vertellen over hun bedrijf. Een ander voorbeeld zijn educatie en non-profit bedrijf. Instellingen voornamelijk gericht op het overdragen van informatie. 

De tech geletterdheid ligt over het algemeen niet extreem hoog. Gewoon mensen die op zoek naar informatie over een bedrijf, persoon of instelling. 

De bepaalde randvoorwaarden die erbij komen kijken is dat de site snel moet laden. Mensen willen niet te lang wachten hun informatie tot beschikking te krijgen. Het moet responsief zijn, want gebruikers zullen gebruik maken van allerlei verschillende devices. 
Verder moet het niet te ingewikkeld zijn en voornamelijk heel duidelijk. 
Ook moet het werken op verschillende browsers en toegankelijk zijn voor iedereen. Van slechtziende en blinde mensen tot aan mensen met epilepsie die Javascript uitzetten om animaties te voorkomen.


### Toegankelijkheid 
De screen reader en tabben door de pagina heen werkt gemakkelijk. Er is makkelijk een kopstructuren aan te brengen (h1 tot h6). Ook is het gebruiken van een link etc erg gemakkelijk. De site is verder voor alle gebruikers toegankelijk zolang er responsive gebouwd wordt. Ook is die toegankelijk voor alle moderne en oude browsers die standaard HTML ondersteunen. De CSS en JS zijn niet noodzakelijk en dus optioneel, de site werkt helemaal prima zonder.

### Performance
Eleventy genereert volledige statische HTML bij build-tijd, dus bezoekers krijgen direct kant-en-klare pagina’s. Er wordt geen zware client-side frameworks toegepast dat eerst moet laden, dit zorgt dus voor snellere laadtijden.



## DEVELOPER EXPERIENCE (DX)

### Functie
Wat Eleventy doet is het neemt content (Markdown, JSON, HTML, etc.) en templates en genereert daar HTML pagina’s van. Het is ook wel een Static site generator genoemd. Hiermee kunnen ze snel en gemakkelijk sites deployen. Een voordeel vanuit DX gezien is dat er geen ingewikkelde server side redering of complexere frameworks gebruikt worden. Alles wordt Build-tijd omgezet naar statische HTML. 

### Betrouwbaarheid
Statische websites zorgen over het algemeen voor een stuk meer stabiliteit. Er wordt zo bijvoorbeeld geen gebruik gemaakt van backend wat meer crashes kan veroorzaken. Ook is er weinig onderhoudsdruk. Omdat alles bij build-tijd wordt gegenereerd, krijg je altijd dezelfde output voor dezelfde input. De fouten zijn vaak gemakkelijk op te lossen omdat het build-time gebeurt. 

### Documentatie
De documentatie van 11ty is erg duidelijk. Er zijn veel bronnen. Zo heb ik zelf een heel eerst mini project kunnen opzetten met 1 bron alleen al. Verder is het gemakkelijk problemen op te lossen of inspiratie op te doen, ze zijn op bijvoorbeeld discord en reddit. Er wordt gebruik gemaakt van handige shortcuts, statische bestanden kunnen omgezet worden en zo kan er ook gefilterd worden en Eleventy integreert goed. 

### Heldere Interface
Als developer is Eleventy goed overzichtelijk. Het is niet erg ingewikkeld en ziet er logisch uit. 



## CONTENT MANAGEMENT EXPERIENCE
Over algemeen is Eleventy niet het meest ingewikkeld. Om bijvoorbeeld tekst te kunnen wijzigen is geen code kennis nodig, dit kan al simpel op bijvoorbeeld Github. Het Markdown bestand kan zo gewijzigd worden en het wordt automatisch op de website aangepast,. Wil er echt een nieuwe pagina of iets dergelijks aangemaakt/gewijzigd worden moet er lichte HTML kennis zijn. Dit voor meer rich content. De mappenstructuur moet begrepen worden. Voor content die gebruik maakt van shortcodes, includes of custom filters, is een basiskennis van templating nodig om fouten te voorkomen.

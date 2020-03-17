#Portfolio Timo Jenkins

##Week 2
In week 2 zijn we begonnen met het ontwerpen en implementeren van de agenda modullen.
Als eerste hebben we met zijn alle gekeken wat er voor klassen er moesten komen.
Toen we het klasse diagram gemaakt hadden hebben we de verschillende klasse verdeeld.
Ik heb de taak gekregen om de artist klasse te maken. Ook moest het plan van
aanpak nog worden afgemaakt. Deze week had ik verder nog geen taken gekregen waardoor
ik al snel klaar was met mijn deel.

**Wat is de situatie(context)?**
Ik moest de artist klasse maken.

**Welke keuzemogelijkheden heb je?**
Bij een artiest moest een genre, soort artiest en een afbeelding kunnen worden opgeslagen.
Ik moest dus een beslissing maken hoe ik dit ging opslaan.

**Welke keuze heb je gemaakt?**
Het genre sla ik op als String, de soort artiest sla ik ook op als String en de afbeelding
sla ik op als image.

**Waarom heb je deze keuze gemaakt?**
Bij het genre en een soort artiest is het gemakkelijk om dit op te slaan als String,
ik zou namelijk niet weten hoe ik dit anders beter kan doen. Ook wist ik niets anders om 
de afbeelding op te slaan dan image.

##Week 3
In week 3 heb ik samen met Nathalie de map gemaakt voor ons festival in Tiled.
Ook is aan ons de taak gegeven om de hoofdstukken van het plan van aanpak
die niet voor de proftaak nodig waren maar wel voor P&OC, te maken.

**Wat is de situatie(context)?**
Een tiledmap maken met Tiled

**Welke keuzemogelijkheden heb je?**
We hadden veel keuzemogelijkheden dit keer. Wat voor tile maps we gaan gebruiken, hoe groot we
onze tile map gaan maken en hoe onze tile map eruit komt te zien.

**Welke keuze heb je gemaakt?**
We hebben gekozen voor een tile map van 50 bij 50. We gaan 3 verschillende soorten tile maps gebruiken
en onze tile map komt er als volgt uit te zien: 
![](map-schets.jpg)

**Waarom heb je deze keuze gemaakt?**
Een tile map van 50 bij 50 leek ons wel groot genoeg. We hebben gekozen voor 3 verschillende soorten tile maps
omdat we uit elke tile map iets wilde gebruiken voor ons festival. Het kiezen van het ontwerp van onze map is 
gewoon langzamer hand gekomen. We zijn hiermee gewoon begonnen door te gaan tekenen en kijken hoe het er mooi uit zag.

##Week 4
In week 4 hebben we geprobeerd de map uit te lezen als een json file.
In het begin ging dit nogal stroef doordat het json file vanuit het voorbeeld niet overeen kwam met dat van ons. Na eerst
nog wat onderzoek te hebben gedaan op internet waar het eigenlijk niet duidelijker van werdt ben ik toch maar dingen gaan proberen.
Tijdens het proberen van verschillende dingen werdt het steeds duidelijker. Uiteindelijk is het dus gelukt om een json
uit te laten lezen.

**Wat is de situatie(context)?**
Json file uitlaten lezen

**Welke keuzemogelijkheden heb je?**
Waar moet het uitlezen van de map gedaan worden en hoe gaat dit er uitzien qua ontwerp?

**Welke keuze heb je gemaakt?**
Het uitlezen van de map hebben we in een apparte module gemaakt. Verder hebben we eigenlijk dezelfde klasse als het voorbeeld.
Een klasse mapDemo en Map. Ook hebben we nog een apparte klasse voor Tilelayer gemaakt.

**Waarom heb je deze keuze gemaakt?**
We hebben het uitlezen van de map in een apparte module gedaan zodat dit geen problemen gaf met de agenda module. Zo
kunnen we eerst alles goed laten werken en testen voor we het bij elkaar gaan doen. De klasse die we hebben gekozen is 
eigenlijk grootten deels door het voorbeeld. We hebben het voorbeeld namelijk gewoon aangehouden.

##Week 5
In week 5 hebben we de map nog wat uitgebreid. De projectgroep vond hem namelijk
iets te klein. Ook zijn er nog wat uitbreidingen gemaakt op de map. Ook hebben we de code wat verbeterd voor het uitlezen van de file.

**Wat is de situatie(context)?**
De map is verbeterd en het uitlezen van de map is verbeterd.

**Welke keuzemogelijkheden heb je?**
Hoe groot moet de map uiteindlijk dan zijn? Gaan de bezoekers en de artiesten door elkaar heen lopen op het festival?
Wat moet er verbeterd worden aan het uitlezen van de map?

**Welke keuze heb je gemaakt?**
De map is nu uiteindelijk 110 bij 80. Dit vonden we allemaal een prima formaat. We hebben gekozen om voor de artiesten
een apart pad achter het festival te maken. Zo lopen de bezoekers en de artiesten niet door elkaar heen. Er is een nieuwe
klasse Tilelayer bijgekomen.

**Waarom heb je deze keuze gemaakt?**
We hebben de grootte van de map gewoon een beetje op gevoel gekozen. We vonden de grootte die we nu hebben wel er gewoon
goed uitzien. Op een festival zie je de artiesten ook niet echt door de bezoekers heenlopen. Daarom hebben we
hier een apart pad voor gemaakt. Er is een nieuwe klasse Tilelayer aangemaakt zodat er van iedere layer makkelijker
eigenschappen kan worden opgevraagd. Zoals bijvoorbeeld of de tilelayer wel visible is.

##Week 6
In week 6 hebben we een collision en object laag gemaakt in onze map.
Hierna zijn we begonnen aan het implementeren van de path finding.

**Wat is de situatie(context)?**

In deze week moeten we een keuze maken wat voor algoritmen we gaan gebruiken voor de path finding.
In het begin van het project had onze project groep het vooral over het A* algoritmen.

**Welke keuzemogelijkheden heb je?**

- A* star algoritmen
- Depth first algoritmen
- Breath first algoritmen

**Welke keuze heb je gemaakt?**

We hebben gekozen voor het breath first algoritmen.

**Waarom heb je deze keuze gemaakt?**

Deze keuze hebben we gemaakt omdat we hier ten eerste veel informatie over hebben gehad. 
Ook bleek het A* algoritmen niet goed te werken bij veel NPC's, aangezien ons festival meer
dan 100 NPC's krijgt zijn we dus van deze methode afgestapt. Hierdoor hadden we dus nog de keuze
tussen depth first en breath first. Uit de informatie die we in de les OGP hebben gekregen bleek
dat breath first een beter algoritmen is om de kortste route te krijgen. Daarom hebben we hiervoor gekozen.

##Week 7
Deze week was er geen opstart college. Dit is ook de eerste week dat de school dicht is ivm het corona virus.
We hebben deze week via discord vergaderd om te kijken wat de voortgang van ons project is. Verder moet deze week de
path finding af worden gemaakt. Ook moet er van de tiled map één afbeelding van worden gemaakt zodat het
renderen van de map soepel gaat. Vorige week was ik hier
ook al naar aan het kijken, helaas was me het nog niet gelukt om goed te implementeren.

**Wat is de situatie(context)?**
De tiled map beweegt haperig bij het renderen

**Welke keuzemogelijkheden heb je?**
De enige manier die ik kan bedenken is van de tiled map één afbeelding maken.

**Welke keuze heb je gemaakt?**
Van de tiled map één afbeelding maken doormiddel van setRGB en getRGB.

**Waarom heb je deze keuze gemaakt?**
Verder kon ik eigenlijk niet echt een andere oplossing bedenken.

##Week 8

**Wat is de situatie(context)?**

**Welke keuzemogelijkheden heb je?**

**Welke keuze heb je gemaakt?**

**Waarom heb je deze keuze gemaakt?**

##Week 9

**Wat is de situatie(context)?**

**Welke keuzemogelijkheden heb je?**

**Welke keuze heb je gemaakt?**

**Waarom heb je deze keuze gemaakt?**
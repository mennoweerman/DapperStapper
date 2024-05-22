# Dapper Stapper

In deze repository vind je de informatie over het project Dapper Stapper.

De opdracht is om een game te maken voor de klant gemeente Amsterdam. Het doel voor de klant is om een game te hebben waarmee ze nieuwe collega's binnen Amsterdam Oost een leuke rondleiding door de stad kunnen geven.
Het idee van onze game is dat je in het echt door de Dapperbuurt in Amsterdam Oost loopt en dan in de game kan zien waar je bent en een soort speurtocht volgt via instructies. De instructies zien er bijvoorbeeld zo uit: "ga nu richting de rode deur". 

# Geproduceerde Game Onderdelen
  
Menno Weerman:
  * [Point Information](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-point-information)
  * [Gps](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-point-information)
  * [Game Intro](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-point-information)
  * [Main Menu](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-point-information)
  * [Mini Game](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-point-information)
  * [New Game](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-point-information)
      

Patricia Kuipers:
  * [Quiz](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-quiz)
  * [Hints](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-hints)
  * Collectables - Code te vinden bij [Quiz](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-quiz)
    
Bart de Boer:
  * [Inventaris](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-inventaris)
  * [GPS berekening](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints-%E2%80%90-Bart#-gps)
  * [Inventaris update](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints-%E2%80%90-Bart#-inventaris-update)

## Point Information door Menno Weerman

Als je de point of interest aanklikt, krijg je een widget voor je waarop je informatie krijgt van een mascotte op het scherm. Doormiddel van de next knop kan je naar de volgende slide gaan en meer informatie krijgen en met de previous knop terug gaan naar de slide ervoor. Hierin vertelt de mascotte wat over de locatie

![Visual Sheet Point Information](https://github.com/mennoweerman/OostQuest/assets/70953228/2c3aec7a-5492-426b-9afd-2e60cb7e2ae2)

## GPS door Menno Weerman

Gebaseerd op de gps locatie beweegt het poppetje naar de goeie locatie op de kaart. Dit is gemaakt om het een echte wandelsimulatie te maken. Voor meer informatie klik hier: https://github.com/mennoweerman/DapperStapper/wiki/Technisch-Ontwerp#gps


## Game Intro door Menno Weerman

Als je een nieuwe game opstart, komt pieter paaltje in je beeld en geeft je uitleg over de dapperbuurt. Als je dit afgerond hebt begint het spel.

![image](https://github.com/mennoweerman/DapperStapper/assets/70953228/02c9244c-bab1-445b-b376-bc4150e48098)

## Main Menu door Menno Weerman

Als je de game opstart, komt de main menu op het scherm, als je nog geen save hebt staan er 2 knoppen. Een om de game te starten en een om het spel af te sluiten. 
![image](https://github.com/mennoweerman/DapperStapper/assets/70953228/65b497fa-c1a1-420d-b225-9484cd3a86f3)
Mocht je wel een save hebben, dan heb je een om een nieuwe game te starten, een button om verder te gaan met de huidige save en een om het spel af te sluiten.

![image](https://github.com/mennoweerman/DapperStapper/assets/70953228/3fe00ee9-6473-48fd-8aab-f5bbad4b80fa)


## Mini Game door Menno Weerman

Als je bij de dappermarkt bent, dan zal je een minigame krijgen voor het tellen van de reigers. Dit hebben we om de game leuk te houden en proberen de meeste reigers te tellen. Dit word opgeslagen in een aparte save file dus de high score van het tellen wordt opgeslagen op het apparaat.

![image](https://github.com/mennoweerman/DapperStapper/assets/70953228/994c1562-4f32-4fc7-a9a6-76c596b90283)

## New Game door Menno Weerman

Als je op de knop klikt. Word je oude save verwijdert en een nieuwe aangemaakt en gebruikt.

![image](https://github.com/mennoweerman/DapperStapper/assets/70953228/d8422a75-d622-42fb-92a3-4630535773e8)



## Quiz, Hints & Collectables door Patricia Kuipers

Als je een Point of Interest bezoekt en je hebt de informatie ervan gelezen, kun je vervolgens een quiz doen. Je kunt de quiz ten allen tijde sluiten. 

In de video hieronder zie je de Quiz, de Hints en de Collectables:

https://github.com/mennoweerman/DapperStapper/assets/54790202/0343c2c0-0353-41f8-9936-695f995e470e

Eerst tikt de speler een punt aan en krijgt informatie. Nadat de informatie is doorgelezen, krijgt hij als er geen quiz bij dit punt hoort, de hint om het volgende punt te vinden. Dit is een tekstje met een model erbij van iets wat hij in het echt kan zoeken.

Mocht de speler verdwaalt zijn geraakt of zijn vorige hint vergeten zijn, dan kan hij altijd linksboven op het knopje drukken om de vorige hint nogmaals op het scherm te laten zien.

Bij sommige punten hoort wel een quiz, dus als de speler op een punt met quiz tikt en de informatie heeft doorgelezen, krijgt hij vervolgens de quiz voor zich. Als hij een antwoord kiest, wordt het groen of rood, aan de hand van of het correct was of niet. Als de speler het juiste antwoord geeft, gaat de quiz verder, en anders kan hij het nogmaals proberen. De speler heeft gewoon de mogelijkheid om door te blijven klikken tot hij het goed heeft, dit om te voorkomen dat het te lastig wordt en/of de speler maar één kans krijgt. 

Aan het einde van de quiz krijgt de speler een collectable, die wordt laten zien en draait rond, net zoals de hint. De speler kan er op tikken om verder te gaan. In de code wordt bijgehouden of de speler deze collectable al heeft, dat zie je ook aan het kopje tekst wat er onder de collectable verschijnt. 

De quiz is volledig instelbaar. Hij kan worden aangepast in de inspector.

![image](https://github.com/mennoweerman/OostQuest/assets/54790202/96603f7d-7aac-4784-9e15-09d9f318ae83)

Je kunt per locatie (Point of Interest) instellen welke vragen erbij horen en welke collectable je daar kan krijgen. Ook kun je per vraag instellen welke antwoorden erbij horen en per antwoord kiezen of dat het juiste antwoord is of niet. 

![SplineInspector01](https://github.com/mennoweerman/DapperStapper/assets/54790202/cad04d21-f2c7-497b-a199-97a8b55d7d11)

De hints zijn instelbaar aan de hand van (X,Y,Z) waardes die je in een Map zet (punt 1). Daarbij kun je de tekst van de hint (punt 2) instellen en de mesh die er bij de hint op het scherm komt te staan (punt 3). 

![SplineInspector01](https://github.com/mennoweerman/DapperStapper/assets/54790202/3c862610-96e4-46fa-a26f-05834300a2f3)

Het is makkelijk om de juiste (X,Y,Z) waardes te krijgen door gebruik te maken van de punten op de spline die langs de hele route loopt. Je kunt deze punten selecteren en gemakkelijk hun positie copy-pasten om te gebruiken voor de hints. 

![Spline](https://github.com/mennoweerman/DapperStapper/assets/54790202/c0490954-6c20-40cc-b3ae-bd4f518b47ac)

Hier zie je de spline in detail. Alle witte puntjes die erop zitten zijn punten waarvan je de coordinaten makkelijk kan kopiëren en gebruiken voor hints, maar je kunt ze ook verplaatsen en nieuwe punten op de spline aanmaken.

## Inventaris door Bart de Boer

Deze feature is een inventaris waarin je kan zien welke collectables je al gevonden hebt in de game. Waneer je op de inventaris knop drukt komt er een plane over de gameplay waardoor je alleen nog maar de inventaris, collectables en de knop ziet waarmee je de inventaris sluit.

![InventarisSheet1](https://github.com/mennoweerman/DapperStapper/assets/70643398/b0c98dbb-72f7-405b-a611-5004b5b840dc)
![InventarisSheet2](https://github.com/mennoweerman/DapperStapper/assets/70643398/4975c33d-0bf5-47fc-a4f0-c756c080409c)
![Inventory](https://github.com/mennoweerman/DapperStapper/assets/70643398/7028ed6b-d269-484c-828a-e3033ea400df)

## GPS berekening door Bart de Boer  

Ik heb de berekening voor het omrekenen van gps coordinaten naar Unreal coordinaten geschreven. Documtatie daarover is hier te vinden: https://github.com/mennoweerman/DapperStapper/wiki/Blueprints-%E2%80%90-Bart#-gps


## Inventaris update door Bart de Boer

Later in het project heb ik de inventaris herschreven. Het gebruikt nu twee pagina's en de code is reusable.

![InventoryUpdate](https://github.com/mennoweerman/DapperStapper/assets/70643398/a074018e-464c-4252-872b-4e25a9730967)
![Inventoryupdate](https://github.com/mennoweerman/DapperStapper/assets/70643398/e0afd120-6056-42ba-bd23-dc6fdf76a6c8)





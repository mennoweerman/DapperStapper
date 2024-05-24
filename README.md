# Dapper Stapper

In deze repository vind je de informatie over het project Dapper Stapper.

De opdracht is om een game te maken voor de klant gemeente Amsterdam. Het doel voor de klant is om een game te hebben waarmee ze nieuwe collega's binnen Amsterdam Oost een leuke rondleiding door de stad kunnen geven.
Het idee van onze game is dat je in het echt door de Dapperbuurt in Amsterdam Oost loopt en dan in de game kan zien waar je bent en een soort speurtocht volgt via instructies. De instructies zien er bijvoorbeeld zo uit: "ga nu richting de rode deur". 

# Geproduceerde Game Onderdelen
  
Menno Weerman:
  * [Point Information](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#bp_pointofinterest)
  * [Gps](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#topdowncharacter)
  * [Game Intro](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#wbp_gameintro)
  * [Main Menu](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#wbp_mainmenu)
  * [Mini Game](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#wbp_minigame)
  * [New Game](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#wbp_newgame)
      

Patricia Kuipers:
  * [Quiz](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#bp_quizmanager)
  * [Hints](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#bp_mapspline)
  * [Collectables](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#wbp_collectableacquired)
  * [Menu's Sluiten](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#wbp_closebutton)
    
Bart de Boer:
  * [Inventaris en de meerdere updates ervan](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#bp_inventory)
  * [GPS berekening](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#topdowncharacter)
  * [Game Ending](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#bp_pointofinterest)

## Point Information door Menno Weerman

Als je de point of interest aanklikt, krijg je een widget voor je waarop je informatie krijgt van een mascotte op het scherm. Doormiddel van de next knop kan je naar de volgende slide gaan en meer informatie krijgen en met de previous knop terug gaan naar de slide ervoor. Hierin vertelt de mascotte wat over de locatie

![Visual Sheet Point Information](https://github.com/mennoweerman/OostQuest/assets/70953228/2c3aec7a-5492-426b-9afd-2e60cb7e2ae2)

## GPS door Menno Weerman

Gebaseerd op de gps locatie beweegt het poppetje naar de goeie locatie op de kaart. Dit is gemaakt om het een echte wandelsimulatie te maken. Voor meer informatie klik hier: https://github.com/mennoweerman/DapperStapper/wiki/Technisch-Ontwerp#gps


## Game Intro door Menno Weerman

Als je een nieuwe game opstart, komt pieter paaltje in je beeld en geeft je uitleg over de dapperbuurt. Als je dit afgerond hebt begint het spel.

![GameIntroPhoto](https://github.com/mennoweerman/DapperStapper/assets/70953228/340fedc5-3860-4f86-8f65-fdcccfbdf183)

## Main Menu door Menno Weerman

Als je de game opstart, komt de main menu op het scherm, als je nog geen save hebt staan er 2 knoppen. Een om de game te starten en een om het spel af te sluiten. 

![NoSavePhoto](https://github.com/mennoweerman/DapperStapper/assets/70953228/76e5ce1a-e010-49dc-937e-91bb83e1ed53)

Mocht je wel een save hebben, dan heb je een om een nieuwe game te starten, een button om verder te gaan met de huidige save en een om het spel af te sluiten.

![SavePhoto](https://github.com/mennoweerman/DapperStapper/assets/70953228/6acbf850-5b77-4a6b-ad81-f83a96487fcc)

## Mini Game door Menno Weerman

Als je bij de dappermarkt bent, dan zal je een minigame krijgen voor het tellen van de reigers. Dit hebben we om de game leuk te houden en proberen de meeste reigers te tellen. Dit word opgeslagen in een aparte save file dus de high score van het tellen wordt opgeslagen op het apparaat.

![MiniGamePhoto](https://github.com/mennoweerman/DapperStapper/assets/70953228/366c2413-93b6-46c1-a544-133153f3a3c7)

## New Game door Menno Weerman

Als je op de knop klikt. Word je oude save verwijdert en een nieuwe aangemaakt en gebruikt.

![SavePhoto](https://github.com/mennoweerman/DapperStapper/assets/70953228/9de1868d-102a-4758-a391-86ae821ad165)

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
![InventoryUpdateMeshes](https://github.com/mennoweerman/DapperStapper/assets/70643398/63b55e43-386b-45f3-9e54-42e4d8d29d70)


## Game Ending door Bart de Boer

Als je alle collectables hebt gevonden en je weer bij het gemeentehuis bent, komt het einde van de game tevoorzijn. Pieter zegt dat je het spel hebt gewonnen en er komt een knop die je naar het hoofdmenu stuurt.

![Ending](https://github.com/mennoweerman/DapperStapper/assets/70643398/e1018bbe-532d-41c9-a2c0-c393bd55a15f)
![Ending](https://github.com/mennoweerman/DapperStapper/assets/70643398/7b388df2-36de-4442-b329-5ff5af401265)

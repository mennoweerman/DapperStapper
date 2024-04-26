# Dapper Stapper

In deze repository vind je de informatie over het project Dapper Stapper.

De opdracht is om een game te maken voor de klant gemeente Amsterdam. Het doel voor de klant is om een game te hebben waarmee ze nieuwe collega's binnen Amsterdam Oost een leuke rondleiding door de stad kunnen geven.
Het idee van onze game is dat je in het echt door de Dapperbuurt in Amsterdam Oost loopt en dan in de game kan zien waar je bent en een soort speurtocht volgt via instructies. De instructies zien er bijvoorbeeld zo uit: "ga nu richting de rode deur". 

# Geproduceerde Game Onderdelen
  
Menno Weerman:
  * [Point Information](https://github.com/mennoweerman/OostQuest/wiki/Blueprints#point-information)

Patricia Kuipers:
  * [Quiz](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-quiz)
  * [Hints](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-hints)
  * [Collectables]
    
Bart de Boer:
  * [Inventaris](https://github.com/mennoweerman/DapperStapper/wiki/Blueprints#-inventaris)

## Point Information door Menno Weerman

Als je de point of interest aanklikt, krijg je een widget voor je waarop je informatie krijgt van een mascotte op het scherm. Doormiddel van de next knop kan je naar de volgende slide gaan en meer informatie krijgen en met de previous knop terug gaan naar de slide ervoor.

![Visual Sheet Point Information](https://github.com/mennoweerman/OostQuest/assets/70953228/2c3aec7a-5492-426b-9afd-2e60cb7e2ae2)

## Quiz, Hints & Collectables door Patricia Kuipers

Als je een Point of Interest bezoekt en je hebt de informatie ervan gelezen, kun je vervolgens een quiz doen. Je kunt de quiz ten allen tijde sluiten. 

In de video hieronder zie je de quiz op mobiel:

https://github.com/mennoweerman/OostQuest/assets/54790202/7a91db15-813e-4672-bd04-cdc74cf92742

Als de speler een antwoord kiest, wordt het groen of rood, aan de hand van of het correct was of niet. Als de speler het juiste antwoord geeft, gaat de quiz verder, en anders kan hij het nogmaals proberen. De speler heeft gewoon de mogelijkheid om door te blijven klikken tot hij het goed heeft, dit om te voorkomen dat het te lastig wordt en/of de speler maar één kans krijgt. 

Aan het einde van de quiz krijgt de speler een collectable, die wordt laten zien en draait rond. De speler kan er op tikken om verder te gaan. In de code wordt bijgehouden of de speler deze collectable al heeft, dat zie je ook aan het kopje tekst wat er onder de collectable verschijnt. 

De quiz is ook volledig instelbaar. Hij kan worden aangepast in de inspector.

![image](https://github.com/mennoweerman/OostQuest/assets/54790202/96603f7d-7aac-4784-9e15-09d9f318ae83)

Je kunt per locatie (Point of Interest) instellen welke vragen erbij horen en welke collectable je daar kan krijgen. Ook kun je per vraag instellen welke antwoorden erbij horen en per antwoord kiezen of dat het juiste antwoord is of niet. 

## Inventaris door Bart de Boer

Deze feature is een inventaris waarin je kan zien welke collectables je al gevonden hebt in de game. Waneer je op de inventaris knop drukt komt er een plane over de gameplay waardoor je alleen nog maar de inventaris, collectables en de knop ziet waarmee je de inventaris sluit.

![InventarisSheet1](https://github.com/mennoweerman/DapperStapper/assets/70643398/b0c98dbb-72f7-405b-a611-5004b5b840dc)
![InventarisSheet2](https://github.com/mennoweerman/DapperStapper/assets/70643398/4975c33d-0bf5-47fc-a4f0-c756c080409c)
![Inventory](https://github.com/mennoweerman/DapperStapper/assets/70643398/7028ed6b-d269-484c-828a-e3033ea400df)



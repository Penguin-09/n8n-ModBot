# n8n ModBot

Om ervaring op te doen met n8n hebben we, met behulp van een package ontwikkeld door een mede-student, een Discord-bot gebouwd met diverse functionaliteiten. Dit project heeft ook bijgedragen aan het opdoen van ervaring met de SCRUM-werkmethode.

## Functionaliteiten

De bot controleert of gebruikers scheldwoorden gebruiken en spreekt hen hierop aan. Daarnaast reageert de bot op verschillende commando's:
- **grap**: Wanneer een gebruiker het woord "grap" in een bericht verwerkt, zoals "ModBot, vertel me een grap", zal de bot een grap vertellen.
- **steen papier schaar**: Door de woorden "steen papier schaar" samen met de gewenste hand in een bericht te zetten, zoals "Speel steen papier schaar met me, ik speel steen", kun je het spel spelen tegen de bot. ModBot kiest vervolgens willekeurig een hand en bepaalt wie de winnaar is.

## Dependencies

Dit project bestaat uit twee n8n-workflows, die beide gebruikmaken van de "n8n-nodes-bit-discord" package. Deze package is een aangepaste versie van "n8n-nodes-discord", ontwikkeld door een van onze mede-studenten, omdat de originele package verouderd was.

## How to run

Om dit project goed te laten draaien, zijn de volgende componenten nodig:
- **Docker**: Vereist om n8n correct uit te voeren.
- **n8n**: Dit project is gebouwd in n8n, dus n8n moet geïnstalleerd zijn.
- **Supabase**: Gebruikt voor het beheren van eenvoudige databases, wat essentieel is voor dit project.

## Meet the team

### Son Bram van der Burg

Son is een full-stack developer met ervaring in JavaScript en heeft daarom een groot deel van de JavaScript-code geschreven die nodig was om dit project succesvol te laten werken.

[Website](https://vdburg.site/) | [Github](https://github.com/Penguin-09) | [LinkedIn](https://www.linkedin.com/in/son-bram/)

### Sven Hoeksema

Sven is een back-end developer en heeft een groot deel van de workflows ontwikkeld. Daarnaast was zijn kennis van Discord van grote waarde voor het project.

[Website](https://snevver.github.io/) | [Github](https://github.com/Snevver) | [LinkedIn](https://www.linkedin.com/in/sven-hoeksema/)

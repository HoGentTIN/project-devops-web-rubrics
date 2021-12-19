# Rubrics DevOps - Web
Hieronder vinden jullie de Rubrics voor het Web gedeelte van het DevOps project. 
Enkel geslaagd indien Backend en Frontend **minimum** bekwaam

## Backend

### Bekwaam
- Kunnen een REST/GraphQL/gRPC API uitbouwen
    - Endpoints goed gedefinieerd
    - Naamgeving is volgens de principes van REST / GraphQL / gRPC
    - Correcte HTTP methods (in geval van REST)
- Er is authenticatie / authorisatie waar nodig
- Draait online
- Foutafhandeling is voorzien

### Gevorderd
- Een of meerdere end points hebben end-to-end testen 
- Er zijn relevante unit testen geschreven
- Er is geen onnodige data duplicatie
- Endpoints geven enkel relevante data terug (geen over-/underfetching)

### Deskundig
- Alle niet triviale end points hebben end-to-end testen
- Er is een goede API documentatie voorzien
- Er is logging voorzien
- Resultaten worden correct gecached waar nodig

## Frontend

### Bekwaam
- De Blazor (server of wasm) frontend is opgebouwd volgens de principes van een Single Page Application
    - Geen onnodige (hard) refreshes
    - Backend requests gebeuren asynchroon
- De website is responsive, gebruiksvriendelijk en bruikbaar zowel op desktop als op mobile devices
- Alle functionaliteiten hebben juist ingedeelde componenten
- Er is authenticatie / authorisatie waar nodig
- Draait online
- Foutafhandeling is voorzien

### Gevorderd
- Er is een opsplitsing van componenten en services zoals het hoort
- Correct gebruik van State Management
- Een of meerdere end-to-end testen 
- EditForm werd correct gebruikt met Data- of Fluent Validation
- Client maakt geen gebruik van Domein klassen

### Deskundig
- Er is caching voorzien op de client
- Er is pre-rendering voorzien
- Geen enkele foutmelding in console van browser
- Alle pages hebben tenminste een end-to-end test

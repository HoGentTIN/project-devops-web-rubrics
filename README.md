# Rubrics DevOps - Web
> English version below


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

---
# Rubrics DevOps - Web
Below are the Rubrics for the Web part of the DevOps project. 
Passed only if Backend and Frontend **minimum** competent

## Backend

### Proficient
- Can build a REST/GraphQL/gRPC API
    - Endpoints are well defined
    - Naming is according to the principles of REST / GraphQL / gRPC
    - Correct HTTP methods (in case of REST)
- There is authentication / authorisation where needed
- Runs online
- Error handling is provided

### Advanced
- One or more end points have end-to-end testing 
- Relevant unit tests have been written
- There is no unnecessary data duplication
- Endpoints return only relevant data (no over/underfetching)

### Expert
- All non-trivial endpoints have end-to-end testing
- Proper API documentation is provided
- Logging is provided
- Results are correctly cached where necessary

## Frontend

### Proficient
- The Blazor (server or wasm) frontend is built according to the principles of a Single Page Application
    - No unnecessary (hard) refreshes
    - Backend requests happen asynchronously
- The website is responsive, user-friendly and usable on both desktop and mobile devices
- All functionalities have correctly classified components
- There is authentication / authorisation where needed
- Runs online
- Error handling is provided

### Advanced
- There is a breakdown of components and services as appropriate
- Proper use of State Management
- One or more end-to-end tests 
- EditForm was correctly used with Data- or Fluent Validation
- Client does not use Domain classes

### Expert
- Caching is provided on the client
- Pre-rendering has been provided
- No error message in console of browser
- All pages have at least one end-to-end test

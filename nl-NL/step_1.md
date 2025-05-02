Containerqueryhoogte (cqh) en containerquerybreedte (cqw) zijn eenheden die een grootte specificeren ten opzichte van de afmetingen van het containerelement van een element.

`1cqh` is 1% van de hoogte van de container. Bijvoorbeeld, als de hoogte van de container 300px is, dan komt een waarde van `10cqh` voor een eigenschap neer op 30px.

Een voordeel van het gebruiken van `cqh`-eenheden in plaats van `px` (pixeleenheden) voor het bepalen van de grootte van elementen, is dat de grootte van de elementen mee verandert met de grootte van hun container. Dit gebeurt meestal wanneer je het formaat van een browservenster wijzigt of een webpagina op een ander scherm bekijkt.

Hier is een voorbeeld:

![Een gif die laat zien hoe de lettergrootte verandert wanneer de hoogte en breedte van de browser verandert.](images/cqh_cqw.gif)

In het voorbeeld is de lettergrootte van de hoofdtekst ingesteld op `cqh`, zodat deze verandert met de hoogte van de browser.

De lettergrootte van de tekst in de navigatiebalk is ingesteld op `cqw`, wat betekent dat deze verandert met de breedte van de browser.
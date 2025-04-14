Container query height (cqh) and container query width (cqw) are units that specify a size relative to the dimensions of an element's container element.

`1cqh` is 1% van de hoogte van de container. Bijvoorbeeld, als de hoogte van de container 300px is, dan zal een waarde `10cqh` op een eigenschap 30px zijn.

Een voordeel van het gebruiken van `cqh`-eenheden in plaats van `px` (pixeleenheden) voor het bepalen van de grootte van elementen, is dat de grootte van de elementen mee verandert met de grootte van hun container. This usually happens when you resize a browser window, or view a webpage on a different screen.

Hier is een voorbeeld:

![A gif showing font sizes changing when the browser changes height and width.](images/cqh_cqw.gif)

In the example, the font size of the the main story text has been set to use `cqh`, so it changes with the browser's height.

The font size of the text in the navbar has been set to use `cqw`, so it changes with the browser's width.

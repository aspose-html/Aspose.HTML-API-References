---
title: "ICSS2Properties.Azimuth"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. Ruimtelijke audio is een belangrijke stilistische eigenschap voor auditieve presentatie. Het biedt een natuurlijke manier om verschillende stemmen van elkaar te onderscheiden, zoals in het echte leven mensen zelden allemaal op dezelfde plek in een kamer staan."
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

Ruimtelijke audio is een belangrijke stilistische eigenschap voor auditieve presentatie. Het biedt een natuurlijke manier om verschillende stemmen van elkaar te onderscheiden, zoals in het echte leven (mensen zelden allemaal op dezelfde plek in een kamer staan).

```java
public String Azimuth { get; set; }
```

### Retourwaarde

De azimuth eigenschap

### Property Value

De waarden hebben de volgende betekenissen:

hoek - Positie wordt beschreven in termen van een hoek binnen het bereik '-360deg' tot '360deg'. De waarde '0deg' betekent direct recht vooruit in het midden van het geluidsveld. '90deg' is naar rechts, '180deg' achter, en '270deg' (of, gelijkwaardig en handiger, '-90deg') naar links.

linkerkant - Hetzelfde als '270deg'. Met 'behind', '270deg'.

verre linkerkant - Hetzelfde als '300deg'. Met 'behind', '240deg'.

links - Hetzelfde als '320deg'. Met 'behind', '220deg'.

centrum-links - Hetzelfde als '340deg'. Met 'behind', '200deg'.

centrum - Hetzelfde als '0deg'. Met 'behind', '180deg'.

centrum-rechts - Hetzelfde als '20deg'. Met 'behind', '160deg'.

rechts - Hetzelfde als '40deg'. Met 'behind', '140deg'.

verre rechts - Hetzelfde als '60deg'. Met 'behind', '120deg'.

rechterkant - Hetzelfde als '90deg'. Met 'behind', '90deg'.

naar links - Verplaatst het geluid naar links, ten opzichte van de huidige hoek. Preciezer: trekt 20 graden af. Rekenkundige bewerkingen worden uitgevoerd modulo 360 graden. Merk op dat 'naar links' nauwkeuriger wordt beschreven als "tegen de klok in gedraaid", omdat het altijd 20 graden aftrekt, zelfs als de geërfde azimuth al achter de luisteraar ligt (in dat geval lijkt het geluid feitelijk naar rechts te bewegen).

naar rechts - Verplaatst het geluid naar rechts, ten opzichte van de huidige hoek. Preciezer: voegt 20 graden toe. Zie 'naar links' voor de rekenkunde.

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

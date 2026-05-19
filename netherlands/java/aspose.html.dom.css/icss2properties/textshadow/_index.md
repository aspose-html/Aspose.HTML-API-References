---
title: "ICSS2Properties.TextShadow"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. Deze eigenschap accepteert een door komma's gescheiden lijst van schaduweffecten die op de tekst van het element worden toegepast. De schaduweffecten worden toegepast in de opgegeven volgorde en kunnen daardoor elkaar overlappen, maar ze zullen de tekst zelf nooit overlappen. Schaduweffecten wijzigen de grootte van een vak niet, maar kunnen buiten de grenzen ervan uitsteken. Het stapelniveau van de schaduweffecten is hetzelfde als voor het element zelf."
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

Deze eigenschap accepteert een door komma's gescheiden lijst van schaduweffecten die op de tekst van het element worden toegepast. De schaduweffecten worden toegepast in de opgegeven volgorde en kunnen daardoor elkaar overlappen, maar ze zullen de tekst zelf nooit overlappen. Schaduweffecten wijzigen de grootte van een vak niet, maar kunnen buiten de grenzen ervan uitsteken. Het [stapelniveau](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) van de schaduweffecten is hetzelfde als voor het element zelf.

Elk schaduweffect moet een schaduwverschuiving specificeren en kan optioneel een vervagingsradius en een schaduwkleur specificeren.

Een schaduwverschuiving wordt gespecificeerd met twee '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' waarden die de afstand tot de tekst aangeven. De eerste lengtwaarde specificeert de horizontale afstand naar rechts van de tekst. Een negatieve horizontale lengtwaarde plaatst de schaduw links van de tekst. De tweede lengtwaarde specificeert de verticale afstand onder de tekst. Een negatieve verticale lengtwaarde plaatst de schaduw boven de tekst.

Een vervagingsradius kan optioneel worden gespecificeerd na de schaduwverschuiving. De vervagingsradius is een lengtwaarde die de grenzen van het vervage effect aangeeft. Het exacte algoritme voor het berekenen van het vervage effect is niet gespecificeerd.

Een kleurwaarde kan optioneel worden gespecificeerd vóór of na de lengtwaarden van het schaduweffect. De kleurwaarde wordt gebruikt als basis voor het schaduweffect. Als er geen kleur is gespecificeerd, wordt de waarde van de ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) eigenschap in plaats daarvan gebruikt.

```java
public String TextShadow { get; set; }
```

### Retourwaarde

text-shadow eigenschap

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

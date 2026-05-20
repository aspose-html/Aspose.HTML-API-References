---
title: "ICSS2Properties.TextShadow"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties‑egenskap. Denna egenskap accepterar en kommaseparerad lista av skuggeffekter som ska tillämpas på elementets text. Skuggeffekterna appliceras i den angivna ordningen och kan därför överlappa varandra, men de kommer aldrig att överlappa själva texten. Skuggeffekter ändrar inte storleken på en ruta men kan sträcka sig utanför dess gränser. Stapelnivån för skuggeffekterna är densamma som för själva elementet."
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

Denna egenskap accepterar en kommaseparerad lista av skuggeffekter som ska tillämpas på elementets text. Skuggeffekterna appliceras i den angivna ordningen och kan därför överlappa varandra, men de kommer aldrig att överlappa själva texten. Skuggeffekter ändrar inte storleken på en ruta, men kan sträcka sig utanför dess gränser. [stack level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) för skuggeffekterna är densamma som för själva elementet.

Varje skuggeffekt måste specificera en skuggförskjutning och kan valfritt specificera en oskärpegrad och en skuggfärg.

En skuggförskjutning specificeras med två '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)'‑värden som anger avståndet från texten. Det första längdvärdet specificerar det horisontella avståndet till höger om texten. Ett negativt horisontellt längdvärde placerar skuggan till vänster om texten. Det andra längdvärdet specificerar det vertikala avståndet under texten. Ett negativt vertikalt längdvärde placerar skuggan ovanför texten.

En oskärpegrad kan valfritt specificeras efter skuggförskjutningen. Oskärpegraden är ett längdvärde som anger gränserna för oskärpeeffekten. Den exakta algoritmen för att beräkna oskärpeeffekten är inte specificerad.

Ett färgvärde kan valfritt specificeras före eller efter längdvärdena för skuggeffekten. Färgvärdet kommer att användas som grund för skuggeffekten. Om ingen färg anges kommer värdet för egenskapen ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) att användas istället.

```java
public String TextShadow { get; set; }
```

### Returvärde

text-shadow-egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---
title: "ICSS2Properties.Clear"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. Deze eigenschap geeft aan welke zijden van de vakken van een element niet aangrenzend mogen zijn aan een eerder zwevend vak. Het kan zijn dat het element zelf zwevende afstammelingen heeft; de clear eigenschap heeft daarop geen effect."
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Deze eigenschap geeft aan welke zijden van de box(es) van een element niet aangrenzend mogen zijn aan een eerder zwevend vak. (Het kan zijn dat het element zelf zwevende afstammelingen heeft; de 'clear' eigenschap heeft daarop geen effect.)

Deze eigenschap mag alleen worden gespecificeerd voor blokniveau-elementen (inclusief zwevers). Voor compacte en run-in vakken is deze eigenschap van toepassing op het uiteindelijke blokvak waartoe het compacte of run-in vak behoort.

Waarden hebben de volgende betekenissen wanneer toegepast op niet-zwevende blokvakken:

left - De bovenmarge van het gegenereerde vak wordt voldoende vergroot zodat de bovenrand onder de onderste buitenrand van alle linkszwevende vakken die voortkwamen uit eerdere elementen in het brondocument ligt. right - De bovenmarge van het gegenereerde vak wordt voldoende vergroot zodat de bovenrand onder de onderste buitenrand van alle rechtszwevende vakken die voortkwamen uit eerdere elementen in het brondocument ligt. both - Het gegenereerde vak wordt verplaatst onder alle zwevende vakken van eerdere elementen in het brondocument. none - Geen beperking op de positie van het vak ten opzichte van zwevers.

```java
public String Clear { get; set; }
```

### Retourwaarde

clear eigenschap

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

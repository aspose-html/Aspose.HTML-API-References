---
title: "ICSS2Properties.Clear"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties-eigenschap. Deze eigenschap geeft aan welke zijden van de boxen van een element niet aangrenzend mogen zijn aan een eerder zwevend vak. Het kan zijn dat het element zelf zwevende afstammelingen heeft; de clear-eigenschap heeft geen effect op die."
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Deze eigenschap geeft aan welke zijden van de box(en) van een element niet aangrenzend mogen zijn aan een eerder zwevend vak. (Het kan zijn dat het element zelf zwevende afstammelingen heeft; de 'clear'-eigenschap heeft geen effect op die.)

Deze eigenschap mag alleen worden gespecificeerd voor blokniveau-elementen (inclusief zwevers). Voor compacte en run-in boxen is deze eigenschap van toepassing op de uiteindelijke blokbox waartoe de compacte of run-in box behoort.

Waarden hebben de volgende betekenissen wanneer toegepast op niet-zwevende blokboxen:

left - De bovenmarge van de gegenereerde box wordt voldoende vergroot zodat de bovenrand onder de onderste buitenrand van alle linkszwevende boxen die voortkwamen uit eerdere elementen in het brondocument ligt. right - De bovenmarge van de gegenereerde box wordt voldoende vergroot zodat de bovenrand onder de onderste buitenrand van alle rechtszwevende boxen die voortkwamen uit eerdere elementen in het brondocument ligt. both - De gegenereerde box wordt verplaatst onder alle zwevende boxen van eerdere elementen in het brondocument. none - Geen beperking op de positie van de box ten opzichte van zwevers.

```java
public String Clear { get; set; }
```

### Retourwaarde

clear-eigenschap

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

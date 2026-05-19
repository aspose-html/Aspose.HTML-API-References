---
title: "IStyleSheet.Disabled"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IStyleSheet-eigenschap. De disabled-eigenschap van de StyleSheet-interface bepaalt of het stylesheet wordt verhinderd toe te passen op het document."
type: docs

url: /nl/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

De disabled-eigenschap van de [`StyleSheet`](../)-interface bepaalt of het stylesheet wordt verhinderd toe te passen op het document.

Een stylesheet kan worden uitgeschakeld door handmatig deze eigenschap op true te zetten of als het een inactief alternatief stylesheet is. Merk op dat disabled == false niet garandeert dat het stylesheet wordt toegepast (het kan bijvoorbeeld uit het document zijn verwijderd).

Het wijzigen van dit attribuut kan een nieuwe stijlresolutie voor het document veroorzaken. Een stylesheet wordt alleen toegepast als zowel een passende mediumdefinitie aanwezig is als het disabled-attribuut false is. Dus, als het medium niet van toepassing is op de huidige user agent, wordt het disabled-attribuut genegeerd.

```java
public bool Disabled { get; set; }
```

### Retourwaarde

Het disabled-attribuut moet bij ophalen true retourneren als de disabled-vlag is ingesteld, of anders false. Bij instellen moet het disabled-attribuut de disabled-vlag instellen als de nieuwe waarde true is, of de disabled-vlag anders uitschakelen.

### Property Value

Het disabled-attribuut moet bij ophalen true retourneren als de disabled-vlag is ingesteld, of anders false. Bij instellen moet het disabled-attribuut de disabled-vlag instellen als de nieuwe waarde true is, of de disabled-vlag anders uitschakelen.

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### Zie ook

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

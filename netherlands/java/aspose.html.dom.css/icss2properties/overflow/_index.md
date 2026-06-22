---
title: "ICSS2Properties.Overflow"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. Deze eigenschap specificeert of de inhoud van een blokniveau-element wordt bijgesneden wanneer deze de box van het element overstroomt die fungeert als een omvattend blok voor de inhoud. Waarden hebben de volgende betekenissen"
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

Deze eigenschap specificeert of de inhoud van een blokniveau-element wordt bijgesneden wanneer deze de box van het element (die fungeert als een omvattend blok voor de inhoud) overstroomt. Waarden hebben de volgende betekenissen:

visible - Deze waarde geeft aan dat de inhoud niet wordt bijgesneden, d.w.z. dat deze buiten de blokbox kan worden weergegeven. hidden - Deze waarde geeft aan dat de inhoud wordt bijgesneden en dat er geen scrollmechanisme moet worden aangeboden om de inhoud buiten het bijsnijdingsgebied te bekijken; gebruikers hebben geen toegang tot bijgesneden inhoud. De grootte en vorm van het bijsnijdingsgebied wordt gespecificeerd door de ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip) eigenschap. scroll - Deze waarde geeft aan dat de inhoud wordt bijgesneden en dat, indien de user agent een scrollmechanisme gebruikt dat zichtbaar is op het scherm (zoals een schuifbalk of een panner), dat mechanisme moet worden weergegeven voor een box, ongeacht of een deel van de inhoud is bijgesneden. Dit voorkomt problemen met het verschijnen en verdwijnen van schuifbalken in een dynamische omgeving. Wanneer deze waarde is gespecificeerd en het doelmedium 'print' of 'projection' is, moet overstroomde inhoud worden afgedrukt. auto - Het gedrag van de 'auto' waarde is afhankelijk van de user agent, maar moet een scrollmechanisme bieden voor overstroomde boxen.

```java
public String Overflow { get; set; }
```

### Retourwaarde

overflow eigenschap

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

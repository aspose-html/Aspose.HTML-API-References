---
title: "IStyleSheet.Disabled"
second_title: "Aspose.HTML för Java API-referens"
description: "IStyleSheet‑egenskap. disabled‑egenskapen i StyleSheet‑gränssnittet avgör om stilarket hindras från att tillämpas på dokumentet."
type: docs

url: /sv/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

disabled‑egenskapen i [`StyleSheet`](../)‑gränssnittet avgör om stilarket hindras från att tillämpas på dokumentet.

Ett stilark kan inaktiveras genom att manuellt sätta denna egenskap till true eller om det är ett inaktivt alternativt stilark. Observera att disabled == false inte garanterar att stilarket tillämpas (det kan till exempel ha tagits bort från dokumentet).

Att ändra detta attribut kan leda till en ny stilupplösning för dokumentet. Ett stilark tillämpas endast om både en lämplig mediumdefinition finns och disabled‑attributet är false. Så om mediet inte gäller för den aktuella användaragenten ignoreras disabled‑attributet.

```java
public bool Disabled { get; set; }
```

### Returvärde

Det inaktiverade attributet, vid läsning, måste returnera true om den inaktiverade flaggan är satt, eller false annars. Vid skrivning måste det inaktiverade attributet sätta den inaktiverade flaggan om det nya värdet är true, eller ta bort den inaktiverade flaggan annars.

### Property Value

Det inaktiverade attributet, vid läsning, måste returnera true om den inaktiverade flaggan är satt, eller false annars. Vid skrivning måste det inaktiverade attributet sätta den inaktiverade flaggan om det nya värdet är true, eller ta bort den inaktiverade flaggan annars.

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### Se även

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

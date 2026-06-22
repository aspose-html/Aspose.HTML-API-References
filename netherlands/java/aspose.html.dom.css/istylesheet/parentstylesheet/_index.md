---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IStyleSheet property. Voor stylesheet-talen die het concept van stylesheet-inclusie ondersteunen, vertegenwoordigt dit attribuut het includerende stylesheet als er één bestaat. Als het stylesheet een top-level stylesheet is of de stylesheet-taal geen inclusie ondersteunt, is de waarde van dit attribuut null."
type: docs

url: /nl/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

Voor stylesheet-talen die het concept van stylesheet-inclusie ondersteunen, vertegenwoordigt dit attribuut het includerende stylesheet, als er één bestaat. Als het stylesheet een top-level stylesheet is, of de stylesheet-taal geen inclusie ondersteunt, is de waarde van dit attribuut null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

Het parentStyleSheet‑attribuut moet het bovenliggende [`CSS style sheet`](../../icssstylesheet/) retourneren.

## Opmerkingen

Deze eigenschap retourneert null als het huidige stylesheet een top-level stylesheet is of als stylesheet-inclusie niet wordt ondersteund.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### Zie ook

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

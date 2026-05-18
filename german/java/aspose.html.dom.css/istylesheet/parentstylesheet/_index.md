---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IStyleSheet-Eigenschaft. Für Stylesheet-Sprachen, die das Konzept der Stylesheet-Einbindung unterstützen, stellt dieses Attribut das einbindende Stylesheet dar, falls eines existiert. Ist das Stylesheet ein Top-Level-Stylesheet oder unterstützt die Stylesheet-Sprache keine Einbindung, ist der Wert dieses Attributs null."
type: docs

url: /de/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

Für Stylesheet-Sprachen, die das Konzept der Stylesheet-Einbindung unterstützen, stellt dieses Attribut das einbindende Stylesheet dar, falls eines existiert. Ist das Stylesheet ein Top-Level-Stylesheet oder unterstützt die Stylesheet-Sprache keine Einbindung, ist der Wert dieses Attributs null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

Das parentStyleSheet‑Attribut muss das übergeordnete [`CSS style sheet`](../../icssstylesheet/) zurückgeben.

## Hinweise

Diese Eigenschaft gibt null zurück, wenn das aktuelle Stylesheet ein Top-Level-Stylesheet ist oder die Stylesheet-Einbindung nicht unterstützt wird.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### Siehe auch

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---
title: "IViewCSS Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.IViewCSS Schnittstelle. Die IViewCSS interface stellt eine Erweiterung des Window‑Objekts dar, die Zugriff auf die Werte aller CSS‑Eigenschaften eines Elements gewährt."
type: docs

url: /de/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

Das IViewCSS-Interface stellt eine Erweiterung des Window‑Objekts dar, die Zugriff auf die Werte aller CSS‑Eigenschaften eines Elements gewährt.

Der CSS‑Stil für ein bestimmtes Element kann mithilfe der IViewCSS.GetComputedStyle()‑Methode abgerufen werden.

```java
public interface IViewCSS : IAbstractView
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | Die IViewCSS.getComputedStyle()‑Methode gibt ein Objekt zurück, das die Werte aller CSS‑Eigenschaften eines Elements enthält, nachdem aktive Stylesheets angewendet und etwaige grundlegende Berechnungen dieser Werte aufgelöst wurden. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | Die IViewCSS.getComputedStyle()‑Methode gibt ein Objekt zurück, das die Werte aller CSS‑Eigenschaften eines Elements enthält, nachdem aktive Stylesheets angewendet und etwaige grundlegende Berechnungen dieser Werte aufgelöst wurden. |

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Siehe auch

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

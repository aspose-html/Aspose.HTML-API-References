---
title: "IStyleSheet Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.IStyleSheet Schnittstelle. Die **StyleSheet** Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von Stylesheet. Sie repräsentiert ein einzelnes Stylesheet, das mit einem strukturierten Dokument verknüpft ist. In HTML stellt die **StyleSheet** Schnittstelle entweder ein externes Stylesheet dar, das über das HTML‑LINK‑Element eingebunden wird, oder ein Inline‑STYLE‑Element. In XML repräsentiert diese Schnittstelle ein externes Stylesheet, das über eine Stylesheet‑Verarbeitungsanweisung eingebunden wird. CSS‑Stylesheets implementieren anschließend die spezialisiertere **CSSStyleSheet** Schnittstelle."
type: docs

url: /de/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

Die **StyleSheet** Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von Stylesheet. Sie repräsentiert ein einzelnes Stylesheet, das mit einem strukturierten Dokument verknüpft ist. In HTML stellt die **StyleSheet** Schnittstelle entweder ein externes Stylesheet dar, das über das HTML‑LINK‑Element eingebunden wird, oder ein Inline‑STYLE‑Element. In XML repräsentiert diese Schnittstelle ein externes Stylesheet, das über eine Stylesheet‑Verarbeitungsanweisung eingebunden wird. CSS‑Stylesheets implementieren anschließend die spezialisiertere [`CSSStyleSheet`](../icssstylesheet/) Schnittstelle.

Siehe auch das [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) Die **href**‑Eigenschaft der `StyleSheet` Schnittstelle gibt den Speicherort des Stylesheets zurück. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) Die **media**‑Eigenschaft der `StyleSheet` Schnittstelle gibt das beabsichtigte Zielmedium für Stilinformationen an. Es ist ein schreibgeschütztes, array‑ähnliches [`MediaList`](../imedialist/) Objekt und kann mit deleteMedium() entfernt und mit appendMedium() hinzugefügt werden. |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Der Knoten, der dieses Stylesheet mit dem Dokument verknüpft. Für HTML kann dies das entsprechende LINK‑ oder STYLE‑Element sein. Für XML kann es die verknüpfende Verarbeitungsanweisung sein. Für Stylesheets, die von anderen Stylesheets eingebunden werden, ist der Wert dieses Attributs null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) Für Stylesheet‑Sprachen, die das Konzept der Stylesheet‑Einbindung unterstützen, stellt dieses Attribut das einbindende Stylesheet dar, falls eines existiert. Ist das Stylesheet ein Top‑Level‑Stylesheet oder unterstützt die Stylesheet‑Sprache keine Einbindung, ist der Wert dieses Attributs null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) Die **title**‑Eigenschaft der `StyleSheet` Schnittstelle gibt den beratenden Titel des aktuellen Stylesheets zurück. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Dies gibt die Stylesheet‑Sprache für dieses Stylesheet an. Die Stylesheet‑Sprache wird als Content‑Typ angegeben (z. B. "text/css"). |

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Siehe auch

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

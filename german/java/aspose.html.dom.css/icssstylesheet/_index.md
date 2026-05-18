---
title: "ICSSStyleSheet Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSStyleSheet Schnittstelle. Das CSSStyleSheet‑Interface stellt ein einzelnes CSS‑Stylesheet dar und ermöglicht das Inspizieren und Ändern der Regel‑Liste, die im Stylesheet enthalten ist. Es erbt Eigenschaften und Methoden von seinem übergeordneten IStyleSheet."
type: docs

url: /de/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Das CSSStyleSheet‑Interface stellt ein einzelnes CSS‑Stylesheet dar und ermöglicht das Inspizieren und Ändern der Regel‑Liste, die im Stylesheet enthalten ist. Es erbt Eigenschaften und Methoden von seinem übergeordneten [`IStyleSheet`](../istylesheet/).

Ein Stylesheet besteht aus einer Sammlung von [`ICSSRule`](../icssrule/)‑Objekten, die jede Regel im Stylesheet repräsentieren. Die Regeln sind in einer [`ICSSRuleList`](../icssrulelist/) enthalten, die über die cssRules‑Eigenschaft des Stylesheets abgerufen werden kann.

Zum Beispiel könnte eine Regel ein [`ICSSStyleRule`](../icssstylerule/)‑Objekt sein, das einen Stil wie folgt enthält

```java
h1, h2 {   font-size: 16pt; }
```

Eine andere Regel könnte eine At‑Rule wie @import oder @media sein usw.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) Die schreibgeschützte CSSStyleSheet‑Eigenschaft cssRules liefert eine Live‑[`CSSRuleList`](../icssrulelist/), die eine Echtzeit‑, aktuelle Liste aller CSS‑Regeln bereitstellt, aus denen das Stylesheet besteht. Jeder Eintrag in der Liste ist ein [`CSSRule`](../icssrule/), der eine einzelne Regel definiert. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) Die schreibgeschützte CSSStyleSheet‑Eigenschaft ownerRule gibt die [`CSSImportRule`](../icssimportrule/) zurück, die der @import‑At‑Rule entspricht, welche das Stylesheet in das Dokument importiert hat. Wenn das Stylesheet nicht mittels @import in das Dokument importiert wurde, ist der zurückgegebene Wert null. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Die `CSSStyleSheet`‑Methode deleteRule() entfernt eine Regel aus dem Stylesheet‑Objekt. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | Die CSSStyleSheet.insertRule()‑Methode fügt eine neue CSS‑Regel in das aktuelle Stylesheet ein, mit einigen Einschränkungen. |

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### Siehe auch

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

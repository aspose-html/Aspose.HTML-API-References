---
title: Interface ICSSCharsetRule
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Css.ICSSCharsetRule koppel. Die CSSCharsetRuleSchnittstelle repräsentiert eine charsetRegel in einem CSSStylesheet. Der Wert des Attributs encoding wirkt sich nicht auf die Codierung von Textdaten in den DOMObjekten aus diese Kodierung ist immer UTF16. Nachdem ein Stylesheet geladen wurde ist der Wert des Attributs encoding der Wert der in der charsetRegel gefunden wird. Wenn im Originaldokument kein charset vorhanden war wird keine CSSCharsetRule erstellt. Der Wert des Attributs encoding kann auch als Hinweis auf die Codierung verwendet werden die bei der Serialisierung des Stylesheets verwendet wird.
type: docs
weight: 380
url: /de/net/aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

Die CSSCharsetRule-Schnittstelle repräsentiert eine @charset-Regel in einem CSS-Stylesheet. Der Wert des Attributs encoding wirkt sich nicht auf die Codierung von Textdaten in den DOM-Objekten aus; diese Kodierung ist immer UTF-16. Nachdem ein Stylesheet geladen wurde, ist der Wert des Attributs encoding der Wert, der in der @charset-Regel gefunden wird. Wenn im Originaldokument kein @charset vorhanden war, wird keine CSSCharsetRule erstellt. Der Wert des Attributs encoding kann auch als Hinweis auf die Codierung verwendet werden, die bei der Serialisierung des Stylesheets verwendet wird.

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../aspose.html.dom.css/icsscharsetrule/encoding/) { get; set; } | Die Codierungsinformationen, die in dieser @charset-Regel verwendet werden. |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* namensraum [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* Montage [Aspose.HTML](../../)



---
title: "ICSSCharsetRule Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSCharsetRule Interface. Das CSSCharsetRule-Interface stellt eine Charset-Regel in einem CSS-Stylesheet dar. Der Wert des encoding-Attributs beeinflusst nicht die Kodierung von Textdaten in den DOM-Objekten; diese Kodierung ist stets UTF-16. Nach dem Laden eines Stylesheets ist der Wert des encoding-Attributs der im Charset-Regel gefundene Wert. Wenn im Originaldokument kein Charset vorhanden war, wird kein CSSCharsetRule erstellt. Der Wert des encoding-Attributs kann auch als Hinweis für die bei der Serialisierung des Stylesheets verwendete Kodierung dienen."
type: docs

url: /de/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

Das CSSCharsetRule‑Interface repräsentiert eine @charset‑Regel in einem CSS‑Stylesheet. Der Wert des encoding‑Attributs beeinflusst nicht die Kodierung von Textdaten in den DOM‑Objekten; diese Kodierung ist stets UTF‑16. Nachdem ein Stylesheet geladen wurde, entspricht der Wert des encoding‑Attributs dem in der @charset‑Regel gefundenen Wert. Wenn im Originaldokument keine @charset‑Regel vorhanden war, wird kein CSSCharsetRule erstellt. Der Wert des encoding‑Attributs kann zudem als Hinweis für die bei der Serialisierung des Stylesheets zu verwendende Kodierung dienen.

```java
public interface ICSSCharsetRule : ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

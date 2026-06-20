---
title: "ICSSImportRule Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.ICSSImportRule Interface. Das CSSImportRule-Interface repräsentiert eine Importregel innerhalb eines CSS-Stylesheets. Die Importregel wird verwendet, um Stilregeln aus anderen Stylesheets zu importieren."
type: docs

url: /de/java/com.aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

Das CSSImportRule‑Interface repräsentiert eine @import‑Regel innerhalb eines CSS‑Stylesheets. Die @import‑Regel wird verwendet, um Stilregeln aus anderen Stylesheets zu importieren.

```java
public interface ICSSImportRule : ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getHref](../../com.aspose.html.dom.css/icssimportrule/href/) Die schreibgeschützte href-Eigenschaft des CSSImportRule-Interface gibt die durch die @import-At-Rule angegebene URL zurück. |
| [getMedia](../../com.aspose.html.dom.css/icssimportrule/media/) Die schreibgeschützte media-Eigenschaft des CSSImportRule-Interface gibt ein MediaList-Objekt zurück, das den Wert des media-Attributs des zugehörigen Stylesheets enthält. |
| [getStyleSheet](../../com.aspose.html.dom.css/icssimportrule/stylesheet/) Das von dieser Regel referenzierte Stylesheet, falls es geladen wurde. Der Wert dieses Attributs ist null, wenn das Stylesheet noch nicht geladen wurde oder nicht geladen wird (z. B. wenn das Stylesheet für einen Medientyp bestimmt ist, der vom User-Agent nicht unterstützt wird). |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

---
title: "IDocumentCSS Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.IDocumentCSS Schnittstelle. Diese Schnittstelle stellt ein Dokument mit einer CSS‑Ansicht dar."
type: docs

url: /de/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Dieses Interface stellt ein Dokument mit einer CSS-Ansicht dar.

Die Methode getOverrideStyle bietet einen Mechanismus, mit dem ein DOM‑Autor sofortige Änderungen am Stil eines Elements vornehmen kann, ohne die explizit verknüpften Stylesheets eines Dokuments oder den Inline‑Stil von Elementen in den Stylesheets zu ändern. Dieses Stylesheet wird nach dem Autor‑Stylesheet im Kaskaden‑Algorithmus eingefügt und wird Override‑Stylesheet genannt. Das Override‑Stylesheet hat Vorrang vor Autor‑Stylesheets. Eine \"!important\"‑Deklaration hat weiterhin Vorrang vor einer normalen Deklaration. Override‑, Autor‑ und Benutzer‑Stylesheets können alle \"!important\"‑Deklarationen enthalten. Benutzer‑\"!important\"‑Regeln haben Vorrang vor sowohl Override‑ als auch Autor‑\"!important\"‑Regeln, und Override‑\"!important\"‑Regeln haben Vorrang vor Autor‑\"!important\"‑Regeln.

Es wird erwartet, dass eine Instanz der DocumentCSS‑Schnittstelle durch bindungsspezifische Cast‑Methoden auf einer Instanz der Document‑Schnittstelle erhalten werden kann.

Siehe auch die [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Diese Methode wird verwendet, um die Override‑Stil‑Deklaration für ein angegebenes Element und ein angegebenes Pseudo‑Element abzurufen. |

### Siehe auch

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

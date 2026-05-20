---
title: "IDocumentCSS gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.IDocumentCSS gränssnitt. Detta gränssnitt representerar ett dokument med en CSS‑vy."
type: docs

url: /sv/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Detta gränssnitt representerar ett dokument med en CSS‑vy.

Metoden getOverrideStyle tillhandahåller en mekanism genom vilken en DOM‑författare kan omedelbart ändra stilen för ett element utan att modifiera de explicit länkade stilarken i ett dokument eller inline‑stilen för element i stilarken. Detta stilark kommer efter författarens stilark i kaskadalgoritmen och kallas override‑stilark. Override‑stilarket har företräde framför författarens stilark. En \"!important\"‑deklaration har fortfarande företräde framför en normal deklaration. Override‑, författar‑ och användarstilark kan alla innehålla \"!important\"‑deklarationer. Användarens \"!important\"‑regler har företräde framför både override‑ och författarens \"!important\"‑regler, och override‑\"!important\"‑regler har företräde framför författarens \"!important\"‑regler.

Förväntningen är att en instans av DocumentCSS‑gränssnittet kan erhållas genom att använda bindningsspecifika cast‑metoder på en instans av Document‑gränssnittet.

Se även [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Denna metod används för att hämta override‑stildeklarationen för ett specificerat element och ett specificerat pseudo‑element. |

### Se även

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

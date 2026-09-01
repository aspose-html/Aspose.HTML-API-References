---
title: "Classe RGBColor"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.css.RGBColor class. L'interfaccia RGBColor è usata per rappresentare qualsiasi valore di colore RGB. Questa interfaccia riflette i valori nella proprietà di stile sottostante. Pertanto le modifiche apportate agli oggetti CSSPrimitiveValue modificano la proprietà di stile."
type: docs

url: /it/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

L'interfaccia RGBColor viene utilizzata per rappresentare qualsiasi valore di colore RGB. Questa interfaccia riflette i valori nella proprietà di stile sottostante. Pertanto, le modifiche apportate agli oggetti CSSPrimitiveValue modificano la proprietà di stile.

Un colore RGB specificato non viene tagliato (anche se il numero è fuori dall'intervallo 0-255 o 0%-100%). Un colore RGB calcolato viene tagliato in base al dispositivo.

Anche se un foglio di stile può contenere solo un intero per un valore di colore, l'archiviazione interna di questo intero è un float, e può essere usato come float nello stile specificato o calcolato.

Un valore di percentuale di colore può sempre essere convertito in un numero e viceversa.

```java
public class RGBColor : DOMObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Restituisce il valore della componente alfa di questa struttura Color. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Restituisce il valore della componente blu di questa struttura Color. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Restituisce il valore della componente verde di questa struttura Color. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Restituisce il valore della componente rossa di questa struttura Color. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Converte all'oggetto colore nativo. |

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Vedi anche

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

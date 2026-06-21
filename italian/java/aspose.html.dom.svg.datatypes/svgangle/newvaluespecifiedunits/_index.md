---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo SVGAngle. Reimposta il valore come numero con un unitType associato, sostituendo così i valori di tutti gli attributi sull'oggetto"
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Reimposta il valore come numero con un unitType associato, sostituendo così i valori di tutti gli attributi dell'oggetto.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newUnitType | UInt16 | Il tipo di unità per il valore (ad es., SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Il valore dell'angolo. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) generato se unitType è SVG_ANGLETYPE_UNKNOWN o non è una costante di tipo unità valida (una delle altre costanti SVG_ANGLETYPE_* definite su questa interfaccia). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Generato quando l'angolo corrisponde a un attributo di sola lettura o quando l'oggetto stesso è di sola lettura. |

### Vedi anche

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

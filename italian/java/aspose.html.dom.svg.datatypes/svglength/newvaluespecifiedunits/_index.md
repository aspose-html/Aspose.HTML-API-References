---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo SVGLength. Reimposta il valore come numero con un unitType associato, sostituendo così i valori di tutti gli attributi dell'oggetto"
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Reimposta il valore come numero con un unitType associato, sostituendo così i valori di tutti gli attributi dell'oggetto.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| unitType | UInt16 | Il tipo di unità per il valore. |
| valueInSpecifiedUnits | Single | Il nuovo valore.. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) generato se unitType è SVG_LENGTHTYPE_UNKNOWN o non è una costante di tipo unità valida (una delle altre costanti SVG_LENGTHTYPE_* definite su questa interfaccia). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) generato quando la lunghezza corrisponde a un attributo di sola lettura o quando l'oggetto stesso è di sola lettura. |

### Vedi anche

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo SVGLength. Conserva lo stesso valore di base memorizzato ma reimposta l'identificatore di unità memorizzato al unitType fornito. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati a seguito di questo metodo. Per esempio, se il valore originale fosse 0,5cm e il metodo fosse invocato per convertire in millimetri, allora unitType verrebbe cambiato in SVG_LENGTHTYPE_MM, valueInSpecifiedUnits verrebbe cambiato al valore numerico 5 e valueAsString verrebbe cambiato in 5mm."
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Conserva lo stesso valore memorizzato di base, ma reimposta l'identificatore di unità memorizzato al unitType fornito. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati a seguito di questo metodo. Per esempio, se il valore originale fosse \"0.5cm\" e il metodo fosse invocato per convertire in millimetri, allora unitType verrebbe cambiato in SVG_LENGTHTYPE_MM, valueInSpecifiedUnits verrebbe cambiato nel valore numerico 5 e valueAsString verrebbe cambiato in \"5mm\".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| unitType | UInt16 | Il tipo di unità a cui passare (ad es., SVG_LENGTHTYPE_MM). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Generato se unitType è SVG_LENGTHTYPE_UNKNOWN o non è una costante di tipo unità valida (una delle altre costanti SVG_LENGTHTYPE_* definite su questa interfaccia). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Generato quando la lunghezza corrisponde a un attributo di sola lettura o quando l'oggetto stesso è di sola lettura. |

### Vedi anche

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo SVGAngle. Conserva lo stesso valore memorizzato sottostante ma reimposta l'identificatore di unità memorizzato al unitType fornito. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati a seguito di questo metodo."
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Mantieni lo stesso valore memorizzato di base, ma reimposta l'identificatore dell'unità memorizzato al unitType fornito. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| unitType | UInt16 | Il tipo di unità a cui passare (ad es., SVG_ANGLETYPE_DEG). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) generato se unitType è SVG_ANGLETYPE_UNKNOWN o non è una costante di tipo unità valida (una delle altre costanti SVG_ANGLETYPE_* definite su questa interfaccia). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Generato quando l'angolo corrisponde a un attributo di sola lettura o quando l'oggetto stesso è di sola lettura. |

### Vedi anche

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

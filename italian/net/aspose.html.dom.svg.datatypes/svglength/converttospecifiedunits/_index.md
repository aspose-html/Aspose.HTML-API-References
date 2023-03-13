---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML per riferimento API .NET
description: SVGLength metodo. Conserva lo stesso valore archiviato sottostante ma reimposta lidentificatore dellunità memorizzata sul tipo di unità specificato. Gli attributi delloggetto unitType valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo. Ad esempio se il valore originale fosse 05 cm e il metodo fosse richiamato per convertire in millimetri unitType verrebbe modificato in SVG_LENGTHTYPE_MM valueInSpecifiedUnits verrebbe modificato nel valore numerico 5 e valueAsString verrebbe modificato in 5mm.
type: docs
weight: 50
url: /it/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Conserva lo stesso valore archiviato sottostante, ma reimposta l'identificatore dell'unità memorizzata sul tipo di unità specificato. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo. Ad esempio, se il valore originale fosse "0,5 cm" e il metodo fosse richiamato per convertire in millimetri, unitType verrebbe modificato in SVG_LENGTHTYPE_MM, valueInSpecifiedUnits verrebbe modificato nel valore numerico 5 e valueAsString verrebbe modificato in "5mm".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| unitType | UInt16 | Il tipo di unità a cui passare (ad esempio, SVG_LENGTHTYPE_MM). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Generato se unitType è SVG_LENGTHTYPE_UNKNOWN o non è una costante del tipo di unità valida (una delle altre costanti SVG_LENGTHTYPE_* definite su questa interfaccia). |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Generato quando la lunghezza corrisponde a un attributo di sola lettura o quando l'oggetto stesso è di sola lettura. |

### Guarda anche

* class [SVGLength](../)
* spazio dei nomi [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* assemblea [Aspose.HTML](../../../)



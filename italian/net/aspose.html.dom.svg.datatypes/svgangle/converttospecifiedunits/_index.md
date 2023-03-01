---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML per riferimento API .NET
description: SVGAngle metodo. Conserva lo stesso valore archiviato sottostante ma reimposta lidentificatore dellunità memorizzata sul tipo di unità specificato. Gli attributi delloggetto unitType valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo.
type: docs
weight: 50
url: /it/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Conserva lo stesso valore archiviato sottostante, ma reimposta l'identificatore dell'unità memorizzata sul tipo di unità specificato. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| unitType | UInt16 | Il tipo di unità a cui passare (ad esempio, SVG_ANGLETYPE_DEG). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Generato se unitType è SVG_ANGLETYPE_UNKNOWN o non è una costante del tipo di unità valida (una delle altre costanti SVG_ANGLETYPE_* definite su questa interfaccia). |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Aumentato quando l'angolo corrisponde a un attributo di sola lettura o quando l'oggetto stesso è di sola lettura. |

### Guarda anche

* class [SVGAngle](../)
* spazio dei nomi [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* assemblea [Aspose.HTML](../../../)



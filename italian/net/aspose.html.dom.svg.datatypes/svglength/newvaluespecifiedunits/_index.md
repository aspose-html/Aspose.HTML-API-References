---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.HTML per riferimento API .NET
description: SVGLength metodo. Reimposta il valore come numero con un unitType associato sostituendo così i valori per tutti gli attributi sulloggetto.
type: docs
weight: 60
url: /it/net/aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Reimposta il valore come numero con un unitType associato, sostituendo così i valori per tutti gli attributi sull'oggetto.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| unitType | UInt16 | Il tipo di unità per il valore. |
| valueInSpecifiedUnits | Single | Il nuovo valore.. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Generato se unitType è SVG_LENGTHTYPE_UNKNOWN o non è una costante del tipo di unità valida (una delle altre costanti SVG_LENGTHTYPE_* definite su questa interfaccia). |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Generato quando la lunghezza corrisponde a un attributo di sola lettura o quando l'oggetto stesso è di sola lettura. |

### Guarda anche

* class [SVGLength](../)
* spazio dei nomi [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* assemblea [Aspose.HTML](../../../)



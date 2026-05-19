---
title: "Classe SVGAngle"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.svg.datatypes.SVGAngle. L'interfaccia SVGAngle corrisponde al tipo di dato base angolo"
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

L'interfaccia SVGAngle corrisponde al tipo di dato base angolo.

```java
public class SVGAngle : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) Il tipo del valore come specificato da una delle costanti SVG_ANGLETYPE_* definite su questa interfaccia. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Mantieni lo stesso valore di base memorizzato, ma reimposta l'identificatore di unità memorizzato al unitType fornito. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Reimposta il valore come numero con un unitType associato, sostituendo così i valori di tutti gli attributi dell'oggetto. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Restituisce una String che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Il tipo di unità è stato impostato esplicitamente a gradi. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Il tipo di unità è radianti. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Il tipo di unità è radianti. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Il tipo di unità non è uno dei tipi di unità predefiniti. È invalido tentare di definire un nuovo valore di questo tipo o di cambiare un valore esistente a questo tipo. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Non è stato fornito alcun tipo di unità (cioè è stato specificato un valore senza unità). Per gli angoli, un valore senza unità è trattato come se fossero stati specificati i gradi. |

### Vedi anche

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)

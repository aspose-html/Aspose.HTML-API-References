---
title: "Classe SVGLength"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.svg.datatypes.SVGLength. L'interfaccia SVGLength corrisponde al tipo di dato base lunghezza. Un oggetto SVGLength può essere designato come sola lettura, il che significa che i tentativi di modificare l'oggetto genereranno un'eccezione come descritto di seguito"
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

L'interfaccia SVGLength corrisponde al tipo di dato di base length. Un oggetto SVGLength può essere designato come sola lettura, il che significa che i tentativi di modificare l'oggetto genereranno un'eccezione, come descritto di seguito.

```java
public class SVGLength : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) Il tipo del valore come specificato da una delle costanti SVG_LENGTHTYPE_* definite su questa interfaccia. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Conserva lo stesso valore memorizzato di base, ma reimposta l'identificatore di unità memorizzato al unitType fornito. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati a seguito di questo metodo. Per esempio, se il valore originale fosse \"0.5cm\" e il metodo fosse invocato per convertire in millimetri, allora unitType verrebbe cambiato in SVG_LENGTHTYPE_MM, valueInSpecifiedUnits verrebbe cambiato nel valore numerico 5 e valueAsString verrebbe cambiato in \"5mm\". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Reimposta il valore come numero con un unitType associato, sostituendo così i valori di tutti gli attributi dell'oggetto. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Restituisce una String che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | È stato specificato un valore utilizzando le unità cm definite in CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | È stato specificato un valore utilizzando le unità em definite in CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | È stato specificato un valore utilizzando le unità ex definite in CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | È stato specificato un valore utilizzando le unità in definite in CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | È stato specificato un valore utilizzando le unità mm definite in CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Non è stato fornito alcun tipo di unità (cioè è stato specificato un valore senza unità), il che indica un valore in unità utente. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | È stato specificato un valore utilizzando le unità pc definite in CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | È stato specificato un valore percentuale. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | È stato specificato un valore utilizzando le unità pt definite in CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | È stato specificato un valore utilizzando le unità px definite in CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Il tipo di unità non è uno dei tipi di unità predefiniti. È invalido tentare di definire un nuovo valore di questo tipo o di cambiare un valore esistente a questo tipo. |

### Vedi anche

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)

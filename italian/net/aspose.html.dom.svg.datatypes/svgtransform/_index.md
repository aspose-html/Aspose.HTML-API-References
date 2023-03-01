---
title: Class SVGTransform
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform classe. SVGTransform è linterfaccia per una delle trasformazioni dei componenti allinterno di un SVGTransformList quindi un oggetto SVGTransform corrisponde a un singolo componente ad esempio scale o matrix allinterno di una specifica dellattributo transform.
type: docs
weight: 1300
url: /it/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform è l'interfaccia per una delle trasformazioni dei componenti all'interno di un SVGTransformList; quindi, un oggetto SVGTransform corrisponde a un singolo componente (ad esempio, 'scale(…)' o 'matrix(…)') all'interno di una specifica dell'attributo 'transform'.

```csharp
public class SVGTransform : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | Un attributo utile per SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX e SVG_TRANSFORM_SKEWY. Mantiene l'angolo specificato. Per SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE e SVG_TRANSFORM_SCALE, l'angolo sarà zero. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | La matrice che rappresenta questa trasformazione. L'oggetto matrice è attivo, il che significa che qualsiasi modifica apportata all'oggetto SVGTransform si riflette immediatamente nell'oggetto matrice e viceversa. Nel caso in cui l'oggetto matrice venga modificato direttamente (ovvero, senza utilizzare i metodi sull'interfaccia SVGTransform stessa), il tipo di SVGTransform cambia in SVG_TRANSFORM_MATRIX. Per SVG_TRANSFORM_MATRIX, la matrice contiene a, b, c, d, e, f valori forniti dall'utente. Per SVG_TRANSFORM_TRANSLATE, e e f rappresentano gli importi di traduzione (a= 1, b= 0, c= 0 e d = 1). Per SVG_TRANSFORM_SCALE, a e d rappresentano gli importi di scala (b= 0 , c= 0, e= 0 e f = 0). Per SVG_TRANSFORM_SKEWX e SVG_TRANSFORM_SKEWY, a, b, c e d rappresentano la matrice che risulterà nella data skew (e= 0 e f = 0). Per SVG_TRANSFORM_ROTATE , a, b, c, d, e ed f insieme rappresentano la matrice che risulterà nella data rotazione. Quando la rotazione è attorno al punto centrale (0, 0), e ed f saranno zero. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | Il tipo del valore come specificato da una delle costanti SVG_TRANSFORM_* definite su questa interfaccia. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e, facoltativamente, gestite. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Imposta il tipo di trasformazione su SVG_TRANSFORM_MATRIX, con matrice di parametri che definisce la nuova trasformazione. I valori dalla matrice del parametro vengono copiati, il parametro matrice non sostituisce SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Imposta il tipo di trasformazione su SVG_TRANSFORM_ROTATE, con il parametro angle che definisce l'angolo di rotazione e i parametri cx e cy che definiscono il centro di rotazione facoltativo. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Imposta il tipo di trasformazione su SVG_TRANSFORM_SCALE, con i parametri sx e sy che definiscono le quantità di scala. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Imposta il tipo di trasformazione su SVG_TRANSFORM_SKEWX, con il parametro angolo che definisce la quantità di inclinazione. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Imposta il tipo di trasformazione su SVG_TRANSFORM_SKEWY, con il parametro angolo che definisce la quantità di inclinazione. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Imposta il tipo di trasformazione su SVG_TRANSFORM_TRANSLATE, con i parametri tx e ty che definiscono gli importi della traduzione. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Una trasformazione 'matrice(...)'. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Una trasformazione 'ruota(...)'. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Una trasformazione 'scala(...)'. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Una trasformazione 'skewX(...)'. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Una trasformazione 'skewY(...)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Una trasformazione 'traduci(...)'. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Il tipo di unità non è uno dei tipi predefiniti. Non è valido tentare di definire un nuovo valore di questo tipo o tentare di convertire un valore esistente in questo tipo. |

### Guarda anche

* class [SVGValueType](../svgvaluetype/)
* spazio dei nomi [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* assemblea [Aspose.HTML](../../)



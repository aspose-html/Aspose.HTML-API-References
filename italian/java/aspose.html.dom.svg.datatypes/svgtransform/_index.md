---
title: "SVGTransform Classe"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform classe. SVGTransform è l'interfaccia per una delle trasformazioni componenti all'interno di una SVGTransformList, quindi un oggetto SVGTransform corrisponde a un singolo componente, ad es. scala o matrice, all'interno di una specifica di attributo transform"
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform è l'interfaccia per una delle trasformazioni componenti all'interno di una SVGTransformList; quindi, un oggetto SVGTransform corrisponde a un singolo componente (ad es., 'scale(…)' o 'matrix(…)') all'interno di una specifica dell'attributo ‘transform’.

```java
public class SVGTransform : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Un attributo di convenienza per SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX e SVG_TRANSFORM_SKEWY. Contiene l'angolo specificato. Per SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE e SVG_TRANSFORM_SCALE, l'angolo sarà zero. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) La matrice che rappresenta questa trasformazione. L'oggetto matrice è dinamico, il che significa che qualsiasi modifica apportata all'oggetto SVGTransform viene immediatamente riflessa nell'oggetto matrice e viceversa. Nel caso in cui l'oggetto matrice venga modificato direttamente (cioè senza utilizzare i metodi sull'interfaccia SVGTransform stessa), il tipo di SVGTransform cambia in SVG_TRANSFORM_MATRIX. Per SVG_TRANSFORM_MATRIX, la matrice contiene i valori a, b, c, d, e, f forniti dall'utente. Per SVG_TRANSFORM_TRANSLATE, e e f rappresentano le quantità di traslazione (a= 1, b= 0, c= 0 e d = 1). Per SVG_TRANSFORM_SCALE, a e d rappresentano le quantità di scala (b= 0, c= 0, e= 0 e f = 0). Per SVG_TRANSFORM_SKEWX e SVG_TRANSFORM_SKEWY, a, b, c e d rappresentano la matrice che produrrà la skew indicata (e= 0 e f = 0). Per SVG_TRANSFORM_ROTATE, a, b, c, d, e e f insieme rappresentano la matrice che produrrà la rotazione indicata. Quando la rotazione è attorno al punto centrale (0, 0), e e f saranno zero. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) Il tipo del valore come specificato da una delle costanti SVG_TRANSFORM_* definite su questa interfaccia. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Imposta il tipo di trasformazione a SVG_TRANSFORM_MATRIX, con il parametro matrix che definisce la nuova trasformazione. I valori del parametro matrix vengono copiati, il parametro matrix non sostituisce SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Imposta il tipo di trasformazione a SVG_TRANSFORM_ROTATE, con il parametro angle che definisce l'angolo di rotazione e i parametri cx e cy che definiscono il centro di rotazione opzionale. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Imposta il tipo di trasformazione a SVG_TRANSFORM_SCALE, con i parametri sx e sy che definiscono le quantità di scala. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Imposta il tipo di trasformazione a SVG_TRANSFORM_SKEWX, con il parametro angle che definisce l'entità dello skew. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Imposta il tipo di trasformazione a SVG_TRANSFORM_SKEWY, con il parametro angle che definisce l'entità dello skew. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Imposta il tipo di trasformazione a SVG_TRANSFORM_TRANSLATE, con i parametri tx e ty che definiscono le quantità di traslazione. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Restituisce una stringa che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Una trasformazione 'matrix(…)'. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Una trasformazione 'rotate(…)'. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Una trasformazione 'scale(…)' |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Una trasformazione 'skewX(…)' |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Una trasformazione 'skewY(…)' |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Una trasformazione 'translate(…)' |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Il tipo di unità non è uno dei tipi predefiniti. È invalido tentare di definire un nuovo valore di questo tipo o di tentare di cambiare un valore esistente a questo tipo. |

### Vedi anche

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)

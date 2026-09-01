---
title: "SVGTransform.Matrix"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà SVGTransform. La matrice che rappresenta questa trasformazione. L'oggetto matrice è live, il che significa che qualsiasi modifica apportata all'oggetto SVGTransform viene immediatamente riflessa nell'oggetto matrice e viceversa. Nel caso in cui l'oggetto matrice venga modificato direttamente, cioè senza utilizzare i metodi dell'interfaccia SVGTransform stessa, il tipo di SVGTransform cambia in SVG_TRANSFORM_MATRIX. Per SVG_TRANSFORM_MATRIX la matrice contiene i valori a, b, c, d, e, f forniti dall'utente. Per SVG_TRANSFORM_TRANSLATE e e f rappresentano le quantità di traslazione (a=1, b=0, c=0 e d=1). Per SVG_TRANSFORM_SCALE a e d rappresentano le quantità di scala (b=0, c=0, e=0 e f=0). Per SVG_TRANSFORM_SKEWX e SVG_TRANSFORM_SKEWY a, b, c e d rappresentano la matrice che produrrà lo skew specificato (e=0 e f=0). Per SVG_TRANSFORM_ROTATE a, b, c, d, e e f insieme rappresentano la matrice che produrrà la rotazione specificata. Quando la rotazione è intorno al punto centrale (0,0), e e f saranno zero."
type: docs

url: /it/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

La matrice che rappresenta questa trasformazione. L'oggetto matrice è live, il che significa che qualsiasi modifica apportata all'oggetto SVGTransform viene immediatamente riflessa nell'oggetto matrice e viceversa. Nel caso in cui l'oggetto matrice venga modificato direttamente (cioè senza utilizzare i metodi dell'interfaccia SVGTransform stessa), il tipo di SVGTransform cambia in SVG_TRANSFORM_MATRIX. Per SVG_TRANSFORM_MATRIX, la matrice contiene i valori a, b, c, d, e, f forniti dall'utente. Per SVG_TRANSFORM_TRANSLATE, e e f rappresentano le quantità di traslazione (a=1, b=0, c=0 e d=1). Per SVG_TRANSFORM_SCALE, a e d rappresentano le quantità di scala (b=0, c=0, e=0 e f=0). Per SVG_TRANSFORM_SKEWX e SVG_TRANSFORM_SKEWY, a, b, c e d rappresentano la matrice che produrrà lo skew specificato (e=0 e f=0). Per SVG_TRANSFORM_ROTATE, a, b, c, d, e e f insieme rappresentano la matrice che produrrà la rotazione specificata. Quando la rotazione è intorno al punto centrale (0, 0), e e f saranno zero.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

La matrice che rappresenta questa trasformazione.

### Vedi anche

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

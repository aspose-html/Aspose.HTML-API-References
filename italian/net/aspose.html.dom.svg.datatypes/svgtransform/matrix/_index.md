---
title: SVGTransform.Matrix
second_title: Aspose.HTML per riferimento API .NET
description: SVGTransform proprietà. La matrice che rappresenta questa trasformazione. Loggetto matrice è attivo il che significa che qualsiasi modifica apportata alloggetto SVGTransform si riflette immediatamente nelloggetto matrice e viceversa. Nel caso in cui loggetto matrice venga modificato direttamente ovvero senza utilizzare i metodi sullinterfaccia SVGTransform stessa il tipo di SVGTransform cambia in SVG_TRANSFORM_MATRIX. Per SVG_TRANSFORM_MATRIX la matrice contiene a b c d e f valori forniti dallutente. Per SVG_TRANSFORM_TRANSLATE e e f rappresentano gli importi di traduzione a 1 b 0 c 0 e d  1. Per SVG_TRANSFORM_SCALE a e d rappresentano gli importi di scala b 0  c 0 e 0 e f  0. Per SVG_TRANSFORM_SKEWX e SVG_TRANSFORM_SKEWY a b c e d rappresentano la matrice che risulterà nella data skew e 0 e f  0. Per SVG_TRANSFORM_ROTATE  a b c d e ed f insieme rappresentano la matrice che risulterà nella data rotazione. Quando la rotazione è attorno al punto centrale 0 0 e ed f saranno zero.
type: docs
weight: 20
url: /it/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

La matrice che rappresenta questa trasformazione. L'oggetto matrice è attivo, il che significa che qualsiasi modifica apportata all'oggetto SVGTransform si riflette immediatamente nell'oggetto matrice e viceversa. Nel caso in cui l'oggetto matrice venga modificato direttamente (ovvero, senza utilizzare i metodi sull'interfaccia SVGTransform stessa), il tipo di SVGTransform cambia in SVG_TRANSFORM_MATRIX. Per SVG_TRANSFORM_MATRIX, la matrice contiene a, b, c, d, e, f valori forniti dall'utente. Per SVG_TRANSFORM_TRANSLATE, e e f rappresentano gli importi di traduzione (a= 1, b= 0, c= 0 e d = 1). Per SVG_TRANSFORM_SCALE, a e d rappresentano gli importi di scala (b= 0 , c= 0, e= 0 e f = 0). Per SVG_TRANSFORM_SKEWX e SVG_TRANSFORM_SKEWY, a, b, c e d rappresentano la matrice che risulterà nella data skew (e= 0 e f = 0). Per SVG_TRANSFORM_ROTATE , a, b, c, d, e ed f insieme rappresentano la matrice che risulterà nella data rotazione. Quando la rotazione è attorno al punto centrale (0, 0), e ed f saranno zero.

```csharp
public SVGMatrix Matrix { get; }
```

### Valore della proprietà

La matrice che rappresenta questa trasformazione.

### Guarda anche

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* spazio dei nomi [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* assemblea [Aspose.HTML](../../../)



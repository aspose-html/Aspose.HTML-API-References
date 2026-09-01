---
title: "ICSS2Properties.Position"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSS2Properties. Los valores de esta propiedad tienen los siguientes significados"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/position/
---
## ICSS2Properties.Position property

Los valores de esta propiedad tienen los siguientes significados:

static - La caja es una caja normal, dispuesta según el [flujo normal](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow). Las propiedades ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left) y ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) no se aplican. relative - La posición de la caja se calcula según el [flujo normal](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) (esto se llama posición en flujo normal). Luego la caja se desplaza [relativamente](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#relative-positioning) a su posición normal. Cuando una caja B está posicionada relativamente, la posición de la caja siguiente se calcula como si B no estuviera desplazada. absolute - La posición de la caja (y posiblemente su tamaño) se especifica con las propiedades ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left), ['right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-right), ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) y ['bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-bottom). Estas propiedades especifican desplazamientos respecto al [bloque contenedor](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block). Las cajas posicionadas absolutamente se sacan del flujo normal. Esto significa que no afectan al diseño de los hermanos posteriores. Además, aunque las cajas [posicionadas absolutamente](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#absolutely-positioned) tengan márgenes, no se [colapsan](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#collapsing-margins) con ningún otro margen. fixed - La posición de la caja se calcula según el modelo 'absolute', pero además la caja está [fijada](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#fixed-positioning) respecto a alguna referencia. En el caso de [medios continuos](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#continuous-media-group), la caja está fijada respecto al [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (y no se mueve al desplazarse). En el caso de [medios paginados](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#paged-media-group), la caja está fijada respecto a la página, incluso si esa página se ve a través de un [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (por ejemplo, en una vista previa de impresión). Los autores pueden querer especificar 'fixed' de forma dependiente del medio.

```java
public String Position { get; set; }
```

### Valor devuelto

propiedad position

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

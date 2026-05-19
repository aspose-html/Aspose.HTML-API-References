---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGGraphicsElement. Devuelve la matriz de transformación desde las unidades de usuario actuales, es decir, después de aplicar el atributo transform, si lo hay, al aviso del agente de usuario padre de un píxel. Para dispositivos de visualización, idealmente esto representa un píxel físico de pantalla. Para otros dispositivos o entornos donde no se conocen los tamaños físicos de los píxeles, se puede usar en su lugar un algoritmo similar a la definición de píxel de CSS2. Nota que se devuelve null si este elemento no está conectado al árbol del documento. Este método podría haberse llamado más apropiadamente getClientCTM, pero se mantiene el nombre getScreenCTM por razones históricas"
type: docs

url: /es/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Devuelve la matriz de transformación desde las unidades de usuario actuales (es decir, después de aplicar el atributo ‘transform’, si lo hay) al aviso del agente de usuario padre de un \"píxel\". Para dispositivos de visualización, idealmente esto representa un píxel físico de pantalla. Para otros dispositivos o entornos donde no se conocen los tamaños físicos de los píxeles, se puede usar un algoritmo similar a la definición de \"píxel\" en CSS2. Observe que se devuelve nulo si este elemento no está conectado al árbol del documento. Este método habría sido más apropiadamente llamado getClientCTM, pero se mantiene el nombre getScreenCTM por razones históricas.

```java
public SVGMatrix GetScreenCTM()
```

### Valor de retorno

Un objeto SVGMatrix que define la matriz de transformación dada.

### Ver también

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

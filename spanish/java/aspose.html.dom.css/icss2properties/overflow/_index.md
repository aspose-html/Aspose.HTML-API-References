---
title: "ICSS2Properties.Overflow"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "propiedad ICSS2Properties. Esta propiedad especifica si el contenido de un elemento de nivel de bloque se recorta cuando desborda la caja del elemento que actúa como bloque contenedor del contenido. Los valores tienen los siguientes significados"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

Esta propiedad especifica si el contenido de un elemento de nivel de bloque se recorta cuando desborda la caja del elemento (que actúa como bloque contenedor del contenido). Los valores tienen los siguientes significados:

visible - Este valor indica que el contenido no se recorta, es decir, puede renderizarse fuera de la caja de bloque. hidden - Este valor indica que el contenido se recorta y que no se debe proporcionar ningún mecanismo de desplazamiento para ver el contenido fuera de la región de recorte; los usuarios no tendrán acceso al contenido recortado. El tamaño y la forma de la región de recorte se especifican mediante la propiedad ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip). scroll - Este valor indica que el contenido se recorta y que si el agente de usuario utiliza un mecanismo de desplazamiento visible en la pantalla (como una barra de desplazamiento o un panel), ese mecanismo debe mostrarse para una caja, haya o no contenido recortado. Esto evita cualquier problema con la aparición y desaparición de barras de desplazamiento en un entorno dinámico. Cuando se especifica este valor y el medio de destino es 'print' o 'projection', el contenido que desborda debe imprimirse. auto - El comportamiento del valor 'auto' depende del agente de usuario, pero debe provocar que se proporcione un mecanismo de desplazamiento para las cajas que desbordan.

```java
public String Overflow { get; set; }
```

### Valor de retorno

propiedad overflow

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

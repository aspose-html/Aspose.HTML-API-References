---
title: "ICSS2Properties.Clear"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSS2Properties. Esta propiedad indica qué lados de las cajas de un elemento no pueden estar adyacentes a una caja flotante anterior. Puede ser que el propio elemento tenga descendientes flotantes; la propiedad clear no tiene efecto sobre ellos."
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Esta propiedad indica qué lados de la(s) caja(s) de un elemento no pueden estar adyacentes a una caja flotante anterior. (Puede ser que el propio elemento tenga descendientes flotantes; la propiedad 'clear' no tiene efecto sobre ellos.)

Esta propiedad solo puede especificarse para elementos de nivel de bloque (incluidos los flotantes). Para cajas compactas y de inserción (run-in), esta propiedad se aplica a la caja de bloque final a la que pertenece la caja compacta o de inserción.

Los valores tienen los siguientes significados cuando se aplican a cajas de bloque no flotantes:

left - El margen superior de la caja generada se incrementa lo suficiente como para que el borde superior quede por debajo del borde exterior inferior de cualquier caja flotante a la izquierda que provenga de elementos anteriores en el documento fuente. right - El margen superior de la caja generada se incrementa lo suficiente como para que el borde superior quede por debajo del borde exterior inferior de cualquier caja flotante a la derecha que provenga de elementos anteriores en el documento fuente. both - La caja generada se mueve debajo de todas las cajas flotantes de elementos anteriores en el documento fuente. none - No hay restricción sobre la posición de la caja respecto a los flotantes.

```java
public String Clear { get; set; }
```

### Valor de retorno

propiedad clear

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

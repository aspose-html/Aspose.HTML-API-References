---
title: "ICSS2Properties.Volume"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "ICSS2Properties propiedad. Volume se refiere al volumen medio de la forma de onda. En otras palabras, una voz muy inflexiva con un volumen de 50 podría superar ese nivel. Es probable que los valores globales sean ajustables por el usuario para comodidad, por ejemplo con un control físico de volumen que aumentaría tanto los valores 0 como 100 de forma proporcional; lo que hace esta propiedad es ajustar el rango dinámico."
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/volume/
---
## ICSS2Properties.Volume property

Volume se refiere al volumen medio de la forma de onda. En otras palabras, una voz muy inflexiva con un volumen de 50 podría superar ese nivel. Es probable que los valores globales sean ajustables por el usuario para comodidad, por ejemplo con un control físico de volumen (que aumentaría tanto los valores 0 como 100 de forma proporcional); lo que hace esta propiedad es ajustar el rango dinámico.

Los valores tienen los siguientes significados:

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - Cualquier número entre '0' y '100'. '0' representa el nivel de volumen audible mínimo y 100 corresponde al nivel máximo cómodo. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Los valores de porcentaje se calculan en relación al valor heredado y luego se recortan al rango '0' a '100'. silent - No hay sonido en absoluto. El valor '0' no significa lo mismo que 'silent'. x-soft - Igual que '0'. soft - Igual que '25'. medium - Igual que '50'. loud - Igual que '75'. x-loud - Igual que '100'.

```java
public String Volume { get; set; }
```

### Valor devuelto

propiedad volume

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

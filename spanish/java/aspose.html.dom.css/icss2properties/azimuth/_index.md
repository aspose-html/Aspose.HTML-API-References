---
title: "ICSS2Properties.Azimuth"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "ICSS2Properties propiedad. El audio espacial es una propiedad estilística importante para la presentación auditiva. Proporciona una forma natural de distinguir varias voces, como en la vida real, la gente rara vez se encuentra todas en el mismo punto de una habitación."
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

El audio espacial es una propiedad estilística importante para la presentación auditiva. Proporciona una forma natural de distinguir varias voces, como en la vida real (la gente rara vez se encuentra todas en el mismo punto de una habitación).

```java
public String Azimuth { get; set; }
```

### Valor de retorno

La propiedad azimuth

### Property Value

Los valores tienen los siguientes significados:

ángulo - La posición se describe en términos de un ángulo dentro del rango '-360deg' a '360deg'. El valor '0deg' significa directamente al frente en el centro del escenario sonoro. '90deg' está a la derecha, '180deg' detrás, y '270deg' (o, de forma equivalente y más conveniente, '-90deg') a la izquierda.

lado-izquierdo - Igual que '270deg'. Con 'behind', '270deg'.

extremo-izquierdo - Igual que '300deg'. Con 'behind', '240deg'.

izquierda - Igual que '320deg'. Con 'behind', '220deg'.

centro-izquierda - Igual que '340deg'. Con 'behind', '200deg'.

centro - Igual que '0deg'. Con 'behind', '180deg'.

centro-derecha - Igual que '20deg'. Con 'behind', '160deg'.

derecha - Igual que '40deg'. Con 'behind', '140deg'.

extremo-derecha - Igual que '60deg'. Con 'behind', '120deg'.

lado-derecho - Igual que '90deg'. Con 'behind', '90deg'.

leftwards - Mueve el sonido a la izquierda, relativo al ángulo actual. Más precisamente, resta 20 grados. La aritmética se realiza módulo 360 grados. Nota que 'leftwards' se describe más acertadamente como "turned counter-clockwise", ya que siempre resta 20 grados, incluso si el azimuth heredado ya está detrás del oyente (en cuyo caso el sonido parece moverse a la derecha).

rightwards - Mueve el sonido a la derecha, relativo al ángulo actual. Más precisamente, suma 20 grados. Ver 'leftwards' para la aritmética.

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

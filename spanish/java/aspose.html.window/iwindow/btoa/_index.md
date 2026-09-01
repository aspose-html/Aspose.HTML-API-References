---
title: "IWindow.Btoa"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IWindow. Toma los datos de entrada en forma de una cadena Unicode que contiene solo caracteres en el rango U0000 a U00FF, cada uno representando un byte binario con valores 0x00 a 0xFF respectivamente, y lo convierte a su representación base64 que devuelve."
type: docs

url: /es/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Toma los datos de entrada, en forma de una cadena Unicode que contiene solo caracteres en el rango U+0000 a U+00FF, cada uno representando un byte binario con valores 0x00 a 0xFF respectivamente, y los convierte a su representación base64, que devuelve.

```java
public String Btoa(String data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | Cadena | La cadena Unicode que contiene solo caracteres en el rango U+0000 a U+00FF. |

### Valor devuelto

La cadena base64.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Lanza una excepción DOMException "InvalidCharacterError" si la cadena de entrada contiene caracteres fuera del rango. |

### Ver también

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

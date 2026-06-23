---
title: "IWindow.Atob"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IWindow. Toma los datos de entrada en forma de una cadena Unicode que contiene datos binarios codificados en base64, los decodifica y devuelve una cadena compuesta por caracteres en el rango U0000 a U00FF, cada uno representando un byte binario con valores 0x00 a 0xFF respectivamente, correspondiente a esos datos binarios."
type: docs

url: /es/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Toma los datos de entrada, en forma de una cadena Unicode que contiene datos binarios codificados en base64, los decodifica y devuelve una cadena compuesta por caracteres en el rango U+0000 a U+00FF, cada uno representando un byte binario con valores 0x00 a 0xFF respectivamente, correspondiente a esos datos binarios.

```java
public String Atob(String data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | Cadena | La cadena Unicode que contiene datos binarios codificados en base64 |

### Valor devuelto

La cadena compuesta por caracteres en el rango U+0000 a U+00FF

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Lanza una excepción DOMException "InvalidCharacterError" si la cadena de entrada no es un dato base64 válido. |

### Ver también

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

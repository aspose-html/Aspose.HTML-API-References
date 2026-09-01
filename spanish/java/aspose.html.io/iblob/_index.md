---
title: "Interfaz IBlob"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.io.IBlob interface. Un objeto Blob se refiere a una secuencia de bytes y tiene un atributo size que es el número total de bytes en la secuencia, y un atributo type que es una String codificada en ASCII en minúsculas que representa el tipo de medio de la secuencia de bytes."
type: docs

url: /es/java/com.aspose.html.io/iblob/
---
## IBlob interface

Un objeto Blob se refiere a una secuencia de bytes y tiene un atributo size que es el número total de bytes en la secuencia, y un atributo type, que es una cadena codificada en ASCII en minúsculas que representa el tipo de medio de la secuencia de bytes.

```java
public interface IBlob
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) Devuelve el tamaño de la secuencia de bytes en número de bytes. Al obtenerlo, los agentes de usuario conformes deben devolver el número total de bytes que pueden ser leídos por un objeto FileReader o FileReaderSync, o 0 si el Blob no tiene bytes para leer. |
| [getType](../../com.aspose.html.io/iblob/type/) La String codificada en ASCII en minúsculas que representa el tipo de medio del Blob. Al obtenerla, los agentes de usuario deben devolver el tipo de un Blob como una String codificada en ASCII en minúsculas, de modo que al convertirse en una secuencia de bytes sea un tipo MIME analizable, o la String vacía – 0 bytes – si no se puede determinar el tipo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | Devuelve un nuevo objeto Blob con bytes que van desde el parámetro opcional start hasta, pero sin incluir, el parámetro opcional end, y con un atributo type cuyo valor es el del parámetro opcional contentType. |

### Ver también

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)

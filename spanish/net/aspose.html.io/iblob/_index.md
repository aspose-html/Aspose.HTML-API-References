---
title: Interface IBlob
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.IO.IBlob interfaz. Un objeto Blob se refiere a una secuencia de bytes y tiene un atributo de tamaño que es el número total de bytes en la secuencia de bytes y un atributo de tipo que es una cadena codificada en ASCII en minúsculas que representa el tipo de medio de la secuencia de bytes .
type: docs
weight: 3700
url: /es/net/aspose.html.io/iblob/
---
## IBlob interface

Un objeto Blob se refiere a una secuencia de bytes y tiene un atributo de tamaño que es el número total de bytes en la secuencia de bytes y un atributo de tipo, que es una cadena codificada en ASCII en minúsculas que representa el tipo de medio de la secuencia de bytes .

```csharp
public interface IBlob
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | Devuelve el tamaño de la secuencia de bytes en número de bytes. Al obtener, los agentes de usuario conformes deben devolver el número total de bytes que puede leer un objeto FileReader o FileReaderSync, o 0 si el Blob no tiene bytes para leer . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | La cadena codificada en ASCII en minúsculas que representa el tipo de medio del Blob. Al obtener, los agentes de usuario deben devolver el tipo de un Blob como una cadena codificada en ASCII en minúsculas, tal que cuando se convierte en un byte secuencia, es un tipo MIME analizable, o la cadena vacía (0 bytes) si no se puede determinar el tipo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | Devuelve un nuevo objeto Blob con bytes que van desde el parámetro de inicio opcional hasta el parámetro final opcional, pero sin incluirlo, y con un atributo de tipo que es el valor del parámetro contentType opcional. |

### Ver también

* espacio de nombres [Aspose.Html.IO](../../aspose.html.io/)
* asamblea [Aspose.HTML](../../)



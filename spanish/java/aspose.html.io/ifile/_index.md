---
title: "Interfaz IFile"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.io.IFile. Un objeto File es un objeto Blob con un atributo name que es una String; puede crearse dentro de la aplicación web mediante un constructor o es una referencia a una secuencia de bytes de un archivo del sistema operativo subyacente."
type: docs

url: /es/java/com.aspose.html.io/ifile/
---
## IFile interface

Un objeto File es un objeto Blob con un atributo name, que es una cadena; puede crearse dentro de la aplicación web mediante un constructor, o es una referencia a una secuencia de bytes de un archivo del sistema de archivos subyacente (SO).

```java
public interface IFile : IBlob
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) La fecha de última modificación del archivo. Al obtenerla, si los agentes de usuario pueden proporcionar esta información, debe devolver un long long establecido al momento en que el archivo fue modificado por última vez, como el número de milisegundos desde la época Unix. |
| [getName](../../com.aspose.html.io/ifile/name/) El nombre del archivo. Al obtenerlo, debe devolver el nombre del archivo como una String. |

### Ver también

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)

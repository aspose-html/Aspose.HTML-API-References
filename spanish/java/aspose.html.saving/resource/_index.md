---
title: "Clase Resource"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.saving.Resource. Esta clase describe un recurso y proporciona métodos para procesarlo."
type: docs

url: /es/java/com.aspose.html.saving/resource/
---
## Resource class

Esta clase describe un recurso y proporciona métodos para procesarlo.

```java
public class Resource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Devuelve el [`MimeType`](../../com.aspose.html/mimetype/) de este recurso. Puede ser `null` si no se encontró el recurso. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Devuelve una cadena que contiene la referencia original a este recurso. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Devuelve una URL que indica dónde se encontraba este recurso. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Devuelve el estado actual del recurso. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Incrusta este recurso dentro de su padre codificándolo como Base64. El resultado de la codificación se escribirá en [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Guarda el recurso en el flujo proporcionado. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Especifica la nueva URL que indica dónde se ubicará el recurso después del procesamiento. |

### Ver también

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

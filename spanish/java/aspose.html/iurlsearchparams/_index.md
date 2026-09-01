---
title: "Interfaz IUrlSearchParams"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Interfaz com.aspose.html.IUrlSearchParams. Proporciona métodos para trabajar con la cadena de consulta de URLs"
type: docs

url: /es/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

Proporciona métodos para trabajar con la cadena de consulta de URLs.

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | Agrega un nuevo par nombre-valor cuyo nombre es `name` y cuyo valor es `value`. |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | Elimina todos los pares nombre-valor cuyo nombre es `name`. |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | Devuelve el valor del primer par nombre-valor cuyo nombre es `name`. |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | Devuelve todos los valores cuyo nombre es `name`. |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | Comprueba si hay un par nombre-valor cuyo nombre es `name` en la lista. |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | Establece el valor del primer par nombre-valor encontrado al valor especificado y elimina los demás. Si no se encuentran pares nombre-valor con el nombre especificado, se añadirá uno nuevo a la lista. |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | Ordena todos los pares nombre-valor, si los hay, por sus nombres. |

### Ver también

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

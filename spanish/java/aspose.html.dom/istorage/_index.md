---
title: "Interfaz IStorage"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.IStorage interfaz. Esta interfaz de la API Web Storage proporciona acceso a la sesión o almacenamiento local de un dominio particular. Consulte la especificación Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /es/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Esta interfaz de la API Web Storage proporciona acceso al almacenamiento de sesión o local de un dominio particular. Consulte la especificación de Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Devuelve el número de pares clave/valor. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Elimina todos los pares clave/valor, si existen. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Devuelve el valor actual asociado con la clave proporcionada, o null si la clave proporcionada no existe. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Devuelve el nombre de la n‑ésima clave, o null si n es mayor o igual que el número de pares clave/valor. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Elimina el par clave/valor con la clave proporcionada, si existe un par clave/valor con esa clave. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Establece el valor del par identificado por la clave a value, creando un nuevo par clave/valor si previamente no existía ninguno para esa clave. |

### Ver también

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

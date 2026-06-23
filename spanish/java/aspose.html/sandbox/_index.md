---
title: "Enumeración Sandbox"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Enumeración com.aspose.html.Sandbox. Un conjunto de banderas de sandbox es un conjunto de cero o más de las siguientes banderas que se utilizan para restringir las capacidades de recursos potencialmente no confiables"
type: docs

url: /es/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Un conjunto de banderas de sandboxing es un conjunto de cero o más de las siguientes banderas, que se utilizan para restringir las capacidades de recursos potencialmente no confiables.

```java
[Flags]
public enum Sandbox
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | No hay ninguna bandera establecida, se aceptan todas las funciones de sandbox |
| Navigation | `1` | Esta bandera impide que el contenido navegue contextos de navegación diferentes al sandboxed browsing context (o a los contextos de navegación anidados dentro de él), contextos de navegación auxiliares (que están protegidos por la sandboxed auxiliary navigation browsing context flag definida a continuación) y el top-level browsing context (que está protegido por la sandboxed top-level navigation browsing context flag definida más abajo). Si la sandboxed auxiliary navigation browsing context flag no está establecida, entonces, en ciertos casos, las restricciones aún permiten abrir popups (nuevos top-level browsing contexts). Estos contextos de navegación siempre tienen un sandboxed navigator permitido, establecido cuando se crea el contexto de navegación, lo que permite al contexto que los creó navegar realmente en ellos. (De lo contrario, la sandboxed navigation browsing context flag impediría que fueran navegados incluso si se abrieran.) |
| AuxiliaryNavigation | `2` | Esta bandera impide que el contenido cree nuevos auxiliary browsing contexts, p. ej., usando el atributo target o el método window.open(). |
| TopLevelNavigation | `4` | Esta bandera impide que el contenido navegue su top-level browsing context y evita que el contenido cierre su top-level browsing context. Cuando la sandboxed top-level navigation browsing context flag no está establecida, el contenido puede navegar su top-level browsing context, pero los demás browsing contexts siguen protegidos por la sandboxed navigation browsing context flag y, posiblemente, por la sandboxed auxiliary navigation browsing context flag. |
| Plugins | `8` | Esta bandera impide que el contenido instancie plugins, ya sea usando el elemento embed, el elemento object, el elemento applet o mediante la navegación de un nested browsing context, a menos que esos plugins puedan asegurarse. |
| Origin | `10` | Esta bandera obliga al contenido a un origen único, evitando así que acceda a otro contenido del mismo origen. |
| Forms | `20` | Esta bandera bloquea el envío de formularios. |
| PointerLock | `40` | Esta bandera desactiva la API Pointer Lock. |
| Scripts | `80` | Esta bandera bloquea la ejecución de scripts. |
| AutomaticFeatures | `100` | Esta bandera bloquea características que se activan automáticamente, como la reproducción automática de un video o el enfoque automático de un control de formulario. |
| Fullscreen | `200` | Esta bandera impide que el contenido use el método requestFullscreen(). |
| DocumentDomain | `400` | Esta bandera impide que el contenido use la característica document.domain para cambiar el origen efectivo del script. |
| Images | `800` | Esta bandera desactiva la carga de imágenes. |

### Ver también

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

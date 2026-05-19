---
title: "Enumeración Sandbox"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Enumeración com.aspose.html.Sandbox. Un conjunto de banderas de sandbox es un conjunto de cero o más de las siguientes banderas que se utilizan para restringir las capacidades de recursos potencialmente no confiables"
type: docs

url: /es/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Un conjunto de indicadores de sandbox es un conjunto de cero o más de los siguientes indicadores, que se utilizan para restringir las capacidades de recursos potencialmente no confiables.

```java
[Flags]
public enum Sandbox
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | No se ha establecido ninguna bandera, se aceptan todas las funciones de sandbox |
| Navigation | `1` | Esta bandera impide que el contenido navegue por contextos de navegación distintos al contexto de navegación aislado en sí (o a contextos de navegación más anidados dentro de él), contextos de navegación auxiliares (que están protegidos por la bandera de navegación auxiliar del contexto de navegación aislado definida a continuación), y el contexto de navegación de nivel superior (que está protegido por la bandera de navegación de nivel superior del contexto de navegación aislado definida más abajo). Si la bandera de navegación auxiliar del contexto de navegación aislado no está establecida, entonces, en ciertos casos, las restricciones aún permiten que se abran ventanas emergentes (nuevos contextos de navegación de nivel superior). Estos contextos de navegación siempre tienen un navegador aislado permitido, establecido cuando se crea el contexto de navegación, lo que permite que el contexto que los creó los navegue realmente. (De lo contrario, la bandera de navegación del contexto de navegación aislado evitaría que fueran navegados incluso si se abrieran.) |
| AuxiliaryNavigation | `2` | Esta bandera impide que el contenido cree nuevos contextos de navegación auxiliares, p. ej., usando el atributo target o el método window.open(). |
| TopLevelNavigation | `4` | Esta bandera impide que el contenido navegue su contexto de navegación de nivel superior y evita que el contenido cierre su contexto de navegación de nivel superior. Cuando la bandera de navegación de nivel superior del contexto de navegación aislado no está establecida, el contenido puede navegar su contexto de nivel superior, pero los demás contextos de navegación siguen protegidos por la bandera de navegación del contexto de navegación aislado y, posiblemente, por la bandera de navegación auxiliar del contexto de navegación aislado. |
| Plugins | `8` | Esta bandera impide que el contenido instancie complementos, ya sea usando el elemento embed, el elemento object, el elemento applet o mediante la navegación de un contexto de navegación anidado, a menos que esos complementos puedan asegurarse. |
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

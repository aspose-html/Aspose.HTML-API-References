---
title: "Enum MarkdownFeatures"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.saving.MarkdownFeatures enum. Un conjunto de banderas MarkdownFeatures es un conjunto de cero o más de las siguientes banderas que se utilizan para seleccionar los elementos convertidos a markdown."
type: docs

url: /es/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

Un conjunto de banderas `MarkdownFeatures` es un conjunto de cero o más de las siguientes banderas, que se utilizan para seleccionar los elementos convertidos a markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| InlineHTML | `1` | Esta bandera habilita la inserción en línea de elementos HTML. Si esta bandera está activada, los elementos de nivel de bloque (como `div`) cuyo atributo `markdown` tiene el valor `inline` se insertarán en el markdown resultante. |
| AutomaticParagraph | `2` | Esta bandera habilita la conversión de elementos `paragraph`. El contenido de dichos elementos se colocará en líneas separadas, por lo que los manejadores de markdown lo envolverán. |
| Header | `4` | Esta bandera habilita la conversión de elementos `header`. |
| Blockquote | `8` | Esta bandera habilita la conversión de elementos `blockquote`. |
| List | `10` | Esta bandera habilita la conversión de elementos `list`. |
| CodeBlock | `20` | Esta bandera habilita la conversión de bloques de código. Un bloque de código consta de 2 elementos `pre` y `code`, el contenido de dicha construcción se procesa "tal cual". |
| HorizontalRule | `40` | Esta bandera habilita la conversión de `horizontal rules`. |
| Link | `80` | Esta bandera habilita la conversión de elementos `a`. |
| Emphasis | `100` | Esta bandera permite la conversión de los elementos `emphasis`. |
| InlineCode | `200` | Esta bandera permite la conversión de los elementos `code`. |
| Image | `400` | Esta bandera permite la conversión de los elementos `img`. |
| LineBreak | `800` | Esta bandera permite la conversión de los elementos `br`. |
| Video | `1000` | Esta bandera permite la conversión de los elementos `video`. |
| Table | `2000` | Esta bandera permite la conversión de los elementos `table`. |
| TaskList | `4000` | Esta bandera permite la conversión de listas de tareas. La lista de tareas consiste en el elemento `input`, que debe ser el primer hijo del elemento `list` y cuyo valor del atributo `type` debe ser igual a `checkbox`. |
| Strikethrough | `8000` | Esta bandera permite la conversión de los elementos `del`. |
| Strong | `10000` | Esta bandera permite la conversión de los elementos `strong`. |

### Ver también

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)

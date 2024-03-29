---
title: Enum MarkdownFeatures
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Saving.MarkdownFeatures enumeración. AMarkdownFeatures conjunto de indicadores es un conjunto de cero o más de los siguientes indicadores que se utilizan para seleccionar elementos convertidos a rebajas.
type: docs
weight: 4620
url: /es/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

A`MarkdownFeatures` conjunto de indicadores es un conjunto de cero o más de los siguientes indicadores, que se utilizan para seleccionar elementos convertidos a rebajas.

```csharp
[Flags]
public enum MarkdownFeatures
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| InlineHTML | `1` | Esta bandera habilita la inserción de elementos HTML. Si esta bandera está establecida, los elementos de nivel de bloque (como`división` ) cuyo`reducción` el valor del atributo es igual`en línea` se insertará en el descuento resultante. |
| AutomaticParagraph | `2` | Esta bandera permite la conversión de`párrafo` elementos. El contenido de dichos elementos se colocará en líneas separadas, por lo que los controladores de rebajas lo envolverán. |
| Header | `4` | Esta bandera permite la conversión de`encabezamiento` elementos. |
| Blockquote | `8` | Esta bandera permite la conversión de`cita en bloque` elementos. |
| List | `10` | Esta bandera permite la conversión de`lista` elementos. |
| CodeBlock | `20` | Esta bandera permite la conversión de bloques de código. El bloque de código consta de 2 elementos`pre` y`código` , el contenido de dicha construcción son procesos "tal cual". |
| HorizontalRule | `40` | Esta bandera permite la conversión de`reglas horizontales` . |
| Link | `80` | Esta bandera permite la conversión de`a` elementos. |
| Emphasis | `100` | Esta bandera permite la conversión de`énfasis` elementos. |
| InlineCode | `200` | Esta bandera permite la conversión de`código` elementos. |
| Image | `400` | Esta bandera permite la conversión de`imagen` elementos. |
| LineBreak | `800` | Esta bandera permite la conversión de`hermano` elementos. |
| Video | `1000` | Esta bandera permite la conversión de`video` elementos. |
| Table | `2000` | Esta bandera permite la conversión de`mesa` elementos. |
| TaskList | `4000` | Este indicador permite la conversión de listas de tareas. La lista de tareas consta de`aporte` elemento, que debe ser el primer hijo de`lista` elemento y cuyo`tipo` el valor del atributo debe ser igual`caja` . |
| Strikethrough | `8000` | Esta bandera permite la conversión de`del` elementos. |
| Strong | `10000` | Esta bandera permite la conversión de`fuerte` elementos. |

### Ver también

* espacio de nombres [Aspose.Html.Saving](../../aspose.html.saving/)
* asamblea [Aspose.HTML](../../)



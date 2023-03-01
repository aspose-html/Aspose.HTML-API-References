---
title: Interface ICSSImportRule
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Css.ICSSImportRule interfaz. La interfaz CSSImportRule representa una regla import dentro de una hoja de estilo CSS. La regla import se utiliza para importar reglas de estilo de otras hojas de estilo.
type: docs
weight: 410
url: /es/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

La interfaz CSSImportRule representa una regla @import dentro de una hoja de estilo CSS. La regla @import se utiliza para importar reglas de estilo de otras hojas de estilo.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | La ubicación de la hoja de estilo que se va a importar. El atributo no contendrá el especificador "url(...)" alrededor del URI. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | Una lista de tipos de medios para los que se puede usar esta hoja de estilo. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | La hoja de estilo a la que hace referencia esta regla, si se ha cargado. El valor de este atributo es nulo si la hoja de estilo aún no se ha cargado o si no se cargará (p. ej., si la hoja de estilo es para un tipo de medio no compatible con el agente de usuario). |

### Ver también

* interface [ICSSRule](../icssrule/)
* espacio de nombres [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* asamblea [Aspose.HTML](../../)



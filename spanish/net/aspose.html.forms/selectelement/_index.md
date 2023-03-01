---
title: Class SelectElement
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Forms.SelectElement clase. SelectElement representa un contenedor que está asociado con HTMLSelectElement
type: docs
weight: 3020
url: /es/net/aspose.html.forms/selectelement/
---
## SelectElement class

SelectElement representa un contenedor que está asociado con HTMLSelectElement

```csharp
public class SelectElement : FormElement<HTMLSelectElement>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | Obtiene el tipo del elemento. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/selectelement/id/) { get; set; } | Representa el atributo Id del elemento de entrada. |
| [Multiple](../../aspose.html.forms/selectelement/multiple/) { get; set; } | Si es verdadero, múltiples`OPCIÓN` los elementos pueden ser seleccionados en este`SELECCIONAR` . Ver la definición de múltiples atributos en HTML 4.01. |
| override [Name](../../aspose.html.forms/selectelement/name/) { get; set; } | Representa el atributo de nombre del elemento de entrada. |
| [Options](../../aspose.html.forms/selectelement/options/) { get; } | Devuelve una lista de opciones |
| [SelectedOptions](../../aspose.html.forms/selectelement/selectedoptions/) { get; } | Devuelve una lista de opciones seleccionadas |
| [Type](../../aspose.html.forms/selectelement/type/) { get; } | El tipo de este control de formulario. Esta es la cadena "select-multiple" cuando el atributo multiple es`verdadero` y la cadena "select-one" cuando`FALSO` . |
| override [Value](../../aspose.html.forms/selectelement/value/) { get; set; } | Al obtener, debe devolver el valor del primer elemento de opción en la lista de opciones en orden de árbol que tiene su selección establecida en verdadero, si corresponde. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SelectItems](../../aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | Este método permite seleccionar múltiples opciones por sus índices. |
| [SelectItems](../../aspose.html.forms/selectelement/selectitems/#selectitems_1)(params string[]) | Este método permite seleccionar múltiples opciones por sus valores. |

### Ver también

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../aspose.html/htmlselectelement/)
* espacio de nombres [Aspose.Html.Forms](../../aspose.html.forms/)
* asamblea [Aspose.HTML](../../)



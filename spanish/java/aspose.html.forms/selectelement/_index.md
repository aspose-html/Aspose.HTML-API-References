---
title: "Clase SelectElement"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.forms.SelectElement. El SelectElement representa un contenedor asociado con el HTMLSelectElement."
type: docs

url: /es/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

El SelectElement representa un contenedor que está asociado con el HTMLSelectElement

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Obtiene el tipo del elemento. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | Representa el atributo Id del elemento input. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | Representa el atributo name del elemento input. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) Devuelve una lista de opciones |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) Devuelve una lista de opciones seleccionadas |
| [getType](../../com.aspose.html.forms/selectelement/type/) El tipo de este control de formulario. Es la cadena "select-multiple" cuando el atributo multiple es `true` y la cadena "select-one" cuando es `false`. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | Al obtenerlo, debe devolver el valor del primer elemento option en la lista de opciones en orden de árbol que tenga su estado selected establecido en true, si existe. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | Este método permite seleccionar múltiples opciones por sus índices. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | Este método permite seleccionar múltiples opciones por sus valores. |

### Ver también

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)

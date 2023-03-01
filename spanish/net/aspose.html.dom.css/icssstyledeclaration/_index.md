---
title: Interface ICSSStyleDeclaration
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration interfaz. La interfaz CSSStyleDeclaration representa un solo bloque de declaración CSS. Esta interfaz se puede usar para determinar las propiedades de estilo establecidas actualmente en un bloque o para establecer las propiedades de estilo explícitamente dentro del bloque.
type: docs
weight: 490
url: /es/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

La interfaz CSSStyleDeclaration representa un solo bloque de declaración CSS. Esta interfaz se puede usar para determinar las propiedades de estilo establecidas actualmente en un bloque o para establecer las propiedades de estilo explícitamente dentro del bloque.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | La representación textual analizable del bloque de declaración (sin incluir las llaves que lo rodean). Establecer este atributo dará como resultado el análisis del nuevo valor y el restablecimiento de todas las propiedades en el bloque de declaración, incluida la eliminación o adición de propiedades. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Se utiliza para recuperar las propiedades que se han establecido explícitamente en este bloque de declaración. El orden de las propiedades recuperadas mediante este método no tiene que ser el orden en que se establecieron. Este método se puede usar para iterar sobre todas las propiedades en este bloque de declaración. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | El número de propiedades que se han establecido explícitamente en este bloque de declaración. El rango de índices válidos es de 0 a longitud-1 inclusive. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | La regla CSS que contiene este bloque de declaración o nulo si esta CSSStyleDeclaration no está adjunta a una CSSRule. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Se utiliza para recuperar la representación de objeto del valor de una propiedad CSS si se ha establecido explícitamente dentro de este bloque de declaración. Este método devuelve un valor nulo si la propiedad es una propiedad abreviada. Los valores de propiedad abreviados solo se pueden acceder y modificar como cadenas, usando los métodos getPropertyValue y setProperty. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Se utiliza para recuperar la prioridad de una propiedad CSS (por ejemplo, el calificador "importante") si la propiedad se ha establecido explícitamente en este bloque de declaración. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Se utiliza para recuperar el valor de una propiedad CSS si se ha establecido explícitamente dentro de este bloque de declaración. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | Se usa para eliminar una propiedad CSS si se ha establecido explícitamente dentro de este bloque de declaración. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Se utiliza para establecer un valor de propiedad con prioridad predeterminada dentro de este bloque de declaración. La prioridad predeterminada no es "importante", es decir, String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Se utiliza para establecer un valor de propiedad y una prioridad dentro de este bloque de declaración. |

### Ver también

* interface [ICSS2Properties](../icss2properties/)
* espacio de nombres [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* asamblea [Aspose.HTML](../../)



---
title: TypeInfo.IsDerivedFrom
second_title: Referencia de API de Aspose.HTML para .NET
description: TypeInfo método. Este método devuelve si existe una derivación entre la definición de tipo de referencia es decir el TypeInfo sobre el que se llama al método y la otra definición de tipo es decir la que se pasa como parámetros.
type: docs
weight: 30
url: /es/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Este método devuelve si existe una derivación entre la definición de tipo de referencia, es decir, el TypeInfo sobre el que se llama al método, y la otra definición de tipo, es decir, la que se pasa como parámetros.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| typeNamespaceArg | String | el espacio de nombres de la otra definición de tipo |
| typeNameArg | String | el nombre de la otra definición de tipo. |
| derivationMethod | UInt64 | el tipo de derivación y las condiciones aplicadas entre dos tipos, como se describe en la lista de constantes proporcionada en esta interfaz. |

### Valor_devuelto

Si el esquema del documento es una DTD o no hay ningún esquema asociado con el documento, este método siempre devolverá falso. Si el esquema del documento es un esquema XML, el método será verdadero si la definición de tipo de referencia se deriva de la otra definición de tipo según el parámetro de derivación. Si el valor del parámetro es 0 (ningún bit se establece en 1 para el parámetro derivationMethod), el método devolverá verdadero si se puede llegar a la otra definición de tipo recurriendo a cualquier combinación de {definición de tipo base}, {definición de tipo de elemento} , o {definiciones de tipo de miembro} de la definición de tipo de referencia.

### Ver también

* class [TypeInfo](../)
* espacio de nombres [Aspose.Html.Dom](../../typeinfo/)
* asamblea [Aspose.HTML](../../../)



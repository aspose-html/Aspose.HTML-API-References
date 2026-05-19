---
title: "TypeInfo.IsDerivedFrom"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método TypeInfo. Este método devuelve si existe una derivación entre la definición de tipo de referencia, es decir, el TypeInfo sobre el cual se llama el método, y la otra definición de tipo, es decir, la que se pasa como parámetro"
type: docs

url: /es/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Este método devuelve si existe una derivación entre la definición del tipo de referencia, es decir, el TypeInfo sobre el cual se llama el método, y la otra definición de tipo, es decir, la que se pasa como parámetro.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeNamespaceArg | String | el paquete de la otra definición de tipo |
| typeNameArg | String | el nombre de la otra definición de tipo. |
| derivationMethod | UInt64 | el tipo de derivación y las condiciones aplicadas entre dos tipos, como se describe en la lista de constantes proporcionada en esta interfaz. |

### Valor de retorno

Si el esquema del documento es un DTD o no hay ningún esquema asociado al documento, este método siempre devolverá false. Si el esquema del documento es un XML Schema, el método devolverá true si la definición de tipo de referencia está derivada de la otra definición de tipo según el parámetro de derivación. Si el valor del parámetro es 0 (ningún bit está establecido en 1 para el parámetro derivationMethod), el método devolverá true si la otra definición de tipo puede alcanzarse recursivamente mediante cualquier combinación de {base type definition}, {item type definition} o {member type definitions} desde la definición de tipo de referencia.

### Ver también

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

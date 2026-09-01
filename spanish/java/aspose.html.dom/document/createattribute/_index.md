---
title: "Document.CreateAttribute"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. El método Document.createAttribute crea un nuevo nodo de atributo y lo devuelve. El objeto crea un nodo que implementa la interfaz Attr. El DOM no impone qué tipo de atributos pueden añadirse a un elemento particular de esta manera."
type: docs

url: /es/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

El método Document.createAttribute() crea un nuevo nodo de atributo y lo devuelve. El objeto crea un nodo que implementa la interfaz [`Attr`](../../attr/). El DOM no impone qué tipo de atributos pueden añadirse a un elemento particular de esta manera.

```java
public Attr CreateAttribute(String localName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | Cadena | name es una cadena que contiene el nombre del atributo. |

### Valor devuelto

Un nodo [`Attr`](../../attr/).

## Ejemplos

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### Ver también

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

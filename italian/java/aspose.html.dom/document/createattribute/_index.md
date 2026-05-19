---
title: "Document.CreateAttribute"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Document. Il metodo Document.createAttribute crea un nuovo nodo attributo e lo restituisce. L'oggetto crea un nodo che implementa l'interfaccia Attr. Il DOM non impone quale tipo di attributi possa essere aggiunto a un elemento in questo modo."
type: docs

url: /it/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Il metodo Document.createAttribute() crea un nuovo nodo attributo e lo restituisce. L'oggetto crea un nodo che implementa l'interfaccia [`Attr`](../../attr/). Il DOM non impone quale tipo di attributi possa essere aggiunto a un elemento in questo modo.

```java
public Attr CreateAttribute(String localName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | String | name è una String che contiene il nome dell'attributo. |

### Valore di ritorno

Un nodo [`Attr`](../../attr/).

## Esempi

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### Vedi anche

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

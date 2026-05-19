---
title: "Clase MutationRecord"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.mutations.MutationRecord class. Un MutationRecord representa una mutación individual del DOM. Es el objeto que se pasa al MutationCallback de MutationObservers."
type: docs

url: /es/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Un MutationRecord representa una mutación individual del DOM. Es el objeto que se pasa al [`MutationCallback`](../mutationcallback/) de [`MutationObserver`](../mutationobserver/).

```java
public class MutationRecord : DOMObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Devuelve los nodos añadidos. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Devuelve el nombre local del atributo modificado, o null en caso contrario. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Devuelve el espacio de nombres del atributo modificado, o null en caso contrario. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Devuelve el siguiente hermano de los nodos añadidos o eliminados, o null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) El valor devuelto depende del tipo. Para "attributes", es el valor del atributo modificado antes del cambio. Para "characterData", son los datos del nodo modificado antes del cambio. Para "childList", es null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Devuelve el hermano anterior de los nodos añadidos o eliminados, o null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Devuelve los nodos eliminados. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Devuelve el nodo afectado por la mutación, según el tipo. Para "attributes", es el elemento cuyo atributo cambió. Para "characterData", es el nodo CharacterData. Para "childList", es el nodo cuyos hijos cambiaron. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Devuelve "attributes" si fue una mutación de atributo, "characterData" si fue una mutación a un nodo CharacterData y "childList" si fue una mutación al árbol de nodos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |

### Ver también

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)

---
title: Class MutationRecord
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Mutations.MutationRecord clase. Un MutationRecord representa una mutación DOM individual. Es el objeto que se pasa aMutationObserver sMutationCallback .
type: docs
weight: 990
url: /es/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Un MutationRecord representa una mutación DOM individual. Es el objeto que se pasa a[`MutationObserver`](../mutationobserver/) s[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | Devuelve los nodos agregados. |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | Devuelve el nombre local del atributo modificado y nulo en caso contrario. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | Devuelve el espacio de nombres del atributo modificado y nulo en caso contrario. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | Devuelve el siguiente hermano de los nodos agregados o eliminados, o nulo. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | El valor devuelto depende del tipo. Para "atributos", es el valor del atributo modificado antes del cambio. Para "characterData", es el dato del nodo modificado antes del cambio. Para "childList", es nulo. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | Devuelve el hermano anterior de los nodos agregados o eliminados, o nulo. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | Devuelve los nodos eliminados. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | Devuelve el nodo afectado por la mutación, según el tipo. Para "atributos", es el elemento cuyo atributo cambió. Para "characterData", es el nodo CharacterData. Para "childList", es el nodo cuyos hijos cambiaron. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | Devuelve "attributes" si fue una mutación de atributo, "characterData" si fue una mutación a un nodo CharacterData y "childList" si fue una mutación al árbol de nodos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |

### Ver también

* class [DOMObject](../../aspose.html.dom/domobject/)
* espacio de nombres [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* asamblea [Aspose.HTML](../../)



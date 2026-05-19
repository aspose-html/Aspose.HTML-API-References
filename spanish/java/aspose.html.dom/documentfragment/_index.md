---
title: "Clase DocumentFragment"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.DocumentFragment. DocumentFragment es un objeto Document ligero o mínimo. Es muy común querer extraer una porción del árbol de un documento o crear un nuevo fragmento de un documento."
type: docs

url: /es/java/com.aspose.html.dom/documentfragment/
---
## DocumentFragment class

DocumentFragment es un objeto Document "ligero" o "mínimo". Es muy común querer poder extraer una porción del árbol de un documento o crear un nuevo fragmento de un documento.

```java
public class DocumentFragment : Node, IParentNode
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La propiedad de solo lectura baseURI de la interfaz Node devuelve la URL base absoluta del documento que contiene el nodo. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) Devuelve el número actual de nodos de elemento que son hijos de este elemento. 0 si este elemento no tiene nodos hijos que sean de nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propiedad de solo lectura childNodes de la interfaz Node devuelve una [`NodeList`](../../com.aspose.html.collections/nodelist/) en vivo de los nodos hijos del elemento dado donde el primer nodo hijo tiene el índice 0. Los nodos hijos incluyen elementos, texto y comentarios. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) Devuelve los elementos hijos del elemento actual. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propiedad de solo lectura firstChild de la interfaz [`Node`](../node/) devuelve el primer hijo del nodo en el árbol, o null si el nodo no tiene hijos. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) Devuelve el primer nodo de elemento hijo de este elemento. null si este elemento no tiene elementos hijos. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propiedad de solo lectura lastChild de la interfaz [`Node`](../node/) devuelve el último hijo del nodo. Si su padre es un elemento, entonces el hijo suele ser un nodo de elemento, un nodo de texto o un nodo de comentario. Devuelve null si no hay elementos hijos. |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) Devuelve el último nodo de elemento hijo de este elemento. null si este elemento no tiene elementos hijos. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Devuelve la parte local del nombre calificado de este nodo. Para nodos de cualquier tipo que no sean [`ELEMENT_NODE`](../node/element_node/) y [`ATTRIBUTE_NODE`](../node/attribute_node/) y nodos creados con un método DOM Level 1, como [`Document.createElement()`](../document/createelement/), esto siempre es null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La propiedad de solo lectura Element.packageURI devuelve el URI del paquete del elemento, o null si el elemento no está en un paquete. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) Devuelve el siguiente nodo de elemento hermano de este elemento. null si este elemento no tiene nodos hermanos de elemento que aparezcan después de este en el árbol del documento. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propiedad de solo lectura nextSibling de la interfaz [`Node`](../node/) devuelve el nodo que sigue inmediatamente al especificado en los [`childNodes`](../node/childnodes/) de su padre, o devuelve null si el nodo especificado es el último hijo del elemento padre. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) El nombre de este nodo, según su tipo. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) Un código que representa el tipo del objeto subyacente. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La propiedad nodeValue de la interfaz [`Node `](../node/) devuelve o establece el valor del nodo actual. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propiedad de solo lectura ownerDocument de la interfaz Node devuelve el objeto de documento de nivel superior del nodo. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propiedad de solo lectura parentElement de la interfaz [`Node`](../node/) devuelve el [`Element`](../element/) padre del nodo DOM, o null si el nodo no tiene padre o su padre no es un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propiedad de solo lectura parentNode de la interfaz Node devuelve el padre del nodo especificado en el árbol DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La propiedad de solo lectura prefix devuelve el prefijo del paquete del elemento especificado, o null si no se especifica ningún prefijo. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) Devuelve el nodo de elemento hermano anterior de este elemento. null si este elemento no tiene nodos hermanos de elemento que aparezcan antes de este en el árbol del documento. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propiedad de solo lectura previousSibling de la interfaz [`Node`](../node/) devuelve el nodo que precede inmediatamente al especificado en la lista de [`childNodes`](../node/firstchild/) de su padre, o null si el nodo especificado es el primero de esa lista. |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como null, establecerlo no tiene efecto. Al establecerlo, cualquier hijo posible que pueda tener este nodo se elimina y, si la nueva cadena no está vacía ni es null, se reemplaza por un único nodo Text que contiene la cadena a la que se establece este atributo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | El método addEventListener() de la interfaz [`EventTarget `](../eventtarget/) configura una función que será llamada siempre que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | El método addEventListener() de la [EventTarget ](T:com.aspose.html.dom.EventTarget)interfaz configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | El método addEventListener() de la [EventTarget ](T:com.aspose.html.dom.EventTarget)interfaz configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | El método appendChild() de la interfaz Node agrega un nodo al final de la lista de hijos de un nodo padre especificado. Si el hijo dado es una referencia a un nodo existente en el documento, appendChild() lo mueve de su posición actual a la nueva posición (no es necesario eliminar el nodo de su nodo padre antes de añadirlo a otro nodo). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Envía un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) especificado, (de forma síncrona) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase de burbujeo opcional) también se aplican a los eventos enviados manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | El método hasChildNodes() de la interfaz Node devuelve un valor booleano que indica si el [`Node`](../node/) dado tiene nodos hijos o no. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | El método insertBefore() de la interfaz Node inserta un nodo antes de un nodo de referencia como hijo de un nodo padre especificado. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | El método isDefaultNamespace() de la interfaz Node acepta una URI de paquete como argumento. Devuelve un valor booleano que es true si el paquete es el paquete predeterminado en el nodo dado y false en caso contrario. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | El método isEqualNode() de la interfaz [`Node`](../node/) prueba si dos nodos son iguales. Dos nodos son iguales cuando tienen el mismo tipo, características definitorias (para elementos, esto sería su ID, número de hijos, etc.), sus atributos coinciden, y así sucesivamente. El conjunto específico de datos que deben coincidir varía según los tipos de los nodos. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | El método isSameNode() de la interfaz Node es un alias heredado para el operador de igualdad estricta ===. Es decir, prueba si dos nodos son el mismo (en otras palabras, si hacen referencia al mismo objeto). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | El método lookupNamespaceURI() de la interfaz Node toma un prefijo como parámetro y devuelve la URI del paquete asociada a él en el nodo dado si se encuentra (y null si no). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | El método lookupPrefix() de la interfaz Node devuelve una cadena que contiene el prefijo para una URI de paquete dada, si está presente, y null si no lo está. Cuando son posibles varios prefijos, se devuelve el primer prefijo. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Pone todos los nodos [`Text`](../text/) en toda la profundidad del subárbol bajo este Node, incluidos los nodos de atributo, en una forma \"normal\" donde solo la estructura (p.ej., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), y [`entity references`](../entityreference/)) separa los nodos [`Text`](../text/), es decir, no hay nodos Text adyacentes ni nodos Text vacíos. Esto puede usarse para asegurar que la vista DOM de un documento sea la misma que si se guardara y recargara, y es útil cuando se realizan operaciones (como búsquedas XPointer [XPointer]) que dependen de una estructura de árbol de documento particular. Si el parámetro \"normalize-characters\" del objeto [`DOMConfiguration`](../../com.aspose.html/configuration/) adjunto al [`Node.ownerDocument`](../node/ownerdocument/) es true, este método también normalizará completamente los caracteres de los nodos Text. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | Devuelve el primer Element en el documento que coincide con el selector |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | Devuelve una NodeList de todos los Elements en el documento que coinciden con el selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | El método removeChild() de la interfaz Node elimina un nodo hijo del DOM y devuelve el nodo eliminado. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Reemplaza el nodo hijo oldChild con newChild en la lista de hijos y devuelve el nodo oldChild. Si newChild es un objeto `DocumentFragment`, oldChild es reemplazado por todos los hijos `DocumentFragment`, que se insertan en el mismo orden. Si newChild ya está en el árbol, se elimina primero. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Devuelve una cadena que representa esta instancia. |

### Ver también

* class [Node](../node/)
* interface [IParentNode](../iparentnode/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

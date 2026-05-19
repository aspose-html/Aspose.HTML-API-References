---
title: "Clase CDATASection"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.CDATASection. Las secciones CDATA se utilizan para escapar bloques de texto que contienen caracteres que de otro modo se considerarían como marcado."
type: docs

url: /es/java/com.aspose.html.dom/cdatasection/
---
## CDATASection class

Las secciones CDATA se utilizan para escapar bloques de texto que contienen caracteres que de otro modo se considerarían marcado.

```java
public class CDATASection : Text
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La propiedad de solo lectura baseURI de la interfaz Node devuelve la URL base absoluta del documento que contiene el nodo. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propiedad de solo lectura childNodes de la interfaz Node devuelve una [`NodeList`](../../com.aspose.html.collections/nodelist/) en vivo de los nodos hijos del elemento dado donde el primer nodo hijo tiene el índice 0. Los nodos hijos incluyen elementos, texto y comentarios. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | Los datos de carácter del nodo que implementa esta interfaz. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propiedad de solo lectura firstChild de la interfaz [`Node`](../node/) devuelve el primer hijo del nodo en el árbol, o null si el nodo no tiene hijos. |
| [getIsElementContentWhitespace](../../com.aspose.html.dom/text/iselementcontentwhitespace/) Devuelve si este nodo de texto contiene espacio en blanco de contenido de elemento, a menudo llamado abusivamente "espacio en blanco ignorado". |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propiedad de solo lectura lastChild de la interfaz [`Node`](../node/) devuelve el último hijo del nodo. Si su padre es un elemento, entonces el hijo suele ser un nodo de elemento, un nodo de texto o un nodo de comentario. Devuelve null si no hay elementos hijos. |
| [getLength](../../com.aspose.html.dom/characterdata/length/) El número de unidades de 16 bits disponibles a través de data y el método subStringData a continuación. Este puede tener el valor cero, es decir, los nodos CharacterData pueden estar vacíos. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Devuelve la parte local del nombre calificado de este nodo. Para nodos de cualquier tipo que no sean [`ELEMENT_NODE`](../node/element_node/) y [`ATTRIBUTE_NODE`](../node/attribute_node/) y nodos creados con un método DOM Level 1, como [`Document.createElement()`](../document/createelement/), esto siempre es null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La propiedad de solo lectura Element.packageURI devuelve el URI del paquete del elemento, o null si el elemento no está en un paquete. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propiedad de solo lectura nextSibling de la interfaz [`Node`](../node/) devuelve el nodo que sigue inmediatamente al especificado en los [`childNodes`](../node/childnodes/) de su padre, o devuelve null si el nodo especificado es el último hijo del elemento padre. |
| [getNodeName](../../com.aspose.html.dom/cdatasection/nodename/) El nombre de este nodo, según su tipo. |
| [getNodeType](../../com.aspose.html.dom/cdatasection/nodetype/) Un código que representa el tipo del objeto subyacente. |
| [nodeValue](../../com.aspose.html.dom/text/nodevalue/) { get; set; } | El valor de este nodo, según su tipo. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propiedad de solo lectura ownerDocument de la interfaz Node devuelve el objeto de documento de nivel superior del nodo. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propiedad de solo lectura parentElement de la interfaz [`Node`](../node/) devuelve el [`Element`](../element/) padre del nodo DOM, o null si el nodo no tiene padre o su padre no es un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propiedad de solo lectura parentNode de la interfaz Node devuelve el padre del nodo especificado en el árbol DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La propiedad de solo lectura prefix devuelve el prefijo del paquete del elemento especificado, o null si no se especifica ningún prefijo. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propiedad de solo lectura previousSibling de la interfaz [`Node`](../node/) devuelve el nodo que precede inmediatamente al especificado en la lista de [`childNodes`](../node/firstchild/) de su padre, o null si el nodo especificado es el primero de esa lista. |
| [textContent](../../com.aspose.html.dom/text/textcontent/) { get; set; } | Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como null, establecerlo no tiene efecto. Al establecerlo, cualquier hijo posible que pueda tener este nodo se elimina y, si la nueva cadena no está vacía ni es null, se reemplaza por un único nodo Text que contiene la cadena a la que se establece este atributo. |
| [getWholeText](../../com.aspose.html.dom/text/wholetext/) Devuelve todo el texto de los nodos Text lógicamente adyacentes a este nodo, concatenado en orden de documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | El método addEventListener() de la interfaz [`EventTarget `](../eventtarget/) configura una función que será llamada siempre que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | El método addEventListener() de la [EventTarget ](T:com.aspose.html.dom.EventTarget)interfaz configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | El método addEventListener() de la [EventTarget ](T:com.aspose.html.dom.EventTarget)interfaz configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | El método appendChild() de la interfaz Node agrega un nodo al final de la lista de hijos de un nodo padre especificado. Si el hijo dado es una referencia a un nodo existente en el documento, appendChild() lo mueve de su posición actual a la nueva posición (no es necesario eliminar el nodo de su nodo padre antes de añadirlo a otro nodo). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Añade la cadena al final de los datos de carácter del nodo. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Elimina un rango de unidades de 16 bits del nodo. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Envía un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) especificado, (de forma síncrona) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase de burbujeo opcional) también se aplican a los eventos enviados manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | El método hasChildNodes() de la interfaz Node devuelve un valor booleano que indica si el [`Node`](../node/) dado tiene nodos hijos o no. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | El método insertBefore() de la interfaz Node inserta un nodo antes de un nodo de referencia como hijo de un nodo padre especificado. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Inserta una cadena en el desplazamiento de unidad de 16 bits especificado. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | El método isDefaultNamespace() de la interfaz Node acepta una URI de paquete como argumento. Devuelve un valor booleano que es true si el paquete es el paquete predeterminado en el nodo dado y false en caso contrario. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | El método isEqualNode() de la interfaz [`Node`](../node/) prueba si dos nodos son iguales. Dos nodos son iguales cuando tienen el mismo tipo, características definitorias (para elementos, esto sería su ID, número de hijos, etc.), sus atributos coinciden, y así sucesivamente. El conjunto específico de datos que deben coincidir varía según los tipos de los nodos. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | El método isSameNode() de la interfaz Node es un alias heredado para el operador de igualdad estricta ===. Es decir, prueba si dos nodos son el mismo (en otras palabras, si hacen referencia al mismo objeto). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | El método lookupNamespaceURI() de la interfaz Node toma un prefijo como parámetro y devuelve la URI del paquete asociada a él en el nodo dado si se encuentra (y null si no). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | El método lookupPrefix() de la interfaz Node devuelve una cadena que contiene el prefijo para una URI de paquete dada, si está presente, y null si no lo está. Cuando son posibles varios prefijos, se devuelve el primer prefijo. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Pone todos los nodos [`Text`](../text/) en toda la profundidad del subárbol bajo este Nodo, incluidos los nodos de atributo, en una forma "normal" donde solo la estructura (p. ej., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), `secciones CDATA`, y [`entity references`](../entityreference/)) separa los nodos [`Text`](../text/), es decir, no hay nodos Text adyacentes ni nodos Text vacíos. Esto puede usarse para asegurar que la vista DOM de un documento sea la misma que si se hubiera guardado y recargado, y es útil cuando se utilizan operaciones (como búsquedas XPointer [XPointer]) que dependen de una estructura de árbol de documento particular. Si el parámetro "normalize-characters" del objeto [`DOMConfiguration`](../../com.aspose.html/configuration/) adjunto al [`Node.ownerDocument`](../node/ownerdocument/) es verdadero, este método también normalizará completamente los caracteres de los nodos Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | El método removeChild() de la interfaz Node elimina un nodo hijo del DOM y devuelve el nodo eliminado. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Reemplaza el nodo hijo oldChild con newChild en la lista de hijos, y devuelve el nodo oldChild. Si newChild es un objeto [`DocumentFragment`](../documentfragment/), oldChild es reemplazado por todos los hijos del [`DocumentFragment`](../documentfragment/), que se insertan en el mismo orden. Si newChild ya está en el árbol, se elimina primero. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Reemplaza los caracteres que comienzan en el desplazamiento de unidad de 16 bits especificado con la cadena especificada. |
| [replaceWholeText](../../com.aspose.html.dom/text/replacewholetext/)(String) | Reemplaza el texto del nodo actual y de todos los nodos de texto lógicamente adyacentes con el texto especificado. Todos los nodos de texto lógicamente adyacentes se eliminan, incluido el nodo actual, a menos que haya sido el destinatario del texto de reemplazo. |
| [splitText](../../com.aspose.html.dom/text/splittext/)(int) | Divide este nodo en dos nodos en la posición especificada, manteniendo ambos en el árbol como hermanos. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Extrae un rango de datos del nodo. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Devuelve una cadena que representa esta instancia. |

### Ver también

* class [Text](../text/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

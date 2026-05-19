---
title: "HTMLBRElement Clase"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.HTMLBRElement clase. Fuerza un salto de línea. Consulte la definición del elemento BR en HTML 4.01"
type: docs
url: /es/java/com.aspose.html/htmlbrelement/
---
## HTMLBRElement class

Forzar un salto de línea. Consulte la definición del elemento BR en HTML 4.01.

Véase también la [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLBRElement : HTMLElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) Un NamedNodeMap que contiene los atributos de este nodo (si es un Element) o null en caso contrario. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La propiedad de solo lectura baseURI de la interfaz Node devuelve la URL base absoluta del documento que contiene el nodo. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Devuelve el número actual de nodos de elemento que son hijos de este elemento. 0 si este elemento no tiene nodos hijos de tipo nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propiedad de solo lectura childNodes de la interfaz Node devuelve una [`NodeList`](../../com.aspose.html.collections/nodelist/) en vivo de los nodos hijos del elemento dado donde el primer nodo hijo tiene el índice 0. Los nodos hijos incluyen elementos, texto y comentarios. |
| [getChildren](../../com.aspose.html.dom/element/children/) Devuelve los elementos hijos del elemento actual. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Devuelve un DOMTokenList en vivo que contiene los tokens obtenidos al analizar el atributo \"class\". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getClear]
[setClear] Control flow of text around floats. See the clear attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propiedad de solo lectura firstChild de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el primer hijo del nodo en el árbol, o null si el nodo no tiene hijos. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Devuelve el primer nodo elemento hijo de este elemento. null si este elemento no tiene elementos hijos. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propiedad de solo lectura lastChild de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el último hijo del nodo. Si su padre es un elemento, entonces el hijo suele ser un nodo elemento, un nodo de texto o un nodo de comentario. Devuelve null si no hay elementos hijos |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Devuelve el nodo de elemento hijo último de este elemento. null si este elemento no tiene elementos hijos. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Devuelve la parte local del nombre calificado de este nodo. Para nodos de cualquier tipo que no sea ELEMENT_NODE ni ATTRIBUTE_NODE y nodos creados con un método DOM Level 1, como Document.createElement(), esto siempre es null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) El URI del paquete de este nodo, o null si no está especificado. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Devuelve el nodo de elemento hermano siguiente de este elemento. null si este elemento no tiene nodos hermanos de elemento que aparezcan después de este en el árbol del documento. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propiedad de solo lectura nextSibling de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el nodo que sigue inmediatamente al especificado en los [`childNodes`](../../com.aspose.html.dom/node/childnodes/) de su padre, o devuelve null si el nodo especificado es el último hijo en el elemento padre. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) El nombre de este nodo, según su tipo. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Un código que representa el tipo del objeto subyacente. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La propiedad nodeValue de la interfaz [`Node `](../../com.aspose.html.dom/node/) devuelve o establece el valor del nodo actual. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propiedad de solo lectura ownerDocument de la interfaz Node devuelve el objeto de documento de nivel superior del nodo. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propiedad de solo lectura parentElement de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el [`Element`](../../com.aspose.html.dom/element/) padre del nodo DOM, o null si el nodo no tiene padre o su padre no es un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propiedad de solo lectura parentNode de la interfaz Node devuelve el padre del nodo especificado en el árbol DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) El prefijo del paquete de este nodo, o null si no está especificado. Cuando se define como null, establecerlo no tiene efecto |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Devuelve el nodo de elemento hermano anterior de este elemento. null si este elemento no tiene nodos hermanos de elemento que precedan a este en el árbol del documento. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propiedad de solo lectura previousSibling de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el nodo que precede inmediatamente al especificado en la lista de [`childNodes`](../../com.aspose.html.dom/node/firstchild/) de su padre, o null si el nodo especificado es el primero en esa lista. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Devuelve shadowRoot almacenado en este elemento o null si está cerrado. |
| [getStyle](../../com.aspose.html/htmlelement/style/) Representa un atributo de estilo que permite al autor aplicar directamente información de estilo a un elemento específico. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) El nombre del elemento. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como null, establecerlo no tiene efecto. Al establecerlo, cualquier hijo posible que pueda tener este nodo se elimina y, si la nueva cadena no está vacía ni es null, se reemplaza por un único nodo Text que contiene la cadena a la que se establece este atributo. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | El método addEventListener() de la interfaz [`EventTarget `](../../com.aspose.html.dom/eventtarget/) configura una función que será llamada siempre que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | El método addEventListener() de la [EventTarget ](T:com.aspose.html.dom.EventTarget)interfaz configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | El método addEventListener() de la [EventTarget ](T:com.aspose.html.dom.EventTarget)interfaz configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | El método appendChild() de la interfaz Node agrega un nodo al final de la lista de hijos de un nodo padre especificado. Si el hijo dado es una referencia a un nodo existente en el documento, appendChild() lo mueve de su posición actual a la nueva posición (no es necesario eliminar el nodo de su nodo padre antes de añadirlo a otro nodo). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Crea una raíz sombra y la adjunta al elemento actual. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Envía un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) especificado, (de forma síncrona) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase de burbujeo opcional) también se aplican a los eventos enviados manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Recupera el valor de un atributo por nombre. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Devuelve los nombres de los atributos del elemento como una matriz de cadenas. Si el elemento no tiene atributos, devuelve una matriz vacía. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Recupera un nodo de atributo por nombre. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Recupera un nodo Attr por nombre local y URI del paquete. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Recupera el valor de un atributo por nombre local y URI del paquete. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Devuelve un objeto [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) que contiene todos los elementos dentro de [`element`](../../com.aspose.html.dom/element/) que tienen todas las clases especificadas en el argumento. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Devuelve un objeto [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) que contiene todos los [`elements`](../../com.aspose.html.dom/element/) con un nombre de etiqueta dado, en orden del documento. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Devuelve un objeto [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) que contiene todos los [`elements`](../../com.aspose.html.dom/element/) con un nombre local y una cadena URI del paquete dados, en orden del documento. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Devuelve true cuando un atributo con un nombre dado está especificado en este elemento o tiene un valor predeterminado, false en caso contrario. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Devuelve true cuando un atributo con un nombre local y URI del paquete dados está especificado en este elemento o tiene un valor predeterminado, false en caso contrario. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Devuelve si este nodo (si es un elemento) tiene algún atributo |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | El método hasChildNodes() de la interfaz Node devuelve un valor booleano que indica si el [`Node`](../../com.aspose.html.dom/node/) dado tiene nodos hijos o no. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | El método insertBefore() de la interfaz Node inserta un nodo antes de un nodo de referencia como hijo de un nodo padre especificado. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | El método isDefaultNamespace() de la interfaz Node acepta una URI de paquete como argumento. Devuelve un valor booleano que es true si el paquete es el paquete predeterminado en el nodo dado y false en caso contrario. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | El método isEqualNode() de la interfaz [`Node`](../../com.aspose.html.dom/node/) prueba si dos nodos son iguales. Dos nodos son iguales cuando tienen el mismo tipo, características definitorias (para los elementos, esto sería su ID, número de hijos, etc.), sus atributos coinciden, y así sucesivamente. El conjunto específico de datos que deben coincidir varía según los tipos de los nodos. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | El método isSameNode() de la interfaz Node es un alias heredado para el operador de igualdad estricta ===. Es decir, prueba si dos nodos son el mismo (en otras palabras, si hacen referencia al mismo objeto). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | El método lookupNamespaceURI() de la interfaz Node toma un prefijo como parámetro y devuelve la URI del paquete asociada a él en el nodo dado si se encuentra (y null si no). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | El método lookupPrefix() de la interfaz Node devuelve una cadena que contiene el prefijo para una URI de paquete dada, si está presente, y null si no lo está. Cuando son posibles varios prefijos, se devuelve el primer prefijo. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Pone todos los nodos [`Text`](../../com.aspose.html.dom/text/) en toda la profundidad del subárbol bajo este Nodo, incluidos los nodos de atributos, en una forma "normal" donde solo la estructura (p. ej., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), y [`entity references`](../../com.aspose.html.dom/entityreference/)) separa los nodos [`Text`](../../com.aspose.html.dom/text/), es decir, no hay nodos Text adyacentes ni nodos Text vacíos. Esto puede usarse para asegurar que la vista DOM de un documento sea la misma que si se guardara y recargara, y es útil cuando se realizan operaciones (como búsquedas de XPointer [XPointer]) que dependen de una estructura particular del árbol del documento. Si el parámetro "normalize-characters" del objeto [`DOMConfiguration`](../configuration/) adjunto al [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) es verdadero, este método también normalizará completamente los caracteres de los nodos Text. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Devuelve el primer Element en el documento que coincide con el selector |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Devuelve una NodeList de todos los Elements en el documento que coinciden con el selector |
| [remove](../../com.aspose.html.dom/element/remove/)() | Elimina esta instancia. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Elimina un atributo por nombre. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Elimina el nodo de atributo especificado. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Elimina un atributo por nombre local y URI del paquete. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | El método removeChild() de la interfaz Node elimina un nodo hijo del DOM y devuelve el nodo eliminado. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Reemplaza el nodo hijo oldChild con newChild en la lista de hijos y devuelve el nodo oldChild. Si newChild es un objeto [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild es reemplazado por todos los hijos del [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) que se insertan en el mismo orden. Si newChild ya está en el árbol, se elimina primero. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Añade un nuevo atributo. Si ya existe un atributo con ese nombre en el elemento, su valor se cambia al del parámetro value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Añade un nuevo nodo de atributo. Si ya existe un atributo con ese nombre (nodeName) en el elemento, se reemplaza por el nuevo. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Añade un nuevo atributo. Si ya existe un atributo con ese nombre local y esa URI de paquete en el elemento, se reemplaza por el nuevo. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Añade un nuevo atributo. Si ya existe un atributo con el mismo nombre local y URI de paquete en el elemento, su prefijo se cambia a la parte de prefijo de qualifiedName, y su valor se cambia al parámetro value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Si no se proporciona force, \"alternar\" qualifiedName, eliminándolo si está presente y añadiéndolo si no lo está. Si force es true, se añade qualifiedName. Si force es false, se elimina qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Si no se proporciona force, \"alternar\" qualifiedName, eliminándolo si está presente y añadiéndolo si no lo está. Si force es true, se añade qualifiedName. Si force es false, se elimina qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Devuelve una cadena que representa esta instancia. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | Obtiene o establece el controlador de eventos para el evento OnAbort. |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | Obtiene o establece el controlador de eventos para el evento OnBlur. |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | Obtiene o establece el controlador de eventos para el evento OnCancel. |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | Obtiene o establece el controlador de eventos para el evento OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | Obtiene o establece el controlador de eventos para el evento OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | Obtiene o establece el controlador de eventos para el evento OnChange. |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | Obtiene o establece el controlador de eventos para el evento OnClick. |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | Obtiene o establece el controlador de eventos para el evento OnCueChange. |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | Obtiene o establece el controlador de eventos para el evento OnDblClick. |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | Obtiene o establece el controlador de eventos para el evento OnDurationChange. |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | Obtiene o establece el controlador de eventos para el evento OnEmptied. |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | Obtiene o establece el controlador de eventos para el evento OnEnded. |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | Obtiene o establece el controlador de eventos para el evento OnError. |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | Obtiene o establece el controlador de eventos para el evento OnFocus. |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | Obtiene o establece el controlador de eventos para el evento OnInput. |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | Obtiene o establece el controlador de eventos para el evento OnInvalid. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | Obtiene o establece el controlador de eventos para el evento OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | Obtiene o establece el controlador de eventos para el evento OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | Obtiene o establece el controlador de eventos para el evento OnKeyUp. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | Obtiene o establece el controlador de eventos para el evento OnLoad. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | Obtiene o establece el controlador de eventos para el evento OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | Obtiene o establece el controlador de eventos para el evento OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | Obtiene o establece el controlador de eventos para el evento OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | Obtiene o establece el controlador de eventos para el evento OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | Obtiene o establece el controlador de eventos para el evento OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | Obtiene o establece el controlador de eventos para el evento OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | Obtiene o establece el controlador de eventos para el evento OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | Obtiene o establece el controlador de eventos para el evento OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | Obtiene o establece el controlador de eventos para el evento OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | Obtiene o establece el controlador de eventos para el evento OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | Obtiene o establece el controlador de eventos para el evento OnMouseWheel. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | Obtiene o establece el controlador de eventos para el evento OnPause. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | Obtiene o establece el controlador de eventos para el evento OnPlay. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | Obtiene o establece el controlador de eventos para el evento OnPlaying. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | Obtiene o establece el controlador de eventos para el evento OnProgress. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | Obtiene o establece el controlador de eventos para el evento OnRateChange. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | Obtiene o establece el controlador de eventos para el evento OnReset. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | Obtiene o establece el controlador de eventos para el evento OnResize. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | Obtiene o establece el controlador de eventos para el evento OnScroll. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | Obtiene o establece el controlador de eventos para el evento OnSeeked. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | Obtiene o establece el controlador de eventos para el evento OnSeeking. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | Obtiene o establece el controlador de eventos para el evento OnSelect. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | Obtiene o establece el controlador de eventos para el evento OnShow. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | Obtiene o establece el controlador de eventos para el evento OnStalled. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | Obtiene o establece el controlador de eventos para el evento OnSubmit. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | Obtiene o establece el controlador de eventos para el evento OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | Obtiene o establece el controlador de eventos para el evento OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | Obtiene o establece el controlador de eventos para el evento OnToggle. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | Obtiene o establece el controlador de eventos para el evento OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | Obtiene o establece el controlador de eventos para el evento OnWaiting. |

### Ver también

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

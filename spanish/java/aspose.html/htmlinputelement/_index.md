---
title: "Clase HTMLInputElement"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.HTMLInputElement. Control de formulario. Dependiendo del entorno en el que se visualice la página, la propiedad value puede ser de solo lectura para el tipo de entrada de carga de archivos. Para el tipo de entrada de contraseña, el valor real devuelto puede estar enmascarado para evitar uso no autorizado. Consulte la definición del elemento INPUT en HTML 4.01. Consulte también la especificación Document Object Model DOM Level 2 HTML."
type: docs

url: /es/java/com.aspose.html/htmlinputelement/
---
## HTMLInputElement class

Control de formulario. Dependiendo del entorno en el que se visualice la página, la propiedad value puede ser de solo lectura para el tipo de entrada de carga de archivo. Para el tipo de entrada "password", el valor real devuelto puede estar enmascarado para evitar usos no autorizados. Consulte la definición del elemento INPUT en [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)]. Consulte también la [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLInputElement : HTMLElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getAccept]
[setAccept] A comma-separated list of content types that a server processing this form will handle correctly. See the accept attribute definition in HTML 4.01. |
[getAccessKey]
[setAccessKey] A single character access key to give access to the form control. See the accesskey attribute definition in HTML 4.01. |
[getAlign]
[setAlign] Aligns this object (vertically or horizontally) with respect to its surrounding text. See the align attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
[getAlt]
[setAlt] Alternate text for user agents not rendering the normal content of this element. See the alt attribute definition in HTML 4.01. |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) Un NamedNodeMap que contiene los atributos de este nodo (si es un Element) o null en caso contrario. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La propiedad de solo lectura baseURI de la interfaz Node devuelve la URL base absoluta del documento que contiene el nodo. |
[getChecked]
[setChecked] When the `type` attribute of the element has the value "radio" or "checkbox", this represents the current state of the form control, in an interactive user agent. Changes to this attribute change the state of the form control, but do not change the value of the HTML checked attribute of the INPUT element.During the handling of a click event on an input element with a type attribute that has the value "radio" or "checkbox", some implementations may change the value of this property before the event is being dispatched in the document. If the default action of the event is canceled, the value of the property may be changed back to its original value. This means that the value of this property during the handling of click events is implementation dependent. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Devuelve el número actual de nodos de elemento que son hijos de este elemento. 0 si este elemento no tiene nodos hijos de tipo nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propiedad de solo lectura childNodes de la interfaz Node devuelve una [`NodeList`](../../com.aspose.html.collections/nodelist/) en vivo de los nodos hijos del elemento dado donde el primer nodo hijo tiene el índice 0. Los nodos hijos incluyen elementos, texto y comentarios. |
| [getChildren](../../com.aspose.html.dom/element/children/) Devuelve los elementos hijos del elemento actual. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Devuelve una DOMTokenList en vivo que contiene los tokens obtenidos al analizar el atributo "class". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getDefaultChecked]
[setDefaultChecked] When `type` has the value "radio" or "checkbox", this represents the HTML checked attribute of the element. The value of this attribute does not change if the state of the corresponding form control, in an interactive user agent, changes. See the checked attribute definition in HTML 4.01. |
[getDefaultValue]
[setDefaultValue] When the `type` attribute of the element has the value "text", "file" or "password", this represents the HTML value attribute of the element. The value of this attribute does not change if the contents of the corresponding form control, in an interactive user agent, changes. See the value attribute definition in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
[getDisabled]
[setDisabled] The control is unavailable in this context. See the disabled attribute definition in HTML 4.01. |
| [getFiles](../../com.aspose.html/htmlinputelement/files/) El atributo IDL files permite a los scripts acceder a los archivos seleccionados del elemento. Al obtenerlo, si el atributo IDL se aplica, debe devolver un objeto FileList que representa los archivos seleccionados actualmente. El mismo objeto debe devolverse hasta que la lista de archivos seleccionados cambie. Si el atributo IDL no se aplica, entonces debe devolver null. [FILEAPI] |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propiedad de solo lectura firstChild de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el primer hijo del nodo en el árbol, o null si el nodo no tiene hijos. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Devuelve el primer nodo elemento hijo de este elemento. null si este elemento no tiene elementos hijos. |
[getForm]
[setForm] Returns the `FORM` element containing this control. Returns `null` if this control is not within the context of a form. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propiedad de solo lectura lastChild de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el último hijo del nodo. Si su padre es un elemento, entonces el hijo suele ser un nodo de elemento, un nodo de texto o un nodo de comentario. Devuelve null si no hay elementos hijos |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Devuelve el nodo de elemento hijo último de este elemento. null si este elemento no tiene elementos hijos. |
[getList]
[setList] The list attribute is used to identify an element that lists predefined options suggested to the user. If present, its value must be the ID of a datalist element in the same document. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Devuelve la parte local del nombre calificado de este nodo. Para nodos de cualquier tipo que no sea ELEMENT_NODE y ATTRIBUTE_NODE y nodos creados con un método de DOM Level 1, como Document.createElement(), siempre es null. |
[getMaxLength]
[setMaxLength] Maximum number of characters for text fields, when `type`has the value "text" or "password". See the maxlength attribute definition in HTML 4.01. |
[getName]
[setName] Form control or object name when submitted with a form. See the name attribute definition in HTML 4.01. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) El URI del paquete de este nodo, o null si no está especificado. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Devuelve el nodo de elemento hermano siguiente de este elemento. null si este elemento no tiene nodos hermanos de elemento que lo sigan en el árbol del documento. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propiedad de solo lectura nextSibling de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el nodo que sigue inmediatamente al especificado en los [`childNodes`](../../com.aspose.html.dom/node/childnodes/) de su padre, o devuelve null si el nodo especificado es el último hijo del elemento padre. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) El nombre de este nodo, según su tipo. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Un código que representa el tipo del objeto subyacente. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue property of the [`Node `](../../com.aspose.html.dom/node/)interface returns or sets the value of the current node. La propiedad nodeValue de la interfaz [`Node `](../../com.aspose.html.dom/node/) devuelve o establece el valor del nodo actual. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propiedad de solo lectura ownerDocument de la interfaz Node devuelve el objeto de documento de nivel superior del nodo. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propiedad de solo lectura parentElement de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el [`Element`](../../com.aspose.html.dom/element/) padre del nodo DOM, o null si el nodo no tiene padre o su padre no es un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propiedad de solo lectura parentNode de la interfaz Node devuelve el padre del nodo especificado en el árbol DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) El prefijo del paquete de este nodo, o null si no está especificado. Cuando se define como null, establecerlo no tiene efecto. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Devuelve el nodo de elemento hermano anterior de este elemento. null si este elemento no tiene nodos hermanos de elemento que lo precedan en el árbol del documento. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propiedad de solo lectura previousSibling de la interfaz [`Node`](../../com.aspose.html.dom/node/) devuelve el nodo que precede inmediatamente al especificado en la lista de [`childNodes`](../../com.aspose.html.dom/node/firstchild/) de su padre, o null si el nodo especificado es el primero de esa lista. |
[getReadOnly]
[setReadOnly] This control is read-only. Relevant only when `type` has the value "text" or "password". See the readonly attribute definition in HTML 4.01. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Devuelve shadowRoot almacenado en este elemento o null si está cerrado. |
[getSize]
[setSize] Size information. The precise meaning is specific to each type of field. See the size attribute definition in HTML 4.01. @version DOM Level 2 |
[getSrc]
[setSrc] When the `type` attribute has the value "image", this attribute specifies the location of the image to be used to decorate the graphical submit button. See the src attribute definition in HTML 4.01. |
| [getStyle](../../com.aspose.html/htmlelement/style/) Representa un atributo de estilo que permite al autor aplicar directamente información de estilo a un elemento específico. |
[getTabIndex]
[setTabIndex] Index that represents the element's position in the tabbing order. See the tabindex attribute definition in HTML 4.01. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) El nombre del elemento. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como null, establecerlo no tiene efecto. Al establecerlo, cualquier hijo posible que tenga este nodo se elimina y, si la nueva cadena no está vacía ni es null, se reemplaza por un único nodo Text que contiene la cadena a la que se asigna este atributo. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |
[getType]
[setType] The type of control created (all lower case). See the type attribute definition in HTML 4.01. @version DOM Level 2 |
[getUseMap]
[setUseMap] Use client-side image map. See the usemap attribute definition in HTML 4.01. |
[getValue]
[setValue] When the `type` attribute of the element has the value "text", "file" or "password", this represents the current contents of the corresponding form control, in an interactive user agent. Changing this attribute changes the contents of the form control, but does not change the value of the HTML value attribute of the element. When the `type` attribute of the element has the value "button", "hidden", "submit", "reset", "image", "checkbox" or "radio", this represents the HTML value attribute of the element. See the value attribute definition in HTML 4.01. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. El método addEventListener() de la interfaz [`EventTarget `](../../com.aspose.html.dom/eventtarget/) configura una función que será llamada siempre que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | El método appendChild() de la interfaz Node agrega un nodo al final de la lista de hijos de un nodo padre especificado. Si el hijo dado es una referencia a un nodo existente en el documento, appendChild() lo mueve de su posición actual a la nueva posición (no es necesario eliminar el nodo de su nodo padre antes de añadirlo a otro nodo). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Crea una raíz sombra y la adjunta al elemento actual. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Envía un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) especificado, (de forma sincrónica) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase opcional de burbujeo) también se aplican a los eventos enviados manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el desbloqueo o el restablecimiento de recursos no administrados. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Obtiene el valor de un atributo por nombre. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Devuelve los nombres de los atributos del elemento como una matriz de cadenas. Si el elemento no tiene atributos, devuelve una matriz vacía. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Obtiene un nodo de atributo por nombre. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Obtiene un nodo Attr por nombre local y URI del paquete. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Obtiene el valor de un atributo por nombre local y URI del paquete. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Devuelve un objeto [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) que contiene todos los elementos dentro de [`element`](../../com.aspose.html.dom/element/) que tienen todas las clases especificadas en el argumento. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Devuelve un objeto [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) que contiene todos los [`elements`](../../com.aspose.html.dom/element/) con un nombre de etiqueta dado, en orden del documento. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Devuelve un objeto [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) que contiene todos los [`elements`](../../com.aspose.html.dom/element/) con un nombre local y una cadena de URI del paquete dados, en orden del documento. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Devuelve true cuando un atributo con un nombre dado está especificado en este elemento o tiene un valor predeterminado, false en caso contrario. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Devuelve true cuando un atributo con un nombre local y URI del paquete dados está especificado en este elemento o tiene un valor predeterminado, false en caso contrario. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Devuelve si este nodo (si es un elemento) tiene algún atributo |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | El método hasChildNodes() de la interfaz Node devuelve un valor booleano que indica si el [`Node`](../../com.aspose.html.dom/node/) dado tiene nodos hijos o no. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | El método insertBefore() de la interfaz Node inserta un nodo antes de un nodo de referencia como hijo de un nodo padre especificado. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | El método isDefaultNamespace() de la interfaz Node acepta una URI de paquete como argumento. Devuelve un valor booleano que es true si el paquete es el paquete predeterminado en el nodo dado y false en caso contrario. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | El método isEqualNode() de la interfaz [`Node`](../../com.aspose.html.dom/node/) verifica si dos nodos son iguales. Dos nodos son iguales cuando tienen el mismo tipo, características definitorias (para los elementos, esto sería su ID, número de hijos, etc.), sus atributos coinciden, y así sucesivamente. El conjunto específico de datos que deben coincidir varía según los tipos de los nodos. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | El método isSameNode() de la interfaz Node es un alias heredado para el operador de igualdad estricta ===. Es decir, verifica si dos nodos son el mismo (en otras palabras, si hacen referencia al mismo objeto). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | El método lookupNamespaceURI() de la interfaz Node toma un prefijo como parámetro y devuelve la URI del paquete asociada a él en el nodo dado si se encuentra (y null si no). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | El método lookupPrefix() de la interfaz Node devuelve una cadena que contiene el prefijo para una URI de paquete dada, si está presente, y null si no lo está. Cuando hay varios prefijos posibles, se devuelve el primer prefijo. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Pone todos los nodos [`Text`](../../com.aspose.html.dom/text/) en toda la profundidad del sub‑árbol bajo este Nodo, incluidos los nodos de atributos, en una forma "normal" donde solo la estructura (p. ej., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), y [`entity references`](../../com.aspose.html.dom/entityreference/)) separa los nodos [`Text`](../../com.aspose.html.dom/text/), es decir, no existen nodos Text adyacentes ni nodos Text vacíos. Esto puede usarse para garantizar que la vista DOM de un documento sea la misma que si se hubiera guardado y recargado, y es útil cuando se realizan operaciones (como búsquedas XPointer [XPointer]) que dependen de una estructura de árbol de documento particular. Si el parámetro "normalize-characters" del objeto [`DOMConfiguration`](../configuration/) adjunto al [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) es verdadero, este método también normalizará completamente los caracteres de los nodos Text. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Devuelve el primer Element en el documento que coincide con el selector |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Devuelve una NodeList de todos los Elements en el documento que coinciden con el selector |
| [remove](../../com.aspose.html.dom/element/remove/)() | Elimina esta instancia. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Elimina un atributo por nombre. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Elimina el nodo de atributo especificado. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Elimina un atributo por nombre local y URI del paquete. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | El método removeChild() de la interfaz Node elimina un nodo hijo del DOM y devuelve el nodo eliminado. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Reemplaza el nodo hijo oldChild con newChild en la lista de hijos y devuelve el nodo oldChild. Si newChild es un objeto [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild es reemplazado por todos los hijos del [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) que se insertan en el mismo orden. Si newChild ya está en el árbol, se elimina primero. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Añade un nuevo atributo. Si ya existe un atributo con ese nombre en el elemento, su valor se cambia al del parámetro value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Añade un nuevo nodo de atributo. Si ya existe un atributo con ese nombre (nodeName) en el elemento, se reemplaza por el nuevo. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Añade un nuevo atributo. Si ya existe un atributo con ese nombre local y esa URI de paquete en el elemento, se reemplaza por el nuevo. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Añade un nuevo atributo. Si ya existe un atributo con el mismo nombre local y URI de paquete en el elemento, su prefijo se cambia al prefijo de qualifiedName y su valor se cambia al valor del parámetro value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Si no se proporciona force, "alterna" qualifiedName, eliminándolo si está presente y añadiéndolo si no lo está. Si force es true, añade qualifiedName. Si force es false, elimina qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Si no se proporciona force, "alterna" qualifiedName, eliminándolo si está presente y añadiéndolo si no lo está. Si force es true, añade qualifiedName. Si force es false, elimina qualifiedName. |
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

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.forms;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLFormElement formElement = (HTMLFormElement) document.CreateElement("form");
	// Elemento de etiqueta - Nombre
	// <label for=\"fname\">Nombre:</label><br>
	HTMLLabelElement labelFirstName = (HTMLLabelElement)document.CreateElement("label");
	labelFirstName.For = "fname";
	labelFirstName.InnerHTML = "First name:";
	formElement.AppendChild(labelFirstName);
	formElement.AppendChild(document.CreateElement("br"));

	// Elemento de entrada para Nombre
	// <input type=\"text\" id=\"fname\" name=\"fname\"><br>
	HTMLInputElement inputFirstName = (HTMLInputElement)document.CreateElement("input");
	inputFirstName.Type = InputElementType.Text.ToString(); // "text";
	inputFirstName.Id = "fname";
	inputFirstName.Name = "fname";
	formElement.AppendChild(inputFirstName);
	formElement.AppendChild(document.CreateElement("br"));

	// Elemento de etiqueta - Apellido
	// <label for=\"lname\">Apellido:</label><br>
	HTMLLabelElement labelLastName = (HTMLLabelElement)document.CreateElement("label");
	labelLastName.For = "lname";
	labelLastName.InnerHTML = "Last name:";
	formElement.AppendChild(labelLastName);
	formElement.AppendChild(document.CreateElement("br"));

	// Elemento de entrada para Apellido
	// <input type=\"text\" id=\"lname\" name=\"lname\"><br><br>
	HTMLInputElement inputLastName = (HTMLInputElement)document.CreateElement("input");
	inputLastName.Type = InputElementType.Text.ToString(); // "text";
	inputLastName.Id = "lname";
	inputLastName.Name = "lname";
	formElement.AppendChild(inputLastName);
	formElement.AppendChild(document.CreateElement("br"));
	formElement.AppendChild(document.CreateElement("br"));

	// Elemento de entrada - Enviar
	HTMLInputElement inputSubmit = (HTMLInputElement)document.CreateElement("input");
	inputSubmit.Type = InputElementType.Submit.ToString(); // "submit";
	inputSubmit.Value = "Submit";
	formElement.AppendChild(inputSubmit);
         
	document.Body.AppendChild(formElement);
         
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Ver también

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

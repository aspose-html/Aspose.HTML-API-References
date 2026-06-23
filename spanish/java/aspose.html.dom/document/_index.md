---
title: "Clase Document"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.Document. El Document representa todo el documento HTML, XML o SVG. Conceptualmente es la raíz del árbol del documento y proporciona el acceso principal a los datos del documento."
type: docs

url: /es/java/com.aspose.html.dom/document/
---
## Document class

El Document representa todo el documento HTML, XML o SVG. Conceptualmente, es la raíz del árbol del documento y proporciona el acceso principal a los datos del documento.

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) La URI base absoluta de este nodo o null si la implementación no pudo obtener una URI absoluta. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Obtiene la codificación del documento. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Obtiene la codificación del documento. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Devuelve el número actual de nodos elemento que son hijos de este elemento. 0 si este elemento no tiene nodos hijos de tipo nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propiedad de solo lectura childNodes de la interfaz Node devuelve una [`NodeList`](../../com.aspose.html.collections/nodelist/) en vivo de los nodos hijos del elemento dado donde el primer nodo hijo tiene el índice 0. Los nodos hijos incluyen elementos, texto y comentarios. |
| [getChildren](../../com.aspose.html.dom/document/children/) Devuelve los elementos hijos. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Obtiene el tipo de contenido del documento. |
| [getContext](../../com.aspose.html.dom/document/context/) Obtiene el contexto de navegación actual. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) El atributo IDL defaultView de la interfaz Document, al obtenerse, debe devolver el objeto WindowProxy del contexto de navegación de este Document, si este Document tiene un contexto de navegación asociado, o null en caso contrario. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) La Declaración de Tipo de Documento asociada a este documento. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Este es un atributo de conveniencia que permite el acceso directo al nodo hijo que es el elemento documento del documento. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) La ubicación del documento o null si está indefinida o si el Document fue creado usando DOMImplementation.createDocument. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propiedad de solo lectura firstChild de la interfaz [`Node`](../node/) devuelve el primer hijo del nodo en el árbol, o null si el nodo no tiene hijos. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Devuelve el primer nodo elemento hijo de este elemento. null si este elemento no tiene elementos hijos. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) El objeto DOMImplementation que maneja este documento. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Obtiene la codificación del documento. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propiedad de solo lectura lastChild de la interfaz [`Node`](../node/) devuelve el último hijo del nodo. Si su padre es un elemento, entonces el hijo suele ser un nodo de elemento, un nodo de texto o un nodo de comentario. Devuelve null si no hay elementos hijos. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Devuelve el último nodo elemento hijo de este elemento. null si este elemento no tiene elementos hijos. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Devuelve la parte local del nombre calificado de este nodo. Para nodos de cualquier tipo que no sean [`ELEMENT_NODE`](../node/element_node/) y [`ATTRIBUTE_NODE`](../node/attribute_node/) y nodos creados con un método DOM Level 1, como [`Document.createElement()`](./createelement/), esto siempre es nulo. |
| [getLocation](../../com.aspose.html.dom/document/location/) La ubicación del documento. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La propiedad de solo lectura Element.packageURI devuelve el URI del paquete del elemento, o null si el elemento no está en un paquete. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Devuelve el siguiente nodo elemento hermano de este elemento. null si este elemento no tiene nodos hermanos elemento que vengan después de este en el árbol del documento. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propiedad de solo lectura nextSibling de la interfaz [`Node`](../node/) devuelve el nodo que sigue inmediatamente al especificado en los [`childNodes`](../node/childnodes/) de su padre, o devuelve null si el nodo especificado es el último hijo del elemento padre. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) El nombre de este nodo, según su tipo. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Un código que representa el tipo del objeto subyacente. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La propiedad nodeValue de la [`Node `](../node/)interfaz devuelve o establece el valor del nodo actual. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Obtiene el origen del documento. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Obtiene el documento propietario. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propiedad de solo lectura parentElement de la interfaz [`Node`](../node/) devuelve el [`Element`](../element/) padre del nodo DOM, o null si el nodo no tiene padre o su padre no es un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propiedad de solo lectura parentNode de la interfaz Node devuelve el padre del nodo especificado en el árbol DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La propiedad de solo lectura prefix devuelve el prefijo del paquete del elemento especificado, o null si no se especifica ningún prefijo. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Devuelve el nodo elemento hermano anterior de este elemento. null si este elemento no tiene nodos hermanos elemento que precedan a este en el árbol del documento. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propiedad de solo lectura previousSibling de la interfaz [`Node`](../node/) devuelve el nodo que precede inmediatamente al especificado en la lista de [`childNodes`](../node/firstchild/) de su padre, o null si el nodo especificado es el primero de esa lista. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Devuelve el estado de preparación del documento. "loading" mientras el Document se está cargando, "interactive" una vez que ha terminado de analizarse pero aún carga subrecursos, y "complete" una vez que se ha cargado. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Una lista que contiene todas las hojas de estilo vinculadas explícitamente o incrustadas en un documento. Para documentos HTML, esto incluye hojas de estilo externas, incluidas mediante el elemento HTML LINK, y elementos STYLE en línea. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | La propiedad textContent de la [`Node`](../node/) interfaz representa el contenido de texto del nodo y sus descendientes. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | El método addEventListener() de la interfaz [`EventTarget `](../eventtarget/) configura una función que será llamada siempre que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | El método appendChild() de la interfaz Node agrega un nodo al final de la lista de hijos de un nodo padre especificado. Si el hijo dado es una referencia a un nodo existente en el documento, appendChild() lo mueve de su posición actual a la nueva posición (no es necesario eliminar el nodo de su nodo padre antes de añadirlo a otro nodo). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | El método Document.createAttribute() crea un nuevo nodo de atributo y lo devuelve. El objeto crea un nodo que implementa la interfaz [`Attr`](../attr/). El DOM no impone qué tipo de atributos pueden añadirse a un elemento particular de esta manera. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | El método Document.createAttribute() crea un nuevo nodo de atributo y lo devuelve. El objeto creado es un nodo que implementa la interfaz [Attr](T:com.aspose.html.dom.Attr). El DOM no impone qué tipo de atributos pueden añadirse a un elemento concreto de esta manera. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Crea un nodo [`CDATASection`](../cdatasection/) cuyo valor es la cadena especificada. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Crea un nodo [`Comment`](../comment/) a partir de la cadena especificada. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Crea un nuevo [`DocumentFragment`](../documentfragment/) vacío en el que se pueden añadir nodos DOM para construir un árbol DOM fuera de pantalla. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | El método devuelve un objeto [`DocumentType`](../documenttype/) que puede usarse con DOMImplementation.createDocument al crear el documento o puede insertarse en el documento mediante métodos como Node.insertBefore() o Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | En un documento HTML, el método document.createElement() crea el elemento HTML especificado por tagName, o un [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) si tagName no se reconoce. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Crea un elemento con el nombre calificado y la URI del paquete proporcionados. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Crea un objeto EntityReference. Además, si la entidad referenciada es conocida, la lista de hijos del nodo EntityReference se hace idéntica a la del nodo Entity correspondiente. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Crea un [`Event`](../../com.aspose.html.dom.events/event/) de un tipo admitido por la implementación. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Crea una expresión XPath analizada con paquetes resueltos. Esto es útil cuando una expresión se reutilizará en una aplicación, ya que permite compilar la cadena de expresión en una forma interna más eficiente y preresolver todos los prefijos de paquete que aparecen en la expresión. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Adapta cualquier nodo DOM para resolver paquetes de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método de DOM Level 3 `lookupNamespaceURI` en los nodos para resolver el packageURI a partir de un prefijo dado, utilizando la información disponible en la jerarquía del nodo en el momento de la llamada a lookupNamespaceURI, y también resuelve correctamente el prefijo implícito xml. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Crea un nodo ProcessingInstruction a partir de los strings de nombre y datos especificados. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Crea un nodo Text a partir de la cadena especificada. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Envía un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) especificado, (de forma sincrónica) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase opcional de burbujeo) también se aplican a los eventos enviados manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el desbloqueo o el restablecimiento de recursos no administrados. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | El método getElementById() de Document devuelve un objeto [`Element`](../element/) que representa el elemento cuya propiedad id coincide con la cadena especificada. Dado que los IDs de los elementos deben ser únicos si se especifican, son una forma útil de acceder rápidamente a un elemento específico. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | El método getElementsByClassName de la interfaz `Document` devuelve un objeto similar a un array con todos los elementos hijos que poseen todos los nombres de clase proporcionados. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | El método getElementsByTagName de la interfaz `Document` devuelve una [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) de elementos con el nombre de etiqueta especificado. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Devuelve una lista de elementos con el nombre de etiqueta dado que pertenecen al paquete especificado. Se busca en todo el documento, incluido el nodo raíz. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | El método hasChildNodes() de la interfaz Node devuelve un valor booleano que indica si el [`Node`](../node/) dado tiene nodos hijos o no. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Importa un nodo de otro documento a este documento, sin alterar ni eliminar el nodo fuente del documento original; este método crea una nueva copia del nodo fuente. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | El método insertBefore() de la interfaz Node inserta un nodo antes de un nodo de referencia como hijo de un nodo padre especificado. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | El método isDefaultNamespace() de la interfaz Node acepta una URI de paquete como argumento. Devuelve un valor booleano que es true si el paquete es el paquete predeterminado en el nodo dado y false en caso contrario. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | El método isEqualNode() de la interfaz [`Node`](../node/) verifica si dos nodos son iguales. Dos nodos son iguales cuando tienen el mismo tipo, características definitorias (para elementos, esto sería su ID, número de hijos, etc.), sus atributos coinciden, y así sucesivamente. El conjunto específico de datos que deben coincidir varía según los tipos de los nodos. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | El método isSameNode() de la interfaz Node es un alias heredado para el operador de igualdad estricta ===. Es decir, verifica si dos nodos son el mismo (en otras palabras, si hacen referencia al mismo objeto). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | El método lookupNamespaceURI() de la interfaz Node toma un prefijo como parámetro y devuelve la URI del paquete asociada a él en el nodo dado si se encuentra (y null si no). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | El método lookupPrefix() de la interfaz Node devuelve una cadena que contiene el prefijo para una URI de paquete dada, si está presente, y null si no lo está. Cuando hay varios prefijos posibles, se devuelve el primer prefijo. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Carga el documento según el objeto de solicitud especificado, reemplazando el contenido anterior. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | Carga el documento en el Uniform Resource Locator (URL) especificado en la instancia actual, reemplazando el contenido anterior. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | Carga el documento en el Uniform Resource Locator (URL) especificado en la instancia actual, reemplazando el contenido anterior. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | Carga el documento a partir del contenido especificado y usando baseUri para resolver recursos relativos, reemplazando el contenido anterior. La carga del documento comienza desde la posición actual en el flujo. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Carga el documento a partir del contenido especificado y usando baseUri para resolver recursos relativos, reemplazando el contenido anterior. La carga del documento comienza desde la posición actual en el flujo. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | Carga el documento a partir del contenido especificado y usando baseUri para resolver recursos relativos, reemplazando el contenido anterior. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | Carga el documento a partir del contenido especificado y usando baseUri para resolver recursos relativos, reemplazando el contenido anterior. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Coloca todos los nodos [`Text`](../text/) en toda la profundidad del subárbol bajo este Node, incluidos los nodos de atributo, en una forma "normal" donde solo la estructura (p. ej., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), y [`entity references`](../entityreference/)) separa los nodos [`Text`](../text/), es decir, no hay nodos Text adyacentes ni nodos Text vacíos. Esto puede usarse para asegurar que la vista DOM de un documento sea la misma que si se hubiera guardado y vuelto a cargar, y es útil cuando se realizan operaciones (como búsquedas XPointer [XPointer]) que dependen de una estructura de árbol de documento particular. Si el parámetro "normalize-characters" del objeto [`DOMConfiguration`](../../com.aspose.html/configuration/) adjunto al [`Node.ownerDocument`](../node/ownerdocument/) es true, este método también normalizará completamente los caracteres de los nodos Text. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Devuelve el primer Element en el documento que coincide con el selector |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Devuelve una NodeList de todos los Elements en el documento que coinciden con el selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | El método removeChild() de la interfaz Node elimina un nodo hijo del DOM y devuelve el nodo eliminado. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | Este método se utiliza para renderizar el contenido del documento actual en un dispositivo gráfico especificado. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Reemplaza el nodo hijo oldChild con newChild en la lista de hijos, y devuelve el nodo oldChild. Si newChild es un objeto [`DocumentFragment`](../documentfragment/), oldChild se reemplaza por todos los hijos del [`DocumentFragment`](../documentfragment/), que se insertan en el mismo orden. Si newChild ya está en el árbol, se elimina primero. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Devuelve una cadena que representa esta instancia. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Escribe una cadena de texto en un flujo de documento abierto con open(). Tenga en cuenta que la función producirá un documento que no está necesariamente controlado por una DTD y, por lo tanto, podría generar un resultado inválido en el contexto del documento. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Escribe una cadena de texto seguida de un carácter de nueva línea en un flujo de documento abierto con open(). Tenga en cuenta que la función producirá un documento que no está necesariamente controlado por una DTD y, por lo tanto, podría generar un resultado inválido en el contexto del documento. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Obtiene o establece el controlador de eventos para el evento OnAbort. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Obtiene o establece el controlador de eventos para el evento OnBlur. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Obtiene o establece el controlador de eventos para el evento OnCancel. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Obtiene o establece el controlador de eventos para el evento OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Obtiene o establece el controlador de eventos para el evento OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Obtiene o establece el controlador de eventos para el evento OnChange. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Obtiene o establece el controlador de eventos para el evento OnClick. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Obtiene o establece el controlador de eventos para el evento OnCueChange. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Obtiene o establece el controlador de eventos para el evento OnDblClick. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Obtiene o establece el controlador de eventos para el evento OnDurationChange. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Obtiene o establece el controlador de eventos para el evento OnEmptied. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Obtiene o establece el controlador de eventos para el evento OnEnded. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Obtiene o establece el controlador de eventos para el evento OnError. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Obtiene o establece el controlador de eventos para el evento OnFocus. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Obtiene o establece el controlador de eventos para el evento OnInput. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Obtiene o establece el controlador de eventos para el evento OnInvalid. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Obtiene o establece el controlador de eventos para el evento OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Obtiene o establece el controlador de eventos para el evento OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Obtiene o establece el controlador de eventos para el evento OnKeyUp. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Obtiene o establece el controlador de eventos para el evento OnLoad. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Obtiene o establece el controlador de eventos para el evento OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Obtiene o establece el controlador de eventos para el evento OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Obtiene o establece el controlador de eventos para el evento OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Obtiene o establece el controlador de eventos para el evento OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Obtiene o establece el controlador de eventos para el evento OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Obtiene o establece el controlador de eventos para el evento OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Obtiene o establece el controlador de eventos para el evento OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Obtiene o establece el controlador de eventos para el evento OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Obtiene o establece el controlador de eventos para el evento OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Obtiene o establece el controlador de eventos para el evento OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Obtiene o establece el controlador de eventos para el evento OnMouseWheel. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Obtiene o establece el controlador de eventos para el evento OnPause. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Obtiene o establece el controlador de eventos para el evento OnPlay. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Obtiene o establece el controlador de eventos para el evento OnPlaying. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Obtiene o establece el controlador de eventos para el evento OnProgress. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Obtiene o establece el controlador de eventos para el evento OnRateChange. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Obtiene o establece el controlador de eventos para el evento OnReadyStateChange. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Obtiene o establece el controlador de eventos para el evento OnReset. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Obtiene o establece el controlador de eventos para el evento OnResize. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Obtiene o establece el controlador de eventos para el evento OnScroll. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Obtiene o establece el controlador de eventos para el evento OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Obtiene o establece el controlador de eventos para el evento OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Obtiene o establece el controlador de eventos para el evento OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Obtiene o establece el controlador de eventos para el evento OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Obtiene o establece el controlador de eventos para el evento OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Obtiene o establece el controlador de eventos para el evento OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Obtiene o establece el controlador de eventos para el evento OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Obtiene o establece el controlador de eventos para el evento OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Obtiene o establece el controlador de eventos para el evento OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Obtiene o establece el controlador de eventos para el evento OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Obtiene o establece el controlador de eventos para el evento OnWaiting. |

### Ver también

* class [Node](../node/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../com.aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../com.aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../com.aspose.html.dom.xpath/ixpathevaluator/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

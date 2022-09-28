---
title: SVGElementInstance
second_title: Referencia de API de Aspose.HTML para .NET
description: El objeto raíz de cada árbol de sombra de elementos de uso implementa la interfaz SVGUseElementShadowRoot. Esta interfaz actualmente no define ninguna extensión a las propiedades y métodos definidos para la interfaz ShadowRoot y el mixin DocumentOrShadowRoot. Sin embargo el árbol enraizado en este nodo es completamente de solo lectura desde la perspectiva de los scripts de autor.
type: docs
weight: 2040
url: /es/net/aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

El objeto raíz de cada árbol de sombra de elementos de uso implementa la interfaz SVGUseElementShadowRoot. Esta interfaz actualmente no define ninguna extensión a las propiedades y métodos definidos para la interfaz ShadowRoot y el mixin DocumentOrShadowRoot. Sin embargo, el árbol enraizado en este nodo es completamente de solo lectura desde la perspectiva de los scripts de autor.

```csharp
public class SVGElementInstance : ShadowRoot
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | Un NamedNodeMap que contiene los atributos de este nodo (si es un Elemento) o nulo en caso contrario. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | El URI base absoluto de este nodo o nulo si la implementación no pudo obtener un URI absoluto. |
| [ChildElementCount](../../aspose.html.dom/documentfragment/childelementcount) { get; } | Devuelve el número actual de nodos de elementos que son hijos de este elemento. 0 si este elemento no tiene nodos secundarios que sean de nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | Una lista de nodos que contiene todos los elementos secundarios de este nodo. Si no hay hijos, esta es una lista de nodos que no contiene nodos.. |
| [Children](../../aspose.html.dom/documentfragment/children) { get; } | Devuelve los elementos secundarios del elemento actual. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | El primer hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [FirstElementChild](../../aspose.html.dom/documentfragment/firstelementchild) { get; } | Devuelve el primer nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| [Host](../../aspose.html.dom/shadowroot/host) { get; } | Host es un elemento que contiene este ShadowRoot. |
| [InnerHTML](../../aspose.html.dom/documentfragment/innerhtml) { get; set; } | Devuelve un fragmento de HTML o XML que representa el contenido del elemento. Se puede configurar para reemplazar el contenido del elemento con nodos analizados de la cadena dada. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | El último hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [LastElementChild](../../aspose.html.dom/documentfragment/lastelementchild) { get; } | Devuelve el último nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | Devuelve la parte local del nombre calificado de este nodo. Para los nodos de cualquier tipo que no sean ELEMENT_NODE y ATTRIBUTE_NODE y los nodos creados con un método DOM Nivel 1, como Document.createElement(), esto siempre es nulo. |
| [Mode](../../aspose.html.dom/shadowroot/mode) { get; } | Modo en el que opera este ShadowRoot. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | El URI del espacio de nombres de este nodo, o nulo si no se especifica. |
| [NextElementSibling](../../aspose.html.dom/documentfragment/nextelementsibling) { get; } | Devuelve el siguiente nodo de elemento hermano de este elemento. nulo si este elemento no tiene nodos hermanos del elemento que vienen después de este en el árbol del documento. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | El nodo que sigue inmediatamente a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| override [NodeName](../../aspose.html.dom/documentfragment/nodename) { get; } | El nombre de este nodo, dependiendo de su tipo. |
| override [NodeType](../../aspose.html.dom/documentfragment/nodetype) { get; } | Un código que representa el tipo del objeto subyacente. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | El valor de este nodo, según su tipo. |
| [OuterHTML](../../aspose.html.dom/documentfragment/outerhtml) { get; set; } | Devuelve un fragmento de HTML o XML que representa el elemento y su contenido. Se puede configurar para reemplazar el elemento con nodos analizados de la cadena dada. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | El objeto Documento asociado con este nodo. Este es también el objeto Documento utilizado para crear nuevos nodos. Cuando este nodo es un Documento o un Tipo de documento que aún no se usa con ningún Documento, es nulo. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Obtiene el padre[`Element`](../../aspose.html.dom/element) de este nodo. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | El padre de este nodo. Todos los nodos, excepto Attr, Document, DocumentFragment, Entity y Notation pueden tener un padre. Sin embargo, si se acaba de crear un nodo y aún no se ha agregado al árbol, o si se ha eliminado del árbol, este es nulo. |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | El prefijo del espacio de nombres de este nodo, o nulo si no se especifica. Cuando se define como nulo, configurarlo no tiene efecto |
| [PreviousElementSibling](../../aspose.html.dom/documentfragment/previouselementsibling) { get; } | Devuelve el nodo de elemento hermano anterior de este elemento. nulo si este elemento no tiene nodos hermanos que estén antes de este en el árbol del documento. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | El nodo inmediatamente anterior a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| override [TextContent](../../aspose.html.dom/documentfragment/textcontent) { get; set; } | Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como nulo, establecerlo no tiene ningún efecto. En la configuración, se eliminan todos los posibles elementos secundarios que este nodo pueda tener y, si la nueva cadena no está vacía o es nula, se reemplaza por un solo nodo de texto que contiene la cadena en la que se establece este atributo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | Agrega el nodo newChild al final de la lista de hijos de este nodo. Si newChild ya está en el árbol, primero se elimina. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Este método permite el envío de eventos al modelo de eventos de implementaciones. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | Devuelve si este nodo (si es un elemento) tiene algún atributo |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | Devuelve si este nodo tiene hijos. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | Inserta el nodo antes del nodo secundario existente. Si hijo es nulo, inserte el nodo al final de la lista de hijos. Si hijo es un objeto DocumentFragment, todos sus hijos se insertan, en el mismo orden, antes de hijo. Si el niño ya está en el árbol, primero se elimina. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | Este método comprueba si el namespaceURI especificado es el espacio de nombres predeterminado o no. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | Comprueba si dos nodos son iguales. Este método comprueba la igualdad de los nodos, no la uniformidad (es decir, si los dos nodos son referencias al mismo objeto) que se puede probar con Node.isSameNode(). Todos los nodos que son iguales también serán iguales, aunque lo contrario puede no ser cierto. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | Devuelve si este nodo es el mismo nodo que el dado. Este método proporciona una forma de determinar si dos referencias de nodo devueltas por la implementación hacen referencia al mismo objeto. Cuando dos referencias de Nodo son referencias al mismo objeto, incluso a través de un proxy, las referencias se pueden usar de manera completamente intercambiable, de modo que todos los atributos tengan los mismos valores y llamar al mismo método DOM en cualquiera de las referencias siempre tiene exactamente el mismo efecto. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | Busque el URI del espacio de nombres asociado al prefijo dado, a partir de este nodo. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | Busque el prefijo asociado al URI del espacio de nombres dado, a partir de este nodo. Este método ignora las declaraciones de espacios de nombres predeterminados. Consulte Búsqueda de prefijo de espacio de nombres para obtener detalles sobre el algoritmo utilizado por este método. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Coloca todos los nodos de texto en toda la profundidad del subárbol debajo de este nodo, incluidos los nodos de atributos, en una forma "normal" donde solo la estructura (p. ej., elementos, comentarios, instrucciones de procesamiento, secciones CDATA y referencias a entidades) separa el texto nodos, es decir, no hay nodos de Texto adyacentes ni nodos de Texto vacíos. Esto se puede usar para garantizar que la vista DOM de un documento sea la misma que si se hubiera guardado y vuelto a cargar, y es útil cuando las operaciones (como las búsquedas de XPointer [XPointer]) que dependen de una estructura de árbol de documento en particular deben realizarse. ser usado. Si el parámetro "normalize-characters" del objeto DOMConfiguration adjunto a Node.ownerDocument es verdadero, este método también normalizará por completo los caracteres de Text nodes. |
| [QuerySelector](../../aspose.html.dom/documentfragment/queryselector)(string) | Devuelve el primer Elemento del documento, que coincide con selector |
| [QuerySelectorAll](../../aspose.html.dom/documentfragment/queryselectorall)(string) | Devuelve una lista de nodos de todos los elementos en el documento, que coinciden con selector |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | Elimina el nodo hijo indicado por oldChild de la lista de hijos y lo devuelve. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Reemplaza el nodo secundario oldChild con newChild en la lista de elementos secundarios y devuelve el nodo oldChild. Si newChild es un objeto DocumentFragment, oldChild se reemplaza por todos los hijos de DocumentFragment, que se insertan en el mismo orden. Si newChild ya está en el árbol, primero se elimina. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Devuelve unString que representa esta instancia. |

### Ver también

* class [ShadowRoot](../../aspose.html.dom/shadowroot)
* espacio de nombres [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->

---
title: HTMLInputElement
second_title: Referencia de API de Aspose.HTML para .NET
description: Control de formulario. Según el entorno en el que se visualiza la página  la propiedad de valor puede ser de solo lectura para el tipo de entrada de carga de archivos . Para el tipo de entrada contraseña el valor real devuelto puede enmascararse para evitar el uso no autorizado. Consulte la definición del elemento INPUT en HTML 4.01http//www.w3.org/TR/1999/REChtml40119991224 .
type: docs
weight: 3310
url: /es/net/aspose.html/htmlinputelement/
---
## HTMLInputElement class

Control de formulario. Según el entorno en el que se visualiza la página , la propiedad de valor puede ser de solo lectura para el tipo de entrada de carga de archivos . Para el tipo de entrada "contraseña", el valor real devuelto puede enmascararse para evitar el uso no autorizado. Consulte la definición del elemento INPUT en [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

Véase también el[Especificación HTML de nivel 2 del modelo de objeto de documento (DOM)](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLInputElement : HTMLElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Accept](../../aspose.html/htmlinputelement/accept) { get; set; } | Una lista separada por comas de tipos de contenido que un servidor que procesa este formulario manejará correctamente. Consulte la definición de atributo de aceptación en HTML 4.01. |
| [AccessKey](../../aspose.html/htmlinputelement/accesskey) { get; set; } | Una clave de acceso de un solo carácter para dar acceso al control de formulario. Consulte la definición del atributo de clave de acceso en HTML 4.01. |
| [Align](../../aspose.html/htmlinputelement/align) { get; set; } | Alinea este objeto (vertical u horizontalmente) con respecto al texto que lo rodea . Consulte la definición del atributo de alineación en HTML 4.01. Este atributo está obsoleto en HTML 4.01. |
| [Alt](../../aspose.html/htmlinputelement/alt) { get; set; } | Texto alternativo para agentes de usuario que no muestran el contenido normal de este elemento . Ver la definición del atributo alt en HTML 4.01. |
| override [Attributes](../../aspose.html.dom/element/attributes) { get; } | Un NamedNodeMap que contiene los atributos de este nodo (si es un Elemento) o nulo en caso contrario. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | El URI base absoluto de este nodo o nulo si la implementación no pudo obtener un URI absoluto. |
| [Checked](../../aspose.html/htmlinputelement/checked) { get; set; } | Cuando el`escribe`El atributo del elemento tiene el valor "radio" o "checkbox", esto representa el estado actual del control de formulario , en un agente de usuario interactivo. Los cambios a este atributo cambian el estado del control de formulario, pero no cambian el valor de , el atributo HTML verificado del elemento INPUT. Durante el manejo de un evento de clic en un elemento de entrada con un atributo de tipo que tiene el valor "radio" o "casilla de verificación", algunas implementaciones pueden cambiar el valor de esta propiedad antes de que el evento se envíe en el documento . Si se cancela la acción predeterminada del evento, el valor de la propiedad puede volver a cambiarse a su valor original. Esto significa que el valor de esta propiedad durante el manejo de eventos de clic depende de la implementación. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount) { get; } | Devuelve el número actual de nodos de elementos que son hijos de este elemento. 0 si este elemento no tiene nodos secundarios que sean de nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | Una lista de nodos que contiene todos los elementos secundarios de este nodo. Si no hay hijos, esta es una lista de nodos que no contiene nodos.. |
| [Children](../../aspose.html.dom/element/children) { get; } | Devuelve los elementos secundarios del elemento actual. |
| [ClassList](../../aspose.html.dom/element/classlist) { get; } | Devuelve una DOMTokenList en vivo que contiene los tokens recibidos al analizar el atributo "clase". |
| [ClassName](../../aspose.html/htmlelement/classname) { get; set; } | El atributo de clase del elemento. Se ha cambiado el nombre de este atributo debido a debido a conflictos con la palabra clave "clase" expuesta por muchos idiomas. Ver la definición del atributo de clase en HTML 4.01. |
| [DefaultChecked](../../aspose.html/htmlinputelement/defaultchecked) { get; set; } | cuando`escribe` tiene el valor "radio" o "casilla de verificación", este representa el atributo HTML marcado del elemento. El valor de este atributo no cambia si cambia el estado del control de formulario correspondiente, en un agente de usuario interactivo. Consulte la definición del atributo marcado en HTML 4.01. |
| [DefaultValue](../../aspose.html/htmlinputelement/defaultvalue) { get; set; } | Cuando el`escribe`atributo del elemento tiene el valor "texto", "archivo" o "contraseña", esto representa el valor HTML atributo del elemento. El valor de este atributo no cambia si cambia el contenido del control de formulario correspondiente, en un agente de usuario interactivo. Consulte la definición del atributo de valor en HTML 4.01. |
| [Dir](../../aspose.html/htmlelement/dir) { get; set; } | Especifica la dirección base del texto direccionalmente neutral y la direccionalidad de las tablas. Consulte la definición del atributo dir en HTML 4.01. |
| [Disabled](../../aspose.html/htmlinputelement/disabled) { get; set; } | El control no está disponible en este contexto. Consulte la definición del atributo deshabilitado en HTML 4.01. |
| [Files](../../aspose.html/htmlinputelement/files) { get; } | El atributo IDL de archivos permite que los scripts accedan a los archivos seleccionados del elemento. Al obtener, si se aplica el atributo IDL, debe devolver un objeto FileList que represente los archivos seleccionados actualmente. Se debe devolver el mismo objeto hasta que cambie la lista de archivos seleccionados. Si el atributo IDL no se aplica, debe devolver un valor nulo. [API DE ARCHIVO] |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | El primer hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild) { get; } | Devuelve el primer nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| [Form](../../aspose.html/htmlinputelement/form) { get; set; } | Devuelve el`FORMA` elemento que contiene este control. Devuelve `nulo` si este control no está dentro del contexto de un formulario . |
| [Id](../../aspose.html/htmlelement/id) { get; set; } | El identificador del elemento. Consulte la definición del atributo id en HTML 4.01. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml) { get; set; } | Devuelve un fragmento de HTML o XML que representa el contenido del elemento. Se puede configurar para reemplazar el contenido del elemento con nodos analizados de la cadena dada. |
| [Lang](../../aspose.html/htmlelement/lang) { get; set; } | Código de idioma definido en RFC 1766. Consulte la definición del atributo lang en HTML 4.01. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | El último hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild) { get; } | Devuelve el último nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| [List](../../aspose.html/htmlinputelement/list) { get; set; } | El atributo de lista se utiliza para identificar un elemento que enumera opciones predefinidas sugeridas al usuario. Si está presente, su valor debe ser el ID de un elemento de lista de datos en el mismo documento. |
| override [LocalName](../../aspose.html.dom/element/localname) { get; } | Devuelve la parte local del nombre calificado de este nodo. Para los nodos de cualquier tipo que no sean ELEMENT_NODE y ATTRIBUTE_NODE y los nodos creados con un método DOM Nivel 1, como Document.createElement(), esto siempre es nulo. |
| [MaxLength](../../aspose.html/htmlinputelement/maxlength) { get; set; } | Número máximo de caracteres para campos de texto, cuando`escribe` tiene el valor "texto" o "contraseña". Consulte la definición del atributo maxlength en HTML 4.01. |
| [Name](../../aspose.html/htmlinputelement/name) { get; set; } | Control de formulario o nombre de objeto cuando se envía con un formulario. Ver la definición del atributo name en HTML 4.01. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri) { get; } | El URI del espacio de nombres de este nodo, o nulo si no se especifica. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling) { get; } | Devuelve el siguiente nodo de elemento hermano de este elemento. nulo si este elemento no tiene nodos hermanos del elemento que vienen después de este en el árbol del documento. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | El nodo que sigue inmediatamente a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| override [NodeName](../../aspose.html.dom/element/nodename) { get; } | El nombre de este nodo, dependiendo de su tipo. |
| override [NodeType](../../aspose.html.dom/element/nodetype) { get; } | Un código que representa el tipo del objeto subyacente. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | El valor de este nodo, según su tipo. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml) { get; set; } | Devuelve un fragmento de HTML o XML que representa el elemento y su contenido. Se puede configurar para reemplazar el elemento con nodos analizados de la cadena dada. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | El objeto Documento asociado con este nodo. Este es también el objeto Documento utilizado para crear nuevos nodos. Cuando este nodo es un Documento o un Tipo de documento que aún no se usa con ningún Documento, es nulo. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Obtiene el padre[`Element`](../../aspose.html.dom/element) de este nodo. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | El padre de este nodo. Todos los nodos, excepto Attr, Document, DocumentFragment, Entity y Notation pueden tener un padre. Sin embargo, si se acaba de crear un nodo y aún no se ha agregado al árbol, o si se ha eliminado del árbol, este es nulo. |
| override [Prefix](../../aspose.html.dom/element/prefix) { get; } | El prefijo del espacio de nombres de este nodo, o nulo si no se especifica. Cuando se define como nulo, configurarlo no tiene efecto |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling) { get; } | Devuelve el nodo de elemento hermano anterior de este elemento. nulo si este elemento no tiene nodos hermanos que estén antes de este en el árbol del documento. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | El nodo inmediatamente anterior a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [ReadOnly](../../aspose.html/htmlinputelement/readonly) { get; set; } | Este control es de solo lectura. Relevante sólo cuando`escribe` tiene el valor "texto" o "contraseña". Consulte la definición del atributo de solo lectura en HTML 4.01. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo) { get; } | La información de tipo asociada con este elemento. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot) { get; } | Devuelve shadowRoot almacenado en este elemento o nulo si está cerrado. |
| [Size](../../aspose.html/htmlinputelement/size) { get; set; } | Información de tamaño. El significado preciso es específico para cada tipo de campo . Consulte la definición del atributo de tamaño en HTML 4.01. @version DOM Level 2 |
| [Src](../../aspose.html/htmlinputelement/src) { get; set; } | Cuando el`escribe`El atributo tiene el valor "imagen", este atributo especifica la ubicación de la imagen que se utilizará para decorar el botón gráfico de envío. Ver la definición del atributo src en HTML 4.01. |
| [Style](../../aspose.html/htmlelement/style) { get; } | Representa un atributo de estilo que permite al autor aplicar directamente información de estilo a un elemento específico. |
| [TabIndex](../../aspose.html/htmlinputelement/tabindex) { get; set; } | Índice que representa la posición del elemento en el orden de tabulación. Ver la definición del atributo tabindex en HTML 4.01. |
| [TagName](../../aspose.html.dom/element/tagname) { get; } | El nombre del elemento. |
| override [TextContent](../../aspose.html.dom/element/textcontent) { get; set; } | Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como nulo, establecerlo no tiene ningún efecto. En la configuración, se eliminan todos los posibles elementos secundarios que este nodo pueda tener y, si la nueva cadena no está vacía o es nula, se reemplaza por un solo nodo de texto que contiene la cadena en la que se establece este atributo. |
| [Title](../../aspose.html/htmlelement/title) { get; set; } | El título de aviso del elemento. Consulte la definición del atributo de título en HTML 4.01. |
| [Type](../../aspose.html/htmlinputelement/type) { get; set; } | El tipo de control creado (todo en minúsculas). Consulte la definición del atributo de tipo en HTML 4.01. @versión DOM Nivel 2 |
| [UseMap](../../aspose.html/htmlinputelement/usemap) { get; set; } | Usar mapa de imágenes del lado del cliente. Consulte la definición del atributo usemap en HTML 4.01. |
| [Value](../../aspose.html/htmlinputelement/value) { get; set; } | Cuando el`escribe` El atributo del elemento tiene el valor "texto", "archivo" o "contraseña", esto representa el contenido actual de el control de formulario correspondiente, en un agente de usuario interactivo. Cambiar este atributo cambia el contenido del control de formulario, pero no cambia el valor del atributo de valor HTML del elemento. Cuando el`escribe`El atributo del elemento tiene el valor "botón", "oculto", "enviar", "restablecer", "imagen", "casilla de verificación" o "radio", esto representa el atributo de valor HTML del elemento. Consulte la definición del atributo de valor en HTML 4.01. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | Agrega el nodo newChild al final de la lista de hijos de este nodo. Si newChild ya está en el árbol, primero se elimina. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow)(ShadowRootMode) | Crea shadow root y lo adjunta al elemento actual. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Este método permite el envío de eventos al modelo de eventos de implementaciones. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| [GetAttribute](../../aspose.html.dom/element/getattribute)(string) | Recupera un valor de atributo por nombre. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode)(string) | Recupera un nodo de atributo por nombre. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens)(string, string) | Recupera un nodo Attr por nombre local y URI de espacio de nombres. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens)(string, string) | Recupera un valor de atributo por nombre local y URI de espacio de nombres. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname)(string) | Devuelve un objeto NodeList activo que contiene todos los elementos del documento que tienen todas las clases especificadas en el argumento. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname)(string) | Devuelve una lista de nodos de todos los elementos descendientes con un nombre de etiqueta determinado, en el orden del documento. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens)(string, string) | Devuelve una lista de nodos de todos los elementos descendientes con un nombre local determinado y un URI de espacio de nombres en el orden del documento. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [HasAttribute](../../aspose.html.dom/element/hasattribute)(string) | Devuelve verdadero cuando se especifica un atributo con un nombre determinado en este elemento o tiene un valor predeterminado; de lo contrario, devuelve falso. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens)(string, string) | Devuelve verdadero cuando se especifica un atributo con un nombre local determinado y un URI de espacio de nombres en este elemento o tiene un valor predeterminado; de lo contrario, devuelve falso. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes)() | Devuelve si este nodo (si es un elemento) tiene algún atributo |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | Devuelve si este nodo tiene hijos. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | Inserta el nodo antes del nodo secundario existente. Si hijo es nulo, inserte el nodo al final de la lista de hijos. Si hijo es un objeto DocumentFragment, todos sus hijos se insertan, en el mismo orden, antes de hijo. Si el niño ya está en el árbol, primero se elimina. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | Este método comprueba si el namespaceURI especificado es el espacio de nombres predeterminado o no. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | Comprueba si dos nodos son iguales. Este método comprueba la igualdad de los nodos, no la uniformidad (es decir, si los dos nodos son referencias al mismo objeto) que se puede probar con Node.isSameNode(). Todos los nodos que son iguales también serán iguales, aunque lo contrario puede no ser cierto. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | Devuelve si este nodo es el mismo nodo que el dado. Este método proporciona una forma de determinar si dos referencias de nodo devueltas por la implementación hacen referencia al mismo objeto. Cuando dos referencias de Nodo son referencias al mismo objeto, incluso a través de un proxy, las referencias se pueden usar de manera completamente intercambiable, de modo que todos los atributos tengan los mismos valores y llamar al mismo método DOM en cualquiera de las referencias siempre tiene exactamente el mismo efecto. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | Busque el URI del espacio de nombres asociado al prefijo dado, a partir de este nodo. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | Busque el prefijo asociado al URI del espacio de nombres dado, a partir de este nodo. Este método ignora las declaraciones de espacios de nombres predeterminados. Consulte Búsqueda de prefijo de espacio de nombres para obtener detalles sobre el algoritmo utilizado por este método. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Coloca todos los nodos de texto en toda la profundidad del subárbol debajo de este nodo, incluidos los nodos de atributos, en una forma "normal" donde solo la estructura (p. ej., elementos, comentarios, instrucciones de procesamiento, secciones CDATA y referencias a entidades) separa el texto nodos, es decir, no hay nodos de Texto adyacentes ni nodos de Texto vacíos. Esto se puede usar para garantizar que la vista DOM de un documento sea la misma que si se hubiera guardado y vuelto a cargar, y es útil cuando las operaciones (como las búsquedas de XPointer [XPointer]) que dependen de una estructura de árbol de documento en particular deben realizarse. ser usado. Si el parámetro "normalize-characters" del objeto DOMConfiguration adjunto a Node.ownerDocument es verdadero, este método también normalizará por completo los caracteres de Text nodes. |
| [QuerySelector](../../aspose.html.dom/element/queryselector)(string) | Devuelve el primer Elemento del documento, que coincide con selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall)(string) | Devuelve una lista de nodos de todos los elementos en el documento, que coinciden con selector |
| [Remove](../../aspose.html.dom/element/remove)() | Elimina esta instancia. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute)(string) | Elimina un atributo por nombre. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode)(Attr) | Elimina el nodo de atributo especificado. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens)(string, string) | Elimina un atributo por nombre local y URI de espacio de nombres. |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | Elimina el nodo hijo indicado por oldChild de la lista de hijos y lo devuelve. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Reemplaza el nodo secundario oldChild con newChild en la lista de elementos secundarios y devuelve el nodo oldChild. Si newChild es un objeto DocumentFragment, oldChild se reemplaza por todos los hijos de DocumentFragment, que se insertan en el mismo orden. Si newChild ya está en el árbol, primero se elimina. |
| [SetAttribute](../../aspose.html.dom/element/setattribute)(string, string) | Agrega un nuevo atributo. Si un atributo con ese nombre ya está presente en el elemento, su valor se cambia para ser el del valor parámetro |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode)(Attr) | Agrega un nuevo nodo de atributo. Si un atributo con ese nombre (nodeName) ya está presente en el elemento, se reemplaza por el nuevo. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens)(Attr) | Agrega un nuevo atributo. Si un atributo con ese nombre local y esa URI de espacio de nombres ya está presente en el elemento, se reemplaza por el nuevo. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens)(string, string, string) | Agrega un nuevo atributo. Si un atributo con el mismo nombre local y URI de espacio de nombres ya está presente en el elemento, su prefijo se cambia para que sea la parte del prefijo del nombre calificado y su valor se cambia para que sea el parámetro de valor. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute)(string, bool) | Si el parámetro isId es verdadero, este método declara que el atributo especificado es un atributo de ID determinado por el usuario. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode)(Attr, bool) | Si el parámetro isId es verdadero, este método declara que el atributo especificado es un atributo de ID determinado por el usuario. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens)(string, string, bool) | Si el parámetro isId es verdadero, este método declara que el atributo especificado es un atributo de ID determinado por el usuario. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Devuelve unString que representa esta instancia. |

### Ver también

* class [HTMLElement](../htmlelement)
* espacio de nombres [Aspose.Html](../../aspose.html)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->

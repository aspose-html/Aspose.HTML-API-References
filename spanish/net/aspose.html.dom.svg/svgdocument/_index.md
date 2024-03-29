---
title: Class SVGDocument
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Svg.SVGDocument clase. UnSVGDocumentoes la raíz de la jerarquía SVG y contiene todo el contenido. Además de brindar acceso a la jerarquía también brinda algunos métodos convenientes para acceder a ciertos conjuntos de información del documento. Cuando un elemento svg se incrusta en línea como un componente de un documento de otro espacio de nombres como cuando un elemento svg elemento está incrustado en línea dentro de un documento XHTML XHTML entonces no existirá un objeto SVGDocument en su lugar el objeto raíz en la jerarquía de objetos del documento será un objeto Documento de un tipo diferente como un objeto HTMLDocument. Sin embargo existirá un objeto SVGDocument cuando el elemento raíz de la jerarquía del documento XML sea un elemento svg  como cuando se ve un archivo SVG independiente es decir un archivo con tipo MIME image/svgxml. En este caso el objeto SVGDocument será el objeto raíz de la jerarquía del modelo de objetos de documento.
type: docs
weight: 2010
url: /es/net/aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

Un`SVGDocumento`es la raíz de la jerarquía SVG y contiene todo el contenido. Además de brindar acceso a la jerarquía, también brinda algunos métodos convenientes para acceder a ciertos conjuntos de información del documento. Cuando un elemento 'svg' se incrusta en línea como un componente de un documento de otro espacio de nombres, como cuando un elemento 'svg' elemento está incrustado en línea dentro de un documento XHTML [XHTML], entonces no existirá un objeto SVGDocument; en su lugar, el objeto raíz en la jerarquía de objetos del documento será un objeto Documento de un tipo diferente, como un objeto HTMLDocument. Sin embargo, existirá un objeto SVGDocument cuando el elemento raíz de la jerarquía del documento XML sea un elemento 'svg' , como cuando se ve un archivo SVG independiente (es decir, un archivo con tipo MIME "image/svg+xml"). En este caso, el objeto SVGDocument será el objeto raíz de la jerarquía del modelo de objetos de documento.

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | Inicializa una nueva instancia del`SVGDocument` clase. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | Inicializa una nueva instancia del`SVGDocument` clase. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_10)(string) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_4)(Url) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_8)(Stream, string) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . La carga del documento comienza desde la posición actual en el flujo. |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . La carga del documento comienza desde la posición actual en el flujo. |
| [SVGDocument](svgdocument/#constructor_11)(string, Configuration) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_14)(string, string) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_12)(string, Url) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_9)(Stream, string, Configuration) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . La carga del documento comienza desde la posición actual en el flujo. |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . La carga del documento comienza desde la posición actual en el flujo. |
| [SVGDocument](svgdocument/#constructor_15)(string, string, Configuration) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_13)(string, Url, Configuration) | Inicializa una nueva instancia del`SVGDocument` clase. Constructor funciona de forma sincrónica, espera la carga de todos los recursos externos (imágenes, scripts, etc.). Para cargar el documento de forma asincrónica, use el método[`Navigate`](../../aspose.html.dom/document/navigate/) o sus sobrecargas. O puede deshabilitar la carga de algunos recursos externos configurando los indicadores apropiados en[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Un NamedNodeMap que contiene los atributos de este nodo (si es un Elemento) o nulo en caso contrario. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | El URI base absoluto de este nodo o nulo si la implementación no pudo obtener un URI absoluto. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Obtiene la codificación del documento. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Obtiene la codificación del documento. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Devuelve el número actual de nodos de elementos que son hijos de este elemento. 0 si este elemento no tiene nodos secundarios que sean de nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Una lista de nodos que contiene todos los elementos secundarios de este nodo. Si no hay hijos, esta es una lista de nodos que no contiene nodos.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Devuelve los elementos secundarios. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Obtiene el tipo de contenido del documento. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Obtiene el contexto de navegación actual. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | El atributo defaultView IDL de la interfaz del Documento, al obtenerlo, debe devolver el objeto WindowProxy del contexto de navegación de este Documento, si este Documento tiene un contexto de navegación asociado, o nulo en caso contrario. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | La declaración de tipo de documento asociada con este documento. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | Este es un atributo conveniente que permite el acceso directo al nodo secundario que es el elemento de documento del documento. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | La ubicación del documento o nulo si no está definido o si el documento se creó mediante DOMImplementation.createDocument. |
| [Domain](../../aspose.html.dom.svg/svgdocument/domain/) { get; } | El nombre de dominio del servidor que entregó el documento, o una cadena nula si el servidor no se puede identificar mediante un nombre de dominio. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | El primer hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Devuelve el primer nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | El objeto DOMImplementation que maneja este documento. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Obtiene la codificación del documento. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | El último hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Devuelve el último nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Devuelve la parte local del nombre calificado de este nodo. Para los nodos de cualquier tipo que no sean ELEMENT_NODE y ATTRIBUTE_NODE y los nodos creados con un método DOM Nivel 1, como Document.createElement(), esto siempre es nulo. |
| [Location](../../aspose.html.dom/document/location/) { get; } | La ubicación del documento. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | El URI del espacio de nombres de este nodo, o nulo si no se especifica. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Devuelve el siguiente nodo de elemento hermano de este elemento. nulo si este elemento no tiene nodos hermanos del elemento que vienen después de este en el árbol del documento. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | El nodo que sigue inmediatamente a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | El nombre de este nodo, dependiendo de su tipo. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | Un código que representa el tipo del objeto subyacente. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | El valor de este nodo, según su tipo. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Obtiene el origen del documento. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Obtiene el documento del propietario. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Obtiene el padre[`Element`](../../aspose.html.dom/element/) de este nodo. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | El padre de este nodo. Todos los nodos, excepto Attr, Document, DocumentFragment, Entity y Notation pueden tener un padre. Sin embargo, si se acaba de crear un nodo y aún no se ha agregado al árbol, o si se ha eliminado del árbol, este es nulo. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | El prefijo del espacio de nombres de este nodo, o nulo si no se especifica. Cuando se define como nulo, configurarlo no tiene efecto |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Devuelve el nodo de elemento hermano anterior de este elemento. nulo si este elemento no tiene nodos hermanos que estén antes de este en el árbol del documento. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | El nodo inmediatamente anterior a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Devuelve la preparación del documento. La "carga" mientras se carga el documento, "interactiva" una vez que finaliza el análisis pero sigue cargando subrecursos, y "completa" una vez que se ha cargado. |
| [Referrer](../../aspose.html.dom.svg/svgdocument/referrer/) { get; } | Devuelve el URI de la página que enlaza con esta página. El valor es una cadena vacía si el usuario navegó a la página directamente (no a través de un enlace, sino, por ejemplo, a través de un marcador). |
| [RootElement](../../aspose.html.dom.svg/svgdocument/rootelement/) { get; } | La raíz 'svg' en la jerarquía del documento. |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | Un atributo que especifica si se aplica o no la comprobación de errores. Cuando se establece en falso, la implementación es libre de no probar todos los casos de error posibles normalmente definidos en las operaciones DOM, y no generar ninguna DOMException en las operaciones DOM o informar errores al usar Document.normalizeDocument(). En caso de error, el comportamiento es indefinido. Este atributo es verdadero por defecto. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | Una lista que contiene todas las hojas de estilo explícitamente vinculadas o incrustadas en un documento. Para documentos HTML, esto incluye hojas de estilo externas, incluidas a través del elemento HTML LINK y elementos STYLE en línea. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como nulo, establecerlo no tiene ningún efecto. En la configuración, se eliminan todos los posibles elementos secundarios que este nodo pueda tener y, si la nueva cadena no está vacía o es nula, se reemplaza por un solo nodo de texto que contiene la cadena en la que se establece este atributo. |
| [Title](../../aspose.html.dom.svg/svgdocument/title/) { get; } | El título de un documento según lo especificado por el subelemento 'title' del elemento raíz 'svg' (es decir,Aquí está el título... ) |
| [URL](../../aspose.html.dom.svg/svgdocument/url/) { get; } | La URI completa del documento. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | Un atributo que especifica, como parte de la declaración XML, si este documento es independiente. Esto es falso cuando no se especifica. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | Un atributo que especifica, como parte de la declaración XML, el número de versión de este documento. Si no hay declaración y si este documento admite la función "XML", el valor es "1.0". Si este documento no es compatible con la función "XML", el valor siempre es nulo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Agrega el nodo newChild al final de la lista de hijos de este nodo. Si newChild ya está en el árbol, primero se elimina. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | Crea un Attr del nombre dado. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | Crea un atributo del nombre calificado y el URI del espacio de nombres proporcionados. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Crea un nodo CDATASection cuyo valor es la cadena especificada. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Crea un nodo de comentario dada la cadena especificada. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Crea un objeto DocumentFragment vacío. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | Crea un nodo DocumentType. |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | Crea un elemento del tipo especificado. Tenga en cuenta que la instancia devuelta implementa la interfaz Element, por lo que los atributos se pueden especificar directamente en el objeto devuelto. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Crea un elemento del nombre calificado y el URI del espacio de nombres proporcionados. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Crea un objeto EntityReference. Además, si se conoce la entidad a la que se hace referencia, la lista secundaria del nodo EntityReference se hace igual que la del nodo Entity correspondiente. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | Crea un[`Event`](../../aspose.html.dom.events/event/) de un tipo soportado por la implementación. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Crea una expresión XPath analizada con espacios de nombres resueltos. Esto es útil cuando se va a reutilizar una expresión en una aplicación, ya que permite compilar la cadena de expresión en un formato interno más eficiente y preresolver todos los prefijos de espacio de nombres que se producen dentro de la expresión. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | Crear un nuevo NodeIterator sobre el subárbol enraizado en el nodo especificado. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | Crear un nuevo NodeIterator sobre el subárbol enraizado en el nodo especificado. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Crear un nuevo NodeIterator sobre el subárbol enraizado en el nodo especificado. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Adapta cualquier nodo DOM para resolver espacios de nombres de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método DOM Nivel 3`lookupNamespaceURI` en los nodos para resolver el namespaceURI de un prefijo dado usando la información actual disponible en la jerarquía del nodo en el momento en que se llama a lookupNamespaceURI, también resolviendo correctamente el prefijo xml implícito. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Crea un nodo ProcessingInstruction con el nombre y las cadenas de datos especificados. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Crea un nodo de texto dada la cadena especificada. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Este método permite el envío de eventos al modelo de eventos de implementaciones. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | Devuelve el Elemento que tiene un atributo ID con el valor dado. Si no existe tal elemento, esto devuelve nulo. Si más de un elemento tiene un atributo ID con ese valor, lo que se devuelve es indefinido. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | Devuelve un objeto NodeList activo que contiene todos los elementos del documento que tienen todas las clases especificadas en el argumento. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | Devuelve una lista de nodos de todos los elementos en el orden del documento con un nombre de etiqueta dado y están contenidos en el documento. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Devuelve una lista de nodos de todos los elementos con un nombre local determinado y un URI de espacio de nombres en el orden del documento. |
| [GetOverrideStyle](../../aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, string) | Este método se utiliza para recuperar la declaración de estilo anulada para un elemento especificado y un pseudoelemento especificado. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Devuelve si este nodo (si es un elemento) tiene algún atributo |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Devuelve si este nodo tiene hijos. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Importa un nodo de otro documento a este documento, sin alterar ni eliminar el nodo de origen del documento original; este método crea una nueva copia del nodo de origen. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Inserta el nodo antes del nodo secundario existente. Si hijo es nulo, inserte el nodo al final de la lista de hijos. Si hijo es un objeto DocumentFragment, todos sus hijos se insertan, en el mismo orden, antes de hijo. Si el niño ya está en el árbol, primero se elimina. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Este método comprueba si el namespaceURI especificado es el espacio de nombres predeterminado o no. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Comprueba si dos nodos son iguales. Este método comprueba la igualdad de los nodos, no la uniformidad (es decir, si los dos nodos son referencias al mismo objeto) que se puede probar con Node.isSameNode(). Todos los nodos que son iguales también serán iguales, aunque lo contrario puede no ser cierto. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Devuelve si este nodo es el mismo nodo que el dado. Este método proporciona una forma de determinar si dos referencias de nodo devueltas por la implementación hacen referencia al mismo objeto. Cuando dos referencias de Nodo son referencias al mismo objeto, incluso a través de un proxy, las referencias se pueden usar de manera completamente intercambiable, de modo que todos los atributos tengan los mismos valores y llamar al mismo método DOM en cualquiera de las referencias siempre tiene exactamente el mismo efecto. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Busque el URI del espacio de nombres asociado al prefijo dado, a partir de este nodo. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Busque el prefijo asociado al URI del espacio de nombres dado, a partir de este nodo. Este método ignora las declaraciones de espacios de nombres predeterminados. Consulte Búsqueda de prefijo de espacio de nombres para obtener detalles sobre el algoritmo utilizado por este método. |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | Carga el documento basado en el objeto de solicitud especificado, reemplazando el contenido anterior. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | Carga el documento en el localizador uniforme de recursos (URL) especificado en la instancia actual, reemplazando el contenido anterior. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | Carga el documento en el localizador uniforme de recursos (URL) especificado en la instancia actual, reemplazando el contenido anterior. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | Carga el documento desde el contenido especificado y usa baseUri para resolver los recursos relativos, reemplazando el contenido anterior. La carga del documento comienza desde la posición actual en la secuencia. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | Carga el documento desde el contenido especificado y usa baseUri para resolver los recursos relativos, reemplazando el contenido anterior. La carga del documento comienza desde la posición actual en la secuencia. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | Carga el documento desde el contenido especificado y usa baseUri para resolver los recursos relativos, reemplazando el contenido anterior. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | Carga el documento desde el contenido especificado y usa baseUri para resolver los recursos relativos, reemplazando el contenido anterior. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Coloca todos los nodos de texto en toda la profundidad del subárbol debajo de este nodo, incluidos los nodos de atributos, en una forma "normal" donde solo la estructura (p. ej., elementos, comentarios, instrucciones de procesamiento, secciones CDATA y referencias a entidades) separa el texto nodos, es decir, no hay nodos de Texto adyacentes ni nodos de Texto vacíos. Esto se puede usar para garantizar que la vista DOM de un documento sea la misma que si se hubiera guardado y vuelto a cargar, y es útil cuando las operaciones (como las búsquedas de XPointer [XPointer]) que dependen de una estructura de árbol de documento en particular deben realizarse. ser usado. Si el parámetro "normalize-characters" del objeto DOMConfiguration adjunto a Node.ownerDocument es verdadero, este método también normalizará por completo los caracteres de Text nodes. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Devuelve el primer Elemento del documento, que coincide con selector |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Devuelve una lista de nodos de todos los elementos en el documento, que coinciden con selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Elimina el nodo hijo indicado por oldChild de la lista de hijos y lo devuelve. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| override [RenderTo](../../aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | Este método se utiliza para imprimir el contenido del documento actual en el dispositivo especificado. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Reemplaza el nodo secundario oldChild con newChild en la lista de elementos secundarios y devuelve el nodo oldChild. Si newChild es un objeto DocumentFragment, oldChild se reemplaza por todos los hijos de DocumentFragment, que se insertan en el mismo orden. Si newChild ya está en el árbol, primero se elimina. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save)(IOutputStorage) | Guarda el contenido y los recursos del documento en el almacenamiento de salida. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_6)(string) | Guarda el documento en el archivo local especificado por`camino` Todos los recursos utilizados en este documento se guardarán en en la carpeta adyacente, cuyo nombre se construirá como: nombre_archivo_salida + "_archivos". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | Guarda el documento en el archivo local especificado por`URL` Todos los recursos utilizados en este documento se guardarán en en la carpeta adyacente, cuyo nombre se construirá como: nombre_archivo_salida + "_archivos". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_1)(IOutputStorage, SVGSaveFormat) | Guarda el contenido y los recursos del documento en el almacenamiento de salida. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_2)(IOutputStorage, SVGSaveOptions) | Guarda el contenido y los recursos del documento en el almacenamiento de salida. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_7)(string, SVGSaveFormat) | Guarda el documento en el archivo local especificado por`camino` Todos los recursos utilizados en este documento se guardarán en en la carpeta adyacente, cuyo nombre se construirá como: nombre_archivo_salida + "_archivos". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_8)(string, SVGSaveOptions) | Guarda el documento en el archivo local especificado por`camino` Todos los recursos utilizados en este documento se guardarán en en la carpeta adyacente, cuyo nombre se construirá como: nombre_archivo_salida + "_archivos". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | Guarda el documento en el archivo local especificado por`URL` Todos los recursos utilizados en este documento se guardarán en en la carpeta adyacente, cuyo nombre se construirá como: nombre_archivo_salida + "_archivos". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | Guarda el documento en el archivo local especificado por`URL` Todos los recursos utilizados en este documento se guardarán en en la carpeta adyacente, cuyo nombre se construirá como: nombre_archivo_salida + "_archivos". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Devuelve unString que representa esta instancia. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | Escribe una cadena de texto en un flujo de documentos abierto por open(). Tenga en cuenta que la función producirá un documento que no está necesariamente controlado por una DTD y, por lo tanto, podría ser producir un resultado no válido en el contexto del documento. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | Escribe una cadena de texto seguida de un carácter de nueva línea en una secuencia document abierta por open(). Tenga en cuenta que la función producirá un documento que no está necesariamente controlado por una DTD y, por lo tanto, podría producir un resultado no válido en el contexto de documento |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | Obtiene o establece el controlador de eventos para el evento OnAbort. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | Obtiene o establece el controlador de eventos para el evento OnBlur. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | Obtiene o establece el controlador de eventos para el evento OnCancel. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | Obtiene o establece el controlador de eventos para el evento OnCanplay. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | Obtiene o establece el controlador de eventos para el evento OnCanPlayThrough. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | Obtiene o establece el controlador de eventos para el evento OnChange. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | Obtiene o establece el controlador de eventos para el evento OnClick. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | Obtiene o establece el controlador de eventos para el evento OnCueChange. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | Obtiene o establece el controlador de eventos para el evento OnDblClick. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | Obtiene o establece el controlador de eventos para el evento OnDurationChange. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | Obtiene o establece el controlador de eventos para el evento OnEmptied. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | Obtiene o establece el controlador de eventos para el evento OnEnded. |
| event [OnError](../../aspose.html.dom/document/onerror/) | Obtiene o establece el controlador de eventos para el evento OnError. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | Obtiene o establece el controlador de eventos para el evento OnFocus. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | Obtiene o establece el controlador de eventos para el evento OnInput. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | Obtiene o establece el controlador de eventos para el evento OnInvalid. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | Obtiene o establece el controlador de eventos para el evento OnKeyDown. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | Obtiene o establece el controlador de eventos para el evento OnKeyPress. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | Obtiene o establece el controlador de eventos para el evento OnKeyUp. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | Obtiene o establece el controlador de eventos para el evento OnLoad. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | Obtiene o establece el controlador de eventos para el evento OnLoadedData. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | Obtiene o establece el controlador de eventos para el evento OnLoadedMetadata. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | Obtiene o establece el controlador de eventos para el evento OnLoadStart. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | Obtiene o establece el controlador de eventos para el evento OnMouseDown. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | Obtiene o establece el controlador de eventos para el evento OnMouseEnter. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | Obtiene o establece el controlador de eventos para el evento OnMouseLeave. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | Obtiene o establece el controlador de eventos para el evento OnMouseMove. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | Obtiene o establece el controlador de eventos para el evento OnMouseOut. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | Obtiene o establece el controlador de eventos para el evento OnMouseOver. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | Obtiene o establece el controlador de eventos para el evento OnMouseUp. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | Obtiene o establece el controlador de eventos para el evento OnMouseWheel. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | Obtiene o establece el controlador de eventos para el evento OnPause. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | Obtiene o establece el controlador de eventos para el evento OnPlay. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | Obtiene o establece el controlador de eventos para el evento OnPlaying. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | Obtiene o establece el controlador de eventos para el evento OnProgress. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | Obtiene o establece el controlador de eventos para el evento OnRateChange. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | Obtiene o establece el controlador de eventos para el evento OnReadyStateChange. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | Obtiene o establece el controlador de eventos para el evento OnReset. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | Obtiene o establece el controlador de eventos para el evento OnResize. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | Obtiene o establece el controlador de eventos para el evento OnScroll. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | Obtiene o establece el controlador de eventos para el evento OnSeeked. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | Obtiene o establece el controlador de eventos para el evento OnSeeking. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | Obtiene o establece el controlador de eventos para el evento OnSelect. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | Obtiene o establece el controlador de eventos para el evento OnShow. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | Obtiene o establece el controlador de eventos para el evento OnStalled. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | Obtiene o establece el controlador de eventos para el evento OnSubmit. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | Obtiene o establece el controlador de eventos para el evento OnSuspend. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | Obtiene o establece el controlador de eventos para el evento OnTimeUpdate. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | Obtiene o establece el controlador de eventos para el evento OnToggle. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | Obtiene o establece el controlador de eventos para el evento OnVolumeChange. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | Obtiene o establece el controlador de eventos para el evento OnWaiting. |

### Ver también

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* espacio de nombres [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* asamblea [Aspose.HTML](../../)



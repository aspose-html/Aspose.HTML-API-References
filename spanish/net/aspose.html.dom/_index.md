---
title: Aspose.Html.Dom
second_title: Referencia de API de Aspose.HTML para .NET
description: El Aspose.Html.Dom modelo de objeto de documento El espacio de nombres proporciona una API que representa e interactúa con cualquier documento HTML XML o SVG. El DOM es un modelo de documento cargado en el navegador y que representa el documento como un árbol de nodos donde cada nodo representa parte del documento por ejemplo un elemento texto cadena o comentario.
type: docs
weight: 40
url: /es/net/aspose.html.dom/
---
El **Aspose.Html.Dom (modelo de objeto de documento)** El espacio de nombres proporciona una API que representa e interactúa con cualquier documento HTML, XML o SVG. El DOM es un modelo de documento cargado en el navegador y que representa el documento como un árbol de nodos, donde cada nodo representa parte del documento (por ejemplo, un elemento, texto cadena o comentario).

## Clases

| Clase | Descripción |
| --- | --- |
| [Attr](./attr) | La interfaz Attr representa un atributo en un objeto Elemento. Normalmente, los valores permitidos para el atributo se definen en un esquema asociado con el documento. |
| [CDATASection](./cdatasection) | Las secciones CDATA se utilizan para escapar de bloques de texto que contienen caracteres que, de otro modo, se considerarían marcados. |
| [CharacterData](./characterdata) | CharacterData amplía el nodo con un conjunto de atributos y métodos para acceder a los datos de caracteres en el DOM. |
| [Comment](./comment) | Hereda de CharacterData y representa el contenido de un comentario, es decir, todos los caracteres entre el inicio ' . |
| [Document](./document) | El Documento representa todo el documento HTML, XML o SVG. Conceptualmente, es la raíz del árbol del documento y proporciona el acceso principal a los datos del documento. |
| [DocumentFragment](./documentfragment) | DocumentFragment es un objeto de documento "ligero" o "mínimo". Es muy común querer poder extraer una parte del árbol de un documento o crear un nuevo fragmento de un documento. |
| [DocumentType](./documenttype) | DocumentType proporciona una interfaz a la lista de entidades definidas para document |
| [DOMException](./domexception) | La interfaz DOMException representa un evento anormal (llamado excepción) que ocurre como resultado de llamar a un método o acceder a una propiedad de una API web. Básicamente, así es como se describen las condiciones de error en las API web. |
| [DOMObject](./domobject) | El tipo DOMObject se usa para representar un objeto base para todo el modelo de objetos del documento. Para Java y ECMAScript, DOMObject está vinculado al tipo de objeto. |
| [Element](./element) | La interfaz Elemento representa un elemento en un documento HTML o XML. |
| [Entity](./entity) | Representa una entidad conocida, analizada o no analizada, en un documento XML. |
| [EntityReference](./entityreference) | Los nodos EntityReference se pueden usar para representar una referencia de entidad en el árbol. |
| [EventTarget](./eventtarget) | El[`EventTarget`](../aspose.html.dom/eventtarget) Todos los nodos implementan la interfaz en una implementación que admite el modelo de eventos DOM. Por lo tanto, esta interfaz se puede obtener utilizando métodos de conversión específicos de vinculación en una instancia de la interfaz de nodo. La interfaz permite el registro y la eliminación de escuchas de eventos en un[`EventTarget`](../aspose.html.dom/eventtarget) y envío de eventos a ese[`IEventTarget`](../aspose.html.dom.events/ieventtarget) . |
| [Node](./node) | La interfaz de nodo es el tipo de datos principal para todo el modelo de objetos de documento. Representa un solo nodo en el árbol del documento. |
| [Notation](./notation) | Representa una notación declarada en la DTD. |
| [ProcessingInstruction](./processinginstruction) | ProcessingInstruction representa una "instrucción de procesamiento", utilizada en XML como una forma de mantener información específica del procesador en el texto del documento. |
| [ShadowRoot](./shadowroot) | ShadowRoot es un nodo raíz del árbol de sombra. |
| [Text](./text) | La interfaz de texto hereda de CharacterData y representa el contenido textual (denominado datos de caracteres en XML) de un elemento o atributo. |
| [TypeInfo](./typeinfo) | TypeInfo representa un tipo al que se hace referencia desde los nodos Element o Attr, especificado en los esquemas asociados con el documento. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext) | Un contexto de navegación es un entorno en el que[`Document`](../aspose.html.dom/document) los objetos se presentan al usuario. |
| [IChildNode](./ichildnode) | Define[`IChildNode`](../aspose.html.dom/ichildnode) interfaz que debe ser implementada por[`Node`](../aspose.html.dom/node) que puede tener un padre. |
| [IDocumentInit](./idocumentinit) | Esta interfaz proporciona[`Document`](../aspose.html.dom/document) información de inicialización. |
| [IDOMImplementation](./idomimplementation) | La interfaz DOMImplementation proporciona varios métodos para realizar operaciones que son independientes de cualquier instancia particular del modelo de objeto de documento. |
| [IElementInit](./ielementinit) | Esta interfaz proporciona[`Element`](../aspose.html.dom/element) información de inicialización. |
| [IGlobalEventHandlers](./iglobaleventhandlers) | Representa la interfaz que deben heredar todos los elementos compatibles con el manejo de eventos del sistema |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode) | Define[`IChildNode`](../aspose.html.dom/ichildnode) que no son[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node) . |
| [INonElementParentNode](./inonelementparentnode) | Define[`IParentNode`](../aspose.html.dom/iparentnode) que no son de tipo Elemento. |
| [IParentNode](./iparentnode) | Define el[`IParentNode`](../aspose.html.dom/iparentnode) interfaz que es implementada por cualquier padre posible. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [ShadowRootMode](./shadowrootmode) | Modos en los que puede operar ShadowRoot. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->

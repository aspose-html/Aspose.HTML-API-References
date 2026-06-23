---
title: "com.aspose.html.dom"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "El paquete com.aspose.html.dom Document Object Model proporciona una API que representa e interactúa con cualquier documento HTML, XML o SVG. El DOM es un modelo de documento cargado en el navegador y representa el documento como un árbol de nodos donde cada nodo representa una parte del documento, por ejemplo, un elemento, texto, cadena o comentario."
type: docs

url: /es/java/com.aspose.html.dom/
---
El paquete **com.aspose.html.dom (Document Object Model)** proporciona una API que representa e interactúa con cualquier documento HTML, XML o SVG. El DOM es un modelo de documento cargado en el navegador y representa el documento como un árbol de nodos, donde cada nodo representa una parte del documento (p. ej., un elemento, una cadena de texto o un comentario).

## Clases

| Clase | Descripción |
| --- | --- |
| [Attr](./attr/) | La interfaz Attr representa un atributo en un objeto Element. Normalmente, los valores permitidos para el atributo se definen en un esquema asociado al documento. |
| [CDATASection](./cdatasection/) | Las secciones CDATA se utilizan para escapar bloques de texto que contienen caracteres que de otro modo se considerarían marcado. |
| [CharacterData](./characterdata/) | CharacterData extiende Node con un conjunto de atributos y métodos para acceder a los datos de caracteres en el DOM. |
| [Comment](./comment/) | Hereda de CharacterData y representa el contenido de un comentario, es decir, todos los caracteres entre las comillas iniciales ''. |
| [Document](./document/) | El Document representa todo el documento HTML, XML o SVG. Conceptualmente, es la raíz del árbol del documento y proporciona el acceso principal a los datos del documento. |
| [DocumentFragment](./documentfragment/) | DocumentFragment es un objeto Document "ligero" o "mínimo". Es muy común querer extraer una porción del árbol de un documento o crear un nuevo fragmento de un documento. |
| [DocumentType](./documenttype/) | El DocumentType proporciona una interfaz a la lista de entidades que están definidas para el documento. |
| [DOMException](./domexception/) | La interfaz DOMException representa un evento anormal (llamado excepción) que ocurre como resultado de llamar a un método o acceder a una propiedad de una API web. Básicamente, así se describen las condiciones de error en las APIs web. |
| [DOMObject](./domobject/) | El tipo DOMObject se utiliza para representar un objeto base para todo el Document Object Model. Para Java y ECMAScript, DOMObject está vinculado al tipo Object. |
| [Element](./element/) | La interfaz Element representa un elemento en un documento HTML o XML. |
| [Entity](./entity/) | Representa una entidad conocida, ya sea analizada o no analizada, en un documento XML. |
| [EntityReference](./entityreference/) | Los nodos EntityReference pueden usarse para representar una referencia a una entidad en el árbol. |
| [EventTarget](./eventtarget/) | La interfaz EventTarget es implementada por objetos que pueden recibir eventos y pueden tener escuchadores para ellos. En otras palabras, cualquier objetivo de eventos implementa los tres métodos asociados con esta interfaz. |
| [Node](./node/) | La interfaz Node es el tipo de dato principal para todo el Document Object Model. Representa un único nodo en el árbol del documento. Mientras todos los objetos que implementan la interfaz Node exponen métodos para manejar hijos, no todos los objetos que implementan la interfaz Node pueden tener hijos. Por ejemplo, [`Text`](../com.aspose.html.dom/text/) los nodos pueden no tener hijos, y agregar hijos a dichos nodos produce que se lance una [`DOMException`](../com.aspose.html.dom/domexception/). |
| [Notation](./notation/) | Representa una notación declarada en el DTD. |
| [ProcessingInstruction](./processinginstruction/) | La ProcessingInstruction representa una "instrucción de procesamiento", usada en XML como una forma de mantener información específica del procesador en el texto del documento. |
| [QualifiedName](./qualifiedname/) | Representa un nombre calificado HTML. |
| [ShadowRoot](./shadowroot/) | ShadowRoot es un nodo raíz del árbol sombra. |
| [Text](./text/) | La interfaz Text hereda de CharacterData y representa el contenido textual (denominado datos de caracteres en XML) de un Element o Attr. |
| [TypeInfo](./typeinfo/) | El TypeInfo representa un tipo referenciado desde nodos Element o Attr, especificado en los esquemas asociados al documento. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Un contexto de navegación es un entorno en el que los objetos [`Document`](../com.aspose.html.dom/document/) se presentan al usuario. |
| [IChildNode](./ichildnode/) | Define la interfaz [`IChildNode`](../com.aspose.html.dom/ichildnode/) que debe ser implementada por [`Node`](../com.aspose.html.dom/node/) que pueda tener un padre. |
| [IDOMImplementation](./idomimplementation/) | La interfaz DOMImplementation proporciona una serie de métodos para realizar operaciones que son independientes de cualquier instancia particular del modelo de objetos del documento. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Representa una interfaz que debe ser heredada por todo elemento que admite el manejo de eventos del sistema. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Define [`IChildNode`](../com.aspose.html.dom/ichildnode/) que no son [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | Define [`IParentNode`](../com.aspose.html.dom/iparentnode/) que no son del tipo Element. |
| [IParentNode](./iparentnode/) | Define la interfaz [`IParentNode`](../com.aspose.html.dom/iparentnode/) que es implementada por cualquier posible padre. |
| [IStorage](./istorage/) | Esta interfaz de la API Web Storage proporciona acceso al almacenamiento de sesión o local de un dominio particular. Vea la especificación de Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Modos en los que ShadowRoot puede operar. |

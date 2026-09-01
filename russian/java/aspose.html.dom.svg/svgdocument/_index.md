---
title: "Класс SVGDocument"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.svg.SVGDocument класс. SVGDocument является корнем иерархии SVG и содержит всё содержимое. Помимо предоставления доступа к иерархии, он также предлагает удобные методы для получения определённых наборов информации из документа. Когда элемент svg встроен inline как компонент документа из другого пакета, например когда элемент svg встроен в документ XHTML, объект SVGDocument не будет существовать; вместо него корневым объектом в иерархии объектов документа будет объект Document другого типа, например HTMLDocument. Тем не менее объект SVGDocument действительно существует, когда корневым элементом иерархии XML‑документа является элемент svg, как при просмотре отдельного SVG‑файла, т.е. файла с MIME‑типом image/svg+xml. В этом случае объект SVGDocument будет корневым объектом иерархии модели объектов документа."
type: docs

url: /ru/java/com.aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

`SVGDocument` является корнем иерархии SVG и содержит всё содержимое. Помимо предоставления доступа к иерархии, он также предоставляет некоторые удобные методы для получения определённых наборов информации из документа. Когда элемент ‘svg’ встроен непосредственно как компонент документа из другого пакета, например, когда элемент ‘svg’ встроен в документ XHTML [XHTML], объект `SVGDocument` не будет существовать; вместо этого корневым объектом в иерархии объектов документа будет объект Document другого типа, например объект HTMLDocument. Тем не менее объект `SVGDocument` действительно существует, когда корневым элементом иерархии XML‑документа является элемент ‘svg’, например при просмотре отдельного SVG‑файла (т.е. файла с MIME‑типом "image/svg+xml"). В этом случае объект `SVGDocument` будет корневым объектом иерархии модели объектов документа.

```java
public class SVGDocument : Document, IDocumentCSS
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | Инициализирует новый экземпляр класса `SVGDocument`. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | Инициализирует новый экземпляр класса `SVGDocument`. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_10)(String) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_4)(Url) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_8)(Stream, String) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). Загрузка документа начинается с текущей позиции в потоке. |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). Загрузка документа начинается с текущей позиции в потоке. |
| [SVGDocument](svgdocument/#constructor_11)(String, Configuration) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_14)(String, String) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_12)(String, Url) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_9)(Stream, String, Configuration) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). Загрузка документа начинается с текущей позиции в потоке. |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). Загрузка документа начинается с текущей позиции в потоке. |
| [SVGDocument](svgdocument/#constructor_15)(String, String, Configuration) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_13)(String, Url, Configuration) | Инициализирует новый экземпляр класса `SVGDocument`. Конструктор работает синхронно, ожидая загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../com.aspose.html.dom/document/navigate/) или его перегрузки. Либо можно отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |

## Свойства

| Имя | Описание |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) Абсолютный базовый URI этого узла или null, если реализация не смогла получить абсолютный URI. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Получает кодировку документа. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Получает кодировку документа. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Возвращает текущее количество узлов‑элементов, являющихся дочерними для данного элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Свойство childNodes только для чтения интерфейса Node возвращает живой [`NodeList`](../../com.aspose.html.collections/nodelist/) дочерних узлов данного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [getChildren](../../com.aspose.html.dom/document/children/) Возвращает дочерние элементы. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Получает тип содержимого документа. |
| [getContext](../../com.aspose.html.dom/document/context/) Получает текущий контекст просмотра. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Атрибут IDL defaultView интерфейса Document при получении должен возвращать объект WindowProxy контекста просмотра этого Document, если у Document есть связанный контекст просмотра, иначе null. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) Объявление типа документа, связанное с этим документом. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Это удобный атрибут, позволяющий напрямую получить дочерний узел, являющийся элементом документа. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) Расположение документа или null, если оно не определено или если Document был создан с помощью DOMImplementation.createDocument. |
| [getDomain](../../com.aspose.html.dom.svg/svgdocument/domain/) Доменное имя сервера, предоставившего документ, или строка null, если сервер нельзя определить по доменному имени. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство firstChild только для чтения интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает первый дочерний узел в дереве, или null, если у узла нет детей. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Возвращает первый дочерний элемент этого узла. null, если у элемента нет дочерних элементов. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) Объект DOMImplementation, обрабатывающий этот документ. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Получает кодировку документа. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство lastChild только для чтения интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Возвращает последний дочерний элемент этого узла. null, если у элемента нет дочерних элементов. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) и [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) и узлов, созданных методом уровня DOM 1, таким как [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), всегда возвращается null. |
| [getLocation](../../com.aspose.html.dom/document/location/) Расположение документа. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Свойство только для чтения Element.packageURI возвращает URI пакета элемента или null, если элемент не находится в пакете. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Возвращает следующий соседний элемент этого узла. null, если у элемента нет соседних элементов, идущих после него в дереве документа. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Только для чтения свойство nextSibling интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](../../com.aspose.html.dom/node/childnodes/) его родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Имя этого узла в зависимости от его типа. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Свойство nodeValue интерфейса [`Node `](../../com.aspose.html.dom/node/) возвращает или задаёт значение текущего узла. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Получает происхождение документа. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Получает владелец документа. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Только для чтения свойство parentElement интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает родительский [`Element`](../../com.aspose.html.dom/element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родительский узел указанного узла в дереве DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Свойство только для чтения prefix возвращает префикс пакета указанного элемента или null, если префикс не указан. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Возвращает предыдущий соседний элемент этого узла. null, если у элемента нет соседних элементов, предшествующих ему в дереве документа. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Только для чтения свойство previousSibling интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает узел, непосредственно предшествующий указанному в списке [`childNodes`](../../com.aspose.html.dom/node/firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Возвращает готовность документа. "loading" — пока документ загружается, "interactive" — после завершения парсинга, но пока загружаются подресурсы, и "complete" — после полной загрузки. |
| [getReferrer](../../com.aspose.html.dom.svg/svgdocument/referrer/) Возвращает URI страницы, которая привела к этой странице. Значение — пустая строка, если пользователь перешёл на страницу напрямую (не по ссылке, а, например, через закладку). |
| [getRootElement](../../com.aspose.html.dom.svg/svgdocument/rootelement/) Корневой ‘svg’ в иерархии документа. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Список, содержащий все таблицы стилей, явно связанные или встроенные в документ. Для HTML‑документов это включает внешние таблицы стилей, подключённые через элемент HTML LINK, и встроенные элементы STYLE. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Свойство textContent интерфейса [`Node`](../../com.aspose.html.dom/node/) представляет текстовое содержимое узла и его потомков. |
| [getTitle](../../com.aspose.html.dom.svg/svgdocument/title/) Заголовок документа, указанный в подэлементе ‘title’ корневого элемента ‘svg’ (например, Здесь заголовок...) |
| [getURL](../../com.aspose.html.dom.svg/svgdocument/url/) Полный URI документа. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../../com.aspose.html.dom/eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних узлов указанного родительского узла. Если переданный дочерний узел является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Метод Document.createAttribute() создаёт новый узел‑атрибут и возвращает его. Созданный объект представляет узел, реализующий интерфейс [`Attr`](../../com.aspose.html.dom/attr/). DOM не накладывает ограничений на типы атрибутов, которые можно добавить к конкретному элементу таким способом. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Метод Document.createAttribute() создаёт новый узел‑атрибут и возвращает его. Созданный объект представляет узел, реализующий [Attr](T:com.aspose.html.dom.Attr) интерфейс. DOM не накладывает ограничений на типы атрибутов, которые можно добавить к конкретному элементу таким способом. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Создаёт узел [`CDATASection`](../../com.aspose.html.dom/cdatasection/) со значением, равным указанной строке. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Создаёт узел [`Comment`](../../com.aspose.html.dom/comment/) из указанной строки. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Создаёт новый пустой [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), в который можно добавлять узлы DOM для построения внешнего дерева DOM. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Метод возвращает объект [`DocumentType`](../../com.aspose.html.dom/documenttype/), который можно использовать с DOMImplementation.createDocument при создании документа или вставить в документ с помощью методов, таких как Node.insertBefore() или Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | В HTML‑документе метод document.createElement() создаёт HTML‑элемент, указанный в tagName, или [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/), если tagName не распознан. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Создаёт элемент с указанным квалифицированным именем и URI пакета. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Создаёт объект EntityReference. Кроме того, если ссылка на сущность известна, список дочерних узлов узла EntityReference будет таким же, как у соответствующего узла Entity. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Создаёт [`Event`](../../com.aspose.html.dom.events/event/) указанного типа, поддерживаемого реализацией. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Создаёт разобранное XPath‑выражение с разрешёнными пакетами. Это полезно, когда выражение будет переиспользоваться в приложении, так как позволяет скомпилировать строку выражения во более эффективную внутреннюю форму и предварительно разрешить все префиксы пакетов, встречающиеся в выражении. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | Создайте новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | Создайте новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Создайте новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Адаптирует любой узел DOM для разрешения пакетов, чтобы XPath‑выражение можно было легко оценить относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 `lookupNamespaceURI` у узлов, разрешая packageURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Создаёт узел ProcessingInstruction с указанными строками имени и данных. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Создаёт узел Text из указанной строки. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | Создайте новый TreeWalker для поддерева, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | Создайте новый TreeWalker для поддерева, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Создайте новый TreeWalker для поддерева, корнем которого является указанный узел. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListener в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Выполняет оценку строки XPath‑выражения и, при возможности, возвращает результат указанного типа. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Метод Document getElementById() возвращает объект [`Element`](../../com.aspose.html.dom/element/), представляющий элемент, у которого свойство id совпадает с указанной строкой. Поскольку идентификаторы элементов должны быть уникальными, если они заданы, это удобный способ быстро получить доступ к конкретному элементу. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Метод getElementsByClassName интерфейса [`Document`](../../com.aspose.html.dom/document/) возвращает объект, похожий на массив, со всеми дочерними элементами, имеющими все указанные имена классов. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Метод getElementsByTagName интерфейса [`Document`](../../com.aspose.html.dom/document/) возвращает [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) элементов с указанным именем тега. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Возвращает список элементов с указанным именем тега, принадлежащих заданному пакету. Поиск производится по всему документу, включая корневой узел. |
| [getOverrideStyle](../../com.aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, String) | Этот метод используется для получения объявления переопределяющего стиля для указанного элемента и указанного псевдо‑элемента. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный [`Node`](../../com.aspose.html.dom/node/) дочерние узлы. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Импортирует узел из другого документа в текущий, не изменяя и не удаляя исходный узел из оригинального документа; этот метод создаёт новую копию исходного узла. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед ссылочным узлом в качестве дочернего элемента указанного родительского узла. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса [`Node`](../../com.aspose.html.dom/node/) проверяет, равны ли два узла. Два узла считаются равными, если они имеют один и тот же тип, определяющие характеристики (для элементов это их ID, количество дочерних узлов и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, который должен совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (иначе говоря, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним в данном узле, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для заданного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | Загружает документ на основе указанного объекта запроса, заменяя предыдущее содержимое. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | Загружает документ по указанному Унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | Загружает документ по указанному Унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Помещает все узлы [`Text`](../../com.aspose.html.dom/text/) на полной глубине поддерева под этим Node, включая узлы атрибутов, в «нормальную» форму, где только структура (например, [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), и [`entity references`](../../com.aspose.html.dom/entityreference/)) отделяет узлы [`Text`](../../com.aspose.html.dom/text/), т.е. нет соседних узлов Text и пустых узлов Text. Это можно использовать, чтобы гарантировать, что представление DOM документа совпадает с тем, как оно выглядело бы после сохранения и повторной загрузки, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта [`DOMConfiguration`](../../com.aspose.html/configuration/), привязанного к [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/), имеет значение true, этот метод также полностью нормализует символы узлов Text. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Возвращает первый элемент в документе, который соответствует селектору |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Возвращает NodeList всех элементов в документе, которые соответствуют селектору |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [renderTo](../../com.aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | Этот метод используется для печати содержимого текущего документа на указанное устройство. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild заменяется всеми дочерними элементами [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save)(ResourceHandler) | Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_6)(String) | Сохраняет документ в локальный файл, указанный `path`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | Сохраняет документ в локальный файл, указанный `url`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_1)(ResourceHandler, SVGSaveFormat) | Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_2)(ResourceHandler, SVGSaveOptions) | Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_7)(String, SVGSaveFormat) | Сохраняет документ в локальный файл, указанный `path`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_8)(String, SVGSaveOptions) | Сохраняет документ в локальный файл, указанный `path`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | Сохраняет документ в локальный файл, указанный `url`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | Сохраняет документ в локальный файл, указанный `url`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [toString](../../com.aspose.html.dom/node/toString/)() | Возвращает строку, представляющую этот экземпляр. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Записывает строку текста в поток документа, открытый методом open(). Обратите внимание, что функция может создать документ, который не обязательно управляется DTD, и поэтому может привести к неверному результату в контексте документа. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Записывает строку текста, за которой следует символ новой строки, в поток документа, открытый методом open(). Обратите внимание, что функция может создать документ, который не обязательно управляется DTD, и поэтому может привести к неверному результату в контексте документа. |

## События

| Имя | Описание |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Получает или задает обработчик события для события OnAbort. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Получает или задает обработчик события для события OnBlur. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Получает или задает обработчик события для события OnCancel. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Получает или задает обработчик события для события OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Получает или задает обработчик события для события OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Получает или задает обработчик события для события OnChange. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Получает или задает обработчик события для события OnClick. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Получает или задает обработчик события для события OnCueChange. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Получает или задает обработчик события для события OnDblClick. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Получает или задает обработчик события для события OnDurationChange. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Получает или задает обработчик события для события OnEmptied. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Получает или задает обработчик события для события OnEnded. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Получает или задает обработчик события для события OnError. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Получает или задает обработчик события для события OnFocus. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Получает или задает обработчик события для события OnInput. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Получает или задает обработчик события для события OnInvalid. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Получает или задает обработчик события для события OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Получает или задает обработчик события для события OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Получает или задает обработчик события для события OnKeyUp. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Получает или задает обработчик события для события OnLoad. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Получает или задает обработчик события для события OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Получает или задает обработчик события для события OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Получает или задает обработчик события для события OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Получает или задает обработчик события для события OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Получает или задает обработчик события для события OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Получает или задает обработчик события для события OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Получает или задает обработчик события для события OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Получает или задает обработчик события для события OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Получает или задает обработчик события для события OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Получает или задает обработчик события для события OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Получает или задает обработчик события для события OnMouseWheel. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Получает или задает обработчик события для события OnPause. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Получает или задает обработчик события для события OnPlay. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Получает или задает обработчик события для события OnPlaying. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Получает или задает обработчик события для события OnProgress. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Получает или задает обработчик события для события OnRateChange. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Получает или задает обработчик события для события OnReadyStateChange. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Получает или задает обработчик события для события OnReset. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Получает или задает обработчик события для события OnResize. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Получает или задает обработчик события для события OnScroll. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Получает или задает обработчик события для события OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Получает или задает обработчик события для события OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Получает или задает обработчик события для события OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Получает или задает обработчик события для события OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Получает или задает обработчик события для события OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Получает или задает обработчик события для события OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Получает или задает обработчик события для события OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Получает или задает обработчик события для события OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Получает или задает обработчик события для события OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Получает или задает обработчик события для события OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Получает или задает обработчик события для события OnWaiting. |

### См. также

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)

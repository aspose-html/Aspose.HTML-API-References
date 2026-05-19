---
title: "Класс HTMLDocument"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.HTMLDocument. Представляет HTML‑документ. Все HTML‑объекты верхнего уровня добавляются в этот объект. Этот класс представляет HTML‑страницу так, как мы видим её в браузере. Все формы, таблицы, скрипты ... добавляются на HTML‑страницу через интерфейсы этого класса. HTMLDocument — это HTML‑реализация наиболее общего интерфейса Document, и оба являются ядром или корневой точкой DOM — Document Object Model. Эти концепции полностью соответствуют официальным основам и стандартам веб‑разработки. Для целей веб‑разработки вы обычно можете рассматривать HTMLDocument как псевдоним Document, на котором основан HTMLDocument."
type: docs

url: /ru/java/com.aspose.html/htmldocument/
---
## HTMLDocument class

Представляет HTML‑документ. Все объекты HTML верхнего уровня добавляются в этот объект. Этот класс представляет HTML‑страницу так, как мы видим её в браузере. Все формы, таблицы, скрипты и т.д. добавляются на HTML‑страницу через интерфейсы этого класса. [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) — реализация HTML наиболее общего интерфейса [Document](https://dom.spec.whatwg.org/#document); оба являются ядром или корневой точкой [DOM](https://dom.spec.whatwg.org/) - модели объектного документа. Эти концепции полностью соответствуют официальным основам и стандартам веб‑разработки. Для целей веб‑разработки вы, как правило, можете рассматривать HTMLDocument как синоним Document, на котором основан HTMLDocument.

```java
public class HTMLDocument : Document, IDocumentCSS
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | Конструктор HTMLDocument создает новый объект HTML Document, представляющий веб‑страницу, загруженную в браузере, и служащий точкой входа в содержимое страницы. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | Конструктор HTMLDocument создает новый объект HTML Document, представляющий веб‑страницу, загруженную в браузере, и служащий точкой входа в содержимое страницы. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | Создаёт HTML‑документ из объекта [`RequestMessage`](../../com.aspose.html.net/requestmessage/). |
| [HTMLDocument](htmldocument/#constructor_10)(String) | Загружает HTML‑документ по адресу. |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | Загружает HTML‑документ из URL. |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | Создаёт HTML‑документ из объекта [RequestMessage](T:com.aspose.html.net.RequestMessage). |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, String) | Создаёт HTML‑документ из содержимого [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) с указанным базовым URI, который используется для разрешения путей относительных ресурсов. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | Создаёт HTML‑документ из содержимого [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) с указанным базовым URI, который используется для разрешения путей относительных ресурсов. |
| [HTMLDocument](htmldocument/#constructor_11)(String, Configuration) | Загружает HTML‑документ по адресу с указанными настройками конфигурации среды. |
| [HTMLDocument](htmldocument/#constructor_14)(String, String) | Создаёт HTML‑документ из строкового содержимого с указанным базовым URI. |
| [HTMLDocument](htmldocument/#constructor_12)(String, Url) | Создаёт HTML‑документ из строкового содержимого с указанным базовым URI. |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | Загружает HTML‑документ из URL с указанными настройками конфигурации среды. |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, String, Configuration) | Создаёт HTML‑документ из содержимого [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) с указанным базовым URI и настройками конфигурации среды. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | Создаёт HTML‑документ из содержимого [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) с указанным базовым URI и настройками конфигурации среды. |
| [HTMLDocument](htmldocument/#constructor_15)(String, String, Configuration) | Создаёт HTML‑документ из строкового содержимого с указанным базовым URI и настройками конфигурации среды. |
| [HTMLDocument](htmldocument/#constructor_13)(String, Url, Configuration) | Создаёт HTML‑документ из строкового содержимого с указанным базовым URI и настройками конфигурации среды. |

## Свойства

| Имя | Описание |
| --- | --- |
| [getAnchors](../../com.aspose.html/htmldocument/anchors/) Коллекция всех элементов‑якорей (`A`) в документе, имеющих значение атрибута `name`. По причинам обратной совместимости возвращённый набор якорей содержит только те, которые созданы с атрибутом `name`, а не с атрибутом `id`. Обратите внимание, что в [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)] атрибут `name` (см. раздел 4.10) не имеет семантики и присутствует только для устаревших пользовательских агентов: вместо него используется атрибут `id`. Пользователям рекомендуется использовать механизмы итерации, предоставляемые [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)]. |
| [getApplets](../../com.aspose.html/htmldocument/applets/) Коллекция всех элементов `OBJECT`, содержащих апплеты и элементы `APPLET` (устаревшие) в документе. |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) Абсолютный базовый URI этого узла или null, если реализация не смогла получить абсолютный URI. |
[getBody]
[setBody] The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Получает кодировку документа. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Получает кодировку документа. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Возвращает текущее количество узлов‑элементов, являющихся дочерними для этого элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Свойство childNodes только для чтения интерфейса Node возвращает живой [`NodeList`](../../com.aspose.html.collections/nodelist/) дочерних узлов данного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [getChildren](../../com.aspose.html.dom/document/children/) Возвращает дочерние элементы. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Получает тип содержимого документа. |
| [getContext](../../com.aspose.html.dom/document/context/) Получает текущий контекст просмотра. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) IDL-атрибут defaultView интерфейса Document, при получении, должен возвращать объект WindowProxy контекста просмотра этого Document, если у этого Document есть связанный контекст просмотра, иначе null. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) Объявление типа документа (Document Type Declaration), связанное с этим документом. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Это удобный атрибут, позволяющий прямой доступ к дочернему узлу, являющемуся элементом документа. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) Местоположение документа или null, если неопределено или если Document был создан с помощью DOMImplementation.createDocument. |
| [getDomain](../../com.aspose.html/htmldocument/domain/) Имя домена сервера, который предоставил документ, или `null`, если сервер нельзя определить по имени домена. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство firstChild только для чтения интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает первый дочерний узел в дереве, или null, если у узла нет дочерних элементов. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Возвращает первый дочерний элемент этого узла. null, если у этого узла нет дочерних элементов. |
| [getForms](../../com.aspose.html/htmldocument/forms/) Коллекция всех форм документа. |
| [getImages](../../com.aspose.html/htmldocument/images/) Коллекция всех элементов `IMG` в документе. Поведение ограничено элементами `IMG` для обратной совместимости. Как предлагается в [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], для включения изображений авторы могут использовать элемент `OBJECT` или элемент `IMG`. Поэтому рекомендуется не использовать этот атрибут для поиска изображений в документе, а применять `getElementsByTagName` с HTML 4.01 или `getElementsByTagNameNS` с XHTML 1.0. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) Объект DOMImplementation, обрабатывающий этот документ. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Получает кодировку документа. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство lastChild только для чтения интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Возвращает последний дочерний элемент этого узла. null, если у этого узла нет дочерних элементов. |
| [getLinks](../../com.aspose.html/htmldocument/links/) Коллекция всех элементов `AREA` и якорей (`A`) в документе, имеющих значение атрибута `href`. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) и [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) и узлов, созданных методом уровня DOM 1, например [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), всегда возвращает null. |
| [getLocation](../../com.aspose.html.dom/document/location/) Местоположение документа. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Только для чтения свойство Element.packageURI возвращает URI пакета элемента, или null, если элемент не находится в пакете. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Возвращает следующий соседний элемент этого узла. null, если у этого узла нет последующих соседних элементов в дереве документа. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Только для чтения свойство nextSibling интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](../../com.aspose.html.dom/node/childnodes/) его родителя, или возвращает null, если указанный узел является последним дочерним в родительском элементе. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Имя этого узла, в зависимости от его типа. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Свойство nodeValue интерфейса [`Node `](../../com.aspose.html.dom/node/) возвращает или задаёт значение текущего узла. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Получает происхождение (origin) документа. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Получает документ‑владелец. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Только для чтения свойство parentElement интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает родительский [`Element`](../../com.aspose.html.dom/element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является DOM‑элементом. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родителя указанного узла в дереве DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Только для чтения свойство prefix возвращает префикс пакета указанного элемента, или null, если префикс не указан. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Возвращает предыдущий соседний элемент этого узла. null, если у этого узла нет предшествующих соседних элементов в дереве документа. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Только для чтения свойство previousSibling интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает узел, непосредственно предшествующий указанному в списке [`childNodes`](../../com.aspose.html.dom/node/firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Возвращает готовность документа. "loading" — пока документ загружается, "interactive" — после завершения разбора, но пока подзагружаются ресурсы, и "complete" — после полной загрузки. |
| [getReferrer](../../com.aspose.html/htmldocument/referrer/) Возвращает URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] страницы, которая ссылалась на эту страницу. Значение является пустой строкой, если пользователь перешёл на страницу напрямую (не через ссылку, а, например, через закладку). |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Список, содержащий все таблицы стилей, явно связанные или встроенные в документ. Для HTML‑документов это включает внешние таблицы стилей, включённые через элемент HTML LINK, и встроенные элементы STYLE. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Свойство textContent интерфейса [`Node`](../../com.aspose.html.dom/node/) представляет текстовое содержимое узла и его потомков. |
[getTitle]
[setTitle] The title of a document as specified by the `TITLE` element in the head of the document. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../../com.aspose.html.dom/eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних элементов указанного родительского узла. Если переданный дочерний элемент является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Метод Document.createAttribute() создаёт новый узел атрибута и возвращает его. Созданный объект представляет узел, реализующий интерфейс [`Attr`](../../com.aspose.html.dom/attr/). DOM не ограничивает, какие типы атрибутов могут быть добавлены к конкретному элементу таким способом. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Метод Document.createAttribute() создаёт новый узел атрибута и возвращает его. Созданный объект представляет узел, реализующий [Attr](T:com.aspose.html.dom.Attr) интерфейс. DOM не ограничивает, какие типы атрибутов могут быть добавлены к конкретному элементу таким способом. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Создаёт узел [`CDATASection`](../../com.aspose.html.dom/cdatasection/) со значением, равным указанной строке. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Создаёт узел [`Comment`](../../com.aspose.html.dom/comment/) по указанной строке. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Создаёт новый пустой [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), в который можно добавлять узлы DOM для построения offscreen‑дерева DOM. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Метод возвращает объект [`DocumentType`](../../com.aspose.html.dom/documenttype/), который может быть использован с DOMImplementation.createDocument при создании документа или помещён в документ с помощью методов, таких как Node.insertBefore() или Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | В HTML‑документе метод document.createElement() создаёт HTML‑элемент, указанный в tagName, или [`HTMLUnknownElement`](../htmlunknownelement/), если tagName не распознан. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Создаёт элемент с заданным квалифицированным именем и URI пакета. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Создаёт объект EntityReference. Кроме того, если ссылка на сущность известна, список дочерних узлов узла EntityReference будет таким же, как у соответствующего узла Entity. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Создаёт [`Event`](../../com.aspose.html.dom.events/event/) типа, поддерживаемого реализацией. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Создаёт разобранное XPath‑выражение с разрешёнными пакетами. Это полезно, когда выражение будет переиспользоваться в приложении, так как позволяет компилировать строку выражения во более эффективную внутреннюю форму и предварительно разрешать все префиксы пакетов, встречающиеся в выражении. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | Создайте новый NodeIterator над поддеревом, корнем которого является указанный узел. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | Создайте новый NodeIterator над поддеревом, корнем которого является указанный узел. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Создайте новый NodeIterator над поддеревом, корнем которого является указанный узел. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Адаптирует любой узел DOM для разрешения пакетов, чтобы XPath‑выражение можно было легко оценить относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 `lookupNamespaceURI` у узлов, разрешая packageURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Создаёт узел ProcessingInstruction по указанным строкам имени и данных. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Создаёт узел Text по указанной строке. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет определённые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Выполняет оценку строки XPath‑выражения и, при возможности, возвращает результат указанного типа. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Метод Document getElementById() возвращает объект [`Element`](../../com.aspose.html.dom/element/), представляющий элемент, у которого свойство id совпадает с указанной строкой. Поскольку идентификаторы элементов должны быть уникальными, если они заданы, они являются удобным способом быстро получить доступ к конкретному элементу. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Метод getElementsByClassName интерфейса [`Document`](../../com.aspose.html.dom/document/) возвращает объект, похожий на массив, всех дочерних элементов, имеющих все указанные имена классов. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Метод getElementsByTagName интерфейса [`Document`](../../com.aspose.html.dom/document/) возвращает [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) элементов с указанным именем тега. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Возвращает список элементов с указанным именем тега, принадлежащих заданному пакету. Поиск производится по всему документу, включая корневой узел. |
| [getOverrideStyle](../../com.aspose.html/htmldocument/getoverridestyle/)(Element, String) | Этот метод используется для получения объявления переопределяющего стиля для указанного элемента и указанного псевдоэлемента. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный [`Node`](../../com.aspose.html.dom/node/) дочерние узлы. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Импортирует узел из другого документа в текущий документ, не изменяя и не удаляя исходный узел из оригинального документа; этот метод создаёт новую копию исходного узла. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед опорным узлом в качестве дочернего элемента указанного родительского узла. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса [`Node`](../../com.aspose.html.dom/node/) проверяет, равны ли два узла. Два узла считаются равными, если они имеют один и тот же тип, определяющие характеристики (для элементов это их ID, количество дочерних элементов и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, которые должны совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (другими словами, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним у данного узла, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для данного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | Загружает документ на основе указанного объекта запроса, заменяя предыдущее содержимое. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | Загружает документ по указанному универсальному указателю ресурса (URL) в текущий экземпляр, заменяя прежнее содержимое. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | Загружает документ по указанному универсальному указателю ресурса (URL) в текущий экземпляр, заменяя прежнее содержимое. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя прежнее содержимое. Загрузка документа начинается с текущей позиции в потоке. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя прежнее содержимое. Загрузка документа начинается с текущей позиции в потоке. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя прежнее содержимое. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя прежнее содержимое. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Помещает все узлы [`Text`](../../com.aspose.html.dom/text/) в полной глубине поддерева под этим Узлом, включая узлы атрибутов, в "нормальную" форму, где только структура (например, [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), и [`entity references`](../../com.aspose.html.dom/entityreference/)) разделяет узлы [`Text`](../../com.aspose.html.dom/text/), т.е. нет соседних узлов Text и пустых узлов Text. Это можно использовать, чтобы гарантировать, что представление DOM документа такое же, как если бы он был сохранён и загружен заново, и полезно, когда операции (например, поиск XPointer [XPointer] ) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта [`DOMConfiguration`](../configuration/) , привязанного к [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/), имеет значение true, этот метод также полностью нормализует символы узлов Text. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Возвращает первый элемент в документе, который соответствует селектору |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Возвращает NodeList всех элементов в документе, которые соответствуют селектору |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [renderTo](../../com.aspose.html/htmldocument/renderto/)(IDevice) | Этот метод используется для печати содержимого текущего документа на указанное устройство. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild на newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild заменяется всеми дочерними узлами [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [save](../../com.aspose.html/htmldocument/save/#save)(ResourceHandler) | Сохраняет содержимое документа и ресурсы с использованием [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_10)(String) | Сохраняет документ в локальный файл, указанный путём. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_5)(Url) | Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_1)(ResourceHandler, HTMLSaveFormat) | Сохраняет содержимое документа и ресурсы с использованием [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_2)(ResourceHandler, HTMLSaveOptions) | Сохраняет содержимое документа и ресурсы с использованием [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_3)(ResourceHandler, MarkdownSaveOptions) | Сохраняет содержимое документа и ресурсы с использованием [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_4)(ResourceHandler, MHTMLSaveOptions) | Сохраняет содержимое документа и ресурсы с использованием [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_11)(String, HTMLSaveFormat) | Сохраняет документ в локальный файл, указанный путем. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_12)(String, HTMLSaveOptions) | Сохраняет документ в локальный файл, указанный путём. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_13)(String, MarkdownSaveOptions) | Сохраняет документ в локальный файл, указанный путём. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_14)(String, MHTMLSaveOptions) | Сохраняет документ в локальный файл, указанный путём. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\". |
| [toString](../../com.aspose.html.dom/node/toString/)() | Возвращает строку, представляющую этот экземпляр. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Записывает строку текста в поток документа, открытый методом open(). Обратите внимание, что функция создаст документ, который не обязательно управляется DTD, и поэтому может дать недопустимый результат в контексте документа. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Записывает строку текста, за которой следует символ новой строки, в поток документа, открытый методом open(). Обратите внимание, что функция создаст документ, который не обязательно управляется DTD, и поэтому может дать недопустимый результат в контексте документа. |

## События

| Имя | Описание |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Получает или задает обработчик события OnAbort. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Получает или задает обработчик события OnBlur. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Получает или задает обработчик события OnCancel. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Получает или задает обработчик события OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Получает или задает обработчик события OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Получает или задает обработчик события OnChange. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Получает или задает обработчик события OnClick. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Получает или задает обработчик события OnCueChange. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Получает или задает обработчик события OnDblClick. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Получает или задает обработчик события OnDurationChange. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Получает или задает обработчик события OnEmptied. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Получает или задает обработчик события OnEnded. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Получает или задает обработчик события OnError. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Получает или задает обработчик события OnFocus. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Получает или задает обработчик события OnInput. |
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
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Получает или задает обработчик события OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Получает или задает обработчик события OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Получает или задает обработчик события OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Получает или задает обработчик события OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Получает или задает обработчик события OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Получает или задает обработчик события OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Получает или задает обработчик события OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Получает или задает обработчик события OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Получает или задает обработчик события OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Получает или задает обработчик события OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Получает или задает обработчик события OnWaiting. |

## Примечания

Больше информации о HTMLDocument, Document и DOM можно найти в популярных ресурсах веб‑разработки:

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

Ссылка на стандарты:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
    // Создайте экземпляр HTML‑документа
	using (var document = new HTMLDocument())
      {
        // Создайте элемент style и задайте зелёный цвет для всех элементов с class-name, равным 'gr'.
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // Найдите элемент заголовка документа и добавьте в него элемент style
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // Создайте элемент абзаца с class-name 'gr'.
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // Создайте текстовый узел
        var text = document.CreateTextNode("Hello World!!");

        // Добавьте текстовый узел к абзацу
        p.AppendChild(text);

        // Добавьте абзац к элементу body документа
        document.Body.AppendChild(p);

        // Сохраните HTML‑документ в файл 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // Создайте экземпляр устройства вывода PDF и отрендерите документ в этом устройстве
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // Преобразовать HTML в PDF
          document.RenderTo(device);
        }
      }       
```

### См. также

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

---
title: "Класс Node"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.Node. Интерфейс Node является основным типом данных для всей модели объектного документа (Document Object Model). Он представляет отдельный узел в дереве документа. Хотя все объекты, реализующие интерфейс Node, предоставляют методы для работы с дочерними элементами, не все такие объекты могут иметь дочерние элементы. Например, текстовые узлы (Text) могут не иметь дочерних элементов, и попытка добавить дочерние элементы к таким узлам приводит к возникновению DOMException."
type: docs

url: /ru/java/com.aspose.html.dom/node/
---
## Node class

Интерфейс Node является основным типом данных для всей модели объектного документа (Document Object Model). Он представляет один узел в дереве документа. Хотя все объекты, реализующие интерфейс Node, предоставляют методы для работы с дочерними элементами, не у всех таких объектов могут быть дочерние элементы. Например, узлы [`Text`](../text/) могут не иметь дочерних элементов, и попытка добавить дочерние элементы к таким узлам приводит к возникновению [`DOMException`](../domexception/).

Атрибуты [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) и атрибуты включены как механизм получения информации об узле без приведения к конкретному производному интерфейсу. В случаях, когда нет очевидного соответствия этих атрибутов для конкретного [`nodeType`](./nodetype/) (например, nodeValue для [`Element`](../element/) или атрибуты для [`Comment`](../comment/)), возвращается null. Обратите внимание, что специализированные интерфейсы могут содержать дополнительные и более удобные механизмы получения и установки соответствующей информации.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Свойство baseURI только для чтения интерфейса Node возвращает абсолютный базовый URL документа, содержащего узел. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Свойство childNodes только для чтения интерфейса Node возвращает живой [`NodeList`](../../com.aspose.html.collections/nodelist/) дочерних узлов данного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство только для чтения firstChild интерфейса `Node` возвращает первый дочерний узел в дереве, или null, если у узла нет дочерних элементов. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство только для чтения lastChild интерфейса `Node` возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если дочерних элементов нет. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме [`ELEMENT_NODE`](./element_node/) и [`ATTRIBUTE_NODE`](./attribute_node/), а также узлов, созданных методом уровня DOM 1, например [`Document.createElement()`](../document/createelement/), всегда возвращается null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Только для чтения свойство Element.packageURI возвращает URI пакета элемента, или null, если элемент не находится в пакете. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Свойство только для чтения nextSibling интерфейса `Node` возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](./childnodes/) его родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Свойство только для чтения nodeName интерфейса Node возвращает имя текущего узла как строку. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Свойство nodeValue интерфейса `Node` возвращает или задает значение текущего узла. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Только для чтения свойство ownerDocument интерфейса Node возвращает объект верхнего уровня документа узла. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Свойство только для чтения parentElement интерфейса `Node` возвращает родительский [`Element`](../element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родителя указанного узла в дереве DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Только для чтения свойство prefix возвращает префикс пакета указанного элемента, или null, если префикс не указан. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Свойство только для чтения previousSibling интерфейса `Node` возвращает узел, непосредственно предшествующий указанному в массиве [`childNodes`](./firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Свойство textContent интерфейса `Node` представляет текстовое содержимое узла и его потомков. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних элементов указанного родительского узла. Если переданный дочерний элемент является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет определённые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный `Node` дочерние узлы. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед опорным узлом в качестве дочернего элемента указанного родительского узла. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса `Node` проверяет, равны ли два узла. Два узла считаются равными, если они имеют один тип, определяющие характеристики (для элементов это их ID, количество дочерних элементов и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, который должен совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (другими словами, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним у данного узла, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для данного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Помещает все узлы [`Text`](../text/) полной глубины поддерева под этим Node, включая узлы атрибутов, в «нормальную» форму, где только структура (например, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), и [`entity references`](../entityreference/)) разделяет узлы [`Text`](../text/), т.е. нет соседних Text‑узлов или пустых Text‑узлов. Это может использоваться для обеспечения того, что представление DOM документа совпадает с тем, как он был сохранён и повторно загружен, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от конкретной структуры дерева документа. Если параметр \"normalize-characters\" объекта [`DOMConfiguration`](../../com.aspose.html/configuration/), привязанного к [`Node.ownerDocument`](./ownerdocument/), установлен в true, этот метод также полностью нормализует символы Text‑узлов. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../documentfragment/), oldChild заменяется всеми дочерними узлами [`DocumentFragment`](../documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | Атрибут [`Attribute`](../attr/) элемента [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | Секция CDATA [`CDATASection`](../cdatasection/), например &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | Узел [`Comment`](../comment/), например &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | Узел [`DocumentFragment`](../documentfragment/). |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | Узел [`Document`](../document/). |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | Узел [`DocumentType`](../documenttype/), например &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | Элемент [`Element`](../element/) вроде &lt;p&gt; или &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | Узел [`Entity`](../entity/). |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | Узел [`EntityReference`](../entityreference/). |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | Узел [`Notation`](../notation/). |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | Объект [`ProcessingInstruction`](../processinginstruction/) XML‑документа, например &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | Фактический [`Text`](../text/) внутри [`Element`](../element/) или [`Attr`](../attr/). |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### См. также

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

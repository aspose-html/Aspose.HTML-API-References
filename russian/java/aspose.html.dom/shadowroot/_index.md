---
title: "Класс ShadowRoot"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.ShadowRoot. ShadowRoot — корневой узел теневого дерева."
type: docs

url: /ru/java/com.aspose.html.dom/shadowroot/
---
## ShadowRoot class

ShadowRoot является корневым узлом теневого дерева.

```java
public class ShadowRoot : DocumentFragment
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Свойство baseURI только для чтения интерфейса Node возвращает абсолютный базовый URL документа, содержащего узел. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) Возвращает текущее количество узлов‑элементов, являющихся дочерними для этого элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Свойство childNodes только для чтения интерфейса Node возвращает живой [`NodeList`](../../com.aspose.html.collections/nodelist/) дочерних узлов данного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) Возвращает дочерние элементы текущего элемента. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство только для чтения firstChild интерфейса [`Node`](../node/) возвращает первого дочернего узла в дереве, или null, если у узла нет дочерних элементов. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) Возвращает первый дочерний узел‑элемент этого элемента. null, если у этого элемента нет дочерних элементов. |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host — это элемент, содержащий данный ShadowRoot. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство только для чтения lastChild интерфейса [`Node`](../node/) возвращает последнего дочернего узла. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов. |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) Возвращает последний дочерний узел‑элемент этого элемента. null, если у этого элемента нет дочерних элементов. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме [`ELEMENT_NODE`](../node/element_node/) и [`ATTRIBUTE_NODE`](../node/attribute_node/) и узлов, созданных методом уровня DOM 1, например [`Document.createElement()`](../document/createelement/), это всегда null. |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) Режим, в котором работает данный ShadowRoot. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Только для чтения свойство Element.packageURI возвращает URI пакета элемента, или null, если элемент не находится в пакете. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) Возвращает следующий соседний элемент‑узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих после него в дереве документа. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Свойство только для чтения nextSibling интерфейса [`Node`](../node/) возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](../node/childnodes/) их родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) Имя этого узла, в зависимости от его типа. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Свойство nodeValue интерфейса [`Node `](../node/) возвращает или задает значение текущего узла. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Только для чтения свойство ownerDocument интерфейса Node возвращает объект верхнего уровня документа узла. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Свойство только для чтения parentElement интерфейса [`Node`](../node/) возвращает родительский [`Element`](../element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родителя указанного узла в дереве DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Только для чтения свойство prefix возвращает префикс пакета указанного элемента, или null, если префикс не указан. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) Возвращает предыдущий соседний элемент‑узел этого элемента. null, если у этого элемента нет соседних элементных узлов, предшествующих ему в дереве документа. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Свойство только для чтения previousSibling интерфейса [`Node`](../node/) возвращает узел, непосредственно предшествующий указанному в списке [`childNodes`](../node/firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Если он установлен в null, попытка изменить его не оказывает эффекта. При установке все возможные дочерние узлы удаляются, и если новая строка не пуста и не null, они заменяются одним текстовым узлом, содержащим эту строку. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних элементов указанного родительского узла. Если переданный дочерний элемент является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет определённые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный [`Node`](../node/) дочерние узлы. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед опорным узлом в качестве дочернего элемента указанного родительского узла. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса [`Node`](../node/) проверяет, равны ли два узла. Два узла считаются равными, если они имеют один и тот же тип, определяющие характеристики (для элементов это их ID, количество дочерних узлов и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, который должен совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (другими словами, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним у данного узла, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для данного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Помещает все узлы [`Text`](../text/) на полной глубине поддерева под этим Node, включая узлы атрибутов, в \"нормальную\" форму, где только структура (например, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/) и [`entity references`](../entityreference/)) разделяет узлы [`Text`](../text/), т.е. нет соседних узлов Text и пустых узлов Text. Это может использоваться для обеспечения того, чтобы представление DOM документа было таким же, как если бы документ был сохранён и заново загружен, и полезно, когда операции (например, XPointer [XPointer] lookups), зависящие от определённой структуры дерева документа, должны использоваться. Если параметр \"normalize-characters\" объекта [`DOMConfiguration`](../../com.aspose.html/configuration/), привязанного к [`Node.ownerDocument`](../node/ownerdocument/), установлен в true, этот метод также полностью нормализует символы узлов Text. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | Возвращает первый элемент в документе, который соответствует селектору |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | Возвращает NodeList всех элементов в документе, которые соответствуют селектору |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../documentfragment/), oldChild заменяется всеми дочерними узлами [`DocumentFragment`](../documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [DocumentFragment](../documentfragment/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

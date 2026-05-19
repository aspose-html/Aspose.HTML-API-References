---
title: "Класс Text"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.Text. Интерфейс Text наследуется от CharacterData и представляет текстовое содержимое, называемое символьными данными в XML элемента или атрибута."
type: docs

url: /ru/java/com.aspose.html.dom/text/
---
## Text class

Интерфейс Text наследуется от CharacterData и представляет текстовое содержимое (именуемое символьными данными в XML) элемента Element или атрибута Attr.

```java
public class Text : CharacterData
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Свойство baseURI только для чтения интерфейса Node возвращает абсолютный базовый URL документа, содержащего узел. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Свойство childNodes только для чтения интерфейса Node возвращает живой [`NodeList`](../../com.aspose.html.collections/nodelist/) дочерних узлов данного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | Символьные данные узла, реализующего этот интерфейс. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство только для чтения firstChild интерфейса [`Node`](../node/) возвращает первого дочернего узла в дереве, или null, если у узла нет дочерних элементов. |
| [getIsElementContentWhitespace](../../com.aspose.html.dom/text/iselementcontentwhitespace/) Возвращает, содержит ли данный текстовый узел пробельные символы содержимого элемента, часто ошибочно называемые «игнорируемыми пробелами». |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство только для чтения lastChild интерфейса [`Node`](../node/) возвращает последнего дочернего узла. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов. |
| [getLength](../../com.aspose.html.dom/characterdata/length/) Количество 16‑битных единиц, доступных через data и метод subStringData ниже. Может быть равно нулю, т.е. узлы CharacterData могут быть пустыми. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме [`ELEMENT_NODE`](../node/element_node/) и [`ATTRIBUTE_NODE`](../node/attribute_node/) и узлов, созданных методом уровня DOM 1, например [`Document.createElement()`](../document/createelement/), это всегда null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Только для чтения свойство Element.packageURI возвращает URI пакета элемента, или null, если элемент не находится в пакете. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Свойство только для чтения nextSibling интерфейса [`Node`](../node/) возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](../node/childnodes/) их родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| [getNodeName](../../com.aspose.html.dom/text/nodename/) Имя этого узла, в зависимости от его типа. |
| [getNodeType](../../com.aspose.html.dom/text/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/text/nodevalue/) { get; set; } | Значение этого узла, в зависимости от его типа. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Только для чтения свойство ownerDocument интерфейса Node возвращает объект верхнего уровня документа узла. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Свойство только для чтения parentElement интерфейса [`Node`](../node/) возвращает родительский [`Element`](../element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родителя указанного узла в дереве DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Только для чтения свойство prefix возвращает префикс пакета указанного элемента, или null, если префикс не указан. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Свойство только для чтения previousSibling интерфейса [`Node`](../node/) возвращает узел, непосредственно предшествующий указанному в списке [`childNodes`](../node/firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
| [textContent](../../com.aspose.html.dom/text/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Если он установлен в null, попытка изменить его не оказывает эффекта. При установке все возможные дочерние узлы удаляются, и если новая строка не пуста и не null, они заменяются одним текстовым узлом, содержащим эту строку. |
| [getWholeText](../../com.aspose.html.dom/text/wholetext/) Возвращает весь текст узлов Text, логически смежных с этим узлом, объединённый в порядке следования в документе. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних элементов указанного родительского узла. Если переданный дочерний элемент является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Добавьте строку в конец символьных данных узла. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Удалите диапазон 16‑битных единиц из узла. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет определённые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный [`Node`](../node/) дочерние узлы. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед опорным узлом в качестве дочернего элемента указанного родительского узла. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Вставьте строку по указанному смещению в 16‑битных единицах. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса [`Node`](../node/) проверяет, равны ли два узла. Два узла считаются равными, если они имеют один и тот же тип, определяющие характеристики (для элементов это их ID, количество дочерних узлов и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, который должен совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (другими словами, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним у данного узла, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для данного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Помещает все узлы `Text` на полной глубине поддерева под этим Node, включая узлы атрибутов, в "нормальную" форму, где только структура (например, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), и [`entity references`](../entityreference/)) разделяет узлы `Text`, т.е. нет соседних узлов Text и пустых узлов Text. Это может использоваться для обеспечения того, что представление DOM документа совпадает с тем, как если бы документ был сохранён и заново загружен, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта [`DOMConfiguration`](../../com.aspose.html/configuration/), привязанного к [`Node.ownerDocument`](../node/ownerdocument/), установлен в true, этот метод также полностью нормализует символы узлов Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../documentfragment/), oldChild заменяется всеми дочерними узлами [`DocumentFragment`](../documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Замените символы, начиная с указанного смещения в 16‑битных единицах, указанной строкой. |
| [replaceWholeText](../../com.aspose.html.dom/text/replacewholetext/)(String) | Заменяет текст текущего узла и всех логически смежных текстовых узлов указанным текстом. Все логически смежные текстовые узлы удаляются, включая текущий узел, если только он не был получателем заменяющего текста. |
| [splitText](../../com.aspose.html.dom/text/splittext/)(int) | Разбивает этот узел на два узла в указанной позиции, оставляя оба в дереве как соседние. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Извлекает диапазон данных из узла. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

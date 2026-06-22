---
title: "Класс ProcessingInstruction"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.ProcessingInstruction. ProcessingInstruction представляет инструкцию обработки, используемую в XML для сохранения специфической для процессора информации в тексте документа"
type: docs

url: /ru/java/com.aspose.html.dom/processinginstruction/
---
## ProcessingInstruction class

ProcessingInstruction представляет "инструкцию обработки", используемую в XML как способ сохранять специфичную для процессора информацию в тексте документа.

```java
public class ProcessingInstruction : CharacterData
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Свойство baseURI только для чтения интерфейса Node возвращает абсолютный базовый URL документа, содержащего узел. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Свойство childNodes только для чтения интерфейса Node возвращает живой [`NodeList`](../../com.aspose.html.collections/nodelist/) дочерних узлов данного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | Символьные данные узла, реализующего этот интерфейс. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство firstChild только для чтения интерфейса [`Node`](../node/) возвращает первого потомка узла в дереве, или null, если у узла нет детей. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство lastChild только для чтения интерфейса [`Node`](../node/) возвращает последнего потомка узла. Если его родитель — элемент, то потомок обычно является узлом-элементом, текстовым узлом или узлом‑комментарием. Возвращает null, если нет дочерних элементов. |
| [getLength](../../com.aspose.html.dom/characterdata/length/) Количество 16‑битных единиц, доступных через свойство data и метод subStringData ниже. Может быть равно нулю, т.е. узлы CharacterData могут быть пустыми. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме [`ELEMENT_NODE`](../node/element_node/) и [`ATTRIBUTE_NODE`](../node/attribute_node/) и узлов, созданных методом DOM Level 1, таким как [`Document.createElement()`](../document/createelement/), это всегда null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Свойство только для чтения Element.packageURI возвращает URI пакета элемента или null, если элемент не находится в пакете. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Свойство nextSibling только для чтения интерфейса [`Node`](../node/) возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](../node/childnodes/) их родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| [getNodeName](../../com.aspose.html.dom/processinginstruction/nodename/) Имя этого узла, в зависимости от его типа. |
| [getNodeType](../../com.aspose.html.dom/processinginstruction/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/processinginstruction/nodevalue/) { get; set; } | Значение этого узла, в зависимости от его типа. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Только для чтения свойство ownerDocument интерфейса Node возвращает объект верхнего уровня документа, к которому относится узел. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Свойство parentElement только для чтения интерфейса [`Node`](../node/) возвращает родительский [`Element`](../element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родительский узел указанного узла в дереве DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Свойство только для чтения prefix возвращает префикс пакета указанного элемента или null, если префикс не указан. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Свойство previousSibling только для чтения интерфейса [`Node`](../node/) возвращает узел, непосредственно предшествующий указанному в списке [`childNodes`](../node/firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
| [getTarget](../../com.aspose.html.dom/processinginstruction/target/) Цель этой инструкции обработки. |
| [textContent](../../com.aspose.html.dom/processinginstruction/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Если он задан как null, попытка установить его не оказывает эффекта. При установке все возможные дочерние узлы удаляются, и если новая строка не пуста и не null, она заменяется одним текстовым узлом, содержащим эту строку. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних узлов указанного родительского узла. Если переданный дочерний узел является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Добавьте строку в конец символьных данных узла. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Удалите диапазон 16‑битных единиц из узла. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListener в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный [`Node`](../node/) дочерние узлы. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед ссылочным узлом в качестве дочернего элемента указанного родительского узла. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Вставьте строку по указанному смещению в 16‑битных единицах. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса [`Node`](../node/) проверяет, равны ли два узла. Два узла считаются равными, если они имеют один и тот же тип, определяющие характеристики (для элементов это их ID, количество детей и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, который должен совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (иначе говоря, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним в данном узле, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для заданного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Помещает все узлы [`Text`](../text/) на полной глубине поддерева под этим Узлом, включая атрибутные узлы, в "нормальную" форму, где только структура (например, [`elements`](../element/), [`comments`](../comment/), `processing instructions`, [`CDATA sections`](../cdatasection/), и [`entity references`](../entityreference/)) разделяет узлы [`Text`](../text/), то есть нет соседних узлов Text и пустых узлов Text. Это может быть использовано для обеспечения того, что представление DOM документа совпадает с тем, как если бы он был сохранён и заново загружен, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта [`DOMConfiguration`](../../com.aspose.html/configuration/), привязанного к [`Node.ownerDocument`](../node/ownerdocument/), имеет значение true, этот метод также полностью нормализует символы узлов Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild узлом newChild в списке детей и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../documentfragment/), oldChild заменяется всеми дочерними узлами [`DocumentFragment`](../documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Замените символы, начиная с указанного смещения в 16‑битных единицах, указанной строкой. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Извлекает диапазон данных из узла. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

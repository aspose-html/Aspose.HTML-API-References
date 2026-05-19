---
title: "Класс Element"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.Element. Интерфейс Element представляет элемент в HTML или XML документе."
type: docs

url: /ru/java/com.aspose.html.dom/element/
---
## Element class

Интерфейс Element представляет элемент в документе HTML или XML.

```java
public class Element : Node, IChildNode, IParentNode
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Element](element/)(QualifiedName, Document) | Инициализирует новый экземпляр класса `Element`. Не вызывайте этот конструктор напрямую, используйте [`CreateElement`](../document/createelement/) или [`CreateElementNS`](../document/createelementns/). |

## Свойства

| Имя | Описание |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) NamedNodeMap, содержащий атрибуты этого узла (если это Element), или null в противном случае. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Свойство baseURI только для чтения интерфейса Node возвращает абсолютный базовый URL документа, содержащего узел. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Возвращает текущее количество узлов-элементов, являющихся дочерними для этого элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Свойство childNodes только для чтения интерфейса Node возвращает живой [`NodeList`](../../com.aspose.html.collections/nodelist/) дочерних узлов данного элемента, где первый дочерний узел имеет индекс 0. Дочерние узлы включают элементы, текст и комментарии. |
| [getChildren](../../com.aspose.html.dom/element/children/) Возвращает дочерние элементы текущего элемента. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Возвращает живой DOMTokenList, содержащий токены, полученные при разборе атрибута "class". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство только для чтения firstChild интерфейса [`Node`](../node/) возвращает первого дочернего узла в дереве, или null, если у узла нет дочерних элементов. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Возвращает первый дочерний элемент-узел этого элемента. null, если у этого элемента нет дочерних элементов. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство только для чтения lastChild интерфейса [`Node`](../node/) возвращает последнего дочернего узла. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов. |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Возвращает последний дочерний элементный узел этого элемента. null, если у этого элемента нет дочерних элементов. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме ELEMENT_NODE и ATTRIBUTE_NODE, а также узлов, созданных методом уровня DOM 1, например Document.createElement(), всегда возвращается null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) URI пространства имён этого узла, или null, если не указано. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Возвращает следующий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих после него в дереве документа. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Свойство только для чтения nextSibling интерфейса [`Node`](../node/) возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](../node/childnodes/) их родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Имя этого узла, в зависимости от его типа. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Свойство nodeValue интерфейса [`Node `](../node/) возвращает или задает значение текущего узла. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Только для чтения свойство ownerDocument интерфейса Node возвращает объект верхнего уровня документа узла. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Свойство только для чтения parentElement интерфейса [`Node`](../node/) возвращает родительский `Element` DOM‑узла, или null, если у узла нет родителя или его родитель не является DOM‑Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родителя указанного узла в дереве DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Префикс пространства имён этого узла, или null, если не указан. Если он установлен в null, попытка изменить его не оказывает эффекта. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Возвращает предыдущий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, предшествующих ему в дереве документа. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Свойство только для чтения previousSibling интерфейса [`Node`](../node/) возвращает узел, непосредственно предшествующий указанному в списке [`childNodes`](../node/firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Возвращает shadowRoot, хранящийся в этом элементе, или null, если он закрыт. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Имя элемента. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Если он установлен в null, попытка изменить его не оказывает эффекта. При установке все возможные дочерние узлы удаляются, и если новая строка не пуста и не null, они заменяются одним текстовым узлом, содержащим эту строку. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних элементов указанного родительского узла. Если переданный дочерний элемент является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Создаёт теневой корень и присоединяет его к текущему элементу. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет определённые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Получает значение атрибута по имени. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Возвращает имена атрибутов элемента в виде массива строк. Если у элемента нет атрибутов, возвращается пустой массив. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Получает узел атрибута по имени. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Получает узел Attr по локальному имени и URI пакета. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Получает значение атрибута по локальному имени и URI пакета. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все элементы внутри `element`, которые имеют все классы, указанные в аргументе. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все `elements` с заданным именем тега, в порядке следования в документе. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все `elements` с заданным локальным именем и строкой URI пакета, в порядке следования в документе. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Возвращает true, если атрибут с заданным именем указан у этого элемента или имеет значение по умолчанию, в противном случае — false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Возвращает true, если атрибут с заданным локальным именем и URI пакета указан у этого элемента или имеет значение по умолчанию, в противном случае — false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Возвращает, имеет ли этот узел (если это элемент) какие-либо атрибуты |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный [`Node`](../node/) дочерние узлы. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед опорным узлом в качестве дочернего элемента указанного родительского узла. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса [`Node`](../node/) проверяет, равны ли два узла. Два узла считаются равными, если они имеют один и тот же тип, определяющие характеристики (для элементов это их ID, количество дочерних узлов и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, который должен совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (другими словами, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним у данного узла, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для данного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Помещает все узлы [`Text`](../text/) на полной глубине поддерева под этим Node, включая узлы атрибутов, в "нормальную" форму, где только структура (например, `elements`, [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), и [`entity references`](../entityreference/)) разделяет узлы [`Text`](../text/), т.е. нет соседних узлов Text и пустых узлов Text. Это может использоваться для обеспечения того, что представление DOM документа совпадает с тем, как если бы документ был сохранён и заново загружен, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта [`DOMConfiguration`](../../com.aspose.html/configuration/), привязанного к [`Node.ownerDocument`](../node/ownerdocument/), установлен в true, этот метод также полностью нормализует символы узлов Text. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Возвращает первый элемент в документе, который соответствует селектору |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Возвращает NodeList всех элементов в документе, которые соответствуют селектору |
| [remove](../../com.aspose.html.dom/element/remove/)() | Удаляет этот экземпляр. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Удаляет атрибут по имени. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Удаляет указанный узел атрибута. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Удаляет атрибут по локальному имени и URI пакета. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта. Если обработчик удаляется во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../documentfragment/), oldChild заменяется всеми дочерними узлами [`DocumentFragment`](../documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Добавляет новый атрибут. Если атрибут с таким именем уже присутствует в элементе, его значение изменяется на значение параметра value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Добавляет новый узел атрибута. Если атрибут с таким именем (nodeName) уже присутствует в элементе, он заменяется новым. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Добавляет новый атрибут. Если атрибут с таким локальным именем и URI пакета уже присутствует в элементе, он заменяется новым. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Добавляет новый атрибут. Если атрибут с тем же локальным именем и URI пакета уже присутствует в элементе, его префикс изменяется на префикс из qualifiedName, а его значение изменяется на значение параметра value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute)(String) | Если параметр force не указан, «переключает» qualifiedName, удаляя его, если он присутствует, и добавляя, если отсутствует. Если force равно true, добавляет qualifiedName. Если force равно false, удаляет qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute_1)(String, bool) | Если параметр force не указан, «переключает» qualifiedName, удаляя его, если он присутствует, и добавляя, если отсутствует. Если force равно true, добавляет qualifiedName. Если force равно false, удаляет qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [Node](../node/)
* interface [IChildNode](../ichildnode/)
* interface [IParentNode](../iparentnode/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

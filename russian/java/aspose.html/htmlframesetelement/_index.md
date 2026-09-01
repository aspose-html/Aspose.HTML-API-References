---
title: "HTMLFrameSetElement Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.HTMLFrameSetElement class. Создаёт сетку фреймов. См. определение элемента FRAMESET в HTML 4.01"
type: docs

url: /ru/java/com.aspose.html/htmlframesetelement/
---
## HTMLFrameSetElement class

Создать сетку кадров. См. определение элемента FRAMESET в HTML 4.01.

Смотрите также [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLFrameSetElement : HTMLElement
```

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
[getCols]
[setCols] The number of columns of frames in the frameset. See the cols attribute definition in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство firstChild только для чтения интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает первый дочерний узел в дереве, или null, если у узла нет детей. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Возвращает первый дочерний элемент-узел этого элемента. null, если у этого элемента нет дочерних элементов. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство lastChild только для чтения интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Возвращает последний дочерний элемент‑узел данного элемента. null, если у этого элемента нет дочерних элементов. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, отличных от ELEMENT_NODE и ATTRIBUTE_NODE, а также узлов, созданных методом DOM Level 1, например Document.createElement(), всегда возвращается null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) URI пространства имён этого узла, или null, если не указано. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Возвращает следующий соседний элемент‑узел данного элемента. null, если у этого элемента нет соседних элемент‑узлов, идущих после него в дереве документа. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Только для чтения свойство nextSibling интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](../../com.aspose.html.dom/node/childnodes/) его родителя, или возвращает null, если указанный узел является последним дочерним элементом в родительском элементе. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Имя этого узла, в зависимости от его типа. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Свойство nodeValue интерфейса [`Node `](../../com.aspose.html.dom/node/) возвращает или задаёт значение текущего узла. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Только для чтения свойство ownerDocument интерфейса Node возвращает объект верхнего уровня документа, к которому относится узел. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Только для чтения свойство parentElement интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает родительский [`Element`](../../com.aspose.html.dom/element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является элементом DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родительский узел указанного узла в дереве DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Префикс пространства имён этого узла, или null, если не указан. Если он задан как null, попытка установить его не оказывает эффекта. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Возвращает предыдущий соседний элемент‑узел данного элемента. null, если у этого элемента нет соседних элемент‑узлов, предшествующих ему в дереве документа. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Только для чтения свойство previousSibling интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает узел, непосредственно предшествующий указанному в списке [`childNodes`](../../com.aspose.html.dom/node/firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
[getRows]
[setRows] The number of rows of frames in the frameset. See the rows attribute definition in HTML 4.01. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Возвращает shadowRoot, хранящийся в этом элементе, или null, если он закрыт. |
| [getStyle](../../com.aspose.html/htmlelement/style/) Представляет атрибут стиля, который позволяет автору напрямую применять стилистическую информацию к конкретному элементу. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Имя элемента. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Если он задан как null, попытка установить его не оказывает эффекта. При установке все возможные дочерние узлы удаляются, и если новая строка не пуста и не null, она заменяется одним текстовым узлом, содержащим эту строку. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../../com.aspose.html.dom/eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к цели. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних узлов указанного родительского узла. Если переданный дочерний узел является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Создаёт теневой корень и присоединяет его к текущему элементу. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, для которого был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (синхронно) вызывая затронутые EventListener в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Получает значение атрибута по имени. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Возвращает имена атрибутов элемента в виде массива строк. Если у элемента нет атрибутов, возвращается пустой массив. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Получает узел атрибута по имени. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Получает узел Attr по локальному имени и URI пакета. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Получает значение атрибута по локальному имени и URI пакета. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все элементы внутри [`element`](../../com.aspose.html.dom/element/), у которых присутствуют все классы, указанные в аргументе. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все [`elements`](../../com.aspose.html.dom/element/) с заданным именем тега, в порядке следования в документе. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все [`elements`](../../com.aspose.html.dom/element/) с заданным локальным именем и строкой URI пакета, в порядке следования в документе. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Возвращает true, если атрибут с заданным именем указан у этого элемента или имеет значение по умолчанию, иначе возвращает false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Возвращает true, если атрибут с заданным локальным именем и URI пакета указан у этого элемента или имеет значение по умолчанию, иначе возвращает false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Возвращает, имеет ли этот узел (если это элемент) какие-либо атрибуты |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный [`Node`](../../com.aspose.html.dom/node/) дочерние узлы. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед ссылочным узлом в качестве дочернего элемента указанного родительского узла. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса [`Node`](../../com.aspose.html.dom/node/) проверяет, равны ли два узла. Два узла считаются равными, если они имеют один и тот же тип, определяющие характеристики (для элементов это их ID, количество дочерних узлов и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, который должен совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (иначе говоря, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним в данном узле, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для заданного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Перемещает все узлы [`Text`](../../com.aspose.html.dom/text/) на полной глубине поддерева под этим Node, включая узлы атрибутов, в «нормальную» форму, где только структура (например, [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), и [`entity references`](../../com.aspose.html.dom/entityreference/)) отделяет узлы [`Text`](../../com.aspose.html.dom/text/), т.е. нет соседних узлов Text и пустых узлов Text. Это можно использовать, чтобы гарантировать, что представление DOM документа совпадает с тем, как если бы документ был сохранён и заново загружен, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от конкретной структуры дерева документа. Если параметр "normalize-characters" объекта [`DOMConfiguration`](../configuration/), прикреплённого к [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/), имеет значение true, этот метод также полностью нормализует символы узлов Text. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Возвращает первый элемент в документе, который соответствует селектору |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Возвращает NodeList всех элементов в документе, которые соответствуют селектору |
| [remove](../../com.aspose.html.dom/element/remove/)() | Удаляет этот экземпляр. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Удаляет атрибут по имени. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Удаляет указанный узел атрибута. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Удаляет атрибут по локальному имени и URI пакета. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Метод removeChild() интерфейса Node удаляет дочерний узел из DOM и возвращает удалённый узел. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Этот метод позволяет удалять обработчики событий с целевого объекта события. Если обработчик удаляется из целевого объекта события во время обработки события, он не будет вызван текущими действиями. Обработчики событий никогда не могут быть вызваны после их удаления. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild узлом newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild заменяется всеми дочерними элементами [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Добавляет новый атрибут. Если атрибут с таким именем уже присутствует в элементе, его значение изменяется на значение параметра value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Добавляет новый узел атрибута. Если атрибут с таким именем (nodeName) уже присутствует в элементе, он заменяется новым. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Добавляет новый атрибут. Если атрибут с таким локальным именем и URI пакета уже присутствует в элементе, он заменяется новым. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Добавляет новый атрибут. Если атрибут с тем же локальным именем и URI пакета уже присутствует в элементе, его префикс изменяется на префикс из qualifiedName, а его значение изменяется на значение параметра value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Если параметр force не указан, происходит «переключение» qualifiedName: он удаляется, если присутствует, и добавляется, если отсутствует. Если force равно true, qualifiedName добавляется. Если force равно false, qualifiedName удаляется. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Если параметр force не указан, происходит «переключение» qualifiedName: он удаляется, если присутствует, и добавляется, если отсутствует. Если force равно true, qualifiedName добавляется. Если force равно false, qualifiedName удаляется. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Возвращает строку, представляющую этот экземпляр. |

## События

| Имя | Описание |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | Получает или задает обработчик события для события OnAbort. |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | Получает или задает обработчик события для события OnBlur. |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | Получает или задает обработчик события для события OnCancel. |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | Получает или задает обработчик события для события OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | Получает или задает обработчик события для события OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | Получает или задает обработчик события для события OnChange. |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | Получает или задает обработчик события для события OnClick. |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | Получает или задает обработчик события для события OnCueChange. |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | Получает или задает обработчик события для события OnDblClick. |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | Получает или задает обработчик события для события OnDurationChange. |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | Получает или задает обработчик события для события OnEmptied. |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | Получает или задает обработчик события для события OnEnded. |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | Получает или задает обработчик события для события OnError. |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | Получает или задает обработчик события для события OnFocus. |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | Получает или задает обработчик события для события OnInput. |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | Получает или задает обработчик события для события OnInvalid. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | Получает или задает обработчик события для события OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | Получает или задает обработчик события для события OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | Получает или задает обработчик события для события OnKeyUp. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | Получает или задает обработчик события для события OnLoad. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | Получает или задает обработчик события для события OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | Получает или задает обработчик события для события OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | Получает или задает обработчик события для события OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | Получает или задает обработчик события для события OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | Получает или задает обработчик события для события OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | Получает или задает обработчик события для события OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | Получает или задает обработчик события для события OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | Получает или задает обработчик события для события OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | Получает или задает обработчик события для события OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | Получает или задает обработчик события для события OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | Получает или задает обработчик события для события OnMouseWheel. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | Получает или задает обработчик события для события OnPause. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | Получает или задает обработчик события для события OnPlay. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | Получает или задает обработчик события для события OnPlaying. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | Получает или задает обработчик события для события OnProgress. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | Получает или задает обработчик события для события OnRateChange. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | Получает или задает обработчик события для события OnReset. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | Получает или задает обработчик события для события OnResize. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | Получает или задает обработчик события для события OnScroll. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | Получает или задает обработчик события для события OnSeeked. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | Получает или задает обработчик события для события OnSeeking. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | Получает или задает обработчик события для события OnSelect. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | Получает или задает обработчик события для события OnShow. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | Получает или задает обработчик события для события OnStalled. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | Получает или задает обработчик события для события OnSubmit. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | Получает или задает обработчик события для события OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | Получает или задает обработчик события для события OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | Получает или задает обработчик события для события OnToggle. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | Получает или задает обработчик события для события OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | Получает или задает обработчик события для события OnWaiting. |

### См. также

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

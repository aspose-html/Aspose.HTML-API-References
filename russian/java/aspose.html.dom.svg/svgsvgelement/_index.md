---
title: "SVGSVGElement Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.svg.SVGSVGElement класс. Ключевое определение интерфейса — интерфейс SVGSVGElement, который соответствует элементу svg. Этот интерфейс содержит различные часто используемые вспомогательные методы, такие как операции с матрицами и возможность управлять временем перерисовки на визуальных устройствах отображения."
type: docs

url: /ru/java/com.aspose.html.dom.svg/svgsvgelement/
---
## SVGSVGElement class

Ключевым определением интерфейса является интерфейс SVGSVGElement, который соответствует элементу ‘svg’. Этот интерфейс содержит различные часто используемые вспомогательные методы, такие как операции с матрицами и возможность управлять временем перерисовки на устройствах визуального рендеринга.

```java
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
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
| [getClassName](../../com.aspose.html.dom.svg/svgelement/classname/) Соответствует атрибуту ‘class’ данного элемента. |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getCurrentScale]
[setCurrentScale] On an outermost svg element, this attribute indicates the current scale factor relative to the initial view to take into account user magnification and panning operations, as described under Magnification and panning. DOM attributes currentScale and currentTranslate are equivalent to the 2x3 matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. If "magnification" is enabled (i.e., zoomAndPan="magnify"), then the effect is as if an extra transformation were placed at the outermost level on the SVG document fragment (i.e., outside the outermost svg element). When accessed on an ‘svg’ element that is not an outermost svg element, it is undefined what behavior this attribute has. |
| [getCurrentTranslate](../../com.aspose.html.dom.svg/svgsvgelement/currenttranslate/) На внешнем (outermost) элементе svg возвращает соответствующий коэффициент трансляции, учитывающий пользовательское «увеличение». При обращении к элементу ‘svg’, который не является внешним, поведение этого атрибута не определено. |
| [getFarthestViewportElement](../../com.aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) Самый дальний предок ‘svg’ элемента. Null, если текущий элемент является самым внешним элементом svg. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Свойство firstChild только для чтения интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает первый дочерний узел в дереве, или null, если у узла нет дочерних элементов. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Возвращает первый дочерний элемент-узел этого элемента. null, если у этого элемента нет дочерних элементов. |
| [getHeight](../../com.aspose.html.dom.svg/svgsvgelement/height/) Соответствует атрибуту ‘height’ данного элемента ‘svg’. |
[getId]
[setId] The value of the ‘id’ attribute on the given element, or the empty String if ‘id’ is not present. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Свойство lastChild только для чтения интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает последний дочерний узел. Если его родитель — элемент, то дочерний узел обычно является элементом, текстовым узлом или узлом комментария. Возвращает null, если нет дочерних элементов |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Возвращает последний дочерний элементный узел этого элемента. null, если у этого элемента нет дочерних элементов. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Возвращает локальную часть квалифицированного имени этого узла. Для узлов любого типа, кроме ELEMENT_NODE и ATTRIBUTE_NODE, а также узлов, созданных методом уровня DOM 1, например Document.createElement(), всегда возвращается null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) URI пространства имён этого узла, или null, если не указано. |
| [getNearestViewportElement](../../com.aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) Элемент, который установил текущий viewport. Обычно это ближайший предок ‘svg’ элемента. Null, если текущий элемент является самым внешним элементом svg. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Возвращает следующий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих после него в дереве документа. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Только для чтения свойство nextSibling интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает узел, непосредственно следующий за указанным в массиве [`childNodes`](../../com.aspose.html.dom/node/childnodes/) его родителя, или возвращает null, если указанный узел является последним дочерним в родительском элементе. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Имя этого узла, в зависимости от его типа. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Код, представляющий тип базового объекта. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Свойство nodeValue интерфейса [`Node `](../../com.aspose.html.dom/node/) возвращает или задаёт значение текущего узла. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Только для чтения свойство ownerDocument интерфейса Node возвращает объект верхнего уровня документа узла. |
| [getOwnerSVGElement](../../com.aspose.html.dom.svg/svgelement/ownersvgelement/) Ближайший предок‑элемент ‘svg’. Null, если данный элемент является самым внешним элементом svg. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Только для чтения свойство parentElement интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает родительский [`Element`](../../com.aspose.html.dom/element/) DOM‑узла, или null, если у узла нет родителя или его родитель не является DOM‑элементом. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Только для чтения свойство parentNode интерфейса Node возвращает родителя указанного узла в дереве DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Префикс пространства имён этого узла, или null, если не указан. Если он установлен в null, попытка изменить его не оказывает эффекта. |
| [getPreserveAspectRatio](../../com.aspose.html.dom.svg/svgsvgelement/preserveaspectratio/) Соответствует атрибуту ‘preserveAspectRatio’ данного элемента. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Возвращает предыдущий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, предшествующих ему в дереве документа. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Только для чтения свойство previousSibling интерфейса [`Node`](../../com.aspose.html.dom/node/) возвращает узел, непосредственно предшествующий указанному в списке [`childNodes`](../../com.aspose.html.dom/node/firstchild/) его родителя, или null, если указанный узел является первым в этом списке. |
| [getRequiredExtensions](../../com.aspose.html.dom.svg/svggraphicselement/requiredextensions/) Соответствует атрибуту ‘requiredExtensions’ указанного элемента. |
| [getRequiredFeatures](../../com.aspose.html.dom.svg/svggraphicselement/requiredfeatures/) Соответствует атрибуту ‘requiredFeatures’ указанного элемента. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Возвращает shadowRoot, хранящийся в этом элементе, или null, если он закрыт. |
| [getStyle](../../com.aspose.html.dom.svg/svgelement/style/) Соответствует атрибуту ‘style’ данного элемента. Если пользовательский агент не поддерживает стилизацию с помощью CSS, этот атрибут всегда должен иметь значение null. |
| [getSystemLanguage](../../com.aspose.html.dom.svg/svggraphicselement/systemlanguage/) Соответствует атрибуту ‘systemLanguage’ указанного элемента. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Имя элемента. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Если он установлен в null, попытка изменить его не оказывает эффекта. При установке все возможные дочерние узлы удаляются, и если новая строка не пуста и не null, они заменяются одним текстовым узлом, содержащим эту строку. |
| [getTransform](../../com.aspose.html.dom.svg/svggraphicselement/transform/) Соответствует атрибуту ‘transform’ указанного элемента. |
| [getViewBox](../../com.aspose.html.dom.svg/svgsvgelement/viewbox/) Соответствует атрибуту ‘viewBox’ данного элемента. |
| [getViewportElement](../../com.aspose.html.dom.svg/svgelement/viewportelement/) Элемент, задающий текущий viewport. Чаще всего ближайший предок‑элемент ‘svg’. Null, если данный элемент является самым внешним элементом svg. |
| [getWidth](../../com.aspose.html.dom.svg/svgsvgelement/width/) Соответствует атрибуту ‘width’ данного элемента ‘svg’. |
| [X](../../com.aspose.html.dom.svg/svgsvgelement/x/) { get; } | Соответствует атрибуту ‘x’ данного элемента ‘svg’. |
| [Y](../../com.aspose.html.dom.svg/svgsvgelement/y/) { get; } | Соответствует атрибуту ‘y’ данного элемента ‘svg’. |
[getZoomAndPan]
[setZoomAndPan] Corresponds to attribute ‘zoomAndPan’ on the given element. The value must be one of the SVG_ZOOMANDPAN_* constants defined on this interface. |

## Методы

| Имя | Описание |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Метод addEventListener() интерфейса [`EventTarget `](../../com.aspose.html.dom/eventtarget/) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Метод addEventListener() интерфейса [EventTarget ](T:com.aspose.html.dom.EventTarget) устанавливает функцию, которая будет вызываться каждый раз, когда указанное событие доставляется к целевому объекту. |
| [animationsPaused](../../com.aspose.html.dom.svg/svgsvgelement/animationspaused/)() | Возвращает true, если данный фрагмент SVG‑документа находится в приостановленном состоянии. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Метод appendChild() интерфейса Node добавляет узел в конец списка дочерних элементов указанного родительского узла. Если переданный дочерний элемент является ссылкой на уже существующий узел в документе, appendChild() перемещает его из текущего положения в новое (не требуется удалять узел из его родительского узла перед добавлением его к другому узлу). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Создаёт теневой корень и присоединяет его к текущему элементу. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Метод cloneNode() интерфейса Node возвращает дубликат узла, на котором был вызван этот метод. Его параметр определяет, будет ли также клонировано поддерево, содержащееся в узле, или нет. |
| [createEvent](../../com.aspose.html.dom.svg/svgsvgelement/createevent/)(String) | Создаёт [`Event`](../../com.aspose.html.dom.events/event/) типа, поддерживаемого реализацией. |
| [createSVGAngle](../../com.aspose.html.dom.svg/svgsvgelement/createsvgangle/)() | Создаёт объект SVGAngle вне любых деревьев документа. Объект инициализируется значением 0 градусов (без единицы). |
| [createSVGLength](../../com.aspose.html.dom.svg/svgsvgelement/createsvglength/)() | Создаёт объект SVGLength вне любых деревьев документа. Объект инициализируется значением 0 пользовательских единиц. |
| [createSVGMatrix](../../com.aspose.html.dom.svg/svgsvgelement/createsvgmatrix/)() | Создаёт объект SVGMatrix вне любых деревьев документа. Объект инициализируется единичной матрицей. |
| [createSVGNumber](../../com.aspose.html.dom.svg/svgsvgelement/createsvgnumber/)() | Создаёт объект SVGNumber вне любых деревьев документа. Объект инициализируется значением ноль. |
| [createSVGPoint](../../com.aspose.html.dom.svg/svgsvgelement/createsvgpoint/)() | Создаёт объект SVGPoint вне любых деревьев документа. Объект инициализируется точкой (0,0) в пользовательской системе координат. |
| [createSVGRect](../../com.aspose.html.dom.svg/svgsvgelement/createsvgrect/)() | Создаёт объект SVGRect вне любых деревьев документа. Объект инициализируется так, что все значения установлены в 0 пользовательских единиц. |
| [createSVGTransform](../../com.aspose.html.dom.svg/svgsvgelement/createsvgtransform/)() | Создаёт объект SVGTransform вне любых деревьев документа. Объект инициализируется преобразованием единичной матрицы (SVG_TRANSFORM_MATRIX). |
| [createSVGTransformFromMatrix](../../com.aspose.html.dom.svg/svgsvgelement/createsvgtransformfrommatrix/)(SVGMatrix) | Создаёт объект SVGTransform вне любых деревьев документа. Объект инициализируется заданным преобразованием матрицы (т.е. SVG_TRANSFORM_MATRIX). Значения из переданной матрицы копируются, параметр matrix не принимается в качестве SVGTransform::matrix. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Отправляет событие указанному [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (синхронно), вызывая затронутые EventListeners в соответствующем порядке. Обычные правила обработки событий (включая фазу захвата и необязательную фазу всплытия) также применяются к событиям, отправленным вручную с помощью [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Выполняет определённые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Получает значение атрибута по имени. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Возвращает имена атрибутов элемента в виде массива строк. Если у элемента нет атрибутов, возвращается пустой массив. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Получает узел атрибута по имени. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Получает узел Attr по локальному имени и URI пакета. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Получает значение атрибута по локальному имени и URI пакета. |
| [getBBox](../../com.aspose.html.dom.svg/svggraphicselement/getbbox/)() | Возвращает точный ограничивающий прямоугольник в текущем пользовательском пространстве (т.е. после применения атрибута ‘transform’, если он присутствует) для геометрии всех вложенных графических элементов, исключая обводку, обрезку, маскирование и эффекты фильтра. Обратите внимание, что getBBox должен возвращать фактический ограничивающий прямоугольник в момент вызова метода, даже если элемент ещё не был отрисован. |
| [getCTM](../../com.aspose.html.dom.svg/svggraphicselement/getctm/)() | Возвращает матрицу преобразования из текущих пользовательских единиц (т.е. после применения атрибута ‘transform’, если он присутствует) в систему координат viewport для nearestViewportElement. |
| [getCurrentTime](../../com.aspose.html.dom.svg/svgsvgelement/getcurrenttime/)() | Возвращает текущее время в секундах относительно времени начала текущего фрагмента SVG‑документа. Если getCurrentTime вызывается до начала временной шкалы документа (например, скриптом, выполняющимся в элементе ‘script’ до того, как будет отправлено событие SVGLoad документа), возвращается 0. |
| [getElementById](../../com.aspose.html.dom.svg/svgsvgelement/getelementbyid/)(String) | Ищет в этом фрагменте SVG‑документа (т.е. поиск ограничен подмножеством дерева документа) элемент Element, чей id задан параметром elementId. Если элемент найден, он возвращается. Если такого элемента нет, возвращается null. Поведение не определено, если более одного элемента имеет этот id. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все элементы внутри [`element`](../../com.aspose.html.dom/element/), которые имеют все классы, указанные в аргументе. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все [`elements`](../../com.aspose.html.dom/element/) с заданным именем тега, в порядке следования в документе. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Возвращает объект [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/), содержащий все [`elements`](../../com.aspose.html.dom/element/) с заданным локальным именем и строкой URI пакета, в порядке следования в документе. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [getScreenCTM](../../com.aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Возвращает матрицу преобразования из текущих пользовательских единиц (т.е. после применения атрибута ‘transform’, если он присутствует) к представлению «пикселя» родительского пользовательского агента. Для дисплейных устройств это, как правило, физический пиксель экрана. Для других устройств или сред, где размеры физических пикселей неизвестны, может использоваться алгоритм, аналогичный определению «пикселя» в CSS2. Обратите внимание, что возвращается null, если элемент не включён в дерево документа. Этот метод более точно назывался бы getClientCTM, но имя getScreenCTM сохраняется по историческим причинам. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Возвращает true, если атрибут с заданным именем указан у этого элемента или имеет значение по умолчанию, в противном случае — false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Возвращает true, если атрибут с заданным локальным именем и URI пакета указан у этого элемента или имеет значение по умолчанию, в противном случае — false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Возвращает, имеет ли этот узел (если это элемент) какие-либо атрибуты |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Метод hasChildNodes() интерфейса Node возвращает логическое значение, указывающее, имеет ли данный [`Node`](../../com.aspose.html.dom/node/) дочерние узлы. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Метод insertBefore() интерфейса Node вставляет узел перед опорным узлом в качестве дочернего элемента указанного родительского узла. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Метод isDefaultNamespace() интерфейса Node принимает URI пакета в качестве аргумента. Он возвращает логическое значение true, если пакет является пакетом по умолчанию для данного узла, и false в противном случае. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Метод isEqualNode() интерфейса [`Node`](../../com.aspose.html.dom/node/) проверяет, равны ли два узла. Два узла считаются равными, если они имеют один и тот же тип, определяющие характеристики (для элементов это их ID, количество дочерних элементов и т.д.), их атрибуты совпадают и т.п. Конкретный набор данных, которые должны совпадать, зависит от типов узлов. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Метод isSameNode() интерфейса Node является устаревшим синонимом оператора строгого равенства ===. То есть он проверяет, являются ли два узла одинаковыми (другими словами, ссылаются ли они на один и тот же объект). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Метод lookupNamespaceURI() интерфейса Node принимает префикс в качестве параметра и возвращает URI пакета, связанный с ним у данного узла, если найден (и null, если нет). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для данного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Помещает все узлы [`Text`](../../com.aspose.html.dom/text/) на полной глубине поддерева под этим Node, включая узлы атрибутов, в «нормальную» форму, где только структура (например, [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), и [`entity references`](../../com.aspose.html.dom/entityreference/)) отделяет узлы [`Text`](../../com.aspose.html.dom/text/), т.е. нет соседних узлов Text и пустых узлов Text. Это можно использовать, чтобы гарантировать, что представление DOM документа совпадает с тем, как он выглядел бы после сохранения и повторной загрузки, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта [`DOMConfiguration`](../../com.aspose.html/configuration/), привязанного к [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/), установлен в true, этот метод также полностью нормализует символы узлов Text. |
| [pauseAnimations](../../com.aspose.html.dom.svg/svgsvgelement/pauseanimations/)() | Приостанавливает (т.е. ставит на паузу) все текущие анимации, определённые во фрагменте SVG‑документа, соответствующем этому элементу ‘svg’, заставляя часы анимации этого фрагмента останавливаться, пока они не будут возобновлены. |
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
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild на newChild в списке дочерних узлов и возвращает узел oldChild. Если newChild является объектом [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild заменяется всеми дочерними узлами [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), которые вставляются в том же порядке. Если newChild уже находится в дереве, он сначала удаляется. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Добавляет новый атрибут. Если атрибут с таким именем уже присутствует в элементе, его значение изменяется на значение параметра value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Добавляет новый узел атрибута. Если атрибут с таким именем (nodeName) уже присутствует в элементе, он заменяется новым. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Добавляет новый атрибут. Если атрибут с таким локальным именем и URI пакета уже присутствует в элементе, он заменяется новым. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Добавляет новый атрибут. Если атрибут с тем же локальным именем и URI пакета уже присутствует в элементе, его префикс изменяется на префикс из qualifiedName, а его значение изменяется на значение параметра value. |
| [setCurrentTime](../../com.aspose.html.dom.svg/svgsvgelement/setcurrenttime/)(float) | Регулирует часы для этого фрагмента SVG‑документа, устанавливая новое текущее время. Если setCurrentTime вызывается до того, как таймлайн документа начался (например, скриптом, выполняющимся в элементе ‘script’ до того, как событие SVGLoad документа будет отправлено), то значение секунд в последнем вызове метода задаёт время, к которому документ перейдёт, как только таймлайн документа начнётся. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Если параметр force не указан, «переключает» qualifiedName, удаляя его, если он присутствует, и добавляя, если отсутствует. Если force равно true, добавляет qualifiedName. Если force равно false, удаляет qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Если параметр force не указан, «переключает» qualifiedName, удаляя его, если он присутствует, и добавляя, если отсутствует. Если force равно true, добавляет qualifiedName. Если force равно false, удаляет qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Возвращает строку, представляющую этот экземпляр. |
| [unpauseAnimations](../../com.aspose.html.dom.svg/svgsvgelement/unpauseanimations/)() | Снимает приостановку (т.е. возобновляет) текущие анимации, определённые во фрагменте SVG‑документа, заставляя часы анимации продолжить работу с момента, когда они были приостановлены. |

### См. также

* class [SVGGraphicsElement](../svggraphicselement/)
* interface [ISVGFitToViewBox](../isvgfittoviewbox/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IViewCSS](../../com.aspose.html.dom.css/iviewcss/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* interface [ISVGZoomAndPan](../isvgzoomandpan/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)

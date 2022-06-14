---
title: SVGGeometryElement
second_title: Справочник по Aspose.HTML для .NET API
description: Интерфейс SVGGeometryElement представляет элементы SVG визуализация которых определяется геометрией с эквивалентным путем и которые можно заполнять и обводить. Это включает в себя пути и основные формы.
type: docs
weight: 2200
url: /ru/net/aspose.html.dom.svg/svggeometryelement/
---
## SVGGeometryElement class

Интерфейс SVGGeometryElement представляет элементы SVG, визуализация которых определяется геометрией с эквивалентным путем, и которые можно заполнять и обводить. Это включает в себя пути и основные формы.

```csharp
public class SVGGeometryElement : SVGGraphicsElement
```

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes) { get; } | NamedNodeMap, содержащий атрибуты этого узла (если это элемент) или null в противном случае. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | Абсолютный базовый URI этого узла или ноль, если реализация не смогла получить абсолютный URI. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount) { get; } | Возвращает текущее количество узлов элемента, которые являются дочерними элементами этого элемента. 0, если у этого элемента нет дочерних узлов nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | NodeList, содержащий все дочерние элементы этого узла. Если детей нет, это NodeList, не содержащий узлов.. |
| [Children](../../aspose.html.dom/element/children) { get; } | Возвращает дочерние элементы текущего элемента. |
| [ClassList](../../aspose.html.dom/element/classlist) { get; } | Возвращает живой DOMTokenList, который содержит токены, полученные в результате разбора атрибута "класс". |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname) { get; } | Соответствует атрибуту 'класс' данного элемента. |
| [ClassName](../../aspose.html.dom/element/classname) { get; set; } | Атрибут класса элемента. Этот атрибут был переименован из-за того, что конфликтует с ключевым словом class во многих языках. См. определение атрибута класса в HTML 4.01. |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement) { get; } | Самый дальний предок элемента 'svg'. Null, если текущий элемент является самым внешним элементом svg. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | Первый потомок этого узла. Если такого узла нет, возвращается null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild) { get; } | Возвращает узел первого дочернего элемента этого элемента. null, если у этого элемента нет дочерних элементов. |
| [Id](../../aspose.html.dom.svg/svgelement/id) { get; set; } | Значение атрибута 'id' для данного элемента или пустая строка, если 'id' отсутствует. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml) { get; set; } | Возвращает фрагмент HTML или XML, представляющий содержимое элемента. Можно установить, чтобы заменить содержимое элемента узлами, проанализированными из данной строки. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | Последний дочерний элемент этого узла. Если такого узла нет, возвращается null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild) { get; } | Возвращает последний узел дочернего элемента этого элемента. null, если у этого элемента нет дочерних элементов. |
| override [LocalName](../../aspose.html.dom/element/localname) { get; } | Возвращает локальную часть полного имени этого узла. Для узлов любого типа, кроме ELEMENT_NODE и ATTRIBUTE_NODE, и узлов, созданных с помощью метода DOM уровня 1, такого как Document.createElement(), всегда равно null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri) { get; } | URI пространства имен этого узла или нуль, если он не указан. |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement) { get; } | Элемент, который устанавливает текущее окно просмотра. Часто ближайший предок элемент 'svg'. Null, если текущий элемент является самым внешним элементом svg. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling) { get; } | Возвращает следующий узел элемента-брата этого элемента. null, если у этого элемента нет узлов-сестер, следующих за этим в дереве документа. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | Узел, непосредственно следующий за этим узлом. Если такого узла нет, возвращается null. |
| override [NodeName](../../aspose.html.dom/element/nodename) { get; } | Имя этого узла в зависимости от его типа. |
| override [NodeType](../../aspose.html.dom/element/nodetype) { get; } | Код, представляющий тип базового объекта. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | Значение этого узла в зависимости от его типа. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml) { get; set; } | Возвращает фрагмент HTML или XML, представляющий элемент и его содержимое. Можно установить, чтобы заменить элемент узлами, проанализированными из данной строки. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | Объект Document, связанный с этим узлом. Это также объект Document, используемый для создания новых узлов. Когда этот узел является документом или типом документа, который еще не используется ни с одним документом, это значение равно null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement) { get; } | Ближайший элемент-предок 'svg'. Null, если данный элемент является самым внешним элементом svg. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Получает родителя[`Element`](../../aspose.html.dom/element)этого узла. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | Родитель этого узла. Все узлы, кроме Attr, Document, DocumentFragment, Entity и Notation, могут иметь родителя. Однако, если узел был только что создан и еще не добавлен в дерево, или если он был удален из дерева, это значение равно null. |
| [PathLength](../../aspose.html.dom.svg/svggeometryelement/pathlength) { get; } | Соответствует атрибуту pathLength данного элемента. |
| override [Prefix](../../aspose.html.dom/element/prefix) { get; } | Префикс пространства имен этого узла или ноль, если он не указан. Когда он определен как null, его установка не имеет никакого эффекта |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling) { get; } | Возвращает предыдущий одноуровневый узел этого элемента. null, если этот элемент не имеет родственных узлов, предшествующих ему в дереве документа. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | Узел, непосредственно предшествующий этому узлу. Если такого узла нет, возвращается null. |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions) { get; } | Соответствует атрибуту 'requiredExtensions' данного элемента. |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures) { get; } | Соответствует атрибуту 'requiredFeatures' данного элемента. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo) { get; } | Информация о типе, связанная с этим элементом. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot) { get; } | Возвращает shadowRoot, хранящийся в этом элементе, или ноль, если он закрыт. |
| [Style](../../aspose.html.dom.svg/svgelement/style) { get; } | Соответствует атрибуту 'style' данного элемента. Если пользовательский агент не поддерживает стилизацию с помощью CSS, этот атрибут всегда должен иметь значение null. |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage) { get; } | Соответствует атрибуту 'systemLanguage' данного элемента. |
| [TagName](../../aspose.html.dom/element/tagname) { get; } | Имя элемента. |
| override [TextContent](../../aspose.html.dom/element/textcontent) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Когда он определен как null, его установка не имеет никакого эффекта. При настройке любые возможные дочерние элементы, которые может иметь этот узел, удаляются и, если новая строка не является пустой или нулевой, заменяются одним текстовым узлом, содержащим строку, на которую установлен этот атрибут. |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform) { get; } | Соответствует атрибуту 'transform' данного элемента. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement) { get; } | Элемент, который устанавливает текущее окно просмотра. Часто ближайший предок элемент 'svg'. Null, если данный элемент является самым внешним элементом svg. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | Этот метод позволяет регистрировать прослушиватели событий на цели события. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Этот метод позволяет регистрировать прослушиватели событий на цели события. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Этот метод позволяет регистрировать прослушиватели событий на цели события. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | Добавляет узел newChild в конец списка дочерних элементов этого узла. Если новый дочерний элемент уже находится в дереве, он сначала удаляется. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow)(ShadowRootMode) | Создает теневой корень и прикрепляет его к текущему элементу. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | Возвращает дубликат этого узла, т. е. служит общим конструктором копирования для узлов. Дублирующий узел не имеет родителя (parentNode имеет значение null) и пользовательских данных. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | Возвращает дубликат этого узла, т. е. служит общим конструктором копирования для узлов. Дублирующий узел не имеет родителя (parentNode имеет значение null) и пользовательских данных. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Этот метод позволяет отправлять события в модель событий реализации. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, освобождением или сбросом неуправляемых ресурсов. |
| [GetAttribute](../../aspose.html.dom/element/getattribute)(string) | Извлекает значение атрибута по имени. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode)(string) | Извлекает узел атрибута по имени. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens)(string, string) | Извлекает узел Attr по локальному имени и URI пространства имен. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens)(string, string) | Извлекает значение атрибута по локальному имени и URI пространства имен. |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox)() | Возвращает тесную ограничивающую рамку в текущем пользовательском пространстве (т.е. после применения атрибута 'transform', если он есть) для геометрии всех содержащихся эффекты обводки, обрезки, маскирования и фильтрации). Обратите внимание, что getBBox должен возвращать фактическую ограничивающую рамку во время вызова метода, даже если элемент еще не был визуализирован. |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm)() | Возвращает матрицу преобразования из текущих пользовательских единиц измерения (т.е. после применения атрибута 'transform', если он есть) в систему координат области просмотра для ближайшего элемента ViewportElement. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname)(string) | Возвращает живой объект NodeList, содержащий все элементы в документе, которые имеют все классы, указанные в аргументе. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname)(string) | Возвращает NodeList всех элементов-потомков с заданным именем тега в порядке документа. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens)(string, string) | Возвращает NodeList всех элементов-потомков с заданным локальным именем и URI пространства имен в порядке документа. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| [GetPointAtLength](../../aspose.html.dom.svg/svggeometryelement/getpointatlength)(float) | Возвращает координату (x,y) в пользовательском пространстве, которая представляет собой единицы расстояния вдоль пути, используя алгоритм пользовательского агента расстояния вдоль пути. |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm)() | Возвращает матрицу преобразования из текущих пользовательских единиц (т. е. после применения атрибута 'transform', если он есть) в уведомление родительского пользовательского агента о "пикселе". Для устройств отображения в идеале это представляет собой физический пиксель экрана. Для других устройств или сред, где физические размеры пикселей неизвестны, вместо этого можно использовать алгоритм, аналогичный определению «пикселя» в CSS2. Обратите внимание, что null возвращается, если этот элемент не подключен к дереву документа. Этот метод можно было бы назвать более подходящим как getClientCTM, но название getScreenCTM сохранено по историческим причинам. |
| [GetTotalLength](../../aspose.html.dom.svg/svggeometryelement/gettotallength)() | Возвращает вычисленное агентом пользователя значение общей длины пути с использованием алгоритма расстояния вдоль пути агента пользователя, как расстояние в текущей пользовательской системе координат . |
| [HasAttribute](../../aspose.html.dom/element/hasattribute)(string) | Возвращает значение true, если атрибут с заданным именем указан в этом элементе или имеет значение по умолчанию, в противном случае — значение false. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens)(string, string) | Возвращает значение true, если атрибут с заданным локальным именем и URI пространства имен указан для этого элемента или имеет значение по умолчанию, в противном случае — значение false. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes)() | Возвращает, имеет ли этот узел (если это элемент) какие-либо атрибуты |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | Возвращает, есть ли у этого узла дочерние элементы. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | Вставляет узел перед существующим дочерним узлом. Если дочерний элемент равен нулю, вставьте узел в конец списка дочерних элементов. Если дочерний элемент является объектом DocumentFragment, все его дочерние элементы вставляются в том же порядке перед дочерним. Если дочерний элемент уже находится в дереве, он сначала удаляется. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | Этот метод проверяет, является ли указанный namespaceURI пространством имен по умолчанию или нет. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | Проверяет, равны ли два узла. Этот метод проверяет равенство узлов, а не одинаковость (т. е. являются ли два узла ссылками на один и тот же объект), что можно проверить с помощью Node.isSameNode(). Все одинаковые узлы также будут равными, хотя обратное может быть неверным. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | Возвращает, является ли этот узел тем же узлом, что и заданный. Этот метод позволяет определить, относятся ли две ссылки Node, возвращаемые реализацией, к одному и тому же объекту. Когда две ссылки Node являются ссылками на один и тот же объект, даже через прокси, ссылки могут использоваться полностью взаимозаменяемо, так что все атрибуты имеют одинаковые значения и вызов одного и того же метода DOM для любой ссылки всегда имеет точно такой же эффект. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | Найдите URI пространства имен, связанный с данным префиксом, начиная с этого узла. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | Найдите префикс, связанный с данным URI пространства имен, начиная с этого узла. Объявления пространств имен по умолчанию игнорируются этим методом. Подробнее об алгоритме, используемом этим методом, см. в разделе Поиск префикса пространства имен. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Помещает все узлы Text на всю глубину поддерева под этим узлом, включая узлы атрибутов, в «нормальную» форму, где только структура (например, элементы, комментарии, инструкции по обработке, разделы CDATA и ссылки на сущности) разделяет узлы Text, т. е. нет ни смежных узлов Text, ни пустых узлов Text. Это можно использовать для обеспечения того, чтобы DOM-представление документа было таким же, как если бы он был сохранен и повторно загружен, и полезно, когда операции (такие как поиск XPointer [XPointer]), которые зависят от конкретной древовидной структуры документа, должны выполняться. использоваться. Если параметр «normalize-characters» объекта DOMConfiguration, прикрепленного к Node.ownerDocument, имеет значение true, этот метод также полностью нормализует символы узлов Text. |
| [QuerySelector](../../aspose.html.dom/element/queryselector)(string) | Возвращает первый элемент в документе, соответствующий селектору |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall)(string) | Возвращает NodeList всех элементов в документе, соответствующих селектору |
| [Remove](../../aspose.html.dom/element/remove)() | Удаляет этот экземпляр. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute)(string) | Удаляет атрибут по имени. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode)(Attr) | Удаляет указанный узел атрибута. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens)(string, string) | Удаляет атрибут по локальному имени и URI пространства имен. |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | Удаляет дочерний узел, указанный oldChild, из списка дочерних, и возвращает его. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener)удален из[`EventTarget`](../../aspose.html.dom/eventtarget)в то время как он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener)удален из[`EventTarget`](../../aspose.html.dom/eventtarget)в то время как он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener)удален из[`EventTarget`](../../aspose.html.dom/eventtarget)в то время как он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Заменяет дочерний узел oldChild на newChild в списке дочерних элементов и возвращает узел oldChild. Если newChild является объектом DocumentFragment, то oldChild заменяется всеми дочерними объектами DocumentFragment, которые вставляются в том же порядке. Если новый дочерний элемент уже находится в дереве, он сначала удаляется. |
| [SetAttribute](../../aspose.html.dom/element/setattribute)(string, string) | Добавляет новый атрибут. Если атрибут с таким именем уже присутствует в элементе, его значение изменяется на значение параметра значения |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode)(Attr) | Добавляет новый узел атрибута. Если атрибут с таким именем (nodeName) уже присутствует в элементе, он заменяется новым. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens)(Attr) | Добавляет новый атрибут. Если атрибут с таким локальным именем и этим URI пространства имен уже присутствует в элементе, он заменяется новым. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens)(string, string, string) | Добавляет новый атрибут. Если атрибут с таким же локальным именем и URI пространства имен уже присутствует в элементе, его префикс заменяется на префиксную часть квалифицированного имени, а его значение заменяется на параметр value. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute)(string, bool) | Если параметр isId равен true, этот метод объявляет указанный атрибут как определяемый пользователем атрибут ID. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode)(Attr, bool) | Если параметр isId равен true, этот метод объявляет указанный атрибут как определяемый пользователем атрибут ID. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens)(string, string, bool) | Если параметр isId равен true, этот метод объявляет указанный атрибут как определяемый пользователем атрибут ID. |
| override [ToString](../../aspose.html.dom/node/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

### Смотрите также

* class [SVGGraphicsElement](../svggraphicselement)
* пространство имен [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->

---
title: Class SVGSVGElement
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Svg.SVGSVGElement сорт. Ключевым определением интерфейса является интерфейс SVGSVGElement который соответствует элементу svg. Этот интерфейс содержит различные различные часто используемые служебные методы такие как матричные операции и возможность управления временем перерисовки на устройствах визуального рендеринга.
type: docs
weight: 2260
url: /ru/net/aspose.html.dom.svg/svgsvgelement/
---
## SVGSVGElement class

Ключевым определением интерфейса является интерфейс SVGSVGElement, который соответствует элементу 'svg'. Этот интерфейс содержит различные различные часто используемые служебные методы, такие как матричные операции и возможность управления временем перерисовки на устройствах визуального рендеринга.

```csharp
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
```

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | NamedNodeMap, содержащий атрибуты этого узла (если это элемент) или null в противном случае. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | Абсолютный базовый URI этого узла или ноль, если реализация не смогла получить абсолютный URI. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | Возвращает текущее количество узлов элемента, которые являются дочерними элементами этого элемента. 0, если у этого элемента нет дочерних узлов с nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | NodeList, содержащий все дочерние элементы этого узла. Если нет детей, это NodeList, не содержащий узлов.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | Возвращает дочерние элементы текущего элемента. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | Возвращает активный DOMTokenList, который содержит токены, полученные в результате разбора атрибута "класс". |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | Соответствует атрибуту «класс» данного элемента. |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | Атрибут класса элемента. Этот атрибут был переименован due из-за конфликта с ключевым словом class во многих языках. См. определение атрибута класса в HTML 4.01. |
| [CurrentScale](../../aspose.html.dom.svg/svgsvgelement/currentscale/) { get; set; } | В самом внешнем элементе svg этот атрибут указывает текущий коэффициент масштабирования по отношению к исходному виду, чтобы учитывать операции увеличения и панорамирования, выполняемые пользователем, как описано в разделе «Увеличение и панорамирование». Атрибуты DOM currentScale и currentTranslate эквивалентны матрице 2x3 [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Если включено «увеличение» (т. е. zoomAndPan = «увеличение»), эффект будет таким, как если бы дополнительное преобразование было размещено на самом внешнем уровне фрагмента документа SVG (т. е. за пределами самого внешнего элемента svg). При доступе к элемент 'svg', который не является самым внешним элементом svg, не определено, какое поведение имеет этот атрибут. |
| [CurrentTranslate](../../aspose.html.dom.svg/svgsvgelement/currenttranslate/) { get; } | Для самого внешнего элемента svg — соответствующий коэффициент перевода, учитывающий пользовательское «увеличение». |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | Самый дальний предок элемента 'svg'. Null, если текущий элемент является самым внешним элементом svg. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Первый дочерний элемент этого узла. Если такого узла нет, возвращается null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Возвращает первый узел дочернего элемента этого элемента. null, если у этого элемента нет дочерних элементов. |
| [Height](../../aspose.html.dom.svg/svgsvgelement/height/) { get; } | Соответствует атрибуту «высота» данного элемента «svg». |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | Значение атрибута 'id' для данного элемента или пустая строка, если 'id' отсутствует. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Возвращает фрагмент HTML или XML, представляющий содержимое элемента. Можно установить, чтобы заменить содержимое элемента узлами, проанализированными из заданной строки. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Последний дочерний элемент этого узла. Если такого узла нет, возвращается null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Возвращает последний узел дочернего элемента этого элемента. null, если у этого элемента нет дочерних элементов. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Возвращает локальную часть полного имени этого узла. Для узлов любого типа, кроме ELEMENT_NODE и ATTRIBUTE_NODE, и узлов, созданных с помощью метода DOM уровня 1, такого как Document.createElement(), всегда равно null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | URI пространства имен этого узла или null, если он не указан. |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) { get; } | Элемент, который устанавливает текущее окно просмотра. Часто ближайший предок элемент 'svg'. Null, если текущий элемент является самым внешним элементом svg. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Возвращает следующий узел одноуровневого элемента этого элемента. null, если у этого элемента нет узлов-сестер, следующих за этим в дереве документа. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Узел, следующий непосредственно за этим узлом. Если такого узла нет, возвращается null. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | Имя этого узла в зависимости от его типа. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | Код, представляющий тип базового объекта. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Значение этого узла в зависимости от его типа. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Возвращает фрагмент HTML или XML, представляющий элемент и его содержимое. Может быть установлено, чтобы заменить элемент узлами, проанализированными из заданной строки. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Объект документа, связанный с этим узлом. Это также объект Document, используемый для создания новых узлов. Когда этот узел является документом или типом документа, который еще не используется ни с одним документом, это значение равно null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | Ближайший элемент-предок 'svg'. Null, если данный элемент является самым внешним элементом svg. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Получает родителя[`Element`](../../aspose.html.dom/element/) этого узла. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Родитель этого узла. Все узлы, кроме Attr, Document, DocumentFragment, Entity и Notation, могут иметь родителя. Однако, если узел был только что создан и еще не добавлен в дерево, или если он был удален из дерева, это значение null. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | Префикс пространства имен этого узла или нуль, если он не указан. Когда он определен как нуль, его установка не имеет никакого эффекта |
| [PreserveAspectRatio](../../aspose.html.dom.svg/svgsvgelement/preserveaspectratio/) { get; } | Соответствует атрибуту preserveAspectRatio данного элемента. |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Возвращает предыдущий узел родственного элемента этого элемента. null, если этот элемент не имеет родственных узлов, предшествующих ему в дереве документа. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Узел, непосредственно предшествующий этому узлу. Если такого узла нет, возвращается null. |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions/) { get; } | Соответствует атрибуту «requiredExtensions» данного элемента. |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures/) { get; } | Соответствует атрибуту «requiredFeatures» данного элемента. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | Информация о типе, связанная с этим элементом. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Возвращает shadowRoot, хранящийся в этом элементе, или null, если он закрыт. |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | Соответствует атрибуту «стиль» данного элемента. Если пользовательский агент не поддерживает стилизацию с помощью CSS, этот атрибут всегда должен иметь значение null. |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage/) { get; } | Соответствует атрибуту systemLanguage данного элемента. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | Имя элемента. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Когда он определен как null, его установка не имеет никакого эффекта. При настройке любые возможные дочерние элементы, которые может иметь этот узел, удаляются и, если новая строка не является пустой или нулевой, заменяются одним текстовым узлом, содержащим строку, на которую установлен этот атрибут. |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform/) { get; } | Соответствует атрибуту «преобразование» данного элемента. |
| [ViewBox](../../aspose.html.dom.svg/svgsvgelement/viewbox/) { get; } | Соответствует атрибуту viewBox данного элемента. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | Элемент, который устанавливает текущее окно просмотра. Часто ближайший предок элемент 'svg'. Null, если данный элемент является самым внешним элементом svg. |
| [Width](../../aspose.html.dom.svg/svgsvgelement/width/) { get; } | Соответствует атрибуту «ширина» данного элемента «svg». |
| [X](../../aspose.html.dom.svg/svgsvgelement/x/) { get; } | Соответствует атрибуту «x» данного элемента «svg». |
| [Y](../../aspose.html.dom.svg/svgsvgelement/y/) { get; } | Соответствует атрибуту 'y' данного элемента 'svg'. |
| [ZoomAndPan](../../aspose.html.dom.svg/svgsvgelement/zoomandpan/) { get; set; } | Соответствует атрибуту zoomAndPan данного элемента. Значение должно быть одной из констант SVG_ZOOMANDPAN_*, определенных в этом интерфейсе. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AnimationsPaused](../../aspose.html.dom.svg/svgsvgelement/animationspaused/)() | Возвращает true, если этот фрагмент документа SVG находится в состоянии паузы. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Добавляет узел newChild в конец списка дочерних элементов этого узла. Если новый дочерний элемент уже находится в дереве, он сначала удаляется. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Создает теневой корень и прикрепляет его к текущему элементу. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Возвращает дубликат этого узла, т. е. служит универсальным конструктором копирования для узлов. Дублирующий узел не имеет родителя (parentNode имеет значение null) и пользовательских данных. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Возвращает дубликат этого узла, т. е. служит универсальным конструктором копирования для узлов. Дублирующий узел не имеет родителя (parentNode имеет значение null) и пользовательских данных. |
| [CreateEvent](../../aspose.html.dom.svg/svgsvgelement/createevent/)(string) | Создает[`Event`](../../aspose.html.dom.events/event/) типа, поддерживаемого реализацией. |
| [CreateSVGAngle](../../aspose.html.dom.svg/svgsvgelement/createsvgangle/)() | Создает объект SVGAngle вне каких-либо деревьев документов. Объект инициализируется значением 0 градусов (безразмерно). |
| [CreateSVGLength](../../aspose.html.dom.svg/svgsvgelement/createsvglength/)() | Создает объект SVGLength вне каких-либо деревьев документов. Объект инициализируется значением 0 пользовательских единиц. |
| [CreateSVGMatrix](../../aspose.html.dom.svg/svgsvgelement/createsvgmatrix/)() | Создает объект SVGMatrix вне каких-либо деревьев документов. Объект инициализируется единичной матрицей. |
| [CreateSVGNumber](../../aspose.html.dom.svg/svgsvgelement/createsvgnumber/)() | Создает объект SVGNumber вне каких-либо деревьев документов. Объект инициализируется нулевым значением. |
| [CreateSVGPoint](../../aspose.html.dom.svg/svgsvgelement/createsvgpoint/)() | Создает объект SVGPoint вне каких-либо деревьев документов. Объект инициализируется точкой (0,0) в пользовательской системе координат. |
| [CreateSVGRect](../../aspose.html.dom.svg/svgsvgelement/createsvgrect/)() | Создает объект SVGRect вне каких-либо деревьев документов. Объект инициализируется таким образом, что все значения установлены на 0 пользовательских единиц. |
| [CreateSVGTransform](../../aspose.html.dom.svg/svgsvgelement/createsvgtransform/)() | Создает объект SVGTransform вне каких-либо деревьев документов. Объект инициализируется преобразованием матрицы идентичности (SVG_TRANSFORM_MATRIX). |
| [CreateSVGTransformFromMatrix](../../aspose.html.dom.svg/svgsvgelement/createsvgtransformfrommatrix/)(SVGMatrix) | Создает объект SVGTransform вне каких-либо деревьев документов. Объект инициализируется заданным матричным преобразованием (т. е. SVG_TRANSFORM_MATRIX). Значения из матрицы параметров копируются, параметр матрицы не принимается как SVGTransform::matrix. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Этот метод позволяет отправлять события в модель событий реализации. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | Извлекает значение атрибута по имени. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | Извлекает узел атрибута по имени. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | Извлекает узел Attr по локальному имени и URI пространства имен. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | Извлекает значение атрибута по локальному имени и URI пространства имен. |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | Возвращает тесную ограничивающую рамку в текущем пользовательском пространстве (т. е. после применения атрибута «преобразования», если таковой имеется) к геометрии всех содержащихся графических элементов, за исключением обводки, обрезки, маскирования и эффектов фильтрации). Обратите внимание, что getBBox должен возвращать фактическую ограничивающую рамку во время вызова метода, даже если элемент еще не был отрендерен. |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | Возвращает матрицу преобразования из текущих пользовательских единиц измерения (т. е. после применения атрибута «преобразование», если таковой имеется) в систему координат окна просмотра для ближайшего элемента ViewportElement. |
| [GetCurrentTime](../../aspose.html.dom.svg/svgsvgelement/getcurrenttime/)() | Возвращает текущее время в секундах относительно времени начала для текущего фрагмента документа SVG. Если getCurrentTime вызывается до начала временной шкалы документа (например, при выполнении скрипта в элементе script перед отправкой события SVGLoad документа), то возвращается 0. |
| [GetElementById](../../aspose.html.dom.svg/svgsvgelement/getelementbyid/)(string) | Ищет в этом фрагменте документа SVG (т. е. поиск ограничен подмножеством дерева документа) элемент, чей идентификатор задается elementId. Если элемент найден, этот элемент возвращается. Если такого элемента не существует, возвращает null. Поведение не определено, если этот идентификатор имеет более одного элемента. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | Возвращает активный объект NodeList, содержащий все элементы документа, имеющие все классы, указанные в аргументе. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | Возвращает NodeList всех элементов-потомков с заданным именем тега в порядке документа. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | Возвращает NodeList всех элементов-потомков с заданным локальным именем и URI пространства имен в порядке документа. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Возвращает матрицу преобразования из текущих пользовательских единиц (т. е. после применения атрибута «преобразования», если таковой имеется) в уведомление родительского пользовательского агента о «пикселе». Для устройств отображения в идеале это представляет собой физический пиксель экрана. Для других устройств или сред, где физические размеры пикселей неизвестны, вместо этого можно использовать алгоритм, аналогичный определению «пикселя» в CSS2. Обратите внимание, что null возвращается, если этот элемент не подключен к дереву документа. Этот метод можно было бы назвать более подходящим как getClientCTM, но имя getScreenCTM сохранено по историческим причинам. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | Возвращает значение true, если атрибут с заданным именем указан в этом элементе или имеет значение по умолчанию, в противном случае — значение false. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | Возвращает значение true, если атрибут с заданным локальным именем и URI пространства имен указан в этом элементе или имеет значение по умолчанию, в противном случае — значение false. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | Возвращает, имеет ли этот узел (если это элемент) какие-либо атрибуты |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Возвращает, есть ли у этого узла дочерние элементы. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Вставляет узел перед существующим дочерним узлом. Если дочерний элемент имеет значение null, вставьте узел в конец списка дочерних элементов. Если дочерний элемент является объектом DocumentFragment, все его дочерние элементы вставляются в том же порядке перед дочерним элементом. Если дочерний элемент уже есть в дереве, он сначала удаляется. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Этот метод проверяет, является ли указанный namespaceURI пространством имен по умолчанию или нет. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Проверяет, равны ли два узла. Этот метод проверяет равенство узлов, а не одинаковость (т. е. являются ли два узла ссылками на один и тот же объект), что можно проверить с помощью Node.isSameNode(). Все одинаковые узлы также будут равными, хотя обратное может быть неверным. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Возвращает, является ли этот узел тем же узлом, что и заданный. Этот метод позволяет определить, ссылаются ли две ссылки Node, возвращаемые реализацией, на один и тот же объект. Когда две ссылки Node являются ссылками на один и тот же объект, даже через прокси, ссылки могут использоваться полностью взаимозаменяемо, так что все атрибуты имеют одинаковые значения и вызов одного и того же метода DOM для любой ссылки всегда имеет одинаковый эффект. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Найдите URI пространства имен, связанный с данным префиксом, начиная с этого узла. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Найдите префикс, связанный с данным URI пространства имен, начиная с этого узла. Объявления пространств имен по умолчанию игнорируются этим методом. Подробнее об алгоритме, используемом этим методом, см. в разделе Поиск префикса пространства имен. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Помещает все узлы Text на всю глубину поддерева под этим узлом, включая узлы атрибутов, в «нормальную» форму, где только структура (например, элементы, комментарии, инструкции по обработке, разделы CDATA и ссылки на сущности) разделяет текст узлов, т. е. нет ни смежных узлов Text, ни пустых узлов Text. Это можно использовать для обеспечения того, чтобы DOM-представление документа было таким же, как если бы он был сохранен и повторно загружен, и полезно, когда операции (такие как поиск XPointer [XPointer]), которые зависят от конкретной древовидной структуры документа, должны выполняться. использоваться. Если параметр «normalize-characters» объекта DOMConfiguration, прикрепленного к Node.ownerDocument, имеет значение true, этот метод также полностью нормализует символы узлов Text. |
| [PauseAnimations](../../aspose.html.dom.svg/svgsvgelement/pauseanimations/)() | Приостанавливает (т. е. приостанавливает) все запущенные в данный момент анимации, которые определены в фрагменте документа SVG, соответствующем этому элементу 'svg', в результате чего часы анимации, соответствующие этому фрагменту документа, останавливаются до тех пор, пока они не будут приостановлены. |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | Возвращает первый элемент в документе, соответствующий selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | Возвращает NodeList всех элементов в документе, которые соответствуют selector |
| [Remove](../../aspose.html.dom/element/remove/)() | Удаляет этот экземпляр. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | Удаляет атрибут по имени. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | Удаляет указанный узел атрибута. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | Удаляет атрибут по локальному имени и URI пространства имен. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Удаляет дочерний узел, указанный oldChild, из списка дочерних элементов и возвращает его. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../../aspose.html.dom/eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild на newChild в списке дочерних элементов и возвращает узел oldChild. Если newChild является объектом DocumentFragment, то oldChild заменяется всеми дочерними элементами DocumentFragment, которые вставляются в том же порядке. Если новый дочерний элемент уже находится в дереве, он сначала удаляется. |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | Добавляет новый атрибут. Если атрибут с таким именем уже присутствует в элементе, его значение изменяется на значение параметра . |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | Добавляет новый узел атрибута. Если атрибут с таким именем (nodeName) уже присутствует в элементе, он заменяется новым. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | Добавляет новый атрибут. Если атрибут с таким локальным именем и этим URI пространства имен уже присутствует в элементе, он заменяется новым. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | Добавляет новый атрибут. Если атрибут с тем же локальным именем и URI пространства имен уже присутствует в элементе, его префикс изменяется на префиксную часть квалифицированного имени, а его значение изменяется на параметр значения. |
| [SetCurrentTime](../../aspose.html.dom.svg/svgsvgelement/setcurrenttime/)(float) | Настраивает часы для этого фрагмента документа SVG, устанавливая новое текущее время. Если setCurrentTime вызывается до начала временной шкалы документа (например, при выполнении скрипта в элементе script перед отправкой события SVGLoad документа), то значение секунд в последнем вызове метода дает время, которое документ будет искать после начала временной шкалы документа. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | Если параметр isId имеет значение true, этот метод объявляет указанный атрибут как определяемый пользователем атрибут ID. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | Если параметр isId имеет значение true, этот метод объявляет указанный атрибут как определяемый пользователем атрибут ID. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | Если параметр isId имеет значение true, этот метод объявляет указанный атрибут как определяемый пользователем атрибут ID. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | ВозвращаетString который представляет этот экземпляр. |
| [UnpauseAnimations](../../aspose.html.dom.svg/svgsvgelement/unpauseanimations/)() | Разблокирует (т.е. возобновляет паузу) текущую анимацию, которая определена во фрагменте документа SVG, в результате чего часы анимации продолжаются с того момента, когда они были приостановлены. |

### Смотрите также

* class [SVGGraphicsElement](../svggraphicselement/)
* interface [ISVGFitToViewBox](../isvgfittoviewbox/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IViewCSS](../../aspose.html.dom.css/iviewcss/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* interface [ISVGZoomAndPan](../isvgzoomandpan/)
* пространство имен [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* сборка [Aspose.HTML](../../)



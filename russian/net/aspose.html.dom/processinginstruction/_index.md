---
title: Class ProcessingInstruction
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.ProcessingInstruction сорт. ProcessingInstruction представляет собой инструкцию по обработке используемую в XML как способ сохранения информации о процессоре в тексте документа.
type: docs
weight: 1020
url: /ru/net/aspose.html.dom/processinginstruction/
---
## ProcessingInstruction class

ProcessingInstruction представляет собой «инструкцию по обработке», используемую в XML как способ сохранения информации о процессоре в тексте документа.

```csharp
public class ProcessingInstruction : CharacterData
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | NamedNodeMap, содержащий атрибуты этого узла (если это элемент) или null в противном случае. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | Абсолютный базовый URI этого узла или ноль, если реализация не смогла получить абсолютный URI. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | NodeList, содержащий все дочерние элементы этого узла. Если нет детей, это NodeList, не содержащий узлов.. |
| virtual [Data](../../aspose.html.dom/characterdata/data/) { get; set; } | Символьные данные узла, реализующего этот интерфейс. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Первый дочерний элемент этого узла. Если такого узла нет, возвращается null. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Последний дочерний элемент этого узла. Если такого узла нет, возвращается null. |
| [Length](../../aspose.html.dom/characterdata/length/) { get; } | Количество 16-битных единиц, доступных через данные и метод substringData ниже. Это может иметь нулевое значение, т. е. узлы CharacterData могут быть пустыми. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Возвращает локальную часть полного имени этого узла. Для узлов любого типа, кроме ELEMENT_NODE и ATTRIBUTE_NODE, и узлов, созданных с помощью метода DOM уровня 1, такого как Document.createElement(), всегда равно null. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | URI пространства имен этого узла или null, если он не указан. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Узел, следующий непосредственно за этим узлом. Если такого узла нет, возвращается null. |
| override [NodeName](../../aspose.html.dom/processinginstruction/nodename/) { get; } | Имя этого узла в зависимости от его типа. |
| override [NodeType](../../aspose.html.dom/processinginstruction/nodetype/) { get; } | Код, представляющий тип базового объекта. |
| override [NodeValue](../../aspose.html.dom/processinginstruction/nodevalue/) { get; set; } | Значение этого узла в зависимости от его типа. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Объект документа, связанный с этим узлом. Это также объект Document, используемый для создания новых узлов. Когда этот узел является документом или типом документа, который еще не используется ни с одним документом, это значение равно null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Получает родителя[`Element`](../element/) этого узла. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Родитель этого узла. Все узлы, кроме Attr, Document, DocumentFragment, Entity и Notation, могут иметь родителя. Однако, если узел был только что создан и еще не добавлен в дерево, или если он был удален из дерева, это значение null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Префикс пространства имен этого узла или нуль, если он не указан. Когда он определен как нуль, его установка не имеет никакого эффекта |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Узел, непосредственно предшествующий этому узлу. Если такого узла нет, возвращается null. |
| [Target](../../aspose.html.dom/processinginstruction/target/) { get; } | Цель этой инструкции обработки. |
| override [TextContent](../../aspose.html.dom/processinginstruction/textcontent/) { get; set; } | Этот атрибут возвращает текстовое содержимое этого узла и его потомков. Когда он определен как null, его установка не имеет никакого эффекта. При настройке любые возможные дочерние элементы, которые может иметь этот узел, удаляются и, если новая строка не является пустой или нулевой, заменяются одним текстовым узлом, содержащим строку, на которую установлен этот атрибут. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Этот метод позволяет регистрировать прослушиватели событий в цели события. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Добавляет узел newChild в конец списка дочерних элементов этого узла. Если новый дочерний элемент уже находится в дереве, он сначала удаляется. |
| virtual [AppendData](../../aspose.html.dom/characterdata/appenddata/)(string) | Добавить строку в конец символьных данных узла. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Возвращает дубликат этого узла, т. е. служит универсальным конструктором копирования для узлов. Дублирующий узел не имеет родителя (parentNode имеет значение null) и пользовательских данных. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Возвращает дубликат этого узла, т. е. служит универсальным конструктором копирования для узлов. Дублирующий узел не имеет родителя (parentNode имеет значение null) и пользовательских данных. |
| virtual [DeleteData](../../aspose.html.dom/characterdata/deletedata/)(int, int) | Удалить диапазон 16-битных единиц из узла. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Этот метод позволяет отправлять события в модель событий реализации. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Возвращает, имеет ли этот узел (если это элемент) какие-либо атрибуты |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Возвращает, есть ли у этого узла дочерние элементы. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Вставляет узел перед существующим дочерним узлом. Если дочерний элемент имеет значение null, вставьте узел в конец списка дочерних элементов. Если дочерний элемент является объектом DocumentFragment, все его дочерние элементы вставляются в том же порядке перед дочерним элементом. Если дочерний элемент уже есть в дереве, он сначала удаляется. |
| virtual [InsertData](../../aspose.html.dom/characterdata/insertdata/)(int, string) | Вставить строку с указанным 16-битным смещением. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Этот метод проверяет, является ли указанный namespaceURI пространством имен по умолчанию или нет. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Проверяет, равны ли два узла. Этот метод проверяет равенство узлов, а не одинаковость (т. е. являются ли два узла ссылками на один и тот же объект), что можно проверить с помощью Node.isSameNode(). Все одинаковые узлы также будут равными, хотя обратное может быть неверным. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Возвращает, является ли этот узел тем же узлом, что и заданный. Этот метод позволяет определить, ссылаются ли две ссылки Node, возвращаемые реализацией, на один и тот же объект. Когда две ссылки Node являются ссылками на один и тот же объект, даже через прокси, ссылки могут использоваться полностью взаимозаменяемо, так что все атрибуты имеют одинаковые значения и вызов одного и того же метода DOM для любой ссылки всегда имеет одинаковый эффект. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Найдите URI пространства имен, связанный с данным префиксом, начиная с этого узла. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Найдите префикс, связанный с данным URI пространства имен, начиная с этого узла. Объявления пространств имен по умолчанию игнорируются этим методом. Подробнее об алгоритме, используемом этим методом, см. в разделе Поиск префикса пространства имен. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Помещает все узлы Text на всю глубину поддерева под этим узлом, включая узлы атрибутов, в «нормальную» форму, где только структура (например, элементы, комментарии, инструкции по обработке, разделы CDATA и ссылки на сущности) разделяет текст узлов, т. е. нет ни смежных узлов Text, ни пустых узлов Text. Это можно использовать для обеспечения того, чтобы DOM-представление документа было таким же, как если бы он был сохранен и повторно загружен, и полезно, когда операции (такие как поиск XPointer [XPointer]), которые зависят от конкретной древовидной структуры документа, должны выполняться. использоваться. Если параметр «normalize-characters» объекта DOMConfiguration, прикрепленного к Node.ownerDocument, имеет значение true, этот метод также полностью нормализует символы узлов Text. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Удаляет дочерний узел, указанный oldChild, из списка дочерних элементов и возвращает его. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Этот метод позволяет удалить прослушиватели событий из цели события. Если[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) удаляется из[`EventTarget`](../eventtarget/) пока он обрабатывает событие, он не будет запущен текущими действиями. Прослушиватели событий никогда не могут быть вызваны после удаления. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Заменяет дочерний узел oldChild на newChild в списке дочерних элементов и возвращает узел oldChild. Если newChild является объектом DocumentFragment, то oldChild заменяется всеми дочерними элементами DocumentFragment, которые вставляются в том же порядке. Если новый дочерний элемент уже находится в дереве, он сначала удаляется. |
| virtual [ReplaceData](../../aspose.html.dom/characterdata/replacedata/)(int, int, string) | Заменить символы, начинающиеся с указанного 16-битного смещения, указанной строкой. |
| virtual [SubstringData](../../aspose.html.dom/characterdata/substringdata/)(int, int) | Извлекает диапазон данных из узла. |
| override [ToString](../../aspose.html.dom/characterdata/tostring/)() | ВозвращаетString который представляет этот экземпляр. |

### Смотрите также

* class [CharacterData](../characterdata/)
* пространство имен [Aspose.Html.Dom](../../aspose.html.dom/)
* сборка [Aspose.HTML](../../)



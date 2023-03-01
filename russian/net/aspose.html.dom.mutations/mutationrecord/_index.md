---
title: Class MutationRecord
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Mutations.MutationRecord сорт. MutationRecord представляет собой индивидуальную мутацию DOM. Это объект который передаетсяMutationObserver сMutationCallback .
type: docs
weight: 990
url: /ru/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord представляет собой индивидуальную мутацию DOM. Это объект, который передается[`MutationObserver`](../mutationobserver/) с[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | Вернуть добавленные узлы. |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | Возвращает локальное имя измененного атрибута и null в противном случае. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | Возвращает пространство имен измененного атрибута, иначе null. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | Возвращает следующего родственного узла добавленных или удаленных узлов или null. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | Возвращаемое значение зависит от типа. Для «атрибутов» это значение измененного атрибута до изменения. Для «characterData» это данные измененного узла до изменения. Для «childList» это значение null. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | Возвращает предыдущий одноуровневый узел добавленных или удаленных узлов или null. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | Вернуть удаленные узлы. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | Возвращает узел, на который повлияла мутация, в зависимости от типа. Для «атрибутов» это элемент, атрибут которого изменился. Для «characterData» это узел CharacterData. Для "childList" это узел, чьи дочерние элементы изменились. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | Возвращает «атрибуты», если это была мутация атрибута, «characterData», если это была мутация узла CharacterData, и «childList», если это была мутация дерева узлов. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject/)
* пространство имен [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* сборка [Aspose.HTML](../../)



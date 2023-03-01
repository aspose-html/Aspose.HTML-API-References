---
title: Class MutationObserver
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Mutations.MutationObserver сорт. АMutationObserver объект можно использовать для наблюдения за мутациями в деревеNode .
type: docs
weight: 970
url: /ru/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

А`MutationObserver` объект можно использовать для наблюдения за мутациями в дереве[`Node`](../../aspose.html.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Создает объект MutationObserver и устанавливает его[`MutationCallback`](../mutationcallback/) для обратного звонка. Обратный вызов вызывается со списком объектов MutationRecord в качестве первого аргумента и созданным объектом MutationObserver в качестве второго аргумента. Он вызывается после того, как узлы зарегистрированы в!:Observe(Node, IMutationObserverInit) метод, мутировали. |

## Методы

| Имя | Описание |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | Запрещает наблюдателю наблюдать за любыми мутациями. Пока метод наблюдать() не будет использован снова, обратный вызов наблюдателя не будет вызван. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Указывает пользовательскому агенту наблюдать за заданной целью (узлом) и сообщать о любых мутациях на основе критериев, заданных опциями (объект). Аргумент options позволяет устанавливать параметры наблюдения за мутациями через элементы объекта. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Указывает пользовательскому агенту наблюдать за заданной целью (узлом) и сообщать о любых мутациях на основе критериев, заданных опциями (объект). Аргумент options позволяет устанавливать параметры наблюдения за мутациями через элементы объекта. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | Метод возвращает копию очереди записей, а затем очищает очередь записей. |

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject/)
* пространство имен [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* сборка [Aspose.HTML](../../)



---
title: "Класс MutationObserver"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.mutations.MutationObserver class. Объект может использоваться для наблюдения за мутациями дерева"
type: docs

url: /ru/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Объект может использоваться для наблюдения за мутациями дерева [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Создаёт объект MutationObserver и задаёт его [`MutationCallback`](../mutationcallback/) как callback. Callback вызывается со списком объектов MutationRecord в качестве первого аргумента и созданным объектом MutationObserver в качестве второго аргумента. Он вызывается после того, как узлы, зарегистрированные методом !:Observe(Node, IMutationObserverInit), были изменены. |

## Методы

| Имя | Описание |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Останавливает наблюдатель от отслеживания любых мутаций. Пока метод observe() не будет использован снова, callback наблюдателя не будет вызываться. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Инструктирует пользовательский агент наблюдать за указанной целью (узлом) и сообщать о любых мутациях в соответствии с критериями, заданными параметром options (объект). Параметр options позволяет задавать параметры наблюдения за мутациями через свойства объекта. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Инструктирует пользовательский агент наблюдать за указанной целью (узлом) и сообщать о любых мутациях в соответствии с критериями, заданными параметром options (объект). Параметр options позволяет задавать параметры наблюдения за мутациями через свойства объекта. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | Метод возвращает копию очереди записей и затем очищает очередь записей. |

### См. также

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)

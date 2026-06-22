---
title: "MutationRecord Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.mutations.MutationRecord class. MutationRecord представляет отдельную мутацию DOM. Это объект, который передаётся в MutationObservers MutationCallback"
type: docs

url: /ru/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord представляет отдельную мутацию DOM. Это объект, который передаётся в [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Возвращает добавленные узлы. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Возвращает локальное имя изменённого атрибута, иначе null. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Возвращает пакет изменённого атрибута, иначе null. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Возвращает следующий соседний узел добавленных или удалённых узлов, либо null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) Возвращаемое значение зависит от типа. Для \"attributes\" это значение изменённого атрибута до изменения. Для \"characterData\" это данные изменённого узла до изменения. Для \"childList\" это null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Возвращает предыдущий соседний узел добавленных или удалённых узлов, либо null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Возвращает удалённые узлы. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Возвращает узел, затронутый мутацией, в зависимости от типа. Для \"attributes\" это элемент, у которого изменился атрибут. Для \"characterData\" это узел CharacterData. Для \"childList\" это узел, у которого изменились дочерние элементы. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Возвращает \"attributes\", если это была мутация атрибута, \"characterData\", если это была мутация узла CharacterData, и \"childList\", если это была мутация дерева узлов. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |

### См. также

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)

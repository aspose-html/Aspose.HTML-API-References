---
title: "Element.AttachShadow"
second_title: "Справочник API Aspose.HTML для Java"
description: "Element метод. Создаёт shadow root и присоединяет его к текущему элементу"
type: docs

url: /ru/java/com.aspose.html.dom/element/attachshadow/
---
## Element.AttachShadow method

Создаёт теневой корень и присоединяет его к текущему элементу.

```java
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | ShadowRootMode | Режим, в котором будет создан shadow root. |

### Возвращаемое значение

Создан [`ShadowRoot`](../../shadowroot/).

### Исключения

| исключение | условие |
| --- | --- |
| Ошибка | NotSupportedError: Element не поддерживает shadow tree. |
| Ошибка | InvalidStateError: Element уже имеет shadow tree. |

### См. также

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

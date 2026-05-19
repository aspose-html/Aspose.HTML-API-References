---
title: "ICSS2Properties.Speak"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство ICSS2Properties. Это свойство определяет, будет ли текст воспроизводиться аудиально и, если да, каким образом, отчасти аналогично свойству display. Возможные значения:"
type: docs

url: /ru/java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

Это свойство определяет, будет ли текст воспроизводиться аудиально и, если да, каким образом (отчасти аналогично свойству ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) ). Возможные значения:

none - Подавляет аудиальное отображение, так что элемент не требует времени на рендеринг. Однако обратите внимание, что потомки могут переопределить это значение и будут озвучены. (Чтобы гарантировать подавление отображения элемента и его потомков, используйте свойство ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) ).normal - Использует зависящие от языка правила произношения для отображения элемента и его дочерних элементов. spell-out - Произносит текст по одной букве (полезно для акронимов и аббревиатур).

```java
public String Speak { get; set; }
```

### Возвращаемое значение

свойство speak

### См. также

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

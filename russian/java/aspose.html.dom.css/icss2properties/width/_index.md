---
title: "ICSS2Properties.Width"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство ICSS2Properties. Это свойство указывает ширину содержимого блоков, генерируемых блочными и заменяемыми элементами."
type: docs

url: /ru/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Это свойство указывает [ширину содержимого](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) блоков, генерируемых блочными и [заменяемыми](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) элементами.

Это свойство не применяется к неперезаписанным [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) элементам. Ширина коробок неперезаписанного встроенного элемента соответствует ширине отрисованного содержимого внутри них (до любого относительного смещения дочерних элементов). Помните, что встроенные коробки переходят в [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). Ширина строковых коробок задаётся их [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block), но может быть уменьшена присутствием [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

Ширина коробки заменяемого элемента является [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) и может быть масштабирована пользовательским агентом, если значение этого свойства отличается от 'auto'.

Значения имеют следующее значение:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Задает фиксированную ширину.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Задает ширину в процентах. Процент рассчитывается относительно ширины генерируемой коробки [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block).auto - Ширина зависит от значений других свойств. См. разделы ниже. Примечание: Отрицательные значения для ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) недопустимы.

```java
public String Width { get; set; }
```

### Возвращаемое значение

свойство width

### См. также

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

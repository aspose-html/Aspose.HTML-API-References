---
title: "ICSSRuleList Interface"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.ICSSRuleList interface. CSSRuleList представляет упорядоченную коллекцию только для чтения объектов CSSRule."
type: docs

url: /ru/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList представляет упорядоченную коллекцию только для чтения объектов [`CSSRule`](../icssrule/).

Хотя объект CSSRuleList доступен только для чтения и не может быть изменён напрямую, он считается живым объектом, поскольку его содержимое может изменяться со временем.

Чтобы изменить базовые правила, возвращаемые объектами [`CSSRule`](../icssrule/), используйте CSSStyleSheet.insertRule() и CSSStyleSheet.deleteRule(), которые являются методами [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Используется для получения CSS‑правила методом item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). Порядок в этой коллекции соответствует порядку правил в таблице стилей CSS. Если индекс больше или равен количеству правил в списке, возвращается null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) Свойство length интерфейса `CSSRuleList` возвращает количество объектов [`CSSRule`](../icssrule/) в списке. |

### См. также

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

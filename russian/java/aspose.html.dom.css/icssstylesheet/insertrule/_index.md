---
title: "ICSSStyleSheet.InsertRule"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ICSSStyleSheet. Метод CSSStyleSheet.insertRule вставляет новое CSS‑правило в текущий стиль с некоторыми ограничениями"
type: docs

url: /ru/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

Метод CSSStyleSheet.insertRule() вставляет новое CSS‑правило в текущую таблицу стилей с некоторыми ограничениями.

Примечание: хотя insertRule() является исключительно методом [`CSSStyleSheet`](../), он фактически вставляет правило в CSSStyleSheet.cssRules — его внутренний [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| правило | String | Строка, содержащая правило для вставки. Содержание вставляемого правила зависит от его типа: |
| index | Int32 | Положительное целое число, не превышающее значение stylesheet.cssRules.length, представляющее позицию нового вставленного правила в CSSStyleSheet.cssRules. Значение по умолчанию — 0. |

### Возвращаемое значение

Индекс вновь вставленного правила в списке правил таблицы стилей.

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### См. также

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

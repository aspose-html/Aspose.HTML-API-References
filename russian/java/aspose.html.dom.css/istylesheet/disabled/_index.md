---
title: "IStyleSheet.Disabled"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство IStyleSheet. Свойство disabled интерфейса StyleSheet определяет, предотвращено ли применение таблицы стилей к документу."
type: docs

url: /ru/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

Свойство disabled интерфейса [`StyleSheet`](../) определяет, предотвращено ли применение таблицы стилей к документу.

Таблица стилей может быть отключена путем ручной установки этого свойства в true или если это неактивная альтернативная таблица стилей. Заметьте, что disabled == false не гарантирует применение таблицы стилей (она может быть удалена из документа, например).

Изменение этого атрибута может вызвать новое вычисление стилей для документа. Таблица стилей применяется только если присутствует соответствующее определение среды и атрибут disabled имеет значение false. Поэтому, если среда не подходит текущему агенту пользователя, атрибут disabled игнорируется.

```java
public bool Disabled { get; set; }
```

### Возвращаемое значение

Атрибут disabled при чтении должен возвращать true, если флаг disabled установлен, или false в противном случае. При установке атрибут disabled должен установить флаг disabled, если новое значение равно true, или снять флаг disabled в противном случае.

### Property Value

Атрибут disabled при чтении должен возвращать true, если флаг disabled установлен, или false в противном случае. При установке атрибут disabled должен установить флаг disabled, если новое значение равно true, или снять флаг disabled в противном случае.

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### См. также

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

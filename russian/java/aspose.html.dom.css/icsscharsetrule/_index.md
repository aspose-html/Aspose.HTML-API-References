---
title: "Интерфейс ICSSCharsetRule"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.css.ICSSCharsetRule. Интерфейс CSSCharsetRule представляет правило charset в таблице стилей CSS. Значение атрибута encoding не влияет на кодировку текстовых данных в объектах DOM — эта кодировка всегда UTF-16. После загрузки таблицы стилей значение атрибута encoding соответствует значению, найденному в правиле charset. Если в исходном документе не было charset, то CSSCharsetRule не создаётся. Значение атрибута encoding также может использоваться как подсказка для кодировки, применяемой при сериализации таблицы стилей."
type: docs

url: /ru/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

Интерфейс CSSCharsetRule представляет правило @charset в таблице стилей CSS. Значение атрибута encoding не влияет на кодировку текстовых данных в объектах DOM; эта кодировка всегда UTF-16. После загрузки таблицы стилей значение атрибута encoding равно значению, найденному в правиле @charset. Если в исходном документе не было @charset, то объект CSSCharsetRule не создаётся. Значение атрибута encoding также может использоваться как подсказка для кодировки, применяемой при сериализации таблицы стилей.

```java
public interface ICSSCharsetRule : ICSSRule
```

## Свойства

| Имя | Описание |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### См. также

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

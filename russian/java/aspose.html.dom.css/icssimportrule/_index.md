---
title: "Интерфейс ICSSImportRule"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.css.ICSSImportRule. Интерфейс CSSImportRule представляет правило @import в таблице стилей CSS. Правило импорта используется для импорта правил стилей из других таблиц стилей."
type: docs

url: /ru/java/com.aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

Интерфейс CSSImportRule представляет правило @import в таблице стилей CSS. Правило @import используется для импорта правил стилей из других таблиц стилей.

```java
public interface ICSSImportRule : ICSSRule
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getHref](../../com.aspose.html.dom.css/icssimportrule/href/) Свойство href только для чтения интерфейса CSSImportRule возвращает URL, указанный в at‑rule @import. |
| [getMedia](../../com.aspose.html.dom.css/icssimportrule/media/) Свойство media только для чтения интерфейса CSSImportRule возвращает объект MediaList, содержащий значение атрибута media связанной таблицы стилей. |
| [getStyleSheet](../../com.aspose.html.dom.css/icssimportrule/stylesheet/) Таблица стилей, на которую ссылается это правило, если она была загружена. Значение этого атрибута равно null, если таблица стилей ещё не загружена или не будет загружена (например, если таблица стилей предназначена для типа media, не поддерживаемого пользовательским агентом). |

### См. также

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

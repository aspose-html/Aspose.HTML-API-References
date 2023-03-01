---
title: Interface ICSSImportRule
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Css.ICSSImportRule интерфейс. Интерфейс CSSImportRule представляет правило import в таблице стилей CSS. Правило import используется для импорта правил стиля из других таблиц стилей.
type: docs
weight: 410
url: /ru/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

Интерфейс CSSImportRule представляет правило @import в таблице стилей CSS. Правило @import используется для импорта правил стиля из других таблиц стилей.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | Расположение импортируемой таблицы стилей. Атрибут не будет содержать спецификатор "url(...)" вокруг URI. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | Список типов носителей, для которых может использоваться эта таблица стилей. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | Таблица стилей, на которую ссылается это правило, если она была загружена. Значение этого атрибута равно null, если таблица стилей еще не загружена или не будет загружена (например, если таблица стилей предназначена для типа носителя, не поддерживаемого пользовательским агентом). |

### Смотрите также

* interface [ICSSRule](../icssrule/)
* пространство имен [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* сборка [Aspose.HTML](../../)



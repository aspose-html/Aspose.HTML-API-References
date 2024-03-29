---
title: Class DOMTokenList
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Collections.DOMTokenList сорт. Класс DOMTokenList представляет набор токенов разделенных пробелами. Он индексируется начиная с 0 как и объекты массива JavaScript. DOMTokenList всегда чувствителен к регистру.
type: docs
weight: 20
url: /ru/net/aspose.html.collections/domtokenlist/
---
## DOMTokenList class

Класс DOMTokenList представляет набор токенов, разделенных пробелами. Он индексируется, начиная с 0, как и объекты массива JavaScript. DOMTokenList всегда чувствителен к регистру.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.html.collections/domtokenlist/item/) { get; } | Возвращает элемент в списке по его индексу или null, если индекс больше или равен длине списка. |
| [Length](../../aspose.html.collections/domtokenlist/length/) { get; } | Возвращает ulong, представляющий количество токенов, хранящихся в этом списке. |
| [Value](../../aspose.html.collections/domtokenlist/value/) { get; set; } | Получает или задает значение соответствующего атрибута. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.html.collections/domtokenlist/add/)(params string[]) | Добавляет указанные токены в список. |
| [Contains](../../aspose.html.collections/domtokenlist/contains/)(string) | Возвращает true, если список содержит данный токен, иначе false. |
| [GetEnumerator](../../aspose.html.collections/domtokenlist/getenumerator/)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [Remove](../../aspose.html.collections/domtokenlist/remove/)(params string[]) | Удаляет указанные токены из списка. |
| [Replace](../../aspose.html.collections/domtokenlist/replace/)(string, string) | Заменяет существующий токен новым токеном. Ничего не делает, если первый токен не существует. |
| [Supports](../../aspose.html.collections/domtokenlist/supports/)(string) | Возвращает true, если данный токен находится в поддерживаемых токенах связанного атрибута. |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle)(string) | Удаляет токен из списка, если он существует, или добавляет токен в список, если его нет. |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle_1)(string, bool?) | Удаляет токен из списка, если он существует, или добавляет токен в список, если его нет. |

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject/)
* пространство имен [Aspose.Html.Collections](../../aspose.html.collections/)
* сборка [Aspose.HTML](../../)



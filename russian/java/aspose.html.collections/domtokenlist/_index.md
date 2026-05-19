---
title: "DOMTokenList Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.collections.DOMTokenList класс. Класс DOMTokenList представляет набор токенов, разделённых пробелами. Он индексируется, начиная с 0, как и объекты массива JavaScript. DOMTokenList всегда чувствителен к регистру."
type: docs

url: /ru/java/com.aspose.html.collections/domtokenlist/
---
## DOMTokenList class

Класс DOMTokenList представляет набор токенов, разделённых пробелами. Он индексируется, начиная с 0, как объекты JavaScript Array. DOMTokenList всегда чувствителен к регистру.

```java
public class DOMTokenList : DOMObject, IEnumerable<String>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getItem](../../com.aspose.html.collections/domtokenlist/item/) Возвращает элемент списка по его индексу или null, если индекс больше или равен длине списка. |
| [getLength](../../com.aspose.html.collections/domtokenlist/length/) Возвращает значение типа ulong, представляющее количество токенов, хранящихся в этом списке. |
[getValue]
[setValue] Gets or sets the value of a corresponding attribute. |

## Методы

| Имя | Описание |
| --- | --- |
| [add](../../com.aspose.html.collections/domtokenlist/add/)(params String[]) | Добавляет указанные токены в список. |
| [contains](../../com.aspose.html.collections/domtokenlist/contains/)(String) | Возвращает true, если список содержит указанный токен, иначе false. |
| [getEnumerator](../../com.aspose.html.collections/domtokenlist/getenumerator/)() | Возвращает перечислитель, который проходит по коллекции. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [remove](../../com.aspose.html.collections/domtokenlist/remove/)(params String[]) | Удаляет указанные токены из списка. |
| [replace](../../com.aspose.html.collections/domtokenlist/replace/)(String, String) | Заменяет существующий токен новым токеном. Не делает ничего, если первый токен не существует. |
| [supports](../../com.aspose.html.collections/domtokenlist/supports/)(String) | Возвращает true, если данный токен присутствует в поддерживаемых токенах связанного атрибута. |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle)(String) | Удаляет токен из списка, если он существует, или добавляет токен в список, если его нет. |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle_1)(String, bool) | Удаляет токен из списка, если он существует, или добавляет токен в список, если его нет. |

### См. также

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)

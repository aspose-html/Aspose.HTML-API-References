---
title: "Интерфейс IDocumentCSS"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.IDocumentCSS interface. Этот интерфейс представляет документ с представлением CSS."
type: docs

url: /ru/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Этот интерфейс представляет документ с представлением CSS.

Метод getOverrideStyle предоставляет механизм, позволяющий автору DOM немедленно изменить стиль элемента без изменения явно подключённых таблиц стилей документа или встроенного стиля элементов в таблицах стилей. Эта таблица стилей располагается после таблицы стилей автора в алгоритме каскада и называется таблицей переопределяющих стилей. Таблица переопределяющих стилей имеет приоритет над таблицами стилей автора. Объявление "!important" по‑прежнему имеет приоритет над обычным объявлением. Таблицы переопределяющих, авторских и пользовательских стилей могут содержать объявления "!important". Правила пользователя "!important" имеют приоритет над правилами переопределяющих и авторских "!important", а правила переопределяющих "!important" имеют приоритет над авторскими "!important".

Ожидается, что экземпляр интерфейса DocumentCSS можно получить, используя методы приведения типов, специфичные для привязки, к экземпляру интерфейса Document.

Смотрите также [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Методы

| Имя | Описание |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Этот метод используется для получения объявления переопределяющего стиля для указанного элемента и указанного псевдоэлемента. |

### См. также

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

---
title: "IDocumentCSS Интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.IDocumentCSS интерфейс. Этот интерфейс представляет документ с представлением CSS."
type: docs

url: /ru/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Этот интерфейс представляет документ с представлением CSS.

Метод getOverrideStyle предоставляет механизм, с помощью которого автор DOM может немедленно изменить стиль элемента, не изменяя явно связанные таблицы стилей документа или встроенный стиль элементов в таблицах стилей. Эта таблица стилей располагается после таблицы стилей автора в алгоритме каскада и называется таблицей переопределения стилей. Таблица переопределения стилей имеет приоритет над таблицами стилей автора. Объявление "!important" по‑прежнему имеет приоритет над обычным объявлением. Таблицы стилей переопределения, автора и пользователя могут содержать объявления "!important". Правила пользователя "!important" имеют приоритет над правилами переопределения и автора "!important", а правила переопределения "!important" имеют приоритет над правилами автора "!important".

Ожидается, что экземпляр интерфейса DocumentCSS можно получить, используя методы приведения, специфичные для привязки, к экземпляру интерфейса Document.

Смотрите также [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Методы

| Имя | Описание |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Этот метод используется для получения объявления переопределяющего стиля для указанного элемента и указанного псевдо‑элемента. |

### См. также

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

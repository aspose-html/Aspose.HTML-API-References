---
title: "Document.GetElementById"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Метод Document getElementById возвращает объект Element, представляющий элемент, у свойства id которого совпадает указанная строка String. Поскольку идентификаторы элементов должны быть уникальными, если они указаны, они являются удобным способом быстро получить доступ к конкретному элементу."
type: docs

url: /ru/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Метод Document getElementById() возвращает объект [`Element`](../../element/), представляющий элемент, у свойства id которого совпадает указанная строка String. Поскольку идентификаторы элементов должны быть уникальными, если они указаны, они являются удобным способом быстро получить доступ к конкретному элементу.

Если вам нужно получить доступ к элементу, у которого нет ID, вы можете использовать querySelector() для поиска элемента с помощью любого селектора.

```java
public Element GetElementById(String elementId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| elementId | String | ID элемента, который нужно найти. ID — чувствительная к регистру строка String, уникальная в пределах документа; только один элемент может иметь данный ID. |

### Возвращаемое значение

Объект [`Element`](../../element/), описывающий объект DOM‑элемента, соответствующий указанному ID, или null, если в документе не найдено подходящего элемента.

## Примечания

Обратитесь к официальной [спецификации](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

Практический контент по веб‑разработке можно найти на [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
// HTML‑контент
<div id="uniqueIdentifier">Container with ID - identifier</div>

// Код C#
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// Здесь размещается пользовательский код
   }
```

// Вывод в консоль

Контейнер с ID — идентификатор

*inputHtmlPath - user input html file path

### См. также

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

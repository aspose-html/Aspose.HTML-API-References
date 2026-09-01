---
title: "Element.GetElementsByTagNameNS"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Element. Возвращает объект HTMLCollection, содержащий все элементы с заданным локальным именем и строкой URI пакета в порядке следования в документе"
type: docs

url: /ru/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Возвращает объект [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/), содержащий все [`elements`](../) с заданным локальным именем и строкой URI пакета в порядке следования в документе.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| packageURI | String | Представление строки URI пакета. |
| localName | String | Строковое представление локального имени. |

### Возвращаемое значение

[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) объект представляет собой массивоподобный список [`elements`](../).

## Примечания

Обратитесь к официальной [спецификации](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens).

Возможно, вас также заинтересует [документация](https://docs.aspose.com/html/net/).

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
# .xhtml input file content
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com">
<head>
	<meta charset="UTF-8"/>
	<link rel="stylesheet" href="/styles/main.css"/>
	<title>Title</title>
</head>
<body>
<custom:customtag>
	Custom package custom tag content goes here...
</custom:customtag>
</body>
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// Здесь размещается пользовательский код

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Здесь размещается пользовательский код
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Найдено: 1

Здесь размещается пользовательский контент пользовательского тега пакета...

### См. также

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

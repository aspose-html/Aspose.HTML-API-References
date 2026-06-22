---
title: "Element.GetElementsByClassName"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Element. Возвращает объект HTMLCollection, содержащий все элементы внутри element, имеющие все классы, указанные в аргументе"
type: docs

url: /ru/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Возвращает объект [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) , содержащий все элементы внутри [`element`](../), имеющие все классы, указанные в аргументе.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classNames | String | Строка String String, содержащая неупорядоченный набор уникальных токенов, разделённых пробелами, представляющих классы (имена классов) |

### Возвращаемое значение

[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) объект представляет собой массивоподобный список [`elements`](../).

## Примечания

Обратитесь к официальной [спецификации](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname).

Возможно, вас также заинтересует [документация](https://docs.aspose.com/html/net/).

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
# HTML source content
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Title</title>
</head>
<body>
<div id="divElementContainerId">
	<p class="pStyle">The paragraph styled pStyle class content...</p>
	<p>The second paragraph content...</p>
	<p>The third paragraph content...</p>
	<div class="pStyle">The div element styled pStyle class...</div>
</div>
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

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Здесь размещается пользовательский код
}
```

*inputHtmlPath - user input html file path.

# Console output

Найдено: 2

Параграф, стилизованный классом pStyle, содержит...

Элемент div, стилизованный классом pStyle...

### См. также

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

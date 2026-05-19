---
title: "Element.GetElementsByTagName"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Element. Возвращает объект HTMLCollection, содержащий все элементы с заданным именем тега в порядке документа."
type: docs

url: /ru/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Возвращает объект [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) объект, содержащий все [`elements`](../) с заданным именем тега, в порядке документа.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя тега. Строковое представление имени тега. |

### Возвращаемое значение

Объект [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) представляет собой список, похожий на массив, из [`elements`](../).

## Примечания

Обратитесь к официальной [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname).

Вам также может быть интересна [documentation](https://docs.aspose.com/html/net/).

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
# Html input content
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

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Здесь размещается пользовательский код
}
```

*inputHtmlPath - user input html file.

# Console output

Найдено: 3

Параграф со стилем класса pStyle ...

Содержимое второго параграфа...

Содержимое третьего параграфа...

### См. также

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

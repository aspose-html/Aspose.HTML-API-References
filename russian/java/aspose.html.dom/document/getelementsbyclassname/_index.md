---
title: "Document.GetElementsByClassName"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Метод getElementsByClassName интерфейса Document возвращает объект, похожий на массив, всех дочерних элементов, которые имеют все указанные имена классов."
type: docs

url: /ru/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Метод getElementsByClassName интерфейса [`Document`](../) возвращает объект, похожий на массив, всех дочерних элементов, которые имеют все указанные имена классов.

При вызове на объекте document производится поиск по всему документу, включая корневой узел. Вы также можете вызвать getElementsByClassName() на любом элементе; он вернёт только те элементы, которые являются потомками указанного корневого элемента с заданными именами классов.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classNames | String | Строка String String, содержащая неупорядоченный набор уникальных токенов, разделённых пробелами, представляющих классы (имена классов) |

### Возвращаемое значение

Живая [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) найденных элементов.

## Примечания

Обратитесь к официальной [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

Практический контент по веб-разработке можно найти на [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML‑контент
<div class="custom-class">Customized by css class container</div>

// Код C#
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("custom-class");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Здесь размещается пользовательский код
}
```

// Вывод в консоль

Найдено: 1

Настроено с помощью CSS‑класса container

*inputHtmlPath - user input html file path

```java
// CSS‑стили
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML‑контент
<div id="smart class">
	<p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
	<p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
	<p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("ddd");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Здесь размещается пользовательский код
}
```

# Console output

Найдено: 2

Абзац, стилизованный классом с именем =ddd kkk=

Тип элемента: Aspose.Html.HTMLParagraphElement

Абзац, стилизованный классом с именем =ddd fff=

Тип элемента: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// CSS‑стили
.pStyle{
  font-
}

# HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("pStyle");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Здесь размещается пользовательский код
}
```

# Console output

Найдено: 4

Первый стилизованный абзац классом pStyle

Тип элемента: Aspose.Html.HTMLParagraphElement

Второй стилизованный абзац классом pStyle

Тип элемента: Aspose.Html.HTMLParagraphElement

Третий стилизованный абзац классом pStyle

Тип элемента: Aspose.Html.HTMLParagraphElement

Span, стилизованный с помощью pStyle

Тип элемента: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### См. также

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

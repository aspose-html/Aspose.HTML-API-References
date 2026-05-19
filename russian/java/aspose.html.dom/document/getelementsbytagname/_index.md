---
title: "Document.GetElementsByTagName"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Метод getElementsByTagName интерфейса Document возвращает HTMLCollection элементов с заданным именем тега."
type: docs

url: /ru/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Метод getElementsByTagName интерфейса [`Document`](../) возвращает [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) элементов с заданным именем тега.

Выполняется поиск по всему документу, включая корневой узел. Возвращаемый [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) является «живым», то есть автоматически обновляется, чтобы оставаться синхронным с деревом DOM без необходимости повторного вызова document.getElementsByTagName().

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| tagname | String | String, представляющая имя элементов. Специальный String "*" представляет все элементы. |

### Возвращаемое значение

Живой [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) найденных элементов в порядке их появления в дереве.

## Примечания

Обратитесь к официальной [спецификации](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

Практический контент по веб-разработке можно найти на [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
var elements = document.GetElementsByTagName(name);
```

```java
#HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>
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

import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagName("p");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }

    // Здесь размещается пользовательский код
}
```

# Console output

Найдено: 6

Первый стилизованный абзац классом pStyle

Второй стилизованный абзац классом pStyle

Третий стилизованный абзац классом pStyle

Абзац, стилизованный классом с именем =ddd kkk=

Абзац, стилизованный классом с именем =ddd fff=

Абзац, стилизованный классом с именем =kkk fff=

*inputHtmlPath - user input html file path

### См. также

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

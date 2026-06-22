---
title: "Document.GetElementsByTagNameNS"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Возвращает список элементов с заданным именем тега, принадлежащих указанному пакету. Поиск выполняется по всему документу, включая корневой узел."
type: docs

url: /ru/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Возвращает список элементов с указанным именем тега, принадлежащих заданному пакету. Поиск производится по всему документу, включая корневой узел.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| packageURI | String | URI пакета элементов, которые нужно найти. |
| localName | String | Либо локальное имя элементов для поиска, либо специальное значение *, которое соответствует всем элементам. |

### Возвращаемое значение

Живой [`NodeList`](../../../com.aspose.html.collections/nodelist/) (см. примечание ниже) найденных элементов в порядке их появления в дереве.

## Примечания

Обратитесь к официальной [спецификации](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

Практический контент по веб-разработке можно найти на [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
var elements = document.GetElementsByTagNameNS(@package, name);
```

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
	xmlns="http://www.w3.org/1999/xhtml"
	xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:uniquetag>
  xml package uniquetag content goes here...
</xml:uniquetag>
...
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package","uniquetag");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }  
    // Здесь размещается пользовательский код
}





# Console output

Found: 1

xml package uniquetag content goes here...




```

*inputHtmlPath - user input xhtml file path

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com"
   xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:CATALOG>
	<xml:CD>
    <xml:TITLE>Empire Burlesque</xml:TITLE>
    <xml:ARTIST>Bob Dylan</xml:ARTIST>
    <xml:COUNTRY>USA</xml:COUNTRY>
    <xml:COMPANY>Columbia</xml:COMPANY>
    <xml:PRICE>10.90</xml:PRICE>
    <xml:YEAR>1985</xml:YEAR>
  </xml:CD>
...

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = 
          document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package", "ARTIST");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Здесь размещается пользовательский код
}
```

# Console output

Найдено: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### См. также

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

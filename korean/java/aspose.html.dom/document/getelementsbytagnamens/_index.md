---
title: "Document.GetElementsByTagNameNS"
second_title: "Java용 Aspose.HTML API 참조"
description: "Document 메서드. 지정된 패키지에 속한 주어진 태그 이름을 가진 요소 목록을 반환합니다. 루트 노드를 포함하여 전체 문서를 검색합니다"
type: docs

url: /ko/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

주어진 패키지에 속하고 지정된 태그 이름을 가진 요소들의 목록을 반환합니다. 루트 노드를 포함한 전체 문서를 검색합니다.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| packageURI | String | 찾고자 하는 요소들의 패키지 URI. |
| localName | String | 찾을 요소들의 로컬 이름이거나 모든 요소와 일치하는 특수 값 * 중 하나입니다. |

### 반환 값

트리에서 나타나는 순서대로 찾은 요소들의 실시간 [`NodeList`](../../../com.aspose.html.collections/nodelist/) (하지만 아래 주석을 참고하십시오).

## 비고

공식 [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens)을 참조하십시오.

웹 개발 실습 내용은 [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp)에서 찾을 수 있습니다.

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

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
    // 사용자 코드는 여기에서 작성합니다
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
         
	// 사용자 코드는 여기에서 작성합니다
}
```

# Console output

찾음: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### 또 보기

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Element.GetElementsByTagNameNS"
second_title: "Aspose.HTML for Java API 참조"
description: "Element 메서드. 지정된 로컬 이름과 패키지 URI 문자열을 가진 모든 요소를 문서 순서대로 포함하는 HTMLCollection 객체를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

지정된 로컬 이름과 패키지 URI 문자열을 가진 모든 [`elements`](../)를 문서 순서대로 포함하는 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 객체를 반환합니다.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| packageURI | String | 패키지 URI 문자열 표현. |
| localName | String | 로컬 이름의 문자열 표현. |

### 반환 값

하나의 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 객체는 [`elements`](../)의 배열과 같은 리스트입니다.

## 비고

공식 [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens)을 참조하십시오.

다음 [documentation](https://docs.aspose.com/html/net/)도 관심이 있을 수 있습니다.

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

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
	// 사용자 코드는 여기에서 작성합니다

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// 사용자 코드는 여기에서 작성합니다
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

찾음: 1

여기에 사용자 정의 패키지 사용자 정의 태그 내용이 들어갑니다...

### 또 보기

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

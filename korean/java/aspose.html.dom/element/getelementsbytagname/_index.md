---
title: "Element.GetElementsByTagName"
second_title: "Java용 Aspose.HTML API 참조"
description: "Element 메서드. 지정된 태그 이름을 가진 모든 요소를 문서 순서대로 포함하는 HTMLCollection 객체를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

지정된 태그 이름을 가진 모든 [`elements`](../)를 문서 순서대로 포함하는 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 객체를 반환합니다.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| name | String | 태그 이름. 태그 이름의 문자열 표현. |

### 반환 값

[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 객체는 [`elements`](../)의 배열과 같은 목록입니다.

## 비고

공식 [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname)을 참조하십시오.

또한 [documentation](https://docs.aspose.com/html/net/)을 확인해 보세요.

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

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
	// 사용자 코드는 여기에서 작성합니다

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// 사용자 코드는 여기에서 작성합니다
}
```

*inputHtmlPath - user input html file.

# Console output

찾음: 3

pStyle 클래스가 적용된 단락 내용...

두 번째 단락 내용...

세 번째 단락 내용...

### 또 보기

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

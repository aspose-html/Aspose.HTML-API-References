---
title: "Element.GetElementsByClassName"
second_title: "Java용 Aspose.HTML API 참조"
description: "Element method. 인수에 지정된 모든 클래스를 가진 요소들을 포함하는 HTMLCollection 객체를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

인수에 지정된 모든 클래스를 가진 요소들을 포함하는 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 객체를 반환합니다. 이 객체는 [`element`](../) 내부의 모든 요소를 포함합니다.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| classNames | String | 문자열 문자열은 클래스(클래스 이름)를 나타내는 고유한 공백 구분 토큰들의 순서가 없는 집합을 포함합니다. |

### 반환 값

[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) 객체는 [`elements`](../)의 배열과 같은 목록입니다.

## 비고

공식 [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname)을 참조하십시오.

또한 [documentation](https://docs.aspose.com/html/net/)을 확인해 보세요.

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

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
	// 사용자 코드는 여기에서 작성합니다

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// 사용자 코드는 여기에서 작성합니다
}
```

*inputHtmlPath - user input html file path.

# Console output

찾음: 2

pStyle 클래스가 적용된 단락 내용...

pStyle 클래스가 적용된 div 요소...

### 또 보기

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---
title: "Document.GetElementsByClassName"
second_title: "Java용 Aspose.HTML API 참조"
description: "Document 메서드. Document 인터페이스의 getElementsByClassName 메서드는 지정된 모든 클래스 이름을 가진 모든 자식 요소들의 배열과 유사한 객체를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

해당 [`Document`](../) 인터페이스의 getElementsByClassName 메서드는 지정된 모든 클래스 이름을 가진 모든 자식 요소들의 배열과 유사한 객체를 반환합니다.

document 객체에서 호출하면 루트 노드를 포함한 전체 문서를 검색합니다. 또한 임의의 요소에서 getElementsByClassName()을 호출할 수 있으며, 이 경우 지정된 루트 요소의 하위 요소 중 주어진 클래스 이름을 가진 요소만 반환합니다.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| classNames | String | 문자열 문자열은 클래스(클래스 이름)를 나타내는 고유한 공백 구분 토큰들의 순서가 없는 집합을 포함합니다. |

### 반환 값

찾은 요소들의 실시간 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/).

## 비고

공식 [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname) 을 참조하십시오.

웹 개발 실습 내용은 [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp) 에서 찾을 수 있습니다.

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML 콘텐츠
<div class="custom-class">Customized by css class container</div>

// C# 코드
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
         
	// 사용자 코드는 여기에서 작성합니다
}
```

// 콘솔 출력

찾음: 1

css 클래스 컨테이너에 의해 사용자 정의됨

*inputHtmlPath - user input html file path

```java
// CSS 스타일링
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML 콘텐츠
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
         
	// 사용자 코드는 여기에서 작성합니다
}
```

# Console output

찾음: 2

클래스 이름 =ddd kkk= 로 스타일이 지정된 단락

요소 유형: Aspose.Html.HTMLParagraphElement

클래스 이름 =ddd fff= 로 스타일이 지정된 단락

요소 유형: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// CSS 스타일링
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
         
	// 사용자 코드는 여기에서 작성합니다
}
```

# Console output

찾음: 4

첫 번째는 pStyle 클래스 단락에 스타일이 지정되었습니다

요소 유형: Aspose.Html.HTMLParagraphElement

두 번째는 pStyle 클래스 단락에 스타일이 지정되었습니다

요소 유형: Aspose.Html.HTMLParagraphElement

세 번째는 pStyle 클래스 단락에 스타일이 지정되었습니다

요소 유형: Aspose.Html.HTMLParagraphElement

pStyle에 의해 스타일링된 Span

요소 유형: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### 또 보기

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

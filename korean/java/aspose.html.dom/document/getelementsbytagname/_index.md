---
title: "Document.GetElementsByTagName"
second_title: "Aspose.HTML for Java API 참조"
description: "Document method. Document 인터페이스의 getElementsByTagName 메서드는 지정된 태그 이름을 가진 요소들의 HTMLCollection을 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

[`Document`](../) 인터페이스의 getElementsByTagName 메서드는 지정된 태그 이름을 가진 요소들의 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)을 반환합니다.

전체 문서(루트 노드 포함)를 검색합니다. 반환된 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)은 라이브 컬렉션으로, document.getElementsByTagName()을 다시 호출하지 않아도 자동으로 업데이트되어 DOM 트리와 동기화됩니다.

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tagname | String | 요소 이름을 나타내는 문자열입니다. 특수 문자열 "*"은 모든 요소를 나타냅니다. |

### 반환 값

트리에서 나타나는 순서대로 찾은 요소들의 라이브 [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)입니다.

## 비고

공식 [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname)을 참조하십시오.

웹 개발 실습 내용은 [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp)에서 찾을 수 있습니다.

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

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

    // 사용자 코드는 여기에서 작성합니다
}
```

# Console output

찾음: 6

첫 번째는 pStyle 클래스 단락에 스타일이 적용되었습니다

두 번째는 pStyle 클래스 단락에 스타일이 적용되었습니다

세 번째는 pStyle 클래스 단락에 스타일이 적용되었습니다

클래스 이름 =ddd kkk= 로 스타일이 적용된 단락

클래스 이름 =ddd fff= 로 스타일이 적용된 단락

클래스 이름 =kkk fff= 로 스타일이 적용된 단락

*inputHtmlPath - user input html file path

### 또 보기

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

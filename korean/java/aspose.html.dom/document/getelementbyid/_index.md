---
title: "Document.GetElementById"
second_title: "Aspose.HTML for Java API 참조"
description: "Document 메서드. Document 메서드 getElementById는 지정된 문자열과 일치하는 id 속성을 가진 요소를 나타내는 Element 객체를 반환합니다. 요소 ID는 지정된 경우 고유해야 하므로 특정 요소에 빠르게 접근하는 유용한 방법입니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Document 메서드 getElementById()는 지정된 문자열과 일치하는 id 속성을 가진 요소를 나타내는 [`Element`](../../element/) 객체를 반환합니다. 요소 ID는 지정된 경우 고유해야 하므로 특정 요소에 빠르게 접근하는 유용한 방법입니다.

ID가 없는 요소에 접근해야 하는 경우, querySelector()를 사용하여 임의의 선택자로 요소를 찾을 수 있습니다.

```java
public Element GetElementById(String elementId)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elementId | String | 찾을 요소의 ID. ID는 대소문자를 구분하는 문자열이며 문서 내에서 고유합니다; 동일한 ID를 가진 요소는 하나만 존재할 수 있습니다. |

### 반환 값

지정된 ID와 일치하는 DOM 요소를 설명하는 [`Element`](../../element/) 객체이며, 일치하는 요소가 문서에 없으면 null을 반환합니다.

## 비고

공식 [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid)을 참조하십시오.

[w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp)에서 웹 개발 실습 콘텐츠를 찾을 수 있습니다.

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
// HTML 콘텐츠
<div id="uniqueIdentifier">Container with ID - identifier</div>

// C# 코드
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// 사용자 코드는 여기에서 작성합니다
   }
```

// 콘솔 출력

ID가 있는 컨테이너 - 식별자

*inputHtmlPath - user input html file path

### 또 보기

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

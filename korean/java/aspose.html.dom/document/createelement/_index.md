---
title: "Document.CreateElement"
second_title: "Java용 Aspose.HTML API 참조"
description: "Document 메서드. HTML 문서에서 document.createElement 메서드는 tagName으로 지정된 HTML 요소를 생성하거나, tagName이 인식되지 않으면 HTMLUnknownElement를 생성합니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

HTML 문서에서 document.createElement() 메서드는 tagName으로 지정된 HTML 요소를 생성하거나, tagName이 인식되지 않을 경우 [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/)를 생성합니다.

```java
public Element CreateElement(String localName)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| localName | String | 생성될 요소의 유형을 지정하는 문자열입니다. 생성된 요소의 nodeName은 tagName 값으로 초기화됩니다. 이 메서드와 함께 한정된 이름(예: "html:a")을 사용하지 마세요. HTML 문서에서 호출될 경우, createElement()는 요소를 생성하기 전에 tagName을 소문자로 변환합니다. |

### 반환 값

새로운 [`Element`](../../element/).

## 예제

```java
var element = document.CreateElement(tagName);
```

### 또 보기

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

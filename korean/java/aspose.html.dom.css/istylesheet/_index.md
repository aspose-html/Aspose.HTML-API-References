---
title: "IStyleSheet 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.IStyleSheet 인터페이스. StyleSheet 인터페이스는 모든 유형의 스타일 시트에 대한 추상 기본 인터페이스입니다. 구조화된 문서와 연결된 단일 스타일 시트를 나타냅니다. HTML에서는 StyleSheet 인터페이스가 HTML LINK 요소를 통해 포함된 외부 스타일 시트 또는 인라인 STYLE 요소를 나타냅니다. XML에서는 이 인터페이스가 스타일 시트 처리 명령을 통해 포함된 외부 스타일 시트를 나타냅니다. CSS 스타일 시트는 더 특화된 CSSStyleSheet 인터페이스를 추가로 구현합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet 인터페이스는 모든 유형의 스타일 시트에 대한 추상 기본 인터페이스입니다. 구조화된 문서와 연결된 단일 스타일 시트를 나타냅니다. HTML에서는 StyleSheet 인터페이스가 HTML LINK 요소를 통해 포함된 외부 스타일 시트 또는 인라인 STYLE 요소를 나타냅니다. XML에서는 이 인터페이스가 스타일 시트 처리 명령을 통해 포함된 외부 스타일 시트를 나타냅니다. CSS 스타일 시트는 더 특화된 [`CSSStyleSheet`](../icssstylesheet/) 인터페이스를 추가로 구현합니다.

또한 [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface)을 참조하십시오.

```java
public interface IStyleSheet
```

## 속성

| 이름 | 설명 |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) `StyleSheet` 인터페이스의 href 속성은 스타일 시트의 위치를 반환합니다. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) `StyleSheet` 인터페이스의 media 속성은 스타일 정보의 대상 미디어를 지정합니다. 이는 읽기 전용이며 배열과 같은 형태의 [`MediaList`](../imedialist/) 객체이며 deleteMedium()으로 제거하고 appendMedium()으로 추가할 수 있습니다. |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) 이 스타일 시트를 문서와 연결하는 노드입니다. HTML의 경우 해당 LINK 또는 STYLE 요소일 수 있습니다. XML의 경우 연결 처리 명령일 수 있습니다. 다른 스타일 시트에 의해 포함된 스타일 시트의 경우 이 속성 값은 null입니다. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) 스타일 시트 포함 개념을 지원하는 스타일 시트 언어의 경우, 이 속성은 포함하는 스타일 시트를 나타냅니다(존재하는 경우). 스타일 시트가 최상위 스타일 시트이거나 언어가 포함을 지원하지 않으면 이 속성 값은 null입니다. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) `StyleSheet` 인터페이스의 title 속성은 현재 스타일 시트의 권고 제목을 반환합니다. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) 이는 해당 스타일 시트의 스타일 시트 언어를 지정합니다. 스타일 시트 언어는 콘텐츠 타입(예: "text/css")으로 지정됩니다. |

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### 또 보기

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

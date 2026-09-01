---
title: "IDocumentCSS 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.IDocumentCSS 인터페이스. 이 인터페이스는 CSS 뷰를 가진 문서를 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

이 인터페이스는 CSS 뷰를 가진 문서를 나타냅니다.

getOverrideStyle 메서드는 DOM 작성자가 문서에 명시적으로 연결된 스타일시트나 요소의 인라인 스타일을 수정하지 않고도 요소의 스타일을 즉시 변경할 수 있는 메커니즘을 제공합니다. 이 스타일시트는 캐스케이드 알고리즘에서 작성자 스타일시트 뒤에 위치하며, 오버라이드 스타일시트라고 불립니다. 오버라이드 스타일시트는 작성자 스타일시트보다 우선순위를 가집니다. "!important" 선언은 일반 선언보다 여전히 우선합니다. 오버라이드, 작성자, 사용자 스타일시트 모두 "!important" 선언을 포함할 수 있습니다. 사용자 "!important" 규칙은 오버라이드 및 작성자 "!important" 규칙보다 우선하고, 오버라이드 "!important" 규칙은 작성자 "!important" 규칙보다 우선합니다.

Document 인터페이스 인스턴스에 바인딩 전용 캐스팅 메서드를 사용하여 DocumentCSS 인터페이스 인스턴스를 얻을 수 있다는 기대가 있습니다.

또한 [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)을 참조하십시오.

```java
public interface IDocumentCSS : IDocumentStyle
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | 이 메서드는 지정된 요소와 지정된 의사 요소에 대한 오버라이드 스타일 선언을 검색하는 데 사용됩니다. |

### 또 보기

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

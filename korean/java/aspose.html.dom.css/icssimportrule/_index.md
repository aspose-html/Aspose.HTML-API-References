---
title: "ICSSImportRule 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.ICSSImportRule 인터페이스. CSSImportRule 인터페이스는 CSS 스타일 시트 내의 import 규칙을 나타냅니다. import 규칙은 다른 스타일 시트에서 스타일 규칙을 가져오는 데 사용됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule 인터페이스는 CSS 스타일 시트 내의 @import 규칙을 나타냅니다. @import 규칙은 다른 스타일 시트에서 스타일 규칙을 가져오는 데 사용됩니다.

```java
public interface ICSSImportRule : ICSSRule
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getHref](../../com.aspose.html.dom.css/icssimportrule/href/) CSSImportRule 인터페이스의 읽기 전용 href 속성은 @import at-rule에 지정된 URL을 반환합니다. |
| [getMedia](../../com.aspose.html.dom.css/icssimportrule/media/) CSSImportRule 인터페이스의 읽기 전용 media 속성은 연관된 스타일시트의 media 속성 값을 포함하는 MediaList 객체를 반환합니다. |
| [getStyleSheet](../../com.aspose.html.dom.css/icssimportrule/stylesheet/) 이 규칙이 참조하는 스타일 시트이며, 로드된 경우에만 반환됩니다. 스타일 시트가 아직 로드되지 않았거나 로드되지 않을 경우(예: 사용자 에이전트가 지원하지 않는 미디어 타입인 경우) 이 속성의 값은 null입니다. |

### 또 보기

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

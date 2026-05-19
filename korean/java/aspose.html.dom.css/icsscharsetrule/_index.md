---
title: "ICSSCharsetRule 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.css.ICSSCharsetRule 인터페이스. CSSCharsetRule 인터페이스는 CSS 스타일 시트의 charset 규칙을 나타냅니다. encoding 속성의 값은 DOM 객체의 텍스트 데이터 인코딩에 영향을 주지 않으며, 이 인코딩은 항상 UTF-16입니다. 스타일 시트가 로드된 후 encoding 속성의 값은 charset 규칙에 지정된 값이 됩니다. 원본 문서에 charset이 없으면 CSSCharsetRule이 생성되지 않습니다. encoding 속성의 값은 스타일 시트 직렬화 시 사용되는 인코딩에 대한 힌트로도 사용될 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule 인터페이스는 CSS 스타일시트의 @charset 규칙을 나타냅니다. encoding 속성의 값은 DOM 객체의 텍스트 데이터 인코딩에 영향을 주지 않으며, 이 인코딩은 항상 UTF-16입니다. 스타일시트가 로드된 후, encoding 속성의 값은 @charset 규칙에서 찾은 값이 됩니다. 원본 문서에 @charset이 없으면 CSSCharsetRule가 생성되지 않습니다. encoding 속성의 값은 스타일시트 직렬화 시 사용되는 인코딩에 대한 힌트로도 사용될 수 있습니다.

```java
public interface ICSSCharsetRule : ICSSRule
```

## 속성

| 이름 | 설명 |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### 또 보기

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

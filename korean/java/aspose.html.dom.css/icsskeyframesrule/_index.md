---
title: "ICSSKeyframesRule 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.ICSSKeyframesRule 인터페이스. CSSKeyframeRule 인터페이스의 name 속성은 animation-name 속성에서 사용되는 애니메이션 이름을 가져오고 설정합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframeRule 인터페이스의 name 속성은 animation-name 속성에서 사용되는 애니메이션 이름을 가져오고 설정합니다.

```java
public interface ICSSKeyframesRule : ICSSRule
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) [`CSSKeyframeRule`](../icsskeyframerule/) 인터페이스의 읽기 전용 cssRules 속성은 키프레임 at‑rule에 포함된 규칙을 담은 [`CSSRuleList`](../icssrulelist/)를 반환합니다. |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) [`CSSKeyframeRule`](../icsskeyframerule/) 인터페이스의 name 속성은 animation‑name 속성에서 사용되는 애니메이션 이름을 가져오고 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | appendRule 메서드는 전달된 [`CSSKeyframeRule`](../icsskeyframerule/)을 키프레임 규칙 컬렉션의 끝에 추가합니다. |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | deleteRule 메서드는 전달된 키와 일치하는 [`CSSKeyframeRule`](../icsskeyframerule/)을 삭제합니다. 해당 키를 가진 규칙이 존재하지 않으면 메서드는 아무 작업도 수행하지 않습니다. |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | findRule 메서드는 전달된 키와 일치하는 규칙을 반환합니다. 해당 규칙이 없으면 null 값을 반환합니다. |

### 또 보기

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

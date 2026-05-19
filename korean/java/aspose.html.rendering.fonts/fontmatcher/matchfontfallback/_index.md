---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.HTML for Java API 참조"
description: "FontMatcher 메서드. 이 메서드는 폰트 조회 폴더에서 적절한 폰트를 찾을 수 없을 때 호출됩니다. fontMatchingProperties를 기반으로 charCode를 렌더링할 수 있는 실제 타입 폰트를 반환하거나 해당 폰트를 사용할 수 없으면 null을 반환해야 합니다."
type: docs

url: /ko/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

이 메서드는 글꼴 조회 폴더에서 적절한 글꼴을 찾지 못했을 때 호출됩니다. *fontMatchingProperties*를 기반으로 *charCode*를 렌더링할 수 있는 실제 타입 글꼴을 반환해야 하며, 해당 글꼴이 없으면 `null`을 반환합니다.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | 일치하는 폰트의 속성. |
| charCode | UInt32 | 일치하는 폰트를 사용하여 렌더링될 문자의 코드. |

### 반환 값

폰트 데이터를 포함하는 바이트 배열 또는 `null`.

### 또 보기

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)

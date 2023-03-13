---
title: FontMatcher.MatchFontFallback
second_title: .NET API 참조용 Aspose.HTML
description: FontMatcher 방법. 이 메서드는 글꼴 조회 폴더에 적절한 글꼴이 없을 때 호출됩니다. 해당 글꼴을 기반으로 트루 타입 글꼴을 반환해야 합니다.fontMatchingProperties 렌더링할 수 있는charCode  또는없는 해당 글꼴을 사용할 수 없는 경우.
type: docs
weight: 10
url: /ko/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

이 메서드는 글꼴 조회 폴더에 적절한 글꼴이 없을 때 호출됩니다. 해당 글꼴을 기반으로 트루 타입 글꼴을 반환해야 합니다.*fontMatchingProperties* 렌더링할 수 있는*charCode* , 또는`없는` 해당 글꼴을 사용할 수 없는 경우.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | 일치하는 글꼴의 속성입니다. |
| charCode | UInt32 | 일치하는 글꼴을 사용하여 렌더링할 문자의 코드입니다. |

### 반환 값

글꼴 데이터를 포함하는 바이트 배열 또는`없는`.

### 또한보십시오

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* 네임스페이스 [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* 집회 [Aspose.HTML](../../../)



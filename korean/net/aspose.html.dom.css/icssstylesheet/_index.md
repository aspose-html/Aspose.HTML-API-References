---
title: Interface ICSSStyleSheet
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css.ICSSStyleSheet 상호 작용. CSSStyleSheet 인터페이스는 콘텐츠 유형이 text/css인 스타일 시트인 CSS 스타일 시트를 나타내는 데 사용되는 구체적인 인터페이스입니다.
type: docs
weight: 510
url: /ko/net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet 인터페이스는 콘텐츠 유형이 "text/css"인 스타일 시트인 CSS 스타일 시트를 나타내는 데 사용되는 구체적인 인터페이스입니다.

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules/) { get; } | 스타일 시트에 포함된 모든 CSS 규칙 목록입니다. 여기에는 규칙 집합과 at-rules가 모두 포함됩니다. |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule/) { get; } | 이 스타일 시트가 @import 규칙에서 온 경우 ownerRule 특성에 CSSImportRule이 포함됩니다. 이 경우 StyleSheet 인터페이스의 ownerNode 특성은 null이 됩니다. 스타일 시트가 요소 또는 처리 명령에서 오는 경우 ownerRule 특성은 null이 되고 ownerNode 특성에는 Node. 가 포함됩니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule/)(int) | 스타일 시트에서 규칙을 삭제하는 데 사용됩니다. |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule/)(string, int) | 스타일 시트에 새 규칙을 삽입하는 데 사용됩니다. 새 규칙은 이제 cascade. 의 일부가 됩니다. |

### 또한보십시오

* interface [IStyleSheet](../istylesheet/)
* 네임스페이스 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 집회 [Aspose.HTML](../../)



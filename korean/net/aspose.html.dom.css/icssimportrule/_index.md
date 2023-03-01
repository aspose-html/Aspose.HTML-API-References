---
title: Interface ICSSImportRule
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css.ICSSImportRule 상호 작용. CSSImportRule 인터페이스는 CSS 스타일 시트 내의 import 규칙을 나타냅니다. import 규칙은 다른 스타일 시트에서 스타일 규칙을 가져오는 데 사용됩니다.
type: docs
weight: 410
url: /ko/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule 인터페이스는 CSS 스타일 시트 내의 @import 규칙을 나타냅니다. @import 규칙은 다른 스타일 시트에서 스타일 규칙을 가져오는 데 사용됩니다.

```csharp
public interface ICSSImportRule : ICSSRule
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | 가져올 스타일 시트의 위치입니다. 속성은 URI 주위에 "url(...)" 지정자를 포함하지 않습니다. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | 이 스타일시트를 사용할 수 있는 미디어 유형 목록입니다. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | 이 규칙이 참조하는 스타일 시트(로드된 경우). 스타일 시트가 아직 로드되지 않았거나 로드되지 않을 경우(예: 스타일 시트가 사용자 에이전트에서 지원하지 않는 미디어 유형용인 경우) 이 속성의 값은 null입니다. |

### 또한보십시오

* interface [ICSSRule](../icssrule/)
* 네임스페이스 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 집회 [Aspose.HTML](../../)



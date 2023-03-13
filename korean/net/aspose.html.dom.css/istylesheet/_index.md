---
title: Interface IStyleSheet
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css.IStyleSheet 상호 작용. StyleSheet 인터페이스는 모든 유형의 스타일 시트에 대한 추상 기본 인터페이스입니다. 구조화된 문서와 연결된 단일 스타일 시트를 나타냅니다.
type: docs
weight: 590
url: /ko/net/aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet 인터페이스는 모든 유형의 스타일 시트에 대한 추상 기본 인터페이스입니다. 구조화된 문서와 연결된 단일 스타일 시트를 나타냅니다.

```csharp
public interface IStyleSheet
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Disabled](../../aspose.html.dom.css/istylesheet/disabled/) { get; set; } | 스타일 시트가 문서에 적용된 경우 false입니다. 그렇지 않은 경우 참입니다. 이 속성을 수정하면 문서 스타일이 새로 결정될 수 있습니다. 스타일시트는 적절한 매체 정의가 모두 존재하고 disabled 속성이 false인 경우에만 적용됩니다. 따라서 미디어가 현재 사용자 에이전트에 적용되지 않으면 비활성화 속성이 무시됩니다. |
| [Href](../../aspose.html.dom.css/istylesheet/href/) { get; } | 스타일 시트가 연결된 스타일 시트인 경우 속성 값은 위치입니다. 인라인 스타일 시트의 경우 이 속성 값은 null입니다. |
| [Media](../../aspose.html.dom.css/istylesheet/media/) { get; } | 스타일 정보를 위한 대상 미디어입니다. |
| [OwnerNode](../../aspose.html.dom.css/istylesheet/ownernode/) { get; } | 이 스타일시트를 문서와 연결하는 노드입니다. HTML의 경우 해당 LINK 또는 STYLE 요소일 수 있습니다. XML의 경우 링크 처리 명령일 수 있습니다. 다른 스타일 시트에 포함된 스타일 시트의 경우 이 속성 값은 null. 입니다. |
| [ParentStyleSheet](../../aspose.html.dom.css/istylesheet/parentstylesheet/) { get; } | 스타일 시트 포함 개념을 지원하는 스타일 시트 언어의 경우 이 속성은 포함 스타일 시트(있는 경우)를 나타냅니다. 스타일 시트가 최상위 스타일 시트이거나 스타일 시트 언어가 포함을 지원하지 않는 경우 이 속성의 값은 null입니다. |
| [Title](../../aspose.html.dom.css/istylesheet/title/) { get; } | 권고 제목입니다. |
| [Type](../../aspose.html.dom.css/istylesheet/type/) { get; } | 이 스타일 시트에 대한 스타일 시트 언어를 지정합니다. 스타일 시트 언어는 콘텐츠 유형(예: "text/css")으로 지정됩니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 집회 [Aspose.HTML](../../)



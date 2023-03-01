---
title: Enum PageLayoutOptions
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Rendering.PageLayoutOptions 열거형. 다른 PageSetup 옵션과 함께 페이지의 크기와 레이아웃을 결정하는 플래그를 지정합니다. 이러한 플래그는 해당 설명에 따라 함께 결합될 수 있습니다.
type: docs
weight: 4380
url: /ko/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

다른 PageSetup 옵션과 함께 페이지의 크기와 레이아웃을 결정하는 플래그를 지정합니다. 이러한 플래그는 해당 설명에 따라 함께 결합될 수 있습니다.

```csharp
[Flags]
public enum PageLayoutOptions
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | PageLayoutOptions가 페이지의 크기와 레이아웃에 영향을 미치지 않음을 나타내는 기본값입니다. |
| FitToContentWidth | `1` | 이 플래그는 페이지 너비가 지정된 페이지 너비가 아니라 콘텐츠 크기 자체에서 결정됨을 나타냅니다. 콘텐츠 너비는 모든 페이지에 대해 개별적으로 계산됩니다. |
| UseWidestPage | `2` | 와 결합하는 경우FitToContentWidth 모든 페이지의 너비가 동일하고 모든 페이지 중에서 가장 넓은 콘텐츠 크기와 동일함을 나타냅니다. |
| FitToWidestContentWidth | `3` | 이 플래그는 페이지의 너비가 지정된 페이지 너비가 아니라 콘텐츠 크기 자체에서 결정됨을 나타냅니다. 모든 페이지의 너비는 동일하며 모든 페이지 중에서 가장 넓은 콘텐츠 크기와 같습니다. |
| FitToContentHeight | `10` | 이 플래그는 페이지 높이가 지정된 페이지 높이가 아니라 콘텐츠 크기 자체에서 결정됨을 나타냅니다. 이 플래그가 지정된 경우 모든 문서 콘텐츠는 단일 페이지에 위치합니다. |
| ScaleToPageWidth | `100` | 이 플래그는 사용 가능한 페이지 너비와 겹치는 콘텐츠 간의 차이가 가장 큰 페이지에 맞게 문서 콘텐츠의 크기가 조정됨을 나타냅니다. 충돌합니다.FitToContentWidth 플래그 및 두 플래그가 모두 지정된 경우에만ScaleToPageWidth 적용됩니다. |
| ScaleToPageHeight | `1000` | 이 플래그는 문서의 내용이 첫 번째 페이지의 높이에 맞게 크기가 조정됨을 나타냅니다. 다음과 충돌합니다.FitToContentHeight 플래그 및 두 플래그가 모두 지정된 경우에만ScaleToPageHeight 적용됩니다. 모든 문서 콘텐츠는 단일 페이지에만 배치됩니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 집회 [Aspose.HTML](../../)



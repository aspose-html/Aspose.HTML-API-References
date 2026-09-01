---
title: "PageLayoutOptions 열거형"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.rendering.PageLayoutOptions 열거형. 다른 PageSetup 옵션과 함께 페이지의 크기와 레이아웃을 결정하는 플래그를 지정합니다. 이러한 플래그는 설명에 따라 함께 결합할 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

다른 PageSetup 옵션과 함께 페이지의 크기와 레이아웃을 결정하는 플래그를 지정합니다. 이러한 플래그는 설명에 따라 함께 결합될 수 있습니다.

```java
[Flags]
public enum PageLayoutOptions
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | PageLayoutOptions가 페이지의 크기와 레이아웃에 영향을 주지 않음을 나타내는 기본값. |
| FitToContentWidth | `1` | 이 플래그는 페이지 너비가 지정된 페이지 너비가 아니라 콘텐츠 크기 자체에 따라 결정됨을 나타냅니다. 콘텐츠 너비는 각 페이지마다 개별적으로 계산됩니다. |
| UseWidestPage | `2` | FitToContentWidth와 결합될 때, 모든 페이지의 너비가 동일하며 모든 페이지 중 가장 넓은 콘텐츠 크기와 같게 됩니다. |
| FitToWidestContentWidth | `3` | 이 플래그는 페이지 너비가 지정된 페이지 너비가 아니라 콘텐츠 크기 자체에 따라 결정됨을 나타냅니다. 모든 페이지의 너비는 동일하며 모든 페이지 중 가장 넓은 콘텐츠 크기와 같습니다. |
| FitToContentHeight | `10` | 이 플래그는 페이지 높이가 지정된 페이지 높이가 아니라 콘텐츠 크기 자체에 따라 결정됨을 나타냅니다. 이 플래그가 지정되면 모든 문서의 콘텐츠가 단일 페이지에 배치됩니다. |
| ScaleToPageWidth | `100` | 이 플래그는 사용 가능한 페이지 너비와 겹치는 콘텐츠 사이의 차이가 가장 큰 페이지에 맞게 문서의 콘텐츠가 확대/축소됨을 나타냅니다. FitToContentWidth 플래그와 충돌하며 두 플래그가 모두 지정된 경우 ScaleToPageWidth만 적용됩니다. |
| ScaleToPageHeight | `1000` | 이 플래그는 문서의 콘텐츠가 첫 페이지의 높이에 맞게 확대/축소됨을 나타냅니다. FitToContentHeight 플래그와 충돌하며 두 플래그가 모두 지정된 경우 ScaleToPageHeight만 적용됩니다. 모든 문서 콘텐츠는 단일 페이지에만 배치됩니다. |

### 또 보기

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)

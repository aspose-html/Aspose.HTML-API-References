---
title: Interface ISVGAnimatedPathData
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData 상호 작용. SVGAnimatedPathData 인터페이스는 SVG 경로 데이터를 보유하는 d 속성이 있는 요소를 지원하고 해당 속성에 애니메이션을 적용하는 기능을 지원합니다.
type: docs
weight: 1680
url: /ko/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData 인터페이스는 SVG 경로 데이터를 보유하는 'd' 속성이 있는 요소를 지원하고 해당 속성에 애니메이션을 적용하는 기능을 지원합니다.

```csharp
public interface ISVGAnimatedPathData
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | SVG 구문과 일대일로 일치하는 형식으로 'd' 속성의 현재 애니메이션 콘텐츠에 대한 액세스를 제공합니다. 주어진 속성 또는 속성이 애니메이션되는 경우 속성 또는 속성의 현재 애니메이션 값을 포함하고 개체 자체와 해당 내용이 모두 읽기 전용입니다. 지정된 속성 또는 속성이 현재 애니메이션되지 않는 경우 pathSegList. 와 동일한 값을 포함합니다. |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | SVG 구문과 일대일로 일치하는 형식으로 'd' 속성의 기본(예: 정적) 콘텐츠에 대한 액세스를 제공합니다. 따라서 'd' 속성에 "absolute moveto(M)" 및 "absolute arcto(A)" 명령이 있는 경우 pathSegList에는 SVG_PATHSEG_MOVETO_ABS 및 SVG_PATHSEG_ARC_ABS의 두 항목이 있습니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* 집회 [Aspose.HTML](../../)



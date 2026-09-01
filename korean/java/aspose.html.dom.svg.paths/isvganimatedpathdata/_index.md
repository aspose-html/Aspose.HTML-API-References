---
title: "ISVGAnimatedPathData 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData 인터페이스. SVGAnimatedPathData 인터페이스는 d 속성을 가지고 SVG 경로 데이터를 보유하는 요소를 지원하며 해당 속성을 애니메이션화할 수 있는 기능을 지원합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData 인터페이스는 ‘d’ 속성을 가지고 SVG 경로 데이터를 보유하는 요소를 지원하며, 해당 속성을 애니메이션화할 수 있는 기능을 지원합니다.

```java
public interface ISVGAnimatedPathData
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) 현재 애니메이션된 ‘d’ 속성의 내용을 SVG 구문과 일대일로 일치하는 형태로 제공합니다. 지정된 속성이나 프로퍼티가 애니메이션 중인 경우, 해당 속성이나 프로퍼티의 현재 애니메이션 값을 포함하며 객체 자체와 그 내용은 읽기 전용입니다. 지정된 속성이나 프로퍼티가 현재 애니메이션되지 않은 경우, pathSegList와 동일한 값을 포함합니다. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) ‘d’ 속성의 기본(즉, 정적) 내용을 SVG 구문과 일대일로 일치하는 형태로 제공합니다. 따라서 ‘d’ 속성에 "절대 moveto (M)"와 "절대 arcto (A)" 명령이 포함되어 있으면, pathSegList는 SVG_PATHSEG_MOVETO_ABS와 SVG_PATHSEG_ARC_ABS 두 개의 항목을 가집니다. |

### 또 보기

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)

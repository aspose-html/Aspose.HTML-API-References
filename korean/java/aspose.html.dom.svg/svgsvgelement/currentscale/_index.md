---
title: "SVGSVGElement.CurrentScale"
second_title: "Java용 Aspose.HTML API 참조"
description: "SVGSVGElement 속성. 가장 바깥쪽 svg 요소에서 이 속성은 초기 뷰에 대한 현재 배율 계수를 나타내며, 사용자 확대/축소 및 팬 작업을 고려합니다(‘Magnification and panning’에 설명된 대로). DOM 속성 currentScale 및 currentTranslate는 2x3 행렬 a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y와 동일합니다. 확대가 활성화된 경우(예: zoomAndPanmagnify) 효과는 SVG 문서 조각의 가장 바깥 수준에 추가 변환이 적용된 것과 같습니다(즉, 가장 바깥 svg 요소 외부). 가장 바깥 svg 요소가 아닌 svg 요소에서 접근하면 이 속성이 어떤 동작을 하는지는 정의되지 않습니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

가장 바깥쪽 svg 요소에서 이 속성은 초기 뷰에 대한 현재 배율 계수를 나타내며, 사용자 확대/축소 및 팬 작업을 고려합니다(‘Magnification and panning’에 설명된 대로). DOM 속성 currentScale 및 currentTranslate는 2x3 행렬 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]와 동일합니다. \"magnification\"이 활성화된 경우(i.e., zoomAndPan=\"magnify\"), 효과는 SVG 문서 조각의 가장 바깥 수준에 추가 변환이 적용된 것과 같습니다(즉, 가장 바깥 svg 요소 외부). 가장 바깥 svg 요소가 아닌 ‘svg’ 요소에서 접근하면 이 속성이 어떤 동작을 하는지는 정의되지 않습니다.

```java
public float CurrentScale { get; set; }
```

### Property Value

현재 배율.

### 또 보기

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

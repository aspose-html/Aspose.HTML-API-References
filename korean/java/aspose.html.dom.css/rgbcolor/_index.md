---
title: "RGBColor 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.css.RGBColor 클래스. RGBColor 인터페이스는 모든 RGB 색상 값을 나타내는 데 사용됩니다. 이 인터페이스는 기본 스타일 속성의 값을 반영합니다. 따라서 CSSPrimitiveValue 객체에 대한 수정은 스타일 속성을 변경합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

RGBColor 인터페이스는 모든 RGB 색상 값을 나타내는 데 사용됩니다. 이 인터페이스는 기본 스타일 속성의 값을 반영합니다. 따라서 CSSPrimitiveValue 객체에 대한 수정은 스타일 속성을 변경합니다.

지정된 RGB 색상은 클리핑되지 않습니다(숫자가 0-255 또는 0%-100% 범위를 벗어나더라도). 계산된 RGB 색상은 장치에 따라 클리핑됩니다.

스타일 시트가 색상 값으로 정수만 포함할 수 있더라도, 해당 정수의 내부 저장은 부동소수점이며, 지정된 스타일이나 계산된 스타일에서 부동소수점으로 사용할 수 있습니다.

색상 백분율 값은 언제든지 숫자로 변환될 수 있으며 그 반대도 가능합니다.

```java
public class RGBColor : DOMObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) 이 Color 구조의 알파 구성 요소 값을 가져옵니다. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) 이 Color 구조의 파란색 구성 요소 값을 가져옵니다. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) 이 Color 구조의 녹색 구성 요소 값을 가져옵니다. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) 이 Color 구조의 빨간색 구성 요소 값을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | 네이티브 색상 객체로 변환합니다. |

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### 또 보기

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

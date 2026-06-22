---
title: "Color 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.drawing.Color 클래스. Color 클래스는 색상을 Red-Green-Blue RGB 값, Hue-Saturation-Luminosity HSL 값, Hue-Saturation-Value HSV 값, Hue-Whiteness-Blackness HWB 값, lightness-A-B LAB 값, Luminance-Chroma-Hue LCH 값, Cyan-Magenta-Yellow-Key CMYK 값, Natural colors NCOL 값 또는 색상 이름으로 지정할 수 있게 합니다. 투명도를 나타내는 Alpha 채널도 사용할 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.drawing/color/
---
## Color class

Color 클래스는 빨강-초록-파랑 (RGB) 값, 색조-채도-명도 (HSL) 값, 색조-채도-값 (HSV) 값, 색조-백색도-흑색도 (HWB) 값, 밝기-A-B (LAB) 값, 휘도-채도-색조 (LCH) 값, 시안-마젠타-노랑-키 (CMYK) 값, 자연 색상 (NCOL) 값 또는 색상 이름으로 색상을 지정할 수 있게 해줍니다. 투명도를 나타내는 알파 채널도 사용할 수 있습니다.

```java
public class Color
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Color](color/#constructor)() | 새 `Color` 클래스 인스턴스를 초기화합니다. 기본 색상은 검정색입니다. |
| [Color](color/#constructor_1)(byte, byte, byte) | 새 `Color` 클래스 인스턴스를 초기화합니다. 모든 색상 구성 요소는 0-255 범위여야 합니다. |
| [Color](color/#constructor_5)(float, float, float) | 새 `Color` 클래스 인스턴스를 초기화합니다. 모든 색상 구성 요소는 0-1 범위여야 합니다. |
| [Color](color/#constructor_3)(int, int, int) | 새 `Color` 클래스 인스턴스를 초기화합니다. 모든 색상 구성 요소는 0-255 범위여야 합니다. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | 새 `Color` 클래스 인스턴스를 초기화합니다. 모든 색상 구성 요소는 0-255 범위여야 합니다. |
| [Color](color/#constructor_6)(float, float, float, float) | 새 `Color` 클래스 인스턴스를 초기화합니다. 모든 색상 구성 요소는 0-1 범위여야 합니다. |
| [Color](color/#constructor_4)(int, int, int, int) | 새 `Color` 클래스 인스턴스를 초기화합니다. 모든 색상 구성 요소는 0-255 범위여야 합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) 색상의 알파 구성 요소를 나타냅니다. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) 색상의 파란색 구성 요소를 나타냅니다. |
| [getGreen](../../com.aspose.html.drawing/color/green/) 색상의 녹색 구성 요소를 나타냅니다. |
| [getRed](../../com.aspose.html.drawing/color/red/) 색상의 빨간색 구성 요소를 나타냅니다 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | 요청된 시안, 마젠타, 옐로우, 키(검정) 값을 가진 새 Color를 반환합니다. |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | 요청된 시안, 마젠타, 옐로우, 키(검정), 알파 값을 가진 새 Color를 반환합니다. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | 요청된 회색 값을 가진 새 Color를 반환합니다. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | 요청된 색조, 채도, 채도 값을 가진 새 Color를 반환합니다. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | 요청된 색조, 채도, 채도, 알파 값을 가진 새 Color를 반환합니다. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | 요청된 색조, 채도, 값을 가진 새 Color를 반환합니다. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | 요청된 색조, 채도, 값, 알파 값을 가진 새 Color를 반환합니다. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | 요청된 색조, 백색도, 흑색도 값을 가진 새 Color를 반환합니다. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | 요청된 색조, 백색도, 흑색도 값을 가진 새 Color를 반환합니다. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | 요청된 ARGB 값을 가진 새 Color를 반환합니다. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | 요청된 밝기, A, B 값을 가진 새 Color를 반환합니다. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | 요청된 밝기, A, B, 알파 값을 가진 새로운 Color를 반환합니다. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | 요청된 휘도, 채도, 색상 값을 가진 새로운 Color를 반환합니다. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | 요청된 휘도, 채도, 색상, 알파 값을 가진 새로운 Color를 반환합니다. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | OKLAB 모델에 대한 요청된 밝기, A, B 값을 가진 새로운 Color를 반환합니다. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | OKLAB 모델에 대한 요청된 밝기, A, B, 알파 값을 가진 새로운 Color를 반환합니다. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | OKLAB 모델에 대한 요청된 휘도, 채도, 색상 값을 가진 새로운 Color를 반환합니다. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | OKLAB 모델에 대한 요청된 휘도, 채도, 색상, 알파 값을 가진 새로운 Color를 반환합니다. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | 요청된 ged, green, blue 값을 가진 새로운 Color를 반환합니다. 모든 색 구성 요소는 0-255 범위에 있어야 합니다. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | 요청된 ged, green, blue 값을 가진 새로운 Color를 반환합니다. 모든 색 구성 요소는 0-1 범위에 있어야 합니다. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | 요청된 ged, green, blue 값을 가진 새로운 Color를 반환합니다. 모든 색 구성 요소는 0-255 범위에 있어야 합니다. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | 요청된 ged, green, blue, 알파 값을 가진 새로운 Color를 반환합니다. 모든 색 구성 요소는 0-255 범위에 있어야 합니다. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | 요청된 ged, green, blue, 알파 값을 가진 새로운 Color를 반환합니다. 모든 색 구성 요소는 0-1 범위에 있어야 합니다. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | 요청된 ged, green, blue, 알파 값을 가진 새로운 Color를 반환합니다. 모든 색 구성 요소는 0-255 범위에 있어야 합니다. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | CSS 색상을 포함하는 문자열을 파싱하고 새로운 Color를 반환합니다. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | 요청된 ARGB 값을 가진 새 Color를 반환합니다. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Color의 광도와 델타 값의 합으로 복사본을 생성합니다. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | 지정된 색상 모델 형식으로 색 구성 요소를 반환합니다. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | 지정된 `Color`가 이 인스턴스와 같은지 여부를 판단합니다. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | 원본 색상 휠의 반대쪽에 있는 새로운 색상을 반환합니다. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | 해시 코드를 반환합니다. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Color의 색조를 반환합니다. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Color의 광도를 반환합니다. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Color의 채도를 반환합니다. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Color ARGB 구성 요소를 int로 인코딩합니다. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | CSS 명명된 색상 목록에 있는 색상과 일치하면 색상의 이름을 반환하고, 그렇지 않으면 빈 문자열을 반환합니다. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | 색 문자와 숫자를 사용하여 색으로부터의 거리(퍼센트)를 지정하는 Natural colors (NCol) 지정 색상을 반환합니다. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Hexadecimal 색상은 #RRGGBBAA 형식으로 지정됩니다. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | rgba(R, G, B, A) 로 지정된 RGBA 색상을 포함하는 문자열을 반환합니다. |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | 16진수 색상은 #RRGGBB 형식으로 지정됩니다. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | RGB 색상은 rgb(R, G, B) 형식으로 지정된 문자열을 반환합니다. |
| [toString](../../com.aspose.html.drawing/color/toString/)() | RGBA 구성 요소 값을 포함하는 문자열을 반환합니다. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Color ARGB 구성 요소를 부호 없는 정수로 인코딩합니다. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | 지정된 알파 구성 요소를 가진 Color의 복사본을 생성합니다. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | 지정된 색조(Hue)를 가진 Color의 복사본을 생성합니다. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | 지정된 밝기(luminosity)를 가진 Color의 복사본을 생성합니다. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | 지정된 채도(saturation)를 가진 Color의 복사본을 생성합니다. |

### 또 보기

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)

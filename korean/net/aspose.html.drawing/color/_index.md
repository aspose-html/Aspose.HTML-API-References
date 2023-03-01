---
title: Class Color
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Drawing.Color 수업. Color 클래스를 사용하면 색상을 RGB빨강녹색파랑 값 HSL색조채도광도 값 HSV색조채도값 값 색조백색도검은색HWB으로 지정할 수 있습니다.  values 밝기ABLAB 값 LuminanceChromaHueLCH 값 CyanMagentaYellowKeyCMYK 값 자연색NCOL 값 또는 색상 이름 . 투명도를 나타내는 알파 채널도 사용할 수 있습니다.
type: docs
weight: 2640
url: /ko/net/aspose.html.drawing/color/
---
## Color class

Color 클래스를 사용하면 색상을 RGB(빨강-녹색-파랑) 값, HSL(색조-채도-광도) 값, HSV(색조-채도-값) 값, 색조-백색도-검은색(HWB)으로 지정할 수 있습니다. ) values, 밝기-AB(LAB) 값, Luminance-Chroma-Hue(LCH) 값, Cyan-Magenta-Yellow-Key(CMYK) 값, 자연색(NCOL) 값, 또는 색상 이름 . 투명도를 나타내는 알파 채널도 사용할 수 있습니다.

```csharp
public class Color
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Color](color/#constructor)() | 의 새 인스턴스를 초기화합니다.`Color` class. 기본 색상은 검정색입니다. |
| [Color](color/#constructor_1)(byte, byte, byte) | 의 새 인스턴스를 초기화합니다.`Color`class. 모든 색상 구성 요소는 0-255 범위에 있어야 합니다. |
| [Color](color/#constructor_5)(float, float, float) | 의 새 인스턴스를 초기화합니다.`Color` class. 모든 색상 구성 요소는 0-1. 범위에 있어야 합니다. |
| [Color](color/#constructor_3)(int, int, int) | 의 새 인스턴스를 초기화합니다.`Color`class. 모든 색상 구성 요소는 0-255 범위에 있어야 합니다. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | 의 새 인스턴스를 초기화합니다.`Color`class. 모든 색상 구성 요소는 0-255 범위에 있어야 합니다. |
| [Color](color/#constructor_6)(float, float, float, float) | 의 새 인스턴스를 초기화합니다.`Color` class. 모든 색상 구성 요소는 0-1. 범위에 있어야 합니다. |
| [Color](color/#constructor_4)(int, int, int, int) | 의 새 인스턴스를 초기화합니다.`Color`class. 모든 색상 구성 요소는 0-255 범위에 있어야 합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | 색상의 알파 구성 요소를 나타냅니다. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | 색상의 파란색 구성 요소를 나타냅니다. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | 색상의 녹색 구성 요소를 나타냅니다. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | 는 color 의 빨간색 구성 요소를 나타냅니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | 요청된 시안, 마젠타, 노랑, 키(검정) 값을 가진 새 색상을 반환합니다. |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | 요청된 사이안, 마젠타, 노랑, 키(검정), 알파 값을 가진 새 색상을 반환합니다. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | 요청한 회색 값을 가진 새 색상을 반환합니다. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | 요청된 색조, 채도, 채도 값을 가진 새 색상을 반환합니다. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | 요청된 색조, 채도, 채도, 알파 값을 가진 새 색상을 반환합니다. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | 요청된 색조, 채도, 값으로 새 색상을 반환합니다. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | 요청된 색조, 채도, 값, 알파가 포함된 새 색상을 반환합니다. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | 요청된 색조, 백색도, 흑도 값을 가진 새 색상을 반환합니다. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | 요청된 색조, 백색도, 흑도 값을 가진 새 색상을 반환합니다. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | 요청된 ARGB 값으로 새 색상을 반환합니다. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | 요청한 밝기, A, B 값을 가진 새 색상을 반환합니다. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | 요청한 밝기, A, B, 알파 값을 가진 새 색상을 반환합니다. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | 요청된 광도, 채도, 색조 값을 가진 새 색상을 반환합니다. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | 요청된 광도, 채도, 색조, 알파 값을 가진 새 색상을 반환합니다. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | OKLAB 모델에 대해 요청된 밝기, A, B 값을 가진 새 색상을 반환합니다. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | OKLAB 모델에 대해 요청된 밝기, A, B, 알파 값을 가진 새 색상을 반환합니다. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | OKLAB 모델에 대해 요청된 휘도, 채도, 색조 값으로 새 색상을 반환합니다. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | OKLAB 모델에 대해 요청된 휘도, 채도, 색조, 알파 값으로 새 색상을 반환합니다. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | 요청된 ged, 녹색, 파란색 값을 가진 새 색상을 반환합니다. 모든 색상 구성 요소는 0-255 범위에 있어야 합니다. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | 요청된 ged, 녹색, 파란색 값을 가진 새 색상을 반환합니다. 모든 색상 구성 요소는 0-1 범위에 있어야 합니다. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | 요청된 ged, 녹색, 파란색 값을 가진 새 색상을 반환합니다. 모든 색상 구성 요소는 0-255 범위에 있어야 합니다. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | 요청된 ged, 녹색, 파란색, 알파 값이 있는 새 색상을 반환합니다. 모든 색상 구성 요소는 0-255 범위에 있어야 합니다. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | 요청된 ged, 녹색, 파란색, 알파 값이 있는 새 색상을 반환합니다. 모든 색상 구성 요소는 0-1 범위에 있어야 합니다. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | 요청된 ged, 녹색, 파란색, 알파 값이 있는 새 색상을 반환합니다. 모든 색상 구성 요소는 0-255 범위에 있어야 합니다. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | CSS 색상을 포함하는 문자열을 구문 분석하고 새 색상을 반환합니다. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | 요청된 ARGB 값으로 새 색상을 반환합니다. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | 광도와 델타 값의 합으로 색상의 복사본을 만듭니다. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | 지정된 색상 모델의 형식으로 색상 구성 요소를 반환합니다. |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | 지정된`Color` 이 인스턴스와 같습니다. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | 원본에서 색상환의 반대쪽에 있는 새 색상을 반환합니다. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | 해시 코드를 반환합니다. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | 색상의 색조를 반환합니다. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Color. 의 광도를 반환합니다. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Color. 의 채도를 반환합니다. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Color ARGB 구성 요소를 int. 로 인코딩합니다. |
| [ToName](../../aspose.html.drawing/color/toname/)() | CSS 명명된 색상 목록의 색상 또는 빈 문자열과 일치하는 경우 색상 이름을 반환합니다. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | 색상과의 거리(백분율)를 지정하는 숫자와 함께 색상 문자를 사용하여 자연 색상(NCol) 지정 색상을 반환합니다. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | 다음과 같이 지정된 16진수 색상을 반환합니다. #RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | rgba(R, G, B, A). 에 의해 지정된 RGBA 색상을 포함하는 문자열을 반환합니다. |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | #RRGGBB. 로 지정된 16진수 색상을 반환합니다. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | 다음에 의해 지정된 RGB 색상을 포함하는 문자열을 반환합니다. rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | RGBA 구성 요소 값으로 구성된 문자열을 반환합니다. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Color ARGB 구성 요소를 부호 없는 정수로 인코딩합니다. |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | 지정된 알파 구성 요소로 색상의 복사본을 만듭니다. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | 지정된 색조로 색상의 복사본을 만듭니다. |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | 지정된 광도로 색상의 복사본을 만듭니다. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | 지정된 채도로 색상의 복사본을 만듭니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 집회 [Aspose.HTML](../../)



---
title: Class CSSPrimitiveValue
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css.CSSPrimitiveValue 수업. CSSPrimitiveValue 인터페이스는 단일 CSS 값을 나타냅니다. 이 인터페이스는 현재 블록에 설정된 특정 스타일 속성의 값을 결정하거나 블록 내에서 명시적으로 특정 스타일 속성을 설정하는 데 사용할 수 있습니다. 이 인터페이스의 인스턴스는 CSSStyleDeclaration 인터페이스의 getPropertyCSSValue 메서드에서 가져올 수 있습니다. CSSPrimitiveValue 개체는 CSS 속성의 컨텍스트에서만 발생합니다.
type: docs
weight: 330
url: /ko/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue 인터페이스는 단일 CSS 값을 나타냅니다. 이 인터페이스는 현재 블록에 설정된 특정 스타일 속성의 값을 결정하거나 블록 내에서 명시적으로 특정 스타일 속성을 설정하는 데 사용할 수 있습니다. 이 인터페이스의 인스턴스는 CSSStyleDeclaration 인터페이스의 getPropertyCSSValue 메서드에서 가져올 수 있습니다. CSSPrimitiveValue 개체는 CSS 속성의 컨텍스트에서만 발생합니다.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## 속성

| 이름 | 설명 |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | 현재 값의 문자열 표현입니다. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | 값의 유형을 정의하는 코드. |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype/) { get; } | 위에 지정된 상수로 정의된 값의 유형입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | 지정된Object 이 인스턴스와 같습니다. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | 이 메서드는 카운터 값을 가져오는 데 사용됩니다. 이 CSS 값에 카운터 값이 없으면 DOMException이 발생합니다. 해당 스타일 속성에 대한 수정은 카운터 인터페이스를 사용하여 수행할 수 있습니다. |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | 이 메서드는 지정된 단위로 float 값을 가져오는 데 사용됩니다. 이 CSS 값이 float 값을 포함하지 않거나 지정된 단위로 변환할 수 없는 경우 DOMException이 발생합니다. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | 이 메서드는 지정된 단위로 int 값을 가져오는 데 사용됩니다. 이 CSS 값이 int 값을 포함하지 않거나 지정된 단위로 변환할 수 없는 경우 DOMException이 발생합니다. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | 이 메서드는 Rect 값을 가져오는 데 사용됩니다. 이 CSS 값에 rect 값이 없으면 DOMException이 발생합니다. 해당 스타일 속성에 대한 수정은 Rect 인터페이스를 사용하여 수행할 수 있습니다. |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | 이 메서드는 RGB 색상을 가져오는 데 사용됩니다. 이 CSS 값에 RGB 색상 값이 없으면 DOMException이 발생합니다. RGBColor 인터페이스를 사용하여 해당 스타일 속성을 수정할 수 있습니다. |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue/)() | 이 메서드는 문자열 값을 가져오는 데 사용됩니다. CSS 값에 문자열 값이 없으면 DOMException이 발생합니다. |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | 지정된 단위로 float 값을 설정하는 방법. 이 값이 첨부된 속성이 지정된 단위 또는 부동 소수점 값을 허용할 수 없으면 값이 변경되지 않고 DOMException이 발생합니다. |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | 지정된 단위로 int 값을 설정하는 방법. 이 값으로 연결된 속성이 지정된 단위 또는 int 값을 허용할 수 없으면 값이 변경되지 않고 DOMException이 발생합니다. |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | 지정된 단위로 문자열 값을 설정하는 방법. 이 값에 연결된 속성이 지정된 단위 또는 문자열 값을 허용할 수 없으면 값이 변경되지 않고 DOMException이 발생합니다. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr/) | 값은 속성 함수입니다. 값은 getStringValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch/) | 값은 길이(ch)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm/) | 값은 길이(cm)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter/) | 값이 카운터 또는 카운터 함수입니다. 값은 GetCounterValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg/) | 값은 각도(deg)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension/) | 값은 크기를 알 수 없는 숫자입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | 값은 센티미터당 도트 수(dpcm)입니다. |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi/) | 값은 인치당 도트 수(dpi)입니다. |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx/) | 값은 'px' 단위당 도트 수(dppx)입니다. |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems/) | 값은 길이(ems)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs/) | 값은 길이(exs)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad/) | 값은 각도(grad)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz/) | 값은 주파수(Hz)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident/) | 값은 식별자입니다. 값은 getStringValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in/) | 값은 길이(in)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz/) | 값은 주파수(kHz)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm/) | 값은 길이(mm)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms/) | 값은 시간(ms)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number/) | 값은 단순 숫자입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc/) | 값은 길이(pc)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage/) | 값은 백분율입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt/) | 값은 길이(pt)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px/) | 값은 길이(px)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad/) | 값은 각도(rad)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect/) | 값은 rect 함수입니다. 값은 GetRectValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem/) | 값은 길이(rem)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | 값은 RGB 색상입니다. 값은 GetRGBColorValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s/) | 값은 시간(초)입니다. 값은 getFloatValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string/) | 값은 STRING입니다. 값은 getStringValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown/) | 값이 인식된 CSS2 값이 아닙니다. 이 값은 cssText 속성을 통해서만 얻을 수 있습니다. |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri/) | 값은 URI입니다. 값은 getStringValue 메소드를 사용하여 얻을 수 있습니다. |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh/) | 값은 전체 뷰포트 높이의 백분율입니다. |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax/) | 값은 뷰포트 너비 또는 높이 중 큰 값의 백분율입니다. |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin/) | 값은 뷰포트 너비 또는 높이 중 작은 값의 백분율입니다. |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw/) | 값은 전체 뷰포트 너비의 백분율입니다. |

### 또한보십시오

* class [CSSValue](../cssvalue/)
* 네임스페이스 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 집회 [Aspose.HTML](../../)



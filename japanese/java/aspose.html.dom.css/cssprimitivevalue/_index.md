---
title: "CSSPrimitiveValue クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.CSSPrimitiveValue クラス。CSSPrimitiveValue インターフェイスは CSSValue インターフェイスから派生し、CSS プロパティの現在の計算値を表します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue インターフェイスは CSSValue インターフェイスから派生し、CSS プロパティの現在の計算値を表します。

注: このインターフェイスは型付けされた CSS オブジェクトモデルを作成しようとした試みの一部でした。この試みは中止され、ほとんどのブラウザーは実装していません。

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) インターフェイスの cssText プロパティは、現在の計算済み CSS プロパティ値を表します。 |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 値の型を定義するコードです。 |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) 上記で定義された定数により示される値のタイプです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | このメソッドは Counter の値を取得するために使用されます。この CSS 値にカウンタ値が含まれていない場合、DOMException がスローされます。対応するスタイルプロパティの変更は Counter インターフェイスを使用して行うことができます。 |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | このメソッドは、指定された単位で浮動小数点値を取得するために使用されます。もしこの CSS 値に浮動小数点値が含まれていない、または指定された単位に変換できない場合、DOMException が発生します。 |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | このメソッドは、指定された単位で整数値を取得するために使用されます。もしこの CSS 値に整数値が含まれていない、または指定された単位に変換できない場合、DOMException が発生します。 |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの Type を取得するために使用されます。 |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | このメソッドは Rect 値を取得するために使用されます。もしこの CSS 値に rect 値が含まれていない場合、DOMException が発生します。対応するスタイルプロパティの変更は Rect インターフェイスを使用して行うことができます。 |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | このメソッドは RGB カラーを取得するために使用されます。もしこの CSS 値に RGB カラー値が含まれていない場合、DOMException が発生します。対応するスタイルプロパティの変更は RGBColor インターフェイスを使用して行うことができます。 |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | このメソッドは文字列値を取得するために使用されます。もし CSS 値に文字列値が含まれていない場合、DOMException が発生します。 |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | 指定された単位で浮動小数点値を設定するメソッドです。もしこの値が付随するプロパティが指定された単位または浮動小数点値を受け付けない場合、値は変更されず、DOMException が発生します。 |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | 指定された単位で整数値を設定するメソッドです。もしこの値が付随するプロパティが指定された単位または整数値を受け付けない場合、値は変更されず、DOMException が発生します。 |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | 指定された単位で文字列値を設定するメソッドです。もしこの値が付随するプロパティが指定された単位または文字列値を受け付けない場合、値は変更されず、DOMException が発生します。 |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | このインスタンスを表す文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | この値は属性関数です。値は getStringValue メソッドを使用して取得できます。 |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | この値は長さ (ch) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | この値は長さ (cm) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | この値は counter または counters 関数です。値は GetCounterValue メソッドを使用して取得できます。 |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | この値は角度 (deg) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | この値は未知の次元を持つ数値です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | この値はセンチメートルあたりドット数 (dpcm) です。 |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | この値はインチあたりドット数 (dpi) です。 |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | この値は ‘px’ 単位あたりドット数 (dppx) です。 |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | この値は長さ (ems) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | この値は長さ (exs) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | この値は角度 (grad) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | この値は周波数 (Hz) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | この値は識別子です。値は getStringValue メソッドを使用して取得できます。 |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | この値は長さ (in) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | この値は周波数 (kHz) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | この値は長さ (mm) です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | 値は時間（ms）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | 値は単純な数値です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | 値は長さ（pc）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | 値はパーセンテージです。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | 値は長さ（pt）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | 値は長さ（px）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | 値は角度（rad）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | 値は rect 関数です。値は GetRectValue メソッドを使用して取得できます。 |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | 値は長さ（rem）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | 値は RGB カラーです。値は GetRGBColorValue メソッドを使用して取得できます。 |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | 値は時間（s）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | 値は文字列（STRING）です。値は getStringValue メソッドを使用して取得できます。 |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | 値は認識された CSS2 の値ではありません。値は cssText 属性を使用してのみ取得できます。 |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | 値は URI です。値は getStringValue メソッドを使用して取得できます。 |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | 値はビューポート全体の高さのパーセンテージです。 |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | 値はビューポートの幅または高さのパーセンテージで、より大きい方です。 |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | 値はビューポートの幅または高さのパーセンテージで、より小さい方です。 |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | 値はビューポート全体の幅のパーセンテージです。 |

### 関連項目

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

---
title: Class Color
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Drawing.Color クラス. Color クラスでは色を 赤緑青 RGB 値 色相彩度明度 HSL 値 色相彩度値 HSV 値 色相白度黒度 HWB として指定できます  値 明度AB LAB 値 輝度彩度色相 LCH 値 シアンマゼンタイエローキー CMYK 値 ナチュラル カラー NCOL 値 または色名付き. 透明度を示すアルファチャンネルも利用できます.
type: docs
weight: 2640
url: /ja/net/aspose.html.drawing/color/
---
## Color class

Color クラスでは、色を 赤緑青 (RGB) 値、 色相彩度明度 (HSL) 値、 色相彩度値 (HSV) 値、 色相白度黒度 (HWB) として指定できます。 ) 値、 明度-AB (LAB) 値、 輝度-彩度-色相 (LCH) 値、 シアン-マゼンタ-イエロー-キー (CMYK) 値、 ナチュラル カラー (NCOL) 値、 または色名付き. 透明度を示すアルファチャンネルも利用できます.

```csharp
public class Color
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Color](color/#constructor)() | の新しいインスタンスを初期化します`Color` class. デフォルトの色は黒です. |
| [Color](color/#constructor_1)(byte, byte, byte) | の新しいインスタンスを初期化します`Color`class. すべてのカラー コンポーネントは 0 ～ 255 の範囲内である必要があります。 |
| [Color](color/#constructor_5)(float, float, float) | の新しいインスタンスを初期化します`Color` class. すべての色成分は 0 ～ 1 の範囲内である必要があります。 |
| [Color](color/#constructor_3)(int, int, int) | の新しいインスタンスを初期化します`Color`class. すべてのカラー コンポーネントは 0 ～ 255 の範囲内である必要があります。 |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | の新しいインスタンスを初期化します`Color`class. すべてのカラー コンポーネントは 0 ～ 255 の範囲内である必要があります。 |
| [Color](color/#constructor_6)(float, float, float, float) | の新しいインスタンスを初期化します`Color` class. すべての色成分は 0 ～ 1 の範囲内である必要があります。 |
| [Color](color/#constructor_4)(int, int, int, int) | の新しいインスタンスを初期化します`Color`class. すべてのカラー コンポーネントは 0 ～ 255 の範囲内である必要があります。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | 色のアルファ成分を表します. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | 色の青の成分を表します. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | 色の緑の成分を表します. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | color の赤のコンポーネントを表します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | 要求されたシアン、マゼンタ、イエロー、キー (黒) の値を持つ新しい Color を返します。 |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | 要求されたシアン、マゼンタ、イエロー、キー (黒)、アルファ値を持つ新しい Color を返します。 |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | 要求されたグレー値で新しい Color を返します。 |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | 要求された色相、彩度、彩度の値を持つ新しい Color を返します。 |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | 要求された色相、彩度、彩度、アルファ値を持つ新しい Color を返します。 |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | 要求された色相、彩度、値を持つ新しい Color を返します。 |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | 要求された色相、彩度、値、アルファを持つ新しい Color を返します。 |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | 要求された色相、白さ、黒さの値を持つ新しい Color を返します。 |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | 要求された色相、白さ、黒さの値を持つ新しい Color を返します。 |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | 要求された ARGB 値を持つ新しい Color を返します. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | 要求された明度、A、B 値を持つ新しい Color を返します。 |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | 要求された明度、A、B、アルファ値を持つ新しい Color を返します。 |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | 要求された輝度、彩度、色相の値を持つ新しい Color を返します。 |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | 要求された輝度、彩度、色相、アルファ値を持つ新しい Color を返します。 |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | OKLAB モデルの要求された明度、A、B 値を持つ新しい色を返します。 |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | OKLAB モデルの要求された明度、A、B、アルファ値を持つ新しい色を返します。 |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | OKLAB モデルの要求された輝度、彩度、色相の値を持つ新しい色を返します。 |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | OKLAB モデルの要求された輝度、彩度、色相、アルファ値を持つ新しい色を返します。 |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | 要求された ged、green、blue 値を持つ新しい Color を返します。 すべての色成分は 0 ～ 255 の範囲内である必要があります。 |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | 要求された ged、green、blue の値を持つ新しい Color を返します。 すべてのカラー コンポーネントは 0 ～ 1 の範囲内である必要があります。 |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | 要求された ged、green、blue 値を持つ新しい Color を返します。 すべての色成分は 0 ～ 255 の範囲内である必要があります。 |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | 要求された ged、green、blue、alpha 値を持つ新しい Color を返します。 すべてのカラー コンポーネントは 0 ～ 255 の範囲内である必要があります。 |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | 要求された ged、green、blue、alpha 値を持つ新しい Color を返します。 すべてのカラー コンポーネントは 0 ～ 1 の範囲内である必要があります。 |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | 要求された ged、green、blue、alpha 値を持つ新しい Color を返します。 すべてのカラー コンポーネントは 0 ～ 255 の範囲内である必要があります。 |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | CSS カラーを含む文字列を解析し、新しい Color. を返します。 |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | 要求された ARGB 値を持つ新しい Color を返します. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | 明るさとデルタ値の合計で色のコピーを作成します. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | 指定されたカラー モデルの形式でカラー コンポーネントを返します。 |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | 指定された`Color`このインスタンスと等しい. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | 元のカラー ホイールの反対側にある新しい色を返します。 |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | ハッシュコードを返します. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | 色の色相を返します. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Color の明度を返します。 |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Color の彩度を返します。 |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Color ARGB コンポーネントを int. にエンコードします。 |
| [ToName](../../aspose.html.drawing/color/toname/)() | CSS の名前付き色のリスト内の色、または空の文字列に一致する場合は、色の名前を返します。 |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | 色からの距離 (パーセント) を指定する数値を含む色文字を使用して、自然色 (NCol) で指定された色を返します。 |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | #RRGGBBAA. で指定された 16 進数の色を返します。 |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | rgba(R, G, B, A). で指定された RGBA カラーを含む文字列を返します。 |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | #RRGGBB. で指定された 16 進数の色を返します。 |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | rgb(R, G, B). で指定された RGB カラーを含む文字列を返します。 |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | RGBA コンポーネント値で構成される文字列を返します。 |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Color ARGB コンポーネントを unsigned int. にエンコードします。 |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | 指定されたアルファ コンポーネントで Color のコピーを作成します。 |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | 指定された色相で色のコピーを作成します。 |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | 指定された明度で色のコピーを作成します. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | 指定された彩度で Color のコピーを作成します。 |

### 関連項目

* 名前空間 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 組み立て [Aspose.HTML](../../)



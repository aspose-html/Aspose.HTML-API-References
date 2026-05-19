---
title: "Color クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.drawing.Color クラス。Color クラスを使用すると、Red-Green-Blue RGB 値、Hue-Saturation-Luminosity HSL 値、Hue-Saturation-Value HSV 値、Hue-Whiteness-Blackness HWB 値、lightness-A-B LAB 値、Luminance-Chroma-Hue LCH 値、Cyan-Magenta-Yellow-Key CMYK 値、Natural colors NCOL 値、またはカラー名で色を指定できます。透明度を示す Alpha チャネルも利用可能です。"
type: docs

url: /ja/java/com.aspose.html.drawing/color/
---
## Color class

Color クラスを使用すると、赤緑青 (RGB) 値、色相-彩度-明度 (HSL) 値、色相-彩度-明度 (HSV) 値、色相-白度-黒度 (HWB) 値、光度-A-B (LAB) 値、輝度-彩度-色相 (LCH) 値、シアン-マゼンタ-イエロー-キー (CMYK) 値、自然色 (NCOL) 値、または色名で色を指定できます。アルファチャンネルも利用可能で、透明度を示します。

```java
public class Color
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Color](color/#constructor)() | `Color` クラスの新しいインスタンスを初期化します。デフォルトの色は黒です。 |
| [Color](color/#constructor_1)(byte, byte, byte) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラ―コンポーネントは 0〜255 の範囲でなければなりません。 |
| [Color](color/#constructor_5)(float, float, float) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラ―コンポーネントは 0〜1 の範囲でなければなりません。 |
| [Color](color/#constructor_3)(int, int, int) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラ―コンポーネントは 0〜255 の範囲でなければなりません。 |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラ―コンポーネントは 0〜255 の範囲でなければなりません。 |
| [Color](color/#constructor_6)(float, float, float, float) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラ―コンポーネントは 0〜1 の範囲でなければなりません。 |
| [Color](color/#constructor_4)(int, int, int, int) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラ―コンポーネントは 0〜255 の範囲でなければなりません。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) カラーのアルファ成分を表します。 |
| [getBlue](../../com.aspose.html.drawing/color/blue/) カラーの青成分を表します。 |
| [getGreen](../../com.aspose.html.drawing/color/green/) カラーの緑成分を表します。 |
| [getRed](../../com.aspose.html.drawing/color/red/) カラーの赤成分を表します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | 要求されたシアン、マゼンタ、イエロー、キー（黒）値を持つ新しい Color を返します。 |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | 要求されたシアン、マゼンタ、イエロー、キー（黒）およびアルファ値を持つ新しい Color を返します。 |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | 要求されたグレイ値を持つ新しい Color を返します。 |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | 要求された色相、彩度、彩度の値を持つ新しい Color を返します。 |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | 要求された色相、彩度、彩度、アルファ値を持つ新しい Color を返します。 |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | 要求された色相、彩度、値を持つ新しい Color を返します。 |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | 要求された色相、彩度、値、アルファを持つ新しい Color を返します。 |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | 要求された色相、ホワイトネス、ブラックネスの値を持つ新しい Color を返します。 |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | 要求された色相、ホワイトネス、ブラックネスの値を持つ新しい Color を返します。 |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | 要求された ARGB 値を持つ新しい Color を返します。 |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | 要求されたライトネス、A、B の値を持つ新しい Color を返します。 |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | 要求された明度、A、B、アルファ値を持つ新しい Color を返します。 |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | 要求された輝度、クロマ、色相値を持つ新しい Color を返します。 |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | 要求された輝度、クロマ、色相、アルファ値を持つ新しい Color を返します。 |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | OKLAB モデル用に要求された明度、A、B 値を持つ新しい Color を返します。 |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | OKLAB モデル用に要求された明度、A、B、アルファ値を持つ新しい Color を返します。 |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | OKLAB モデル用に要求された輝度、クロマ、色相値を持つ新しい Color を返します。 |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | OKLAB モデル用に要求された輝度、クロマ、色相、アルファ値を持つ新しい Color を返します。 |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | 要求された ged、緑、青 の値を持つ新しい Color を返します。すべての色成分は 0〜255 の範囲でなければなりません。 |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | 要求された ged、緑、青 の値を持つ新しい Color を返します。すべての色成分は 0〜1 の範囲でなければなりません。 |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | 要求された ged、緑、青 の値を持つ新しい Color を返します。すべての色成分は 0〜255 の範囲でなければなりません。 |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | 要求された ged、緑、青、アルファ の値を持つ新しい Color を返します。すべての色成分は 0〜255 の範囲でなければなりません。 |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | 要求された ged、緑、青、アルファ の値を持つ新しい Color を返します。すべての色成分は 0〜1 の範囲でなければなりません。 |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | 要求された ged、緑、青、アルファ の値を持つ新しい Color を返します。すべての色成分は 0〜255 の範囲でなければなりません。 |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | CSS カラーを含む String を解析し、新しい Color を返します。 |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | 要求された ARGB 値を持つ新しい Color を返します。 |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Color の輝度とデルタ値の合計を持つコピーを作成します。 |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | 指定されたカラーモデルの形式でカラーコンポーネントを返します。 |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | 指定された `Color` がこのインスタンスと等しいかどうかを判定します。 |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | 元の色のカラーホイール上の反対側にある新しい色を返します。 |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | ハッシュコードを返します。 |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Color の色相 (Hue) を返します。 |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Color の輝度を返します。 |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Color の彩度を返します。 |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Color の ARGB コンポーネントを int にエンコードします。 |
| [toName](../../com.aspose.html.drawing/color/toname/)() | CSS の名前付きカラーリストにあるカラーと一致すればその名前を返し、そうでなければ空の String を返します。 |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | 色文字と数値で距離（パーセンテージ）を指定して、自然色 (NCol) の指定カラーを返します。 |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | 16 進数カラーは #RRGGBBAA で指定されます。 |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | rgba(R, G, B, A) で指定された RGBA カラーを含む String を返します。 |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | 16進数カラーは #RRGGBB で指定されます。 |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | rgb(R, G, B) で指定された RGB カラーを含む文字列を返します。 |
| [toString](../../com.aspose.html.drawing/color/toString/)() | RGBA コンポーネント値からなる文字列を返します。 |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Color の ARGB コンポーネントを符号なし整数にエンコードします。 |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | 指定されたアルファコンポーネントを持つ Color のコピーを作成します。 |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | 指定された色相を持つ Color のコピーを作成します。 |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | 指定された輝度を持つ Color のコピーを作成します。 |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | 指定された彩度を持つ Color のコピーを作成します。 |

### 関連項目

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)

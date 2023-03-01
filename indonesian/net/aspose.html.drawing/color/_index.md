---
title: Class Color
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Drawing.Color kelas. Kelas Color memungkinkan Anda menentukan warna sebagai nilai RedGreenBlue RGB nilai HueSaturationLuminosity HSL nilai HueSaturationValue HSV HueWhitenessBlackness HWB  nilai nilai lightnessAB LAB nilai LuminanceChromaHue LCH nilai CyanMagentaYellowKey CMYK Nilai warna natural NCOL atau dengan nama warna . Saluran Alfa juga tersedia untuk menunjukkan transparansi.
type: docs
weight: 2640
url: /id/net/aspose.html.drawing/color/
---
## Color class

Kelas Color memungkinkan Anda menentukan warna sebagai nilai Red-Green-Blue (RGB), nilai Hue-Saturation-Luminosity (HSL), nilai Hue-Saturation-Value (HSV), Hue-Whiteness-Blackness (HWB ) nilai, nilai lightness-AB (LAB), nilai Luminance-Chroma-Hue (LCH), nilai Cyan-Magenta-Yellow-Key (CMYK), Nilai warna natural (NCOL), atau dengan nama warna . Saluran Alfa juga tersedia untuk menunjukkan transparansi.

```csharp
public class Color
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Color](color/#constructor)() | Menginisialisasi instance baru dari`Color` class. Secara default warna hitam. |
| [Color](color/#constructor_1)(byte, byte, byte) | Menginisialisasi instance baru dari`Color`class. Semua komponen warna harus berada dalam rentang 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Menginisialisasi instance baru dari`Color` class. Semua komponen warna harus berada dalam rentang 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Menginisialisasi instance baru dari`Color`class. Semua komponen warna harus berada dalam rentang 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Menginisialisasi instance baru dari`Color`class. Semua komponen warna harus berada dalam rentang 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Menginisialisasi instance baru dari`Color` class. Semua komponen warna harus berada dalam rentang 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Menginisialisasi instance baru dari`Color`class. Semua komponen warna harus berada dalam rentang 0-255. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | Merupakan komponen alfa dari warna. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | Mewakili komponen warna biru. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | Merupakan komponen warna hijau. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | Mewakili komponen warna merah |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Mengembalikan Warna baru dengan nilai cyan, magenta, kuning, kunci (hitam) yang diminta. |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Mengembalikan Warna baru dengan nilai cyan, magenta, kuning, kunci (hitam), alfa yang diminta. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | Mengembalikan Warna baru dengan nilai abu-abu yang diminta. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | Mengembalikan Warna baru dengan nilai rona, saturasi, saturasi yang diminta. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Mengembalikan Warna baru dengan nilai rona, saturasi, saturasi, alfa yang diminta. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | Mengembalikan Warna baru dengan rona, saturasi, nilai yang diminta. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Mengembalikan Warna baru dengan rona, saturasi, nilai, alfa yang diminta. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | Mengembalikan Warna baru dengan nilai hue, whiteness, blackness yang diminta. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Mengembalikan Warna baru dengan nilai hue, whiteness, blackness yang diminta. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | Mengembalikan Warna baru dengan nilai ARGB yang diminta. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | Mengembalikan Warna baru dengan nilai kecerahan, A, B yang diminta. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Mengembalikan Warna baru dengan nilai kecerahan, A, B, alfa yang diminta. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | Mengembalikan Warna baru dengan nilai luminance, chroma, hue yang diminta. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Mengembalikan Warna baru dengan nilai luminance, chroma, hue, alpha yang diminta. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | Mengembalikan Warna baru dengan nilai kecerahan, A, B yang diminta untuk model OKLAB. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Mengembalikan Warna baru dengan nilai kecerahan, A, B, alfa yang diminta untuk model OKLAB. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | Mengembalikan Warna baru dengan nilai luminance, chroma, hue yang diminta untuk model OKLAB. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Mengembalikan Warna baru dengan luminance, chroma, hue, nilai alpha yang diminta untuk model OKLAB. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Mengembalikan Warna baru dengan nilai ged, green, blue yang diminta. Semua komponen warna harus dalam kisaran 0-255. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Mengembalikan Warna baru dengan nilai ged, hijau, biru yang diminta. Semua komponen warna harus dalam kisaran 0-1. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Mengembalikan Warna baru dengan nilai ged, green, blue yang diminta. Semua komponen warna harus dalam kisaran 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Mengembalikan Warna baru dengan nilai ged, hijau, biru, alfa yang diminta. Semua komponen warna harus dalam kisaran 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Mengembalikan Warna baru dengan nilai ged, hijau, biru, alfa yang diminta. Semua komponen warna harus dalam kisaran 0-1. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Mengembalikan Warna baru dengan nilai ged, hijau, biru, alfa yang diminta. Semua komponen warna harus dalam kisaran 0-255. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | Mem-parsing string yang berisi warna CSS dan mengembalikan Color. baru |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | Mengembalikan Warna baru dengan nilai ARGB yang diminta. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | Membuat salinan Warna dengan Jumlah luminositasnya dan nilai delta. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | Mengembalikan komponen warna dalam format model warna yang ditentukan. |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | Menentukan apakah yang ditentukan`Color` sama dengan instance ini. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | Mengembalikan warna baru yang berseberangan dengan roda warna aslinya. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | Mengembalikan kode hash. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | Mengembalikan Rona Warna. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Mengembalikan luminositas Warna. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Mengembalikan saturasi Warna. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Mengkodekan komponen Color ARGB ke dalam int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | Mengembalikan nama warna jika cocok dengan warna dalam daftar warna bernama CSS, atau string kosong. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | Mengembalikan warna Natural colors (NCol) yang ditentukan menggunakan huruf warna dengan angka untuk menentukan jarak (dalam persen) dari warna. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | Mengembalikan warna Heksadesimal ditentukan dengan: #RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | Mengembalikan string yang berisi warna RGBA yang ditentukan oleh: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | Mengembalikan warna heksadesimal yang ditentukan dengan: #RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | Mengembalikan string yang berisi warna RGB yang ditentukan oleh: rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | Mengembalikan string yang terdiri dari nilai komponen RGBA. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Mengkodekan komponen Color ARGB ke int. yang tidak ditandatangani |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | Membuat salinan Warna dengan komponen alfa yang ditentukan. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | Membuat salinan Warna dengan Hue. yang ditentukan |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | Membuat salinan Warna dengan luminositas yang ditentukan. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | Membuat salinan Warna dengan saturasi yang ditentukan. |

### Lihat juga

* ruang nama [Aspose.Html.Drawing](../../aspose.html.drawing/)
* perakitan [Aspose.HTML](../../)



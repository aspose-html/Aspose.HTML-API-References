---
title: "Kelas Color"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.drawing.Color. Kelas Color memungkinkan Anda menentukan warna sebagai nilai Red-Green-Blue RGB, nilai Hue-Saturation-Luminosity HSL, nilai Hue-Saturation-Value HSV, nilai Hue-Whiteness-Blackness HWB, nilai lightness-A-B LAB, nilai Luminance-Chroma-Hue LCH, nilai Cyan-Magenta-Yellow-Key CMYK, nilai Natural colors NCOL, atau dengan nama warna. Saluran Alpha juga tersedia untuk menunjukkan transparansi."
type: docs

url: /id/java/com.aspose.html.drawing/color/
---
## Color class

Kelas Color memungkinkan Anda menentukan warna sebagai nilai Merah-Hijau-Biru (RGB), nilai Hue-Saturation-Luminosity (HSL), nilai Hue-Saturation-Value (HSV), nilai Hue-Whiteness-Blackness (HWB), nilai lightness-A-B (LAB), nilai Luminance-Chroma-Hue (LCH), nilai Cyan-Magenta-Yellow-Key (CMYK), nilai Natural colors (NCOL), atau dengan nama warna. Saluran Alpha juga tersedia untuk menunjukkan transparansi.

```java
public class Color
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Color](color/#constructor)() | Menginisialisasi instance baru dari kelas `Color`. Secara default warna adalah hitam. |
| [Color](color/#constructor_1)(byte, byte, byte) | Menginisialisasi instance baru dari kelas `Color`. Semua komponen warna harus berada dalam rentang 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Menginisialisasi instance baru dari kelas `Color`. Semua komponen warna harus berada dalam rentang 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Menginisialisasi instance baru dari kelas `Color`. Semua komponen warna harus berada dalam rentang 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Menginisialisasi instance baru dari kelas `Color`. Semua komponen warna harus berada dalam rentang 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Menginisialisasi instance baru dari kelas `Color`. Semua komponen warna harus berada dalam rentang 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Menginisialisasi instance baru dari kelas `Color`. Semua komponen warna harus berada dalam rentang 0-255. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Mewakili komponen alpha dari warna. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Mewakili komponen biru dari warna. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Mewakili komponen hijau dari warna. |
| [getRed](../../com.aspose.html.drawing/color/red/) Mewakili komponen merah dari warna |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Mengembalikan Color baru dengan nilai cyan, magenta, kuning, key (hitam) yang diminta. |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Mengembalikan Color baru dengan nilai cyan, magenta, kuning, key (hitam), alpha yang diminta. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Mengembalikan Color baru dengan nilai abu-abu yang diminta. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Mengembalikan Color baru dengan nilai hue, saturasi, saturasi yang diminta. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Mengembalikan Color baru dengan nilai hue, saturasi, saturasi, alpha yang diminta. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Mengembalikan Color baru dengan nilai hue, saturasi, value yang diminta. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Mengembalikan Color baru dengan nilai hue, saturasi, value, alpha yang diminta. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Mengembalikan Color baru dengan nilai hue, whiteness, blackness yang diminta. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Mengembalikan Color baru dengan nilai hue, whiteness, blackness yang diminta. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Mengembalikan Color baru dengan nilai ARGB yang diminta. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Mengembalikan Color baru dengan nilai lightness, A, B yang diminta. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Mengembalikan Color baru dengan nilai kecerahan, A, B, dan alpha yang diminta. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Mengembalikan Color baru dengan nilai luminansi, kroma, hue yang diminta. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Mengembalikan Color baru dengan nilai luminansi, kroma, hue, dan alpha yang diminta. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Mengembalikan Color baru dengan nilai kecerahan, A, B yang diminta untuk model OKLAB. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Mengembalikan Color baru dengan nilai kecerahan, A, B, dan alpha yang diminta untuk model OKLAB. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Mengembalikan Color baru dengan nilai luminansi, kroma, hue yang diminta untuk model OKLAB. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Mengembalikan Color baru dengan nilai luminansi, kroma, hue, dan alpha yang diminta untuk model OKLAB. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Mengembalikan Color baru dengan nilai ged, hijau, biru yang diminta. Semua komponen warna harus berada dalam rentang 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Mengembalikan Color baru dengan nilai ged, hijau, biru yang diminta. Semua komponen warna harus berada dalam rentang 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Mengembalikan Color baru dengan nilai ged, hijau, biru yang diminta. Semua komponen warna harus berada dalam rentang 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Mengembalikan Color baru dengan nilai ged, hijau, biru, alpha yang diminta. Semua komponen warna harus berada dalam rentang 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Mengembalikan Color baru dengan nilai ged, hijau, biru, alpha yang diminta. Semua komponen warna harus berada dalam rentang 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Mengembalikan Color baru dengan nilai ged, hijau, biru, alpha yang diminta. Semua komponen warna harus berada dalam rentang 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Menganalisis String yang berisi warna CSS dan mengembalikan Color baru. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Mengembalikan Color baru dengan nilai ARGB yang diminta. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Membuat salinan Color dengan Jumlah luminositasnya dan nilai delta. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Mengembalikan komponen warna dalam format model warna yang ditentukan. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Menentukan apakah `Color` yang ditentukan sama dengan instance ini. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Mengembalikan warna baru yang berada di sisi berlawanan roda warna dari yang asli. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Mengembalikan kode hash. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Mengembalikan Hue dari Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Mengembalikan luminositas dari Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Mengembalikan saturasi dari Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Menyandi komponen ARGB Color menjadi int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Mengembalikan nama warna jika cocok dengan warna dalam daftar warna bernama CSS, atau String kosong. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Mengembalikan warna Natural (NCol) yang ditentukan menggunakan huruf warna dengan angka untuk menentukan jarak (dalam persen) dari warna. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Mengembalikan warna Hexadecimal yang ditentukan dengan: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Mengembalikan String yang berisi warna RGBA yang ditentukan oleh: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Mengembalikan warna heksadesimal yang ditentukan dengan: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Mengembalikan String yang berisi warna RGB yang ditentukan oleh: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Mengembalikan String yang terdiri dari nilai komponen RGBA. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Mengkode komponen ARGB Warna menjadi unsigned int. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Membuat salinan Warna dengan komponen alpha yang ditentukan. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Membuat salinan Warna dengan Hue yang ditentukan. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Membuat salinan Warna dengan luminositas yang ditentukan. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Membuat salinan Warna dengan saturasi yang ditentukan. |

### Lihat Juga

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)

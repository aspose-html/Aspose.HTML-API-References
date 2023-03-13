---
title: Class CSSPrimitiveValue
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Css.CSSPrimitiveValue kelas. Antarmuka CSSPrimitiveValue mewakili satu nilai CSS. Antarmuka ini dapat digunakan untuk menentukan nilai properti gaya tertentu yang saat ini disetel dalam blok atau untuk menyetel properti gaya tertentu secara eksplisit di dalam blok. Contoh antarmuka ini dapat diperoleh dari metode getPropertyCSSValue dari antarmuka CSSStyleDeclaration. Objek CSSPrimitiveValue hanya muncul dalam konteks properti CSS.
type: docs
weight: 330
url: /id/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Antarmuka CSSPrimitiveValue mewakili satu nilai CSS. Antarmuka ini dapat digunakan untuk menentukan nilai properti gaya tertentu yang saat ini disetel dalam blok atau untuk menyetel properti gaya tertentu secara eksplisit di dalam blok. Contoh antarmuka ini dapat diperoleh dari metode getPropertyCSSValue dari antarmuka CSSStyleDeclaration. Objek CSSPrimitiveValue hanya muncul dalam konteks properti CSS.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Properti

| Nama | Keterangan |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Representasi string dari nilai saat ini. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Kode yang menentukan jenis nilai. |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype/) { get; } | Jenis nilai seperti yang ditentukan oleh konstanta yang ditentukan di atas. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Menentukan apakah yang ditentukanObject sama dengan instance ini. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Metode ini digunakan untuk mendapatkan nilai Counter. Jika nilai CSS ini tidak mengandung nilai penghitung, DOMException akan dimunculkan. Modifikasi ke properti gaya yang sesuai dapat dilakukan dengan menggunakan antarmuka Penghitung. |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Metode ini digunakan untuk mendapatkan nilai float dalam satuan tertentu. Jika nilai CSS ini tidak berisi nilai float atau tidak dapat diubah menjadi unit yang ditentukan, DOMException akan dimunculkan. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Metode ini digunakan untuk mendapatkan nilai int dalam satuan tertentu. Jika nilai CSS ini tidak mengandung nilai int atau tidak dapat diubah menjadi unit yang ditentukan, DOMException akan dimunculkan. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Metode ini digunakan untuk mendapatkan nilai Rect. Jika nilai CSS ini tidak berisi nilai rect, DOMException akan dimunculkan. Modifikasi ke properti style yang sesuai dapat dicapai dengan menggunakan antarmuka Rect. |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Metode ini digunakan untuk mendapatkan warna RGB. Jika nilai CSS ini tidak mengandung nilai warna RGB, DOMException akan dimunculkan. Modifikasi ke properti gaya yang sesuai dapat dicapai dengan menggunakan antarmuka RGBColor. |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue/)() | Metode ini digunakan untuk mendapatkan nilai string. Jika nilai CSS tidak berisi nilai string, DOMException dimunculkan. |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Sebuah metode untuk mengatur nilai float dengan unit tertentu. Jika properti yang dilampirkan dengan nilai ini tidak dapat menerima unit yang ditentukan atau nilai float, nilainya tidak akan berubah dan DOMException akan dimunculkan. |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Sebuah metode untuk mengatur nilai int dengan unit tertentu. Jika properti yang dilampirkan dengan nilai ini tidak dapat menerima unit yang ditentukan atau nilai int, nilainya tidak akan berubah dan DOMException akan dimunculkan. |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | Metode untuk mengatur nilai string dengan unit yang ditentukan. Jika properti yang dilampirkan ke nilai ini tidak dapat menerima unit yang ditentukan atau nilai string, nilainya tidak akan berubah dan DOMException akan dimunculkan. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr/) | Nilainya adalah fungsi atribut. Nilai dapat diperoleh dengan menggunakan metode getStringValue. |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch/) | Nilainya adalah panjang (ch). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm/) | Nilainya adalah panjang (cm). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter/) | Nilainya adalah fungsi counter atau penghitung. Nilai dapat diperoleh dengan menggunakan metode GetCounterValue. |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg/) | Nilainya adalah sudut (deg). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Nilainya adalah angka dengan dimensi yang tidak diketahui. Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Nilainya adalah titik per sentimeter (dpcm). |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Nilainya adalah titik per inci (dpi). |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Nilainya adalah titik per satuan 'px' (dppx). |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems/) | Nilainya adalah panjang (ems). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs/) | Nilainya adalah panjang (ex). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad/) | Nilainya adalah sudut (grad). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz/) | Nilainya adalah frekuensi (Hz). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident/) | Nilainya adalah pengidentifikasi. Nilai dapat diperoleh dengan menggunakan metode getStringValue. |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in/) | Nilainya adalah panjang (in). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz/) | Nilainya adalah frekuensi (kHz). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm/) | Nilainya adalah panjang (mm). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms/) | Nilainya adalah waktu (ms). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number/) | Nilainya adalah angka sederhana. Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc/) | Nilainya adalah panjang (pc). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Nilainya adalah persentase. Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt/) | Nilainya adalah panjang (pt). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px/) | Nilainya adalah panjang (px). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad/) | Nilainya adalah sudut (rad). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect/) | Nilainya adalah fungsi persegi. Nilai dapat diperoleh dengan menggunakan metode GetRectValue. |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem/) | Nilainya adalah panjang (rem). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Nilainya adalah warna RGB. Nilai dapat diperoleh dengan menggunakan metode GetRGBColorValue. |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s/) | Nilainya adalah waktu. Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string/) | Nilainya adalah STRING. Nilai dapat diperoleh dengan menggunakan metode getStringValue. |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Nilainya bukan nilai CSS2 yang dikenali. Nilai tersebut hanya bisa didapatkan dengan menggunakan atribut cssText. |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri/) | Nilainya adalah URI. Nilai dapat diperoleh dengan menggunakan metode getStringValue. |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh/) | Nilainya adalah persentase tinggi viewport penuh. |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Nilai adalah persentase lebar atau tinggi area pandang, mana saja yang lebih besar. |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Nilai adalah persentase lebar atau tinggi area pandang, mana saja yang lebih kecil. |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw/) | Nilainya adalah persentase dari lebar viewport penuh. |

### Lihat juga

* class [CSSValue](../cssvalue/)
* ruang nama [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* perakitan [Aspose.HTML](../../)



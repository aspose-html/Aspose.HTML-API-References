---
title: "Kelas CSSPrimitiveValue"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.css.CSSPrimitiveValue class. Antarmuka CSSPrimitiveValue diturunkan dari antarmuka CSSValue dan mewakili nilai terhitung saat ini dari sebuah properti CSS."
type: docs

url: /id/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Antarmuka CSSPrimitiveValue diturunkan dari antarmuka CSSValue dan merepresentasikan nilai terhitung saat ini dari sebuah properti CSS.

Catatan: Antarmuka ini merupakan bagian dari upaya untuk membuat CSS Object Model yang bertipe. Upaya ini telah ditinggalkan, dan sebagian besar peramban tidak mengimplementasikannya.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Properti cssText dari antarmuka [`CSSValue`](../cssvalue/) mewakili nilai properti CSS terhitung saat ini. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Sebuah kode yang mendefinisikan tipe nilai. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) Tipe nilai sebagaimana didefinisikan oleh konstanta yang disebutkan di atas. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Menentukan apakah Objek yang disebutkan sama dengan instance ini. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Metode ini digunakan untuk mendapatkan nilai Counter. Jika nilai CSS ini tidak mengandung nilai counter, sebuah DOMException akan dilempar. Modifikasi pada properti gaya yang bersangkutan dapat dilakukan menggunakan antarmuka Counter. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Metode ini digunakan untuk mendapatkan nilai float dalam satuan yang ditentukan. Jika nilai CSS ini tidak mengandung nilai float atau tidak dapat dikonversi ke satuan yang ditentukan, sebuah DOMException akan diangkat. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Metode ini digunakan untuk mendapatkan nilai int dalam satuan yang ditentukan. Jika nilai CSS ini tidak mengandung nilai int atau tidak dapat dikonversi ke satuan yang ditentukan, sebuah DOMException akan diangkat. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Metode ini digunakan untuk mengambil Tipe objek ECMAScript. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Metode ini digunakan untuk mendapatkan nilai Rect. Jika nilai CSS ini tidak mengandung nilai rect, sebuah DOMException akan diangkat. Modifikasi properti gaya yang sesuai dapat dilakukan menggunakan antarmuka Rect. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Metode ini digunakan untuk mendapatkan warna RGB. Jika nilai CSS ini tidak mengandung nilai warna RGB, sebuah DOMException akan diangkat. Modifikasi properti gaya yang sesuai dapat dilakukan menggunakan antarmuka RGBColor. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Metode ini digunakan untuk mendapatkan nilai String. Jika nilai CSS tidak mengandung nilai String, sebuah DOMException akan diangkat. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Metode untuk mengatur nilai float dengan satuan yang ditentukan. Jika properti yang terhubung dengan nilai ini tidak dapat menerima satuan yang ditentukan atau nilai float, nilai akan tetap tidak berubah dan sebuah DOMException akan diangkat. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Metode untuk mengatur nilai int dengan satuan yang ditentukan. Jika properti yang terhubung dengan nilai ini tidak dapat menerima satuan yang ditentukan atau nilai int, nilai akan tetap tidak berubah dan sebuah DOMException akan diangkat. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | Metode untuk mengatur nilai String dengan satuan yang ditentukan. Jika properti yang terhubung dengan nilai ini tidak dapat menerima satuan yang ditentukan atau nilai String, nilai akan tetap tidak berubah dan sebuah DOMException akan diangkat. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | Nilai ini adalah fungsi atribut. Nilai dapat diperoleh dengan menggunakan metode getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | Nilai ini adalah panjang (ch). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | Nilai ini adalah panjang (cm). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | Nilai ini adalah fungsi counter atau counters. Nilai dapat diperoleh dengan menggunakan metode GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | Nilai ini adalah sudut (deg). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Nilai ini adalah angka dengan dimensi yang tidak diketahui. Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Nilai ini adalah titik per sentimeter (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Nilai ini adalah titik per inci (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Nilai ini adalah titik per satuan ‘px’ (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | Nilai ini adalah panjang (ems). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | Nilai ini adalah panjang (exs). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | Nilai ini adalah sudut (grad). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | Nilai ini adalah frekuensi (Hz). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | Nilai ini adalah pengidentifikasi. Nilai dapat diperoleh dengan menggunakan metode getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | Nilai ini adalah panjang (in). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | Nilai ini adalah frekuensi (kHz). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | Nilai ini adalah panjang (mm). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | Nilai adalah waktu (ms). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | Nilai adalah angka sederhana. Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | Nilai adalah panjang (pc). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Nilai adalah persentase. Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | Nilai adalah panjang (pt). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | Nilai adalah panjang (px). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | Nilai adalah sudut (rad). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | Nilai adalah fungsi rect. Nilai dapat diperoleh dengan menggunakan metode GetRectValue. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | Nilai adalah panjang (rem). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Nilai adalah warna RGB. Nilai dapat diperoleh dengan menggunakan metode GetRGBColorValue. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | Nilai adalah waktu (s). Nilai dapat diperoleh dengan menggunakan metode getFloatValue. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | Nilai adalah STRING. Nilai dapat diperoleh dengan menggunakan metode getStringValue. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Nilai bukan nilai CSS2 yang dikenali. Nilai hanya dapat diperoleh dengan menggunakan atribut cssText. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | Nilai adalah URI. Nilai dapat diperoleh dengan menggunakan metode getStringValue. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | Nilai adalah persentase dari tinggi viewport penuh. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Nilai adalah persentase dari lebar atau tinggi viewport, mana yang lebih besar. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Nilai adalah persentase dari lebar atau tinggi viewport, mana yang lebih kecil. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | Nilai adalah persentase dari lebar viewport penuh. |

### Lihat Juga

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

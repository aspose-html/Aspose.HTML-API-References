---
title: "Kelas SVGLength"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.svg.datatypes.SVGLength. Antarmuka SVGLength sesuai dengan tipe data dasar length. Sebuah objek SVGLength dapat ditetapkan sebagai read only yang berarti bahwa upaya untuk memodifikasi objek akan menghasilkan pengecualian yang dilemparkan seperti dijelaskan di bawah"
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

Antarmuka SVGLength sesuai dengan tipe data dasar length. Objek SVGLength dapat ditetapkan sebagai read only, yang berarti upaya untuk memodifikasi objek akan menghasilkan pengecualian yang dilemparkan, seperti dijelaskan di bawah.

```java
public class SVGLength : SVGValueType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) Tipe nilai sebagaimana ditentukan oleh salah satu konstanta SVG_LENGTHTYPE_* yang didefinisikan pada antarmuka ini. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Pertahankan nilai yang tersimpan di bawahnya tetap sama, tetapi reset pengidentifikasi satuan yang tersimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini. Misalnya, jika nilai asli adalah "0.5cm" dan metode dipanggil untuk mengonversi ke milimeter, maka unitType akan diubah menjadi SVG_LENGTHTYPE_MM, valueInSpecifiedUnits akan diubah menjadi nilai numerik 5, dan valueAsString akan diubah menjadi "5mm". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Melepaskan sumber daya yang tidak terkelola dan - secara opsional - terkelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Setel ulang nilai sebagai angka dengan unitType yang terkait, sehingga menggantikan nilai untuk semua atribut pada objek. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Nilai ditentukan menggunakan satuan cm yang didefinisikan dalam CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Nilai ditentukan menggunakan satuan em yang didefinisikan dalam CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Nilai ditentukan menggunakan satuan ex yang didefinisikan dalam CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Nilai ditentukan menggunakan satuan in yang didefinisikan dalam CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Nilai ditentukan menggunakan satuan mm yang didefinisikan dalam CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Tidak ada tipe satuan yang diberikan (yaitu, nilai tanpa satuan ditentukan), yang menunjukkan nilai dalam satuan pengguna. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Nilai ditentukan menggunakan satuan pc yang didefinisikan dalam CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Nilai persentase ditentukan. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Nilai ditentukan menggunakan satuan pt yang didefinisikan dalam CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Nilai ditentukan menggunakan satuan px yang didefinisikan dalam CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Tipe unit bukan salah satu tipe unit yang telah ditentukan. Tidak valid mencoba mendefinisikan nilai baru dengan tipe ini atau mencoba mengubah nilai yang ada ke tipe ini. |

### Lihat Juga

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)

---
title: "Kelas SVGAngle"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.svg.datatypes.SVGAngle. Antarmuka SVGAngle berkorespondensi dengan tipe data dasar angle"
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

Antarmuka SVGAngle sesuai dengan tipe data dasar angle.

```java
public class SVGAngle : SVGValueType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) Tipe nilai sebagaimana ditentukan oleh salah satu konstanta SVG_ANGLETYPE_* yang didefinisikan pada antarmuka ini. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Pertahankan nilai dasar yang sama yang disimpan, tetapi setel ulang pengidentifikasi unit yang disimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Melepaskan sumber daya yang tidak terkelola dan - secara opsional - terkelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Setel ulang nilai sebagai angka dengan unitType yang terkait, sehingga menggantikan nilai untuk semua atribut pada objek. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Tipe unit secara eksplisit diatur ke derajat. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Tipe unit adalah radian. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Tipe unit adalah radian. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Tipe unit bukan salah satu tipe unit yang telah ditentukan. Tidak valid mencoba mendefinisikan nilai baru dengan tipe ini atau mencoba mengubah nilai yang ada ke tipe ini. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Tidak ada tipe unit yang diberikan (misalnya, nilai tanpa unit ditentukan). Untuk sudut, nilai tanpa unit diperlakukan sama seolah-olah derajat ditentukan. |

### Lihat Juga

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)

---
title: "SVGSVGElement.CurrentScale"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti SVGSVGElement. Pada elemen svg paling luar, atribut ini menunjukkan faktor skala saat ini relatif terhadap tampilan awal untuk memperhitungkan pembesaran dan operasi panning pengguna seperti yang dijelaskan pada bagian Magnification and panning. Atribut DOM currentScale dan currentTranslate setara dengan matriks 2x3 matrix a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Jika pembesaran diaktifkan i.e. zoomAndPanmagnify maka efeknya seolah ada transformasi tambahan yang ditempatkan pada tingkat terluar fragmen dokumen SVG i.e. di luar elemen svg paling luar. Ketika diakses pada elemen svg yang bukan elemen svg paling luar, perilaku atribut ini tidak terdefinisi."
type: docs

url: /id/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

Pada elemen svg paling luar, atribut ini menunjukkan faktor skala saat ini relatif terhadap tampilan awal untuk memperhitungkan pembesaran dan operasi panning pengguna, seperti yang dijelaskan pada bagian Magnification and panning. Atribut DOM currentScale dan currentTranslate setara dengan matriks 2x3 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Jika \"magnification\" diaktifkan (misalnya, zoomAndPan=\"magnify\"), maka efeknya seolah ada transformasi tambahan yang ditempatkan pada tingkat terluar fragmen dokumen SVG (yaitu, di luar elemen svg paling luar). Ketika diakses pada elemen ‘svg’ yang bukan elemen svg paling luar, perilaku atribut ini tidak terdefinisi.

```java
public float CurrentScale { get; set; }
```

### Property Value

Skala saat ini.

### Lihat Juga

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

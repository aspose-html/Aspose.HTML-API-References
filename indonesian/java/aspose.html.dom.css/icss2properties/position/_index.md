---
title: "ICSS2Properties.Position"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti ICSS2Properties. Nilai-nilai properti ini memiliki arti berikut"
type: docs

url: /id/java/com.aspose.html.dom.css/icss2properties/position/
---
## ICSS2Properties.Position property

Nilai-nilai properti ini memiliki arti berikut:

static - Kotak adalah kotak normal, ditata menurut [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow). Properti ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left) dan ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) tidak berlaku. relative - Posisi kotak dihitung menurut [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) (ini disebut posisi dalam aliran normal). Kemudian kotak dipindahkan secara [relative](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#relative-positioning) ke posisi normalnya. Ketika sebuah kotak B diposisikan relatif, posisi kotak berikutnya dihitung seolah B tidak dipindahkan. absolute - Posisi kotak (dan mungkin ukurannya) ditentukan dengan properti ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left), ['right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-right), ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top), dan ['bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-bottom). Properti ini menentukan offset relatif terhadap [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block). Kotak yang diposisikan secara absolut diambil keluar dari aliran normal. Ini berarti mereka tidak memengaruhi tata letak saudara berikutnya. Juga, meskipun kotak [absolutely positioned](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#absolutely-positioned) memiliki margin, mereka tidak [collapse](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#collapsing-margins) dengan margin lain. fixed - Posisi kotak dihitung menurut model 'absolute', tetapi tambahan, kotak [fixed](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#fixed-positioning) terhadap referensi tertentu. Dalam kasus [continuous media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#continuous-media-group), kotak dipasang tetap terhadap [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (dan tidak bergerak saat digulir). Dalam kasus [paged media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#paged-media-group), kotak dipasang tetap terhadap halaman, bahkan jika halaman tersebut dilihat melalui [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (misalnya dalam pratinjau cetak). Penulis mungkin ingin menentukan 'fixed' secara tergantung media.

```java
public String Position { get; set; }
```

### Nilai Kembali

properti posisi

### Lihat Juga

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

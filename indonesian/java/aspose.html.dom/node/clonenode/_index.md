---
title: "Node.CloneNode"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Node. Metode cloneNode dari antarmuka Node mengembalikan duplikat dari node yang dipanggil metode ini. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak."
type: docs

url: /id/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak.

Menggandakan sebuah node menyalin semua atributnya dan nilai-nilainya, termasuk listener intrinsik (inline). Ini tidak menyalin listener peristiwa yang ditambahkan menggunakan [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) atau yang ditetapkan ke properti elemen (misalnya, node.onclick = someFunction). Selain itu, untuk elemen [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/), gambar yang dilukis tidak disalin.

```java
public Node CloneNode()
```

### Nilai Kembali

Node [`Node`](../) baru yang digandakan. Node yang digandakan tidak memiliki induk dan bukan bagian dari dokumen, sampai ditambahkan ke node lain yang merupakan bagian dari dokumen, menggunakan [`Node.appendChild()`](../appendchild/) atau metode serupa.

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak.

Menggandakan sebuah node menyalin semua atributnya dan nilai-nilainya, termasuk listener intrinsik (inline). Ini tidak menyalin listener peristiwa yang ditambahkan menggunakan [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) atau yang ditetapkan ke properti elemen (misalnya, node.onclick = someFunction). Selain itu, untuk elemen [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement), gambar yang dilukis tidak disalin.

```java
public Node CloneNode(bool deep)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| deep | Boolean | Jika true, maka node dan seluruh subtree-nya, termasuk teks yang mungkin ada di node anak [`Text`](../../text/), juga disalin. |

### Nilai Kembali

Node [Node](T:com.aspose.html.dom.Node) baru yang digandakan. Node yang digandakan tidak memiliki induk dan bukan bagian dari dokumen, sampai ditambahkan ke node lain yang merupakan bagian dari dokumen, menggunakan [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) atau metode serupa.

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

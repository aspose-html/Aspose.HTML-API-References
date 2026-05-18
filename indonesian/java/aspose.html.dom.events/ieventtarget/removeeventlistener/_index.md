---
title: "IEventTarget.RemoveEventListener"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IEventTarget. Metode ini memungkinkan penghapusan Event Listeners dari target peristiwa. Jika sebuah Event Listener dihapus dari target saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Event Listeners tidak pernah dapat dipanggil setelah dihapus."
type: docs

url: /id/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

Metode ini memungkinkan penghapusan event listeners dari target event. Jika sebuah listener dihapus dari sebuah elemen saat sedang memproses sebuah event, listener tersebut tidak akan dipicu oleh aksi saat ini. Event Listeners tidak pernah dapat dipanggil setelah dihapus.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | Menentukan jenis event type yang akan dihapus. |
| pendengar | IEventListener | Parameter menunjukkan yang akan dihapus. |

### Lihat Juga

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

Metode ini memungkinkan penghapusan event listeners dari target event. Jika sebuah listener dihapus dari sebuah elemen saat sedang memproses sebuah event, listener tersebut tidak akan dipicu oleh aksi saat ini. Event Listeners tidak pernah dapat dipanggil setelah dihapus.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | Menentukan jenis event type yang akan dihapus. |
| pendengar | IEventListener | Parameter menunjukkan yang akan dihapus. |
| useCapture | Boolean | Menentukan apakah EventListener yang dihapus terdaftar sebagai listener penangkap atau tidak. Jika sebuah listener terdaftar dua kali, satu dengan penangkapan dan satu tanpa, masing‑masing harus dihapus secara terpisah. Penghapusan listener penangkap tidak memengaruhi versi non‑penangkap dari listener yang sama, dan sebaliknya. |

### Lihat Juga

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

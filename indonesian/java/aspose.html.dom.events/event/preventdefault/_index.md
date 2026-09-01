---
title: "Event.PreventDefault"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode peristiwa. Jika sebuah peristiwa dapat dibatalkan, metode PreventDefault digunakan untuk menandakan bahwa peristiwa tersebut akan dibatalkan, yang berarti setiap aksi default yang biasanya dilakukan oleh implementasi sebagai hasil dari peristiwa tidak akan terjadi"
type: docs

url: /id/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Jika sebuah peristiwa dapat dibatalkan, metode `PreventDefault` digunakan untuk menandakan bahwa peristiwa tersebut akan dibatalkan, yang berarti setiap aksi default yang biasanya dilakukan oleh implementasi sebagai hasil dari peristiwa tidak akan terjadi.

```java
public void PreventDefault()
```

## Catatan

Jika, selama tahap mana pun dari alur peristiwa, metode `PreventDefault` dipanggil, peristiwa dibatalkan. Setiap aksi default yang terkait dengan peristiwa tidak akan terjadi. Memanggil metode ini untuk peristiwa yang tidak dapat dibatalkan tidak berpengaruh. Setelah `PreventDefault` dipanggil, ia akan tetap berlaku selama sisa propagasi peristiwa. Metode ini dapat digunakan selama tahap mana pun dari alur peristiwa.

### Lihat Juga

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

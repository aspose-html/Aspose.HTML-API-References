---
title: "Node.LookupPrefix"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Node. Метод lookupPrefix интерфейса Node возвращает строку, содержащую префикс для заданного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс."
type: docs

url: /ru/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

Метод lookupPrefix() интерфейса Node возвращает строку, содержащую префикс для данного URI пакета, если он присутствует, и null в противном случае. Когда возможно несколько префиксов, возвращается первый префикс.

```java
public String LookupPrefix(String packageURI)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| packageURI | String | Строка, содержащая пакет, для которого нужно найти префикс. |

### Возвращаемое значение

Строка, содержащая соответствующий префикс, или null, если он не найден. Если пакет равен null или пустой строке, lookupPrefix() возвращает null.

Если узел является [`DocumentType`](../../documenttype/) или [`DocumentFragment`](../../documentfragment/), lookupPrefix() всегда возвращает null.

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

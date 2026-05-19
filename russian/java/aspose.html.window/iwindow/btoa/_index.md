---
title: "IWindow.Btoa"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IWindow. Принимает входные данные в виде Unicode‑строки, содержащей только символы в диапазоне U0000‑U00FF, каждый из которых представляет бинарный байт со значениями 0x00‑0xFF соответственно, и преобразует её в её base64‑представление, которое возвращает."
type: docs

url: /ru/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Принимает входные данные в виде Unicode‑строки, содержащей только символы в диапазоне U+0000‑U+00FF, каждый из которых представляет бинарный байт со значением от 0x00 до 0xFF, и преобразует её в представление base64, которое возвращает.

```java
public String Btoa(String data)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | String | Unicode‑строка, содержащая только символы в диапазоне U+0000‑U+00FF. |

### Возвращаемое значение

Base64‑строка.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Выбрасывает исключение DOMException \"InvalidCharacterError\", если входная строка содержит символы за пределами диапазона. |

### См. также

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

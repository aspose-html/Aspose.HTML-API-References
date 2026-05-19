---
title: "Интерфейс IUrlSearchParams"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.IUrlSearchParams. Предоставляет методы для работы со строкой запроса URL"
type: docs

url: /ru/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

Предоставляет методы для работы со строкой запроса URL.

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## Методы

| Имя | Описание |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | Добавляет новую пару имя‑значение, у которой имя — `name`, а значение — `value`. |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | Удаляет все пары имя‑значение, у которых имя — `name`. |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | Возвращает значение первой пары имя‑значение, у которой имя — `name`. |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | Возвращает все значения, у которых имя — `name`. |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | Проверяет, существует ли в списке пара имя‑значение, у которой имя — `name`. |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | Устанавливает значение первой найденной пары имя‑значение в указанное значение и удаляет остальные. Если пары имя‑значение с указанным именем не найдены, в список будет добавлена новая. |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | Сортирует все пары имя‑значение, если они есть, по их именам. |

### См. также

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

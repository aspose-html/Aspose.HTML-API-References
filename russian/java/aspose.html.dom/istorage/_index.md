---
title: "Интерфейс IStorage"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.IStorage. Этот интерфейс Web Storage API предоставляет доступ к сеансовому или локальному хранилищу конкретного домена. См. спецификацию Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /ru/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Этот интерфейс Web Storage API предоставляет доступ к сессионному или локальному хранилищу конкретного домена. См. спецификацию Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Возвращает количество пар ключ/значение. |

## Методы

| Имя | Описание |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Удаляет все пары ключ/значение, если они есть. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Возвращает текущее значение, связанное с указанным ключом, или null, если указанный ключ не существует. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Возвращает имя n‑го ключа, или null, если n больше или равно количеству пар ключ/значение. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Удаляет пару ключ/значение с указанным ключом, если такая пара существует. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Устанавливает значение пары, идентифицированной ключом key, в value, создавая новую пару ключ/значение, если ранее для key не существовало пары. |

### См. также

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

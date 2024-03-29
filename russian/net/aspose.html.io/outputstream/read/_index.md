---
title: OutputStream.Read
second_title: Справочник по Aspose.HTML для .NET API
description: OutputStream метод. Считывает последовательность байтов из упакованного выходного потока и перемещает позицию в потоке на количество прочитанных байтов.
type: docs
weight: 100
url: /ru/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

Считывает последовательность байтов из упакованного выходного потока и перемещает позицию в потоке на количество прочитанных байтов.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | Byte[] | Массив байтов. Когда этот метод возвращается, буфер содержит указанный массив байтов со значениями между offset и (offset + count - 1), замененными на байтами, считанными из обернутого выходного потока. |
| offset | Int32 | Отсчитываемое от нуля смещение байтов в буфере, с которого начинается сохранение данных read из обернутого выходного потока. |
| count | Int32 | Максимальное количество байтов, которое будет считано из обернутого выходного потока. |

### Возвращаемое значение

Общее количество байтов, прочитанных в буфер. Это значение может быть меньше, чем число запрошенных байтов, если такое количество байтов в настоящее время недоступно, или ноль (0) , если достигнут конец потока.

### Смотрите также

* class [OutputStream](../)
* пространство имен [Aspose.Html.IO](../../outputstream/)
* сборка [Aspose.HTML](../../../)



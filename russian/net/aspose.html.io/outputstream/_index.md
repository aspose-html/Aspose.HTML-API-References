---
title: Class OutputStream
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.IO.OutputStream сорт. Суррогатный поток обертывает реальный выходной поток и контролирует доступ к нему. OutputStream содержит данные URI описывающие расположение выходного потока.
type: docs
weight: 3750
url: /ru/net/aspose.html.io/outputstream/
---
## OutputStream class

Суррогатный поток обертывает реальный выходной поток и контролирует доступ к нему. `OutputStream` содержит данные URI, описывающие расположение выходного потока.

```csharp
public class OutputStream : Stream
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | Инициализирует новый экземпляр`OutputStream` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | Получает значение, указывающее, поддерживает ли обернутый поток вывода чтение. |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | Получает значение, указывающее, поддерживает ли обернутый выходной поток поиск. |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | Получает значение, указывающее, поддерживает ли обернутый выходной поток запись. |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | Получает длину в байтах упакованного выходного потока. |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | Получает или задает позицию в обернутом потоке вывода. |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | Получает URI местоположения потока. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | Закрывает обернутый поток вывода и текущий поток. |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | Очищает все буферы для обернутого выходного потока и вызывает запись всех буферизованных данных на базовое устройство. |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | Считывает последовательность байтов из упакованного выходного потока и перемещает позицию в потоке на количество прочитанных байтов. |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | Устанавливает позицию в обернутом потоке вывода. |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | Устанавливает длину обернутого выходного потока. |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | Записывает последовательность байтов в обернутый поток output и продвигает текущую позицию в этом потоке на количество записанных байтов . |

### Смотрите также

* пространство имен [Aspose.Html.IO](../../aspose.html.io/)
* сборка [Aspose.HTML](../../)



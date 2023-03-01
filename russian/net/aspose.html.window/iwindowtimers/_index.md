---
title: Interface IWindowTimers
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Window.IWindowTimers интерфейс. Позволяет авторам планировать обратные вызовы на основе таймера.
type: docs
weight: 5870
url: /ru/net/aspose.html.window/iwindowtimers/
---
## IWindowTimers interface

Позволяет авторам планировать обратные вызовы на основе таймера.

```csharp
public interface IWindowTimers
```

## Методы

| Имя | Описание |
| --- | --- |
| [ClearInterval](../../aspose.html.window/iwindowtimers/clearinterval/)(int) | Отменяет тайм-аут, установленный с помощью setInterval(), идентифицированный handle |
| [ClearTimeout](../../aspose.html.window/iwindowtimers/cleartimeout/)(int) | Отменяет тайм-аут, установленный с помощью setTimeout(), идентифицированный дескриптором. |
| [SetInterval](../../aspose.html.window/iwindowtimers/setinterval/)(object, int, params object[]) | Планирует тайм-аут для запуска обработчика каждые миллисекунды тайм-аута. Любые аргументы передаются непосредственно обработчику. |
| [SetTimeout](../../aspose.html.window/iwindowtimers/settimeout/)(object, int, params object[]) | Планирует тайм-аут для запуска обработчика после тайм-аута в миллисекундах. Любые аргументы передаются непосредственно обработчику. |

### Смотрите также

* пространство имен [Aspose.Html.Window](../../aspose.html.window/)
* сборка [Aspose.HTML](../../)



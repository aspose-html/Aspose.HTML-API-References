---
title: Interface IWindow
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Window.IWindow интерфейс. Объект окна представляет собой окно содержащее документ DOM.
type: docs
weight: 5850
url: /ru/net/aspose.html.window/iwindow/
---
## IWindow interface

Объект окна представляет собой окно, содержащее документ DOM.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document/) { get; } | Атрибут документа должен возвращать самый новый объект Document объекта Window. |
| [FrameElement](../../aspose.html.window/iwindow/frameelement/) { get; } | Объект frameElement документа. |
| [Location](../../aspose.html.window/iwindow/location/) { get; } | Атрибут местоположения интерфейса Window должен возвращать объект Location для документа этого объекта Window. |
| [Name](../../aspose.html.window/iwindow/name/) { get; set; } | Атрибут name объекта Window должен при получении возвращать текущее имя контекста просмотра, а при настройке устанавливать имя контекста просмотра в новое значение. |
| [Opener](../../aspose.html.window/iwindow/opener/) { get; } | IDL-атрибут открывателя объекта Window при получении должен возвращать объект WindowProxy контекста просмотра, из которого был создан текущий контекст просмотра (его контекст просмотра открывателя), если он есть, если он все еще доступен, и если текущий контекст просмотра не отказался от открывателя; в противном случае он должен возвращать значение null. При настройке, если новое значение равно null, текущий контекст просмотра должен отказаться от открывающего; если новое значение является чем-то другим, тогда пользовательский агент должен вызвать внутренний метод [[DefineOwnProperty]] объекта Window, передав имя свойства «opener» в качестве ключа свойства и дескриптор свойства { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } в качестве дескриптора свойства, где value — это новое значение. |
| [Parent](../../aspose.html.window/iwindow/parent/) { get; } | Родительский IDL-атрибут объекта Window документа в контексте просмотра b должен возвращать объект WindowProxy родительского контекста просмотра, если он есть (т. е. если b является дочерним контекстом просмотра), или объект WindowProxy контекста просмотра контекст b сам, в противном случае (то есть, если это контекст просмотра верхнего уровня или отдельный вложенный контекст просмотра). |
| [Self](../../aspose.html.window/iwindow/self/) { get; } | Возвращает объект WindowProxy контекста просмотра объекта Window. |
| [Top](../../aspose.html.window/iwindow/top/) { get; } | Верхний IDL-атрибут объекта Window документа в контексте просмотра b должен возвращать объект WindowProxy своего контекста просмотра верхнего уровня (который был бы его собственным объектом WindowProxy, если бы он сам был контекстом просмотра верхнего уровня), если у него есть один или собственный объект WindowProxy в противном случае (например, если это был отдельный вложенный контекст просмотра). |
| [Window](../../aspose.html.window/iwindow/window/) { get; } | Возвращает объект WindowProxy контекста просмотра объекта Window. |

## Методы

| Имя | Описание |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert/)(string) | Отображает модальное предупреждение с заданным сообщением и ждет, пока пользователь его закроет |
| [Confirm](../../aspose.html.window/iwindow/confirm/)(string) | Отображает модальное приглашение OK/Cancel с данным сообщением, ожидает, пока пользователь отклонит его, и возвращает true, если пользователь нажимает OK, и false, если пользователь нажимает Cancel. |
| [Prompt](../../aspose.html.window/iwindow/prompt/)(string, string) | Отображает приглашение модального текстового поля с заданным сообщением, ожидает, пока пользователь его закроет, и возвращает значение, введенное пользователем. Если пользователь отменяет приглашение, вместо этого возвращается null. Если присутствует второй аргумент, то данное значение используется по умолчанию. |

### Смотрите также

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* пространство имен [Aspose.Html.Window](../../aspose.html.window/)
* сборка [Aspose.HTML](../../)



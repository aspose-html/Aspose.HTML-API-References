---
title: "Интерфейс IWindow"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.window.IWindow. Объект window представляет окно, содержащее DOM‑документ."
type: docs

url: /ru/java/com.aspose.html.window/iwindow/
---
## IWindow interface

Объект window представляет окно, содержащее DOM‑документ.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) Атрибут document должен возвращать самый новый объект Document окна Window. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) Объект frameElement документа. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Возвращает объект Storage, позволяющий сохранять пары ключ/значение в пользовательском агенте. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Атрибут location интерфейса Window должен возвращать объект Location для документа данного объекта Window. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| IDL‑атрибут opener объекта Window при чтении должен возвращать объект WindowProxy контекста просмотра, из которого был создан текущий контекст просмотра (его контекст‑открыватель), если такой существует, доступен и текущий контекст не отказался от своего открывателя; в противном случае он должен возвращать null. При установке, если новое значение равно null, текущий контекст просмотра должен отказаться от своего открывателя; если новое значение отличается от null, пользовательский агент должен вызвать внутренний метод [[DefineOwnProperty]] объекта Window, передавая имя свойства \"opener\" в качестве ключа свойства и дескриптор свойства { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }, где value — новое значение. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) IDL‑атрибут parent объекта Window документа в контексте просмотра b должен возвращать объект WindowProxy родительского контекста просмотра, если он существует (т.е. если b является дочерним контекстом), либо объект WindowProxy самого контекста b в остальных случаях (т.е. если это контекст верхнего уровня или отсоединённый вложенный контекст). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Возвращает объект WindowProxy контекста просмотра объекта Window. |
| [getTop](../../com.aspose.html.window/iwindow/top/) IDL‑атрибут top объекта Window документа в контексте просмотра b должен возвращать объект WindowProxy его контекста верхнего уровня (который будет его собственным объектом WindowProxy, если он сам является контекстом верхнего уровня), если такой существует, либо его собственный объект WindowProxy в остальных случаях (например, если это отсоединённый вложенный контекст). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Возвращает объект WindowProxy контекста просмотра объекта Window. |

## Методы

| Имя | Описание |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Отображает модальное окно предупреждения с заданным сообщением и ждёт, пока пользователь его закроет. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Принимает входные данные в виде Unicode‑строки, содержащей бинарные данные, закодированные в base64, декодирует их и возвращает строку, состоящую из символов в диапазоне U+0000‑U+00FF, каждый из которых представляет бинарный байт со значением от 0x00 до 0xFF, соответствующий этим бинарным данным. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Принимает входные данные в виде Unicode‑строки, содержащей только символы в диапазоне U+0000‑U+00FF, каждый из которых представляет бинарный байт со значением от 0x00 до 0xFF, и преобразует её в представление base64, которое возвращает. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Отображает модальное диалоговое окно OK/Cancel с заданным сообщением, ждёт, пока пользователь его закроет, и возвращает true, если пользователь нажал OK, и false, если нажал Cancel. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Возвращает новый объект MediaQueryList, который затем можно использовать для определения, соответствует ли документ строке медиа‑запроса, а также для мониторинга документа с целью обнаружения, когда он соответствует (или перестаёт соответствовать) этому медиа‑запросу. См. спецификацию модуля CSSOM View: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Отображает модальное диалоговое окно с текстовым полем и заданным сообщением, ждёт, пока пользователь его закроет, и возвращает введённое пользователем значение. Если пользователь отменил запрос, возвращается null. Если присутствует второй аргумент, указанное значение используется как значение по умолчанию. |

### См. также

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)

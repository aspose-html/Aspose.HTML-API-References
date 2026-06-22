---
title: "IWindow.Opener"
second_title: "Справочник API Aspose.HTML для Java"
description: "IWindow property. Атрибут opener IDL на объекте Window при получении должен возвращать объект WindowProxy контекста просмотра, из которого был создан текущий контекст просмотра (его opener‑контекст), если такой существует, если он всё ещё доступен и если текущий контекст просмотра не отказался от своего opener‑а; в противном случае должен возвращать null. При установке, если новое значение равно null, текущий контекст просмотра должен отказаться от своего opener‑а; если новое значение отличается от null, агент пользователя должен вызвать внутренний метод DefineOwnProperty объекта Window, передавая имя свойства \\\"opener\\\" в качестве ключа свойства и дескриптор свойства Value: value, Writable: true, Enumerable: true, Configurable: true, где value — новое значение."
type: docs

url: /ru/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Атрибут opener IDL на объекте Window, при получении, должен возвращать объект WindowProxy контекста просмотра, из которого был создан текущий контекст просмотра (его opener‑контекст), если такой существует, если он всё ещё доступен и если текущий контекст просмотра не отказался от своего opener‑а; в противном случае он должен возвращать null. При установке, если новое значение равно null, текущий контекст просмотра должен отказаться от своего opener‑а; если новое значение отличается от null, агент пользователя должен вызвать внутренний метод [[DefineOwnProperty]] объекта Window, передавая имя свойства \"opener\" в качестве ключа свойства и дескриптор свойства { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }, где value — новое значение.

```java
public IWindow Opener { get; }
```

### Property Value

Opener.

### См. также

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

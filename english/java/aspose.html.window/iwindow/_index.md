---
title: IWindow Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.window.IWindow interface. The window object represents a window containing a DOM document
type: docs
weight: 6110
url: /java/com.aspose.html.window/iwindow/
---
## IWindow interface

The window object represents a window containing a DOM document.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Properties

| Name | Description |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) The document attribute must return the Window object's newest Document object. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) The frameElement object of a Document. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Returns a Storage object that allows you to save key/value pairs in the user agent. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) The location attribute of the Window interface must return the Location object for that Window object's Document. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) The opener IDL attribute on the Window object, on getting, must return the WindowProxy object of the browsing context from which the current browsing context was created (its opener browsing context), if there is one, if it is still available, and if the current browsing context has not disowned its opener; otherwise, it must return null. On setting, if the new value is null then the current browsing context must disown its opener; if the new value is anything else then the user agent must call the [[DefineOwnProperty]] internal method of the Window object, passing the property name "opener" as the property key, and the Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } as the property descriptor, where value is the new value. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) The parent IDL attribute on the Window object of a Document in a browsing context b must return the WindowProxy object of the parent browsing context, if there is one (i.e. if b is a child browsing context), or the WindowProxy object of the browsing context b itself, otherwise (i.e. if it is a top-level browsing context or a detached nested browsing context). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Returns the Window object's browsing context's WindowProxy object. |
| [getTop](../../com.aspose.html.window/iwindow/top/) The top IDL attribute on the Window object of a Document in a browsing context b must return the WindowProxy object of its top-level browsing context (which would be its own WindowProxy object if it was a top-level browsing context itself), if it has one, or its own WindowProxy object otherwise (e.g. if it was a detached nested browsing context). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Returns the Window object's browsing context's WindowProxy object. |

## Methods

| Name | Description |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Displays a modal alert with the given message, and waits for the user to dismiss it |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Takes the input data, in the form of a Unicode String containing base64-encoded binary data, decodes it, and returns a String consisting of characters in the range U+0000 to U+00FF, each representing a binary byte with values 0x00 to 0xFF respectively, corresponding to that binary data. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Takes the input data, in the form of a Unicode String containing only characters in the range U+0000 to U+00FF, each representing a binary byte with values 0x00 to 0xFF respectively, and converts it to its base64 representation, which it returns. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Displays a modal OK/Cancel prompt with the given message, waits for the user to dismiss it, and returns true if the user clicks OK and false if the user clicks Cancel. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Returns a new MediaQueryList object that can then be used to determine if the document matches the media query String, as well as to monitor the document to detect when it matches (or stops matching) that media query. See CSSOM View Module specification: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Displays a modal text field prompt with the given message, waits for the user to dismiss it, and returns the value that the user entered. If the user cancels the prompt, then returns null instead. If the second argument is present, then the given value is used as a default. |

### See Also

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)

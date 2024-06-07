---
title: IWindow class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 10
url: /aspose.html.window/iwindow/
is_root: false
---

## IWindow class

The window object represents a window containing a DOM document.



The IWindow type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [window](/html/python-net/aspose.html.window/iwindow/window) | Returns the Window object's browsing context's WindowProxy object. |
| [self](/html/python-net/aspose.html.window/iwindow/self) | Returns the Window object's browsing context's WindowProxy object. |
| [document](/html/python-net/aspose.html.window/iwindow/document) | The document attribute must return the Window object's newest Document object. |
| [name](/html/python-net/aspose.html.window/iwindow/name) | The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [location](/html/python-net/aspose.html.window/iwindow/location) | The location attribute of the Window interface must return the Location object for that Window object's Document. |
| [top](/html/python-net/aspose.html.window/iwindow/top) | The top IDL attribute on the Window object of a Document in a browsing context b must return the WindowProxy object of its top-level browsing context (which would be its own WindowProxy object if it was a top-level browsing context itself), if it has one, or its own WindowProxy object otherwise (e.g. if it was a detached nested browsing context). |
| [opener](/html/python-net/aspose.html.window/iwindow/opener) | The opener IDL attribute on the Window object, on getting, must return the WindowProxy object of the browsing context from which the current browsing context was created (its opener browsing context), if there is one, if it is still available, and if the current browsing context has not disowned its opener; otherwise, it must return null. On setting, if the new value is null then the current browsing context must disown its opener; if the new value is anything else then the user agent must call the [[DefineOwnProperty]] internal method of the Window object, passing the property name "opener" as the property key, and the Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } as the property descriptor, where value is the new value. |
| [parent](/html/python-net/aspose.html.window/iwindow/parent) | The parent IDL attribute on the Window object of a Document in a browsing context b must return the WindowProxy object of the parent browsing context, if there is one (i.e. if b is a child browsing context), or the WindowProxy object of the browsing context b itself, otherwise (i.e. if it is a top-level browsing context or a detached nested browsing context). |
| [frame_element](/html/python-net/aspose.html.window/iwindow/frame_element) | The frameElement object of a Document. |
| [local_storage](/html/python-net/aspose.html.window/iwindow/local_storage) | Returns a Storage object that allows you to save key/value pairs in the user agent. |
| [default_view](/html/python-net/aspose.html.window/iwindow/default_view) |  |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html.window/iwindow/add_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the registration of event listeners on the event target. |
| [add_event_listener](/html/python-net/aspose.html.window/iwindow/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the registration of event listeners on the event target. |
| [remove_event_listener](/html/python-net/aspose.html.window/iwindow/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [remove_event_listener](/html/python-net/aspose.html.window/iwindow/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [alert](/html/python-net/aspose.html.window/iwindow/alert/#str) | Displays a modal alert with the given message, and waits for the user to dismiss it |
| [confirm](/html/python-net/aspose.html.window/iwindow/confirm/#str) | Displays a modal OK/Cancel prompt with the given message, waits for the user to dismiss it, and returns true if the user clicks OK and false if the user clicks Cancel. |
| [prompt](/html/python-net/aspose.html.window/iwindow/prompt/#str-str) | Displays a modal text field prompt with the given message, waits for the user to dismiss it, and returns the value that the user entered. If the user cancels the prompt, then returns null instead. If the second argument is present, then the given value is used as a default. |
| [btoa](/html/python-net/aspose.html.window/iwindow/btoa/#str) | Takes the input data, in the form of a Unicode string containing only characters in the range U+0000 to U+00FF,<br/>each representing a binary byte with values 0x00 to 0xFF respectively, and converts it to its base64 representation, which it returns. |
| [atob](/html/python-net/aspose.html.window/iwindow/atob/#str) | Takes the input data, in the form of a Unicode string containing base64-encoded binary data,<br/>decodes it, and returns a string consisting of characters in the range U+0000 to U+00FF,<br/>each representing a binary byte with values 0x00 to 0xFF respectively, corresponding to that binary data. |
| [match_media](/html/python-net/aspose.html.window/iwindow/match_media/#str) | Returns a new MediaQueryList object that can then be used to determine if the document matches the media query string, <br/>as well as to monitor the document to detect when it matches (or stops matching) that media query.<br/>See CSSOM View Module specification: |
| [dispatch_event](/html/python-net/aspose.html.window/iwindow/dispatch_event/#aspose.html.dom.events.Event) | This method allows the dispatch of events into the implementations event model. |
| [set_timeout](/html/python-net/aspose.html.window/iwindow/set_timeout/#any-int-list) |  |
| [clear_timeout](/html/python-net/aspose.html.window/iwindow/clear_timeout/#int) |  |
| [set_interval](/html/python-net/aspose.html.window/iwindow/set_interval/#any-int-list) |  |
| [clear_interval](/html/python-net/aspose.html.window/iwindow/clear_interval/#int) |  |



### See Also
* module [`aspose.html.window`](..)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)

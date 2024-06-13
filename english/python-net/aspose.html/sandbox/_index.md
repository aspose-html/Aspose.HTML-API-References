﻿---
title: Sandbox enumeration
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 840
url: /python-net/aspose.html/sandbox/
is_root: false
---

## Sandbox enumeration

A sandboxing flag set is a set of zero or more of the following flags, which are used to restrict the abilities that potentially untrusted resources.



The Sandbox type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NONE | No flag is set, every sandbox feature is accepted |
| NAVIGATION | This flag prevents content from navigating browsing contexts other than the sandboxed browsing context itself (or browsing contexts further nested inside it), auxiliary browsing contexts (which are protected by the sandboxed auxiliary navigation browsing context flag defined next), and the top-level browsing context (which is protected by the sandboxed top-level navigation browsing context flag defined below). 
| AUXILIARY_NAVIGATION | This flag prevents content from creating new auxiliary browsing contexts, e.g. using the target attribute, or the window.open() method. |
| TOP_LEVEL_NAVIGATION | This flag prevents content from navigating their top-level browsing context and prevents content from closing their top-level browsing context. 
| PLUGINS | This flag prevents content from instantiating plugins, whether using the embed element, the object element, the applet element, or through navigation of a nested browsing context, unless those plugins can be secured. |
| ORIGIN | This flag forces content into a unique origin, thus preventing it from accessing other content from the same origin. |
| FORMS | This flag blocks form submission. |
| POINTER_LOCK | This flag disables the Pointer Lock API. |
| SCRIPTS | This flag blocks script execution. |
| AUTOMATIC_FEATURES | This flag blocks features that trigger automatically, such as automatically playing a video or automatically focusing a form control. |
| FULLSCREEN | This flag prevents content from using the requestFullscreen() method. |
| DOCUMENT_DOMAIN | This flag prevents content from using the document.domain feature to change the effective script origin. |
| IMAGES | This flag disables image loading. |



### See Also
* module [`aspose.html`](..)
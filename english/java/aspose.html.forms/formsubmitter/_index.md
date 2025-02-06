---
title: FormSubmitter Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.forms.FormSubmitter class. This class allows to prepare specified HTMLFormElement collects values from the form element submit them to the remote server and receives a response
type: docs
weight: 2980
url: /java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

This class allows to prepare specified [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), collects values from the form element, submit them to the remote server and receives a response.

```java
public class FormSubmitter : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | Initializes a new instance of the `FormSubmitter` class. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | Initializes a new instance of the `FormSubmitter` class based on [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | Initializes a new instance of the `FormSubmitter` class based on [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) selected by index from [`HTMLDocument`](../../com.aspose.html/htmldocument/). |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | Initializes a new instance of the `FormSubmitter` class based on [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) selected by identifier from [`HTMLDocument`](../../com.aspose.html/htmldocument/). |

## Properties

| Name | Description |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | Submits the form data to the server. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | Submits the form data to the server with specified cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | Submits the form data to the server with specified user credentials. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | Submits the form data to the server with specified timeout. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | Submits the form data to the server with specified user credentials and cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | Submits the form data to the server with specified user credentials and timeout. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | Submits the form data to the server with specified timeout and cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | Submits the form data to the server with specified user credentials. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | Submits the form data to the server with specified user credentials, timeout and cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | Submits the form data to the server with specified user credentials and cookies. |

### See Also

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)

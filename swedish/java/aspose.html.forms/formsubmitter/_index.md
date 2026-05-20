---
title: "FormSubmitter-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.forms.FormSubmitter klass. Denna klass möjliggör att förbereda specificerat HTMLFormElement, samla värden från formulärelementet, skicka dem till fjärrservern och ta emot ett svar."
type: docs

url: /sv/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

Denna klass möjliggör att förbereda specificerat [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), samla värden från formulärelementet, skicka dem till fjärrservern och ta emot ett svar.

```java
public class FormSubmitter : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | Initierar en ny instans av `FormSubmitter`-klassen. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | Initierar en ny instans av `FormSubmitter`-klassen baserad på [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | Initierar en ny instans av `FormSubmitter`-klassen baserad på [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) som valts efter index från [`HTMLDocument`](../../com.aspose.html/htmldocument/). |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | Initierar en ny instans av `FormSubmitter`-klassen baserad på [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) som valts efter identifierare från [`HTMLDocument`](../../com.aspose.html/htmldocument/). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | Skickar formulärdata till servern. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | Skickar formulärdata till servern med angivna cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | Skickar formulärdata till servern med angivna användaruppgifter. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | Skickar formulärdata till servern med angiven tidsgräns. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | Skickar formulärdata till servern med angivna användaruppgifter och cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | Skickar formulärdata till servern med angivna användaruppgifter och tidsgräns. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | Skickar formulärdata till servern med angiven tidsgräns och cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | Skickar formulärdata till servern med angivna användaruppgifter. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | Skickar formulärdata till servern med angivna användaruppgifter, tidsgräns och cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | Skickar formulärdata till servern med angivna användaruppgifter och cookies. |

### Se även

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)

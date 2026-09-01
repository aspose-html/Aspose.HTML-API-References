---
title: "FormSubmitter Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.forms.FormSubmitter Klasse. Diese Klasse ermöglicht das Vorbereiten eines angegebenen HTMLFormElement, sammelt Werte aus dem Formularelement, sendet sie an den entfernten Server und empfängt eine Antwort."
type: docs

url: /de/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

Diese Klasse ermöglicht das Vorbereiten eines angegebenen [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), sammelt Werte aus dem Formularelement, sendet sie an den entfernten Server und empfängt eine Antwort.

```java
public class FormSubmitter : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | Initialisiert eine neue Instanz der `FormSubmitter` Klasse. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | Initialisiert eine neue Instanz der `FormSubmitter` Klasse basierend auf [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | Initialisiert eine neue Instanz der `FormSubmitter` Klasse basierend auf [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), das nach Index aus [`HTMLDocument`](../../com.aspose.html/htmldocument/) ausgewählt wurde. |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | Initialisiert eine neue Instanz der `FormSubmitter` Klasse basierend auf [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), das nach Kennung aus [`HTMLDocument`](../../com.aspose.html/htmldocument/) ausgewählt wurde. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | Gibt nicht verwaltete und - optional - verwaltete Ressourcen frei. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | Sendet die Formulardaten an den Server. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | Sendet die Formulardaten mit angegebenen Cookies an den Server. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | Übermittelt die Formulardaten an den Server mit angegebenen Benutzeranmeldeinformationen. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | Übermittelt die Formulardaten an den Server mit angegebenem Timeout. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | Übermittelt die Formulardaten an den Server mit angegebenen Benutzeranmeldeinformationen und Cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | Übermittelt die Formulardaten an den Server mit angegebenen Benutzeranmeldeinformationen und Timeout. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | Übermittelt die Formulardaten an den Server mit angegebenem Timeout und Cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | Übermittelt die Formulardaten an den Server mit angegebenen Benutzeranmeldeinformationen. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | Übermittelt die Formulardaten an den Server mit angegebenen Benutzeranmeldeinformationen, Timeout und Cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | Übermittelt die Formulardaten an den Server mit angegebenen Benutzeranmeldeinformationen und Cookies. |

### Siehe auch

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)

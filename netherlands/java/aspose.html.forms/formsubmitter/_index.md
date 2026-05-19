---
title: "FormSubmitter Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.forms.FormSubmitter class. Deze klasse maakt het mogelijk om een opgegeven HTMLFormElement voor te bereiden, waarden uit het formulierelement te verzamelen, ze naar de externe server te verzenden en een respons te ontvangen."
type: docs

url: /nl/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

Deze klasse maakt het mogelijk om een opgegeven [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) voor te bereiden, waarden uit het formulierelement te verzamelen, ze naar de externe server te verzenden en een respons te ontvangen.

```java
public class FormSubmitter : IDisposable
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | Initialiseert een nieuw exemplaar van de `FormSubmitter` klasse. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | Initialiseert een nieuw exemplaar van de `FormSubmitter` klasse op basis van [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | Initialiseert een nieuw exemplaar van de `FormSubmitter` klasse op basis van [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) geselecteerd op index uit [`HTMLDocument`](../../com.aspose.html/htmldocument/). |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | Initialiseert een nieuw exemplaar van de `FormSubmitter` klasse op basis van [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) geselecteerd op identifier uit [`HTMLDocument`](../../com.aspose.html/htmldocument/). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | Vrijgeeft onbeheerste en - optioneel - beheerde bronnen. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | Verzendt de formuliergegevens naar de server. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | Verzendt de formuliergegevens naar de server met opgegeven cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | Verzendt de formuliergegevens naar de server met opgegeven gebruikersreferenties. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | Verzendt de formuliergegevens naar de server met opgegeven time-out. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | Verzendt de formuliergegevens naar de server met opgegeven gebruikersreferenties en cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | Verzendt de formuliergegevens naar de server met opgegeven gebruikersreferenties en time-out. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | Verzendt de formuliergegevens naar de server met opgegeven time-out en cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | Verzendt de formuliergegevens naar de server met opgegeven gebruikersreferenties. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | Verzendt de formuliergegevens naar de server met opgegeven gebruikersreferenties, time-out en cookies. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | Verzendt de formuliergegevens naar de server met opgegeven gebruikersreferenties en cookies. |

### Zie ook

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)

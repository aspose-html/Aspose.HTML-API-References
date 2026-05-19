---
title: "FormSubmitter Classe"
second_title: "Riferimento API Aspose.HTML per Java"
description: "com.aspose.html.forms.FormSubmitter classe. Questa classe consente di preparare un HTMLFormElement specificato, raccoglie i valori dall'elemento del modulo, li invia al server remoto e riceve una risposta."
type: docs

url: /it/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

Questa classe consente di preparare un [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), raccoglie i valori dall'elemento del modulo, li invia al server remoto e riceve una risposta.

```java
public class FormSubmitter : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | Inizializza una nuova istanza della classe `FormSubmitter`. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | Inizializza una nuova istanza della classe `FormSubmitter` basata su [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | Inizializza una nuova istanza della classe `FormSubmitter` basata su [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), selezionato per indice da [`HTMLDocument`](../../com.aspose.html/htmldocument/). |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | Inizializza una nuova istanza della classe `FormSubmitter` basata su [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), selezionato per identificatore da [`HTMLDocument`](../../com.aspose.html/htmldocument/). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | Rilascia risorse non gestite e - facoltativamente - gestite. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | Invia i dati del modulo al server. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | Invia i dati del modulo al server con i cookie specificati. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | Invia i dati del modulo al server con le credenziali utente specificate. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | Invia i dati del modulo al server con il timeout specificato. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | Invia i dati del modulo al server con le credenziali utente e i cookie specificati. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | Invia i dati del modulo al server con le credenziali utente e il timeout specificati. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | Invia i dati del modulo al server con il timeout e i cookie specificati. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | Invia i dati del modulo al server con le credenziali utente specificate. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | Invia i dati del modulo al server con le credenziali utente, il timeout e i cookie specificati. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | Invia i dati del modulo al server con le credenziali utente e i cookie specificati. |

### Vedi anche

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)

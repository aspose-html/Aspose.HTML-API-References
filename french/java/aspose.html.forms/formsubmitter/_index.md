---
title: "FormSubmitter Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.forms.FormSubmitter classe. Cette classe permet de préparer le HTMLFormElement spécifié, collecte les valeurs du formulaire, les soumet au serveur distant et reçoit une réponse"
type: docs

url: /fr/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

Cette classe permet de préparer le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) spécifié, collecte les valeurs de l'élément du formulaire, les soumet au serveur distant et reçoit une réponse.

```java
public class FormSubmitter : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | Initialise une nouvelle instance de la classe `FormSubmitter`. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | Initialise une nouvelle instance de la classe `FormSubmitter` basée sur le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | Initialise une nouvelle instance de la classe `FormSubmitter` basée sur le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) sélectionné par index depuis le [`HTMLDocument`](../../com.aspose.html/htmldocument/). |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | Initialise une nouvelle instance de la classe `FormSubmitter` basée sur le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) sélectionné par identifiant depuis le [`HTMLDocument`](../../com.aspose.html/htmldocument/). |

## Propriétés

| Nom | Description |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | Soumet les données du formulaire au serveur. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | Soumet les données du formulaire au serveur avec les cookies spécifiés. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | Envoie les données du formulaire au serveur avec les informations d'identification utilisateur spécifiées. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | Envoie les données du formulaire au serveur avec le délai d'attente spécifié. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | Envoie les données du formulaire au serveur avec les informations d'identification utilisateur et les cookies spécifiés. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | Envoie les données du formulaire au serveur avec les informations d'identification utilisateur et le délai d'attente spécifiés. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | Envoie les données du formulaire au serveur avec le délai d'attente et les cookies spécifiés. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | Envoie les données du formulaire au serveur avec les informations d'identification utilisateur spécifiées. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | Envoie les données du formulaire au serveur avec les informations d'identification utilisateur, le délai d'attente et les cookies spécifiés. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | Envoie les données du formulaire au serveur avec les informations d'identification utilisateur et les cookies spécifiés. |

### Voir aussi

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)

---
title: "Classe FormEditor"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.forms.FormEditor. Questa classe rappresenta l'editor su HTMLFormElement che offre un modo più semplice per gli sviluppatori .net di modificare i moduli HTML"
type: docs

url: /it/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Questa classe rappresenta l'editor su [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) che offre un modo più semplice per gli sviluppatori .net di modificare i moduli HTML.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) Il numero di controlli del modulo nel form. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) L'originale [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) associato all'istanza corrente di `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Restituisce l'elemento per l'indice specificato. (2 indicizzatori) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Crea un nuovo `FormEditor` basato su [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Crea un nuovo `FormEditor` basato su [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) selezionato dalla collezione [`Forms`](../../com.aspose.html/htmldocument/forms/) per indice. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Crea un nuovo `FormEditor` basato su [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) selezionato dal documento per id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Crea un nuovo [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) e lo associa a `FormEditor`. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) è creato nello stato separato dal documento; per collegarlo al documento, selezionare la posizione corretta e utilizzare il metodo [`AppendChild`](../../com.aspose.html.dom/node/appendchild/). |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Crea un nuovo [`HTMLElement`](../../com.aspose.html/htmlelement/) e lo aggiunge alla fine del modulo. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Crea un nuovo [`InputElement`](../inputelement/) e lo aggiunge alla fine del modulo. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Crea un nuovo [`InputElement`](../inputelement/) e lo aggiunge alla fine del modulo. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Rilascia le risorse non gestite e gestite. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Restituisce l'elemento per l'indice specificato. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Restituisce l'elemento per il nome specificato. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Ottiene l'enumeratore. |

### Vedi anche

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)

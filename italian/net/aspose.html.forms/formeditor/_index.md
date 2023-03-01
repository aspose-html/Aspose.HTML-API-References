---
title: Class FormEditor
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Forms.FormEditor classe. Questa classe rappresenta leditor rispetto aHTMLFormElement che crea un modo più semplice per gli sviluppatori .net di modificare i moduli html.
type: docs
weight: 2930
url: /it/net/aspose.html.forms/formeditor/
---
## FormEditor class

Questa classe rappresenta l'editor rispetto a[`HTMLFormElement`](../../aspose.html/htmlformelement/) che crea un modo più semplice per gli sviluppatori .net di modificare i moduli html.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Gestore di moduli lato server. Vedi la definizione dell'attributo action in HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Il numero di controlli del modulo nel modulo. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | L'originale[`HTMLFormElement`](../../aspose.html/htmlformelement/) associato all'istanza corrente di`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Restituisce l'elemento in base all'indice specificato. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | Metodo HTTP [[RFC 2616 dell'IETF](http://www.ietf.org/rfc/rfc2616.txt) utilizzato per inviare il modulo. Vedere la definizione dell'attributo del metodo in HTML 4.01. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Crea un nuovo`FormEditor` basato su[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Crea un nuovo`FormEditor` basato su[`HTMLFormElement`](../../aspose.html/htmlformelement/) selezionato dal[`Forms`](../../aspose.html/htmldocument/forms/) raccolta per indice. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Crea un nuovo`FormEditor` basato su[`HTMLFormElement`](../../aspose.html/htmlformelement/) selezionato dal documento da id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Crea un nuovo[`HTMLFormElement`](../../aspose.html/htmlformelement/) e ad esso associato`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) viene creato nello stato distaccato dal documento; per allegarlo al documento, selezionare la posizione e l'uso corretti[`AppendChild`](../../aspose.html.dom/node/appendchild/) metodo. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Crea un nuovo[`HTMLElement`](../../aspose.html/htmlelement/) e lo aggiunge alla fine del modulo. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Crea un nuovo[`InputElement`](../inputelement/) e lo aggiunge alla fine del modulo. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Crea un nuovo[`InputElement`](../inputelement/) e lo aggiunge alla fine del modulo. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Rilascia risorse non gestite e gestite. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Questo metodo riempie l'intero modulo con i valori specificati. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Restituisce l'elemento in base all'indice specificato. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Restituisce l'elemento in base al nome specificato. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Ottiene l'enumeratore. |

### Guarda anche

* class [FormElement](../formelement/)
* spazio dei nomi [Aspose.Html.Forms](../../aspose.html.forms/)
* assemblea [Aspose.HTML](../../)



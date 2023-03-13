---
title: Interface IStyleSheet
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Css.IStyleSheet interfaccia. Linterfaccia StyleSheet è linterfaccia di base astratta per qualsiasi tipo di foglio di stile. Rappresenta un singolo foglio di stile associato a un documento strutturato.
type: docs
weight: 590
url: /it/net/aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

L'interfaccia StyleSheet è l'interfaccia di base astratta per qualsiasi tipo di foglio di stile. Rappresenta un singolo foglio di stile associato a un documento strutturato.

```csharp
public interface IStyleSheet
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Disabled](../../aspose.html.dom.css/istylesheet/disabled/) { get; set; } | false se il foglio di stile è applicato al documento. vero se non lo è. La modifica di questo attributo può causare una nuova risoluzione dello stile per il documento. Un foglio di stile si applica solo se è presente una definizione media appropriata e l'attributo disabled è falso. Quindi, se il supporto non si applica all'agente utente corrente, l'attributo disabilitato viene ignorato. |
| [Href](../../aspose.html.dom.css/istylesheet/href/) { get; } | Se il foglio di stile è un foglio di stile collegato, il valore del suo attributo è la sua posizione. Per i fogli di stile inline, il valore di questo attributo è null. |
| [Media](../../aspose.html.dom.css/istylesheet/media/) { get; } | Il supporto di destinazione previsto per le informazioni sullo stile. |
| [OwnerNode](../../aspose.html.dom.css/istylesheet/ownernode/) { get; } | Il nodo che associa questo foglio di stile al documento. Per HTML, questo può essere l'elemento LINK o STYLE corrispondente. Per XML, potrebbe essere l'istruzione di elaborazione del collegamento. Per i fogli di stile inclusi da altri fogli di stile, il valore di questo attributo è null. |
| [ParentStyleSheet](../../aspose.html.dom.css/istylesheet/parentstylesheet/) { get; } | Per i linguaggi di stile che supportano il concetto di inclusione del foglio di stile, questo attributo rappresenta il foglio di stile di inclusione, se esiste. Se il foglio di stile è un foglio di stile di primo livello o il linguaggio per fogli di stile non supporta l'inclusione, il valore di questo attributo è null. |
| [Title](../../aspose.html.dom.css/istylesheet/title/) { get; } | Il titolo consultivo. |
| [Type](../../aspose.html.dom.css/istylesheet/type/) { get; } | Specifica il linguaggio del foglio di stile per questo foglio di stile. Il linguaggio del foglio di stile è specificato come tipo di contenuto (ad esempio "text/css"). |

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assemblea [Aspose.HTML](../../)



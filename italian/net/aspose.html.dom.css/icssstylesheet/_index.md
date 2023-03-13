---
title: Interface ICSSStyleSheet
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Css.ICSSStyleSheet interfaccia. Linterfaccia CSSStyleSheet è uninterfaccia concreta usata per rappresentare un foglio di stile CSS cioè un foglio di stile il cui tipo di contenuto è text/css.
type: docs
weight: 510
url: /it/net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

L'interfaccia CSSStyleSheet è un'interfaccia concreta usata per rappresentare un foglio di stile CSS, cioè un foglio di stile il cui tipo di contenuto è "text/css".

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules/) { get; } | L'elenco di tutte le regole CSS contenute nel foglio di stile. Ciò include sia set di regole che at-rules. |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule/) { get; } | Se questo foglio di stile proviene da una regola @import, l'attributo ownerRule conterrà CSSImportRule. In tal caso, l'attributo ownerNode nell'interfaccia StyleSheet sarà nullo. Se il foglio di stile proviene da un elemento o da un'istruzione di elaborazione, l'attributo ownerRule sarà nullo e l'attributo ownerNode conterrà il Node. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Utilizzato per eliminare una regola dal foglio di stile. |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule/)(string, int) | Utilizzato per inserire una nuova regola nel foglio di stile. La nuova regola ora diventa parte della cascata. |

### Guarda anche

* interface [IStyleSheet](../istylesheet/)
* spazio dei nomi [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assemblea [Aspose.HTML](../../)



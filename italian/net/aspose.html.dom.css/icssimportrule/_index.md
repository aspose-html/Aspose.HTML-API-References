---
title: Interface ICSSImportRule
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Css.ICSSImportRule interfaccia. Linterfaccia CSSImportRule rappresenta una regola import allinterno di un foglio di stile CSS. La regola import viene utilizzata per importare regole di stile da altri fogli di stile.
type: docs
weight: 410
url: /it/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

L'interfaccia CSSImportRule rappresenta una regola @import all'interno di un foglio di stile CSS. La regola @import viene utilizzata per importare regole di stile da altri fogli di stile.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | La posizione del foglio di stile da importare. L'attributo non conterrà l'identificatore "url(...)" intorno all'URI. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | Un elenco di tipi di media per i quali è possibile utilizzare questo foglio di stile. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | Il foglio di stile a cui fa riferimento questa regola, se è stato caricato. Il valore di questo attributo è null se il foglio di stile non è stato ancora caricato o se non verrà caricato (ad esempio se il foglio di stile è per un tipo di supporto non supportato dall'agente utente). |

### Guarda anche

* interface [ICSSRule](../icssrule/)
* spazio dei nomi [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assemblea [Aspose.HTML](../../)



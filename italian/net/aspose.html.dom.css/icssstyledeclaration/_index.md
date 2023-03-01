---
title: Interface ICSSStyleDeclaration
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration interfaccia. Linterfaccia CSSStyleDeclaration rappresenta un singolo blocco di dichiarazione CSS. Questa interfaccia può essere utilizzata per determinare le proprietà di stile attualmente impostate in un blocco o per impostare le proprietà di stile in modo esplicito allinterno del blocco.
type: docs
weight: 490
url: /it/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

L'interfaccia CSSStyleDeclaration rappresenta un singolo blocco di dichiarazione CSS. Questa interfaccia può essere utilizzata per determinare le proprietà di stile attualmente impostate in un blocco o per impostare le proprietà di stile in modo esplicito all'interno del blocco.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | La rappresentazione testuale analizzabile del blocco di dichiarazione (escluse le parentesi graffe circostanti). L'impostazione di questo attributo comporterà l'analisi del nuovo valore e il ripristino di tutte le proprietà nel blocco di dichiarazione, inclusa la rimozione o l'aggiunta di proprietà. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Utilizzato per recuperare le proprietà che sono state impostate in modo esplicito in questo blocco di dichiarazione. L'ordine delle proprietà recuperate utilizzando questo metodo non deve essere l'ordine in cui sono state impostate. Questo metodo può essere utilizzato per scorrere tutte le proprietà in questo blocco di dichiarazione. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | Il numero di proprietà che sono state impostate in modo esplicito in questo blocco di dichiarazione. L'intervallo di indici validi va da 0 a length-1 incluso. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | La regola CSS che contiene questa dichiarazione block o null se questa CSSStyleDeclaration non è collegata a una CSSRule. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Utilizzato per recuperare la rappresentazione dell'oggetto del valore di una proprietà CSS se è stata impostata esplicitamente all'interno di questo blocco di dichiarazione. Questo metodo restituisce null se la proprietà è una proprietà abbreviata. È possibile accedere e modificare i valori delle proprietà abbreviate solo come stringhe, utilizzando i metodi getPropertyValue e setProperty. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Utilizzato per recuperare la priorità di una proprietà CSS (ad esempio il qualificatore "importante") se la proprietà è stata impostata esplicitamente in questo blocco di dichiarazione. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Utilizzato per recuperare il valore di una proprietà CSS se è stato impostato esplicitamente all'interno di questo blocco di dichiarazione. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | Utilizzato per rimuovere una proprietà CSS se è stata impostata esplicitamente all'interno di questo blocco di dichiarazione. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Utilizzato per impostare un valore di proprietà con priorità predefinita all'interno di questo blocco di dichiarazione. La priorità predefinita non è "importante", ad esempio String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Utilizzato per impostare un valore di proprietà e una priorità all'interno di questo blocco di dichiarazione. |

### Guarda anche

* interface [ICSS2Properties](../icss2properties/)
* spazio dei nomi [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assemblea [Aspose.HTML](../../)



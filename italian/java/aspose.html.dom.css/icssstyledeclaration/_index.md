---
title: "Interfaccia ICSSStyleDeclaration"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.dom.css.ICSSStyleDeclaration. L'interfaccia CSSStyleDeclaration rappresenta un oggetto che è un blocco di dichiarazione CSS e espone informazioni di stile e vari metodi e proprietà relativi allo stile"
type: docs

url: /it/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

L'interfaccia CSSStyleDeclaration rappresenta un oggetto che è un blocco di dichiarazione CSS e espone informazioni sullo stile e vari metodi e proprietà relativi allo stile.

Un oggetto CSSStyleDeclaration può essere esposto utilizzando tre diverse API:

Via HTMLElement.style, che gestisce gli stili inline di un singolo elemento. Via l'API [`CSSStyleSheet`](../icssstylesheet/). Per esempio, document.styleSheets[0].cssRules[0].style restituisce un oggetto `CSSStyleDeclaration` sulla prima regola CSS nel primo foglio di stile del documento. Via Window.getComputedStyle(), che espone l'oggetto `CSSStyleDeclaration` come interfaccia di sola lettura.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Utilizzato per recuperare le proprietà che sono state impostate esplicitamente in questo blocco di dichiarazione. L'ordine delle proprietà recuperate con questo metodo non deve corrispondere all'ordine in cui sono state impostate. Questo metodo può essere usato per iterare su tutte le proprietà in questo blocco di dichiarazione. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) La proprietà di sola lettura restituisce un numero intero di proprietà che sono state impostate esplicitamente in questo blocco di dichiarazione CSS. L'intervallo di indici validi è da 0 a length-1 inclusi. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) La proprietà di sola lettura CSSStyleDeclaration.parentRule restituisce un CSSRule che è il genitore di questo blocco di stile, ad esempio un [`CSSStyleRule`](../icssstylerule/) che rappresenta lo stile per un selettore CSS. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Utilizzato per recuperare la rappresentazione oggetto del valore di una proprietà CSS se è stata impostata esplicitamente all'interno di questo blocco di dichiarazione. Questo metodo restituisce null se la proprietà è una proprietà abbreviata. I valori delle proprietà abbreviate possono essere accessi e modificati solo come stringhe, usando i metodi getPropertyValue e setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Utilizzato per recuperare la priorità di una proprietà CSS (ad es. il qualificatore "important") se la proprietà è stata impostata esplicitamente in questo blocco di dichiarazione. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | L'interfaccia del metodo CSSStyleDeclaration.getPropertyValue() restituisce una String contenente il valore di una proprietà CSS specificata. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | L'interfaccia del metodo CSSStyleDeclaration.removeProperty() rimuove una proprietà da un oggetto dichiarazione di stile CSS. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | L'interfaccia del metodo CSSStyleDeclaration.setProperty() è usata per impostare il valore di una proprietà con priorità predefinita all'interno di questo blocco di dichiarazione. La priorità predefinita non è "important", cioè String.Empty |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | L'interfaccia del metodo CSSStyleDeclaration.setProperty() è usata per impostare il valore di una proprietà con priorità predefinita all'interno di questo blocco di dichiarazione. La priorità predefinita non è "important", cioè String.Empty |

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### Vedi anche

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

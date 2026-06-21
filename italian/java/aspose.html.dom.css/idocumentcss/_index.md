---
title: "Interfaccia IDocumentCSS"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.dom.css.IDocumentCSS. Questa interfaccia rappresenta un documento con una vista CSS"
type: docs

url: /it/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Questa interfaccia rappresenta un documento con una visualizzazione CSS.

Il metodo getOverrideStyle fornisce un meccanismo attraverso il quale un autore DOM può effettuare una modifica immediata allo stile di un elemento senza modificare i fogli di stile collegati esplicitamente a un documento o lo stile inline degli elementi nei fogli di stile. Questo foglio di stile viene dopo il foglio di stile dell'autore nell'algoritmo di cascata ed è chiamato foglio di stile di override. Il foglio di stile di override ha precedenza sui fogli di stile dell'autore. Una dichiarazione "!important" mantiene comunque la precedenza su una dichiarazione normale. I fogli di stile di override, dell'autore e dell'utente possono tutti contenere dichiarazioni "!important". Le regole "!important" dell'utente hanno precedenza sia sulle regole "!important" di override sia su quelle dell'autore, e le regole "!important" di override hanno precedenza sulle regole "!important" dell'autore.

Ci si aspetta che un'istanza dell'interfaccia DocumentCSS possa essere ottenuta utilizzando metodi di casting specifici del binding su un'istanza dell'interfaccia Document.

Vedi anche la [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Questo metodo è usato per recuperare la dichiarazione di stile di override per un elemento specificato e un pseudo-elemento specificato. |

### Vedi anche

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)

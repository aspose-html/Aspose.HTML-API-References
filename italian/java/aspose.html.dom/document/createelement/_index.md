---
title: "Document.CreateElement"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Document. In un documento HTML il metodo document.createElement crea l'elemento HTML specificato da tagName o un HTMLUnknownElement se tagName non è riconosciuto"
type: docs

url: /it/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

In un documento HTML, il metodo document.createElement() crea l'elemento HTML specificato da tagName, o un [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) se tagName non è riconosciuto.

```java
public Element CreateElement(String localName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | String | Una stringa che specifica il tipo di elemento da creare. Il nodeName dell'elemento creato viene inizializzato con il valore di tagName. Non utilizzare nomi qualificati (come "html:a") con questo metodo. Quando viene chiamato su un documento HTML, createElement() converte tagName in minuscolo prima di creare l'elemento. |

### Valore di ritorno

Il nuovo [`Element`](../../element/).

## Esempi

```java
var element = document.CreateElement(tagName);
```

### Vedi anche

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

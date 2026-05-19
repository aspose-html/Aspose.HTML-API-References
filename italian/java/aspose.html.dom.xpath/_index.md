---
title: "com.aspose.html.dom.xpath"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Il pacchetto contiene metodi per navigare tra gli elementi e gli attributi in un documento XML."
type: docs

url: /it/java/com.aspose.html.dom.xpath/
---
Il pacchetto contiene metodi per navigare tra gli elementi e gli attributi in un documento XML.

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | La valutazione delle espressioni XPath è fornita da [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [IXPathExpression](./ixpathexpression/) | L'interfaccia `XPathExpression` rappresenta un'espressione XPath analizzata e risolta. |
| [IXPathNamespace](./ixpathpackage/) | L'interfaccia XPathNamespace è restituita dalle interfacce XPathResult per rappresentare il tipo di nodo del pacchetto XPath che manca nel DOM. |
| [IXPathNSResolver](./ixpathnsresolver/) | L'interfaccia `XPathNSResolver` consente alle stringhe `prefix` nell'espressione di essere correttamente associate alle stringhe `packageURI`. [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) può costruire un'implementazione di [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) a partire da un nodo, oppure l'interfaccia può essere implementata da qualsiasi applicazione. |
| [IXPathResult](./ixpathresult/) | L'interfaccia `XPathResult` rappresenta il risultato della valutazione di un'espressione XPath 1.0 nel contesto di un nodo specifico. Poiché la valutazione di un'espressione XPath può produrre vari tipi di risultato, questo oggetto consente di scoprire e manipolare il tipo e il valore del risultato. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | Un unsigned short che indica il tipo di risultato. Se viene specificato un `type` specifico, il risultato verrà restituito come il tipo corrispondente, utilizzando le conversioni di tipo XPath dove richiesto e possibile. |

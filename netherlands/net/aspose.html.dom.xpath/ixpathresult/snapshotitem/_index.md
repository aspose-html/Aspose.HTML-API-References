---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML voor .NET API-referentie
description: IXPathResult methode. Retourneert deinhoudsopgave e item in de snapshotverzameling. Alsinhoudsopgavegroter is dan of gelijk is aan het aantal knooppunten in de lijst retourneert deze methodenul . In tegenstelling tot het iteratorresultaat wordt de momentopname niet ongeldig maar komt deze mogelijk niet overeen met het huidige document als het is gemuteerd.
type: docs
weight: 90
url: /nl/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Retourneert de`inhoudsopgave` e item in de snapshot-verzameling. Als`inhoudsopgave`groter is dan of gelijk is aan het aantal knooppunten in de lijst, retourneert deze methode`nul` . In tegenstelling tot het iteratorresultaat, wordt de momentopname niet ongeldig, maar komt deze mogelijk niet overeen met het huidige -document als het is gemuteerd.

```csharp
public Node SnapshotItem(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Indexeer in de momentopnameverzameling. |

### Winstwaarde

Het knooppunt bij de`inhoudsopgave` e positie in de`NodeLijst` , of`nul` als dat geen geldige index is.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: verhoogd als`resultaatType` is niet `UnorderedNodeSnapshot` typ of`OrderedNodeSnapshot` type. |

### Zie ook

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* naamruimte [Aspose.Html.Dom.XPath](../../ixpathresult/)
* montage [Aspose.HTML](../../../)



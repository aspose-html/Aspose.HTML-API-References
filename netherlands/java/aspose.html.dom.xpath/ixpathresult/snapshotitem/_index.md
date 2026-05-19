---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IXPathResult method. Retourneert het indexth item in de snapshotcollectie. Als index groter dan of gelijk aan het aantal knopen in de lijst is, retourneert deze methode null. In tegenstelling tot het iteratorresultaat wordt de snapshot niet ongeldig, maar kan deze mogelijk niet overeenkomen met het huidige document als het is gemuteerd"
type: docs

url: /nl/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Retourneert het `index`‑de item in de snapshot‑collectie. Als `index` groter dan of gelijk is aan het aantal knooppunten in de lijst, geeft deze methode `null` terug. In tegenstelling tot het iterator‑resultaat wordt de snapshot niet ongeldig, maar kan deze mogelijk niet overeenkomen met het huidige document als dat is gewijzigd.

```java
public Node SnapshotItem(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Index in de snapshotcollectie. |

### Retourwaarde

De knoop op de `index`th positie in de `NodeList`, of `null` als dat geen geldige index is.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: opgegooid als `resultType` niet `UnorderedNodeSnapshot` type of `OrderedNodeSnapshot` type is. |

### Zie ook

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)

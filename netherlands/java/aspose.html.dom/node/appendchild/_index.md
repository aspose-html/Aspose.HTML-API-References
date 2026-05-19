---
title: "Node.AppendChild"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Node-methode. De appendChild-methode van de Node-interface voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst appendChild deze van zijn huidige positie naar de nieuwe positie; er is geen vereiste om de knoop eerst uit zijn ouderknoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd."
type: docs

url: /nl/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

De appendChild()‑methode van de Node‑interface voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst appendChild() deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de knoop uit zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd).

Dit betekent dat een knoop niet gelijktijdig op twee plaatsen in het document kan staan. Als de knoop al een ouder heeft, wordt de knoop eerst verwijderd en vervolgens op de nieuwe positie toegevoegd. De [`Node.cloneNode()`](../clonenode/)‑methode kan worden gebruikt om een kopie van de knoop te maken voordat deze onder de nieuwe ouder wordt toegevoegd. Kopieën gemaakt met [`cloneNode`](../clonenode/) worden niet automatisch gesynchroniseerd.

```java
public Node AppendChild(Node node)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| knoop | Node | De knoop die moet worden toegevoegd aan de opgegeven bovenliggende knoop (meestal een element). |

### Retourwaarde

Een Node die het toegevoegde kind (aChild) is, behalve wanneer aChild een [`DocumentFragment`](../../documentfragment/) is, in dat geval wordt het lege [`DocumentFragment`](../../documentfragment/) geretourneerd.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../domexception/) | Wordt gegooid wanneer de beperkingen van de DOM-boom worden geschonden. |

### Zie ook

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

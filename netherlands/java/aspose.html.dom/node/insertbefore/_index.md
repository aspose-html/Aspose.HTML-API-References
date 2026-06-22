---
title: "Node.InsertBefore"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Node-methode. De insertBefore-methode van de Node-interface voegt een knoop in vóór een referentieknoop als kind van een opgegeven ouderknoop."
type: docs

url: /nl/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

De insertBefore()‑methode van de Node‑interface voegt een knoop in vóór een referentieknoop als kind van een opgegeven bovenliggende knoop.

Als de opgegeven knoop al bestaat in het document, verplaatst insertBefore() deze van zijn huidige positie naar de nieuwe positie. (Dat betekent dat hij automatisch wordt verwijderd uit zijn bestaande ouder voordat hij wordt toegevoegd aan de opgegeven nieuwe ouder.)

Dit betekent dat een knoop niet gelijktijdig op twee plaatsen in het document kan staan.

```java
public Node InsertBefore(Node node, Node child)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| knooppunt | Node | De knoop die moet worden ingevoegd. |
| kind | Node | De knoop vóór welke newNode wordt ingevoegd. Als dit null is, wordt newNode aan het einde van de kindknopen van de knoop ingevoegd. |

### Retourwaarde

Retourneert het toegevoegde kind (tenzij newNode een [`DocumentFragment`](../../documentfragment/) is, in dat geval wordt het lege [`DocumentFragment`](../../documentfragment/) geretourneerd).

### Zie ook

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

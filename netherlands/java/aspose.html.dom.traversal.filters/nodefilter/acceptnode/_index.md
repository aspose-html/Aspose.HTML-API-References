---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.HTML voor Java API-referentie"
description: "NodeFilter-methode. Test of een opgegeven knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; hij wordt normaal niet rechtstreeks vanuit gebruikerscode aangeroepen. Je kunt dit echter wel doen als je dezelfde filter wilt gebruiken om je eigen toepassingslogica te sturen."
type: docs

url: /nl/java/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Test of een opgegeven knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; hij wordt normaal niet direct vanuit gebruikerscode aangeroepen. (Hoewel je dit wel kunt doen als je hetzelfde filter wilt gebruiken om je eigen toepassingslogica te sturen.)

```java
public abstract short AcceptNode(Node n)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| n | Node | knoop om te controleren of deze door de filter wordt geaccepteerd of niet. |

### Retourwaarde

een constante om te bepalen of de knoop wordt geaccepteerd, afgewezen of overgeslagen, zoals hierboven gedefinieerd.

### Zie ook

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.dom.traversal.filters](../../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../../)

---
title: "Event.PreventDefault"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Event-methode. Als een gebeurtenis annuleerbaar is, wordt de PreventDefault-methode gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie wordt uitgevoerd als gevolg van de gebeurtenis niet zal plaatsvinden."
type: docs

url: /nl/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Als een gebeurtenis annuleerbaar is, wordt de `PreventDefault`-methode gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie wordt uitgevoerd als gevolg van de gebeurtenis niet zal plaatsvinden.

```java
public void PreventDefault()
```

## Opmerkingen

Als tijdens een willekeurige fase van de gebeurtenisstroom de `PreventDefault`-methode wordt aangeroepen, wordt de gebeurtenis geannuleerd. Elke standaardactie die aan de gebeurtenis is gekoppeld, zal niet plaatsvinden. Het aanroepen van deze methode voor een niet‑annuleerbare gebeurtenis heeft geen effect. Zodra `PreventDefault` is aangeroepen, blijft deze van kracht gedurende de rest van de propagatie van de gebeurtenis. Deze methode kan tijdens elke fase van de gebeurtenisstroom worden gebruikt.

### Zie ook

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

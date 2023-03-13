---
title: Event.PreventDefault
second_title: Aspose.HTML voor .NET API-referentie
description: Event methode. Als een evenement kan worden geannuleerd wordt dePreventDefault methode wordt gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd wat betekent dat elke standaardactie die normaal gesproken door de implementatie wordt ondernomen als gevolg van de gebeurtenis niet zal plaatsvinden.
type: docs
weight: 120
url: /nl/net/aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Als een evenement kan worden geannuleerd, wordt de`PreventDefault` methode wordt gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal gesproken door de implementatie wordt ondernomen als gevolg van de gebeurtenis, niet zal plaatsvinden.

```csharp
public void PreventDefault()
```

### Opmerkingen

Als tijdens een fase van de gebeurtenisstroom de`PreventDefault`methode wordt aangeroepen, wordt de gebeurtenis geannuleerd. Elke standaardactie die aan de gebeurtenis is gekoppeld, zal niet plaatsvinden. Het aanroepen van deze methode voor een niet-annuleerbare gebeurtenis heeft geen effect. Eenmaal`PreventDefault` is genoemd, blijft deze van kracht gedurende de rest van de voortplanting van de gebeurtenis. Deze methode kan tijdens elke fase van de gebeurtenisstroom worden gebruikt.

### Zie ook

* class [Event](../)
* naamruimte [Aspose.Html.Dom.Events](../../event/)
* montage [Aspose.HTML](../../../)



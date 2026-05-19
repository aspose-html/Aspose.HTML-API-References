---
title: "IWindow.Opener"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IWindow eigenschap. Het opener‑IDL‑attribuut op het Window‑object moet bij het opvragen het WindowProxy‑object retourneren van de browse‑context waaruit de huidige browse‑context is gecreëerd (de opener‑browse‑context) als die bestaat, nog beschikbaar is en de huidige browse‑context haar opener niet heeft afgewezen; anders moet het null retourneren. Bij het instellen, als de nieuwe waarde null is, moet de huidige browse‑context haar opener afwijzen; als de nieuwe waarde iets anders is, moet de user agent de interne methode DefineOwnProperty van het Window‑object aanroepen, waarbij de eigenschapsnaam \"opener\" als sleutel wordt doorgegeven en de Property Descriptor { Value: value, Writable: true, Enumerable: true, Configurable: true } als eigenschapsdescriptor, waarbij value de nieuwe waarde is."
type: docs

url: /nl/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Het opener‑IDL‑attribuut op het Window‑object, bij het opvragen, moet het WindowProxy‑object retourneren van de browse‑context waaruit de huidige browse‑context is gecreëerd (de opener‑browse‑context), als die bestaat, nog beschikbaar is en de huidige browse‑context haar opener niet heeft afgewezen; anders moet het null retourneren. Bij het instellen, als de nieuwe waarde null is, moet de huidige browse‑context haar opener afwijzen; als de nieuwe waarde iets anders is, moet de user agent de interne methode [[DefineOwnProperty]] van het Window‑object aanroepen, waarbij de eigenschapsnaam "opener" als sleutel wordt doorgegeven, en de Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als eigenschapsdescriptor, waarbij value de nieuwe waarde is.

```java
public IWindow Opener { get; }
```

### Property Value

De opener.

### Zie ook

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

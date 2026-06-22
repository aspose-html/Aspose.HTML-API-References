---
title: "IWindow.Opener"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IWindow property. Het opener‑IDL‑attribuut op het Window‑object moet bij het opvragen het WindowProxy‑object van de browsing‑context retourneren waaruit de huidige browsing‑context is gecreëerd (de opener‑browsing‑context), als die bestaat, als deze nog beschikbaar is en als de huidige browsing‑context zijn opener niet heeft afgewezen; anders moet het null retourneren. Bij het instellen, als de nieuwe waarde null is, moet de huidige browsing‑context zijn opener afwijzen; als de nieuwe waarde iets anders is, moet de user agent de interne methode [[DefineOwnProperty]] van het Window‑object aanroepen, waarbij de eigenschapsnaam \\\"opener\\\" als sleutel wordt doorgegeven en de Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als descriptor, waarbij value de nieuwe waarde is."
type: docs

url: /nl/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Het opener‑IDL‑attribuut op het Window‑object moet bij het opvragen het WindowProxy‑object van de browsing‑context retourneren waaruit de huidige browsing‑context is gecreëerd (de opener‑browsing‑context), als die bestaat, als deze nog beschikbaar is en als de huidige browsing‑context zijn opener niet heeft afgewezen; anders moet het null retourneren. Bij het instellen, als de nieuwe waarde null is, moet de huidige browsing‑context zijn opener afwijzen; als de nieuwe waarde iets anders is, moet de user agent de interne methode [[DefineOwnProperty]] van het Window‑object aanroepen, waarbij de eigenschapsnaam \"opener\" als sleutel wordt doorgegeven en de Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als descriptor, waarbij value de nieuwe waarde is.

```java
public IWindow Opener { get; }
```

### Property Value

De opener.

### Zie ook

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

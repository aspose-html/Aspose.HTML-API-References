---
title: IWindow.Opener
second_title: Aspose.HTML voor .NET API-referentie
description: IWindow eigendom. Het opener IDLattribuut op het Windowobject moet bij het ophalen het WindowProxyobject retourneren van de browsecontext van waaruit de huidige browsecontext is gemaakt de opener browsingcontext als er een is als deze nog beschikbaar is en als de huidige browsercontext heeft zijn opener niet verloochend anders moet het null retourneren. Als bij het instellen de nieuwe waarde null is moet de huidige browsercontext de opener verloochenen als de nieuwe waarde iets anders is moet de useragent de DefineOwnProperty interne methode van het Windowobject aanroepen waarbij de eigenschapsnaam opener wordt doorgegeven als de eigenschapssleutel en de eigenschapsbeschrijving  Value value  Writable true Enumerable true Configurable true  als eigenschapsdescriptor waarbij waarde de nieuwe waarde is.
type: docs
weight: 50
url: /nl/net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Het opener IDL-attribuut op het Window-object moet bij het ophalen het WindowProxy-object retourneren van de browsecontext van waaruit de huidige browsecontext is gemaakt (de opener browsingcontext), als er een is, als deze nog beschikbaar is en als de huidige browsercontext heeft zijn opener niet verloochend; anders moet het null retourneren. Als bij het instellen de nieuwe waarde null is, moet de huidige browsercontext de opener verloochenen; als de nieuwe waarde iets anders is, moet de user-agent de [[DefineOwnProperty]] interne methode van het Window-object aanroepen, waarbij de eigenschapsnaam "opener" wordt doorgegeven als de eigenschapssleutel, en de eigenschapsbeschrijving { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als eigenschapsdescriptor, waarbij waarde de nieuwe waarde is.

```csharp
public IWindow Opener { get; }
```

### Eigendoms-waarde

De opener.

### Zie ook

* interface [IWindow](../)
* naamruimte [Aspose.Html.Window](../../iwindow/)
* montage [Aspose.HTML](../../../)



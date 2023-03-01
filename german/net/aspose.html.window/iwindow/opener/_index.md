---
title: IWindow.Opener
second_title: Aspose.HTML für .NET-API-Referenz
description: IWindow eigendom. Das OpenerIDLAttribut des WindowObjekts muss beim Abrufen das WindowProxyObjekt des BrowsingKontexts zurückgeben aus dem der aktuelle BrowsingKontext erstellt wurde sein OpenerBrowsingKontext falls es einen gibt ob er noch verfügbar ist und falls der aktuelle BrowsingKontext hat seinen Öffner nicht verleugnet andernfalls muss es null zurückgeben. Wenn der neue Wert bei der Einstellung null ist muss der aktuelle BrowsingKontext seinen Opener ablehnen Wenn der neue Wert etwas anderes ist muss der Benutzeragent die interne Methode DefineOwnProperty des WindowObjekts aufrufen und den Eigenschaftsnamen Öffner als Eigenschaftsschlüssel und den Eigenschaftsdeskriptor Wert value übergeben  Writable true Enumerable true Configurable true  als Eigenschaftsdeskriptor wobei value der neue Wert ist.
type: docs
weight: 50
url: /de/net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Das Opener-IDL-Attribut des Window-Objekts muss beim Abrufen das WindowProxy-Objekt des Browsing-Kontexts zurückgeben, aus dem der aktuelle Browsing-Kontext erstellt wurde (sein Opener-Browsing-Kontext), falls es einen gibt, ob er noch verfügbar ist und falls der aktuelle Browsing-Kontext hat seinen Öffner nicht verleugnet; andernfalls muss es null zurückgeben. Wenn der neue Wert bei der Einstellung null ist, muss der aktuelle Browsing-Kontext seinen Opener ablehnen; Wenn der neue Wert etwas anderes ist, muss der Benutzeragent die interne Methode [[DefineOwnProperty]] des Window-Objekts aufrufen und den Eigenschaftsnamen "Öffner" als Eigenschaftsschlüssel und den Eigenschaftsdeskriptor {[[Wert]]: value übergeben , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als Eigenschaftsdeskriptor, wobei value der neue Wert ist.

```csharp
public IWindow Opener { get; }
```

### Eigentumswert

Der Öffner.

### Siehe auch

* interface [IWindow](../)
* namensraum [Aspose.Html.Window](../../iwindow/)
* Montage [Aspose.HTML](../../../)



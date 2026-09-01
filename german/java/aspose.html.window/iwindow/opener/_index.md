---
title: "IWindow.Opener"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IWindow property. Das opener IDL‑Attribut im Window‑Objekt muss beim Lesen das WindowProxy‑Objekt des Browsing‑Kontexts zurückgeben, aus dem der aktuelle Browsing‑Kontext erstellt wurde (sein opener‑Browsing‑Kontext), falls ein solcher existiert, noch verfügbar ist und der aktuelle Browsing‑Kontext seinen opener nicht abgegeben hat; andernfalls muss null zurückgegeben werden. Beim Schreiben muss, wenn der neue Wert null ist, der aktuelle Browsing‑Kontext seinen opener abgeben; ist der neue Wert ein anderer Wert, muss der User‑Agent die interne Methode DefineOwnProperty des Window‑Objekts aufrufen und dabei den Eigenschaftsnamen \"opener\" als Schlüssel sowie den Property Descriptor { Value: value, Writable: true, Enumerable: true, Configurable: true } übergeben, wobei value der neue Wert ist."
type: docs

url: /de/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Das opener IDL‑Attribut im Window‑Objekt muss beim Lesen das WindowProxy‑Objekt des Browsing‑Kontexts zurückgeben, aus dem der aktuelle Browsing‑Kontext erstellt wurde (sein opener‑Browsing‑Kontext), falls ein solcher existiert, noch verfügbar ist und der aktuelle Browsing‑Kontext seinen opener nicht abgegeben hat; andernfalls muss null zurückgegeben werden. Beim Schreiben muss, wenn der neue Wert null ist, der aktuelle Browsing‑Kontext seinen opener abgeben; ist der neue Wert ein anderer Wert, muss der User‑Agent die interne Methode [[DefineOwnProperty]] des Window‑Objekts aufrufen, den Eigenschaftsnamen "opener" als Schlüssel übergeben und den Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als Eigenschafts‑Deskriptor verwenden, wobei value der neue Wert ist.

```java
public IWindow Opener { get; }
```

### Property Value

Der opener.

### Siehe auch

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

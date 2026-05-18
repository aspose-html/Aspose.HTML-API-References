---
title: "Node.Normalize"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Node‑Methode. Fügt alle Text‑Knoten in die volle Tiefe des Unterbaums unterhalb dieses Node ein, einschließlich Attributknoten, in eine Normalform, in der nur die Struktur (z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA‑Abschnitte und Entity‑Referenzen) Text‑Knoten trennt, d. h. es gibt weder benachbarte noch leere Text‑Knoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM‑Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen wie XPointer‑Nachschlagen, die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Ist der Parameter „normalize-characters“ des DOMConfiguration‑Objekts, das an das Node.ownerDocument angehängt ist, wahr, normalisiert diese Methode zudem vollständig die Zeichen der Text‑Knoten."
type: docs

url: /de/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

Fügt alle [`Text`](../../text/)‑Knoten in die volle Tiefe des Unterbaums unterhalb dieses Node ein, einschließlich Attributknoten, in eine „normale“ Form, in der nur die Struktur (z. B. [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), und [`entity references`](../../entityreference/)) [`Text`](../../text/)‑Knoten trennt, d. h. es gibt weder benachbarte noch leere Text‑Knoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM‑Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer‑[XPointer]‑Nachschlagen) verwendet werden, die von einer bestimmten Dokumentbaumstruktur abhängen. Ist der Parameter „normalize-characters“ des [`DOMConfiguration`](../../../com.aspose.html/configuration/)-Objekts, das an das [`Node.ownerDocument`](../ownerdocument/) angehängt ist, wahr, normalisiert diese Methode zudem vollständig die Zeichen der Text‑Knoten.

```java
public void Normalize()
```

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

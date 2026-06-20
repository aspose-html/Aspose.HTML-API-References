---
title: "ICSS2Properties.Position"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties‑Eigenschaft. Die Werte dieser Eigenschaft haben die folgende Bedeutung"
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/position/
---
## ICSS2Properties.Position property

Die Werte dieser Eigenschaft haben die folgende Bedeutung:

static – Die Box ist eine normale Box, die gemäß dem [normalen Fluss](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) angeordnet ist. Die ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left)‑ und ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top)‑Eigenschaften werden nicht angewendet. relative – Die Position der Box wird gemäß dem [normalen Fluss](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) berechnet (dies wird als Position im normalen Fluss bezeichnet). Anschließend wird die Box [relativ](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#relative-positioning) versetzt. Wenn eine Box B relativ positioniert ist, wird die Position der nachfolgenden Box so berechnet, als wäre B nicht versetzt worden. absolute – Die Position (und ggf. Größe) der Box wird mit den ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left), ['right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-right), ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) und ['bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-bottom)‑Eigenschaften angegeben. Diese Eigenschaften geben Versätze relativ zum [umgebenden Block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) der Box an. Absolut positionierte Boxen werden aus dem normalen Fluss genommen. Das bedeutet, dass sie keinen Einfluss auf das Layout nachfolgender Geschwister haben. Außerdem haben, obwohl [absolut positionierte](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#absolutely-positioned) Boxen Ränder, diese nicht die Möglichkeit, mit anderen Rändern zu [kollabieren](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#collapsing-margins). fixed – Die Position der Box wird gemäß dem 'absoluten' Modell berechnet, zusätzlich wird die Box [fixiert](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#fixed-positioning) relativ zu einer Referenz. Im Fall von [kontinuierlichen Medien](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#continuous-media-group) ist die Box relativ zum [Ansichtsfenster](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) fixiert (und bewegt sich beim Scrollen nicht). Im Fall von [seitigen Medien](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#paged-media-group) ist die Box relativ zur Seite fixiert, selbst wenn diese Seite durch ein [Ansichtsfenster](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) betrachtet wird (z. B. bei einer Druckvorschau). Autoren können 'fixed' medienabhängig angeben.

```java
public String Position { get; set; }
```

### Rückgabewert

position-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

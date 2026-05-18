---
title: "ICSS2Properties.Position"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties‑Eigenschaft. Die Werte dieser Eigenschaft haben die folgende Bedeutung"
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/position/
---
## ICSS2Properties.Position property

Die Werte dieser Eigenschaft haben die folgende Bedeutung:

static - Die Box ist eine normale Box, die gemäß dem [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) angeordnet ist. Die ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left) und ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) Eigenschaften gelten nicht.relative - Die Position der Box wird gemäß dem [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) berechnet (dies wird als Position im normalen Fluss bezeichnet). Dann wird die Box relativ zu ihrer normalen Position [relative](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#relative-positioning) versetzt. Wenn eine Box B relativ positioniert ist, wird die Position der folgenden Box berechnet, als wäre B nicht versetzt.absolute - Die Position der Box (und ggf. ihre Größe) wird mit den ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left), ['right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-right), ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) und ['bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-bottom) Eigenschaften angegeben. Diese Eigenschaften geben Versätze relativ zum [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) der Box an. Absolut positionierte Boxen werden aus dem normalen Fluss genommen. Das bedeutet, sie haben keinen Einfluss auf das Layout späterer Geschwister. Außerdem haben, obwohl [absolutely positioned](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#absolutely-positioned) Boxen Ränder, sie kollidieren nicht mit anderen Rändern.fixed - Die Position der Box wird nach dem 'absolute'-Modell berechnet, zusätzlich wird die Box [fixed](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#fixed-positioning) in Bezug auf ein Referenzobjekt fixiert. Im Fall von [continuous media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#continuous-media-group) ist die Box fixiert in Bezug auf das [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (und bewegt sich beim Scrollen nicht). Im Fall von [paged media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#paged-media-group) ist die Box fixiert in Bezug auf die Seite, selbst wenn diese Seite durch ein [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) gesehen wird (z. B. in der Druckvorschau). Autoren möchten möglicherweise 'fixed' medienabhängig angeben.

```java
public String Position { get; set; }
```

### Rückgabewert

position-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

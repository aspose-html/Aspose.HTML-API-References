---
title: "ICSS2Properties.Clear"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties egenskap. Denna egenskap anger vilka sidor av ett elements lådor som inte får ligga intill en tidigare flytande låda. Det kan vara så att elementet självt har flytande underordnade; clear-egenskapen har ingen effekt på dem."
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Denna egenskap anger vilka sidor av ett elements låda(or) som inte får ligga intill en tidigare flytande låda. (Det kan vara så att elementet självt har flytande underordnade; 'clear'-egenskapen har ingen effekt på dem.)

Denna egenskap får endast anges för blocknivåelement (inklusive flytande). För kompakta och run-in-lådor gäller denna egenskap för den sista blocklådan som den kompakta eller run-in-lådan tillhör.

Värden har följande betydelser när de tillämpas på icke-flytande blocklådor:

left - Den övre marginalen för den genererade lådan ökas tillräckligt så att den övre kantlinjen ligger under den nedre yttre kanten av alla vänsterflytande lådor som skapats av element tidigare i källdokumentet. right - Den övre marginalen för den genererade lådan ökas tillräckligt så att den övre kantlinjen ligger under den nedre yttre kanten av alla högerflytande lådor som skapats av element tidigare i källdokumentet. both - Den genererade lådan flyttas under alla flytande lådor från tidigare element i källdokumentet. none - Ingen begränsning på lådans position i förhållande till flytningar.

```java
public String Clear { get; set; }
```

### Returvärde

clear-egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

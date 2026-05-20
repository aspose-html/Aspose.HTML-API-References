---
title: "HTMLInputElement.Checked"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLInputElement-egenskap. När elementets type‑attribut har värdet radio eller checkbox representerar detta det aktuella tillståndet för formulärkontrollen i en interaktiv användaragent. Ändringar av detta attribut ändrar kontrollens tillstånd men ändrar inte värdet på HTML‑checked‑attributet för INPUT‑elementet. Under hanteringen av ett klick‑event på ett input‑element med ett type‑attribut som har värdet radio eller checkbox kan vissa implementationer ändra värdet på denna egenskap innan händelsen dispatchas i dokumentet. Om standardåtgärden för händelsen avbryts kan egenskapens värde återställas till sitt ursprungliga värde. Detta innebär att värdet på denna egenskap under hantering av klick‑händelser är implementationsberoende"
type: docs

url: /sv/java/com.aspose.html/htmlinputelement/checked/
---
## HTMLInputElement.Checked property

När `type`-attributet för elementet har värdet "radio" eller "checkbox" representerar detta det aktuella tillståndet för formulärkontrollen i en interaktiv användaragent. Ändringar av detta attribut ändrar kontrollens tillstånd, men ändrar inte värdet på HTML‑checked‑attributet för INPUT‑elementet. Under hanteringen av ett klick‑event på ett input‑element med ett type‑attribut som har värdet "radio" eller "checkbox" kan vissa implementationer ändra värdet på denna egenskap innan händelsen dispatchas i dokumentet. Om standardåtgärden för händelsen avbryts kan egenskapens värde återställas till sitt ursprungliga värde. Detta innebär att värdet på denna egenskap under hantering av klick‑händelser är implementationsberoende.

```java
public bool Checked { get; set; }
```

### Se även

* class [HTMLInputElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

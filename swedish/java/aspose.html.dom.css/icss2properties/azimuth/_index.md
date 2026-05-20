---
title: "ICSS2Properties.Azimuth"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties egenskap. Rymdljud är en viktig stilistisk egenskap för auditiv presentation. Det ger ett naturligt sätt att särskilja flera röster, eftersom människor i verkligheten sällan alla står på samma plats i ett rum."
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

Rymdljud är en viktig stilistisk egenskap för auditiv presentation. Det ger ett naturligt sätt att särskilja flera röster, som i verkligheten (människor sällan alla står på samma plats i ett rum).

```java
public String Azimuth { get; set; }
```

### Returvärde

Azimut-egenskapen

### Property Value

Värdena har följande betydelser:

vinkel - Positionen beskrivs i termer av en vinkel inom intervallet '-360deg' till '360deg'. Värdet '0deg' betyder rakt fram i mitten av ljudscenen. '90deg' är till höger, '180deg' bakom, och '270deg' (eller, likvärdigt och mer praktiskt, '-90deg') till vänster.

vänster-sida - Samma som '270deg'. Med 'behind', '270deg'.

långt-vänster - Samma som '300deg'. Med 'behind', '240deg'.

vänster - Samma som '320deg'. Med 'behind', '220deg'.

center-vänster - Samma som '340deg'. Med 'behind', '200deg'.

center - Samma som '0deg'. Med 'behind', '180deg'.

center-höger - Samma som '20deg'. Med 'behind', '160deg'.

höger - Samma som '40deg'. Med 'behind', '140deg'.

långt-höger - Samma som '60deg'. Med 'behind', '120deg'.

höger-sida - Samma som '90deg'. Med 'behind', '90deg'.

leftwards - Flyttar ljudet åt vänster, relativt den aktuella vinkeln. Mer exakt subtraheras 20 grader. Aritmetiken utförs modulo 360 grader. Observera att 'leftwards' mer korrekt beskrivs som \"vriden moturs\", eftersom den alltid subtraherar 20 grader, även om den ärvda azimuten redan är bakom lyssnaren (i så fall verkar ljudet faktiskt röra sig åt höger).

rightwards - Flyttar ljudet åt höger, relativt den aktuella vinkeln. Mer exakt adderas 20 grader. Se 'leftwards' för aritmetik.

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

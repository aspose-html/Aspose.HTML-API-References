---
title: "ICSS2Properties.Volume"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties egenskap. Volume avser medianvolymen för vågformen. Med andra ord kan en starkt inflekterad röst vid en volym på 50 toppa långt över detta. De övergripande värdena är sannolikt justerbara av användaren för komfort, till exempel med en fysisk volymkontroll som skulle öka både 0- och 100-värdena proportionellt. Vad denna egenskap gör är att justera det dynamiska omfånget."
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/volume/
---
## ICSS2Properties.Volume property

Volume avser medianvolymen för vågformen. Med andra ord kan en starkt inflekterad röst vid en volym på 50 toppa långt över detta. De övergripande värdena är sannolikt justerbara av användaren för komfort, till exempel med en fysisk volymkontroll (som skulle öka både 0- och 100-värdena proportionellt); vad denna egenskap gör är att justera det dynamiska omfånget.

Värdena har följande betydelser:

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - Vilket som helst tal mellan '0' och '100'. '0' representerar den lägsta hörbara volymnivån och 100 motsvarar den högsta bekväma nivån. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Procentvärden beräknas relativt det ärvda värdet och klipps sedan till intervallet '0' till '100'. silent - Ingen ljud över huvudtaget. Värdet '0' betyder inte samma som 'silent'. x-soft - Samma som '0'. soft - Samma som '25'. medium - Samma som '50'. loud - Samma som '75'. x-loud - Samma som '100'.

```java
public String Volume { get; set; }
```

### Returvärde

volume egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

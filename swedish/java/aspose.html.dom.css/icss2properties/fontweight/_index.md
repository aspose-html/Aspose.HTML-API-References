---
title: "ICSS2Properties.FontWeight"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties egenskap. Egenskapen font-weight specificerar typsnittets vikt. Värden har följande betydelser"
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/fontweight/
---
## ICSS2Properties.FontWeight property

Egenskapen 'font-weight' specificerar typsnittets vikt. Värden har följande betydelser:

100 till 900 - Dessa värden bildar en ordnad sekvens, där varje nummer indikerar en vikt som är minst lika mörk som föregående. normal - Samma som '400'. bold - Samma som '700'. bolder - Anger nästa vikt som tilldelas ett typsnitt som är mörkare än det ärvt. Om det inte finns någon sådan vikt resulterar det helt enkelt i nästa mörkare numeriska värde (och typsnittet förblir oförändrat), såvida inte det ärvda värdet var '900', i så fall blir den resulterande vikten också '900'. lighter - Anger nästa vikt som tilldelas ett typsnitt som är ljusare än det ärvt. Om det inte finns någon sådan vikt resulterar det helt enkelt i nästa ljusare numeriska värde (och typsnittet förblir oförändrat), såvida inte det ärvda värdet var '100', i så fall blir den resulterande vikten också '100'.

```java
public String FontWeight { get; set; }
```

### Returvärde

font-weight-egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

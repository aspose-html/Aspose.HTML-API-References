---
title: "ICSS2Properties.Speak"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSS2Properties-egenskap. Denna egenskap anger huruvida text kommer att renderas auditivt och i så fall på vilket sätt, något som liknar display-egenskapen. De möjliga värdena är"
type: docs

url: /sv/java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

Denna egenskap anger huruvida text kommer att renderas auditivt och i så fall på vilket sätt (något som liknar ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) egenskapen). De möjliga värdena är:

none - Undertrycker auditiv rendering så att elementet inte kräver någon tid för att renderas. Observera dock att underordnade element kan åsidosätta detta värde och kommer att läsas upp. (För att säkert undertrycka rendering av ett element och dess underordnade, använd ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) egenskapen).normal - Använder språkberoende uttalsregler för att rendera ett element och dess barn.spell-out - Stavade texten en bokstav i taget (användbart för akronymer och förkortningar).

```java
public String Speak { get; set; }
```

### Returvärde

speak-egenskap

### Se även

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

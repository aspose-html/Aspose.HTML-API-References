---
title: "ICSS2Properties.Display"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. De waarden van deze eigenschap hebben de volgende betekenissen"
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

De waarden van deze eigenschap hebben de volgende betekenissen:

block - Deze waarde zorgt ervoor dat een element een hoofd‑block‑box genereert. inline - Deze waarde zorgt ervoor dat een element een of meer inline‑boxes genereert. list-item - Deze waarde zorgt ervoor dat een element (bijv. LI in HTML) een hoofd‑block‑box en een list‑item inline‑box genereert. Voor informatie over lijsten en voorbeelden van lijstopmaak, raadpleeg de sectie over [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists). marker - Deze waarde verklaart [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) vóór of na een box als een marker. Deze waarde mag alleen worden gebruikt met [:before en :after pseudo‑elements](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) die aan block‑level elementen zijn gekoppeld. In andere gevallen wordt deze waarde geïnterpreteerd als 'inline'. Raadpleeg de sectie over [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) voor meer informatie. none - Deze waarde zorgt ervoor dat een element geen boxes genereert in de [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (d.w.z. het element heeft geen effect op de lay-out). Afstammelingen genereren ook geen boxes; dit gedrag kan niet worden overschreven door de ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) eigenschap op de afstammelingen in te stellen. Let op dat een weergave van 'none' geen onzichtbare box creëert; het creëert helemaal geen box. CSS bevat mechanismen die een element in staat stellen boxes te genereren in de opmaakstructuur die de opmaak beïnvloeden maar zelf niet zichtbaar zijn. Raadpleeg de sectie over [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) voor details. run-in en compact - Deze waarden creëren respectievelijk block‑ of inline‑boxes, afhankelijk van de context. Eigenschappen zijn van toepassing op run‑in‑ en compact‑boxes op basis van hun uiteindelijke status (inline‑level of block‑level). Bijvoorbeeld, de ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) eigenschap geldt alleen als de box een block‑box wordt. table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell, en table-caption - Deze waarden zorgen ervoor dat een element zich gedraagt als een table‑element (onderhevig aan beperkingen beschreven in het hoofdstuk over [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Retourwaarde

display eigenschap

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

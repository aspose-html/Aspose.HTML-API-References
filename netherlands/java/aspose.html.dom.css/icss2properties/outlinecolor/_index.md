---
title: "Waarden voor deze eigenschap hebben de volgende betekenissen:"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSS2Properties eigenschap. De omtrek die met de outline‑eigenschappen wordt gecreëerd, wordt getekend over een vak, d.w.z. de omtrek staat altijd bovenop en beïnvloedt de positie of grootte van het vak of van andere vakken niet. Daarom veroorzaakt het weergeven of onderdrukken van omtrekken geen reflow."
type: docs

url: /nl/java/com.aspose.html.dom.css/icss2properties/outlinecolor/
---
## ICSS2Properties.OutlineColor property

De omtrek die met de outline‑eigenschappen wordt gecreëerd, wordt "over" een vak getekend, d.w.z. de omtrek staat altijd bovenop en beïnvloedt de positie of grootte van het vak, of van andere vakken, niet. Daarom veroorzaakt het weergeven of onderdrukken van omtrekken geen reflow.

```java
public String OutlineColor { get; set; }
```

### Retourwaarde

normal - Het element opent geen extra niveau van insluiting ten opzichte van het bidirectionele algoritme. Voor inline-niveau elementen werkt impliciete herschikking over elementgrenzen. embed - Als het element inline-niveau is, opent deze waarde een extra niveau van insluiting ten opzichte van het bidirectionele algoritme. De richting van dit insluitingsniveau wordt gegeven door de ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) eigenschap. Binnen het element wordt herschikking impliciet uitgevoerd. Dit komt overeen met het toevoegen van een LRE (U+202A; voor 'direction: ltr') of RLE (U+202B; voor 'direction: rtl') aan het begin van het element en een PDF (U+202C) aan het einde van het element. bidi-override - Als het element inline-niveau of een blokniveau-element is dat alleen inline-elementen bevat, creëert dit een override. Dit betekent dat binnen het element de herschikking strikt in volgorde gebeurt volgens de ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) eigenschap; het impliciete deel van het bidirectionele algoritme wordt genegeerd. Dit komt overeen met het toevoegen van een LRO (U+202D; voor 'direction: ltr') of RLO (U+202E; voor 'direction: rtl') aan het begin van het element en een PDF (U+202C) aan het einde van het element.

### Zie ook

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

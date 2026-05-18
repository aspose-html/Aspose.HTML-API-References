---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGAngle-Methode. Setzt den Wert als Zahl mit einem zugehörigen unitType zurück und ersetzt dadurch die Werte aller Attribute des Objekts."
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Setze den Wert als Zahl mit einem zugehörigen unitType zurück, wodurch die Werte aller Attribute des Objekts ersetzt werden.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newUnitType | UInt16 | Der Einheitstyp für den Wert (z. B. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Der Winkelwert. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Wird ausgelöst, wenn unitType SVG_ANGLETYPE_UNKNOWN ist oder kein gültiger Einheitstyp‑Konstantwert (einer der anderen SVG_ANGLETYPE_*‑Konstanten, die in diesem Interface definiert sind). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Ausgelöst, wenn der Winkel einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

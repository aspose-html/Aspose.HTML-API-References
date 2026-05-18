---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGLength Methode. Setzt den Wert als Zahl mit einem zugehörigen Einheitstyp zurück und ersetzt dadurch die Werte aller Attribute des Objekts."
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Setze den Wert als Zahl mit einem zugehörigen unitType zurück, wodurch die Werte aller Attribute des Objekts ersetzt werden.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unitType | UInt16 | Der Einheitstyp für den Wert. |
| valueInSpecifiedUnits | Single | Der neue Wert.. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Wird ausgelöst, wenn unitType SVG_LENGTHTYPE_UNKNOWN ist oder keine gültige Einheitstyp‑Konstante (eine der anderen SVG_LENGTHTYPE_* Konstanten, die in diesem Interface definiert sind). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) ausgelöst, wenn die Länge einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

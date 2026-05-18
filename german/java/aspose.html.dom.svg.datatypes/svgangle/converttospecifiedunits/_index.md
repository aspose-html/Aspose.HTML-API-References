---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGAngle‑Methode. Bewahrt den gleichen zugrunde liegenden gespeicherten Wert, setzt jedoch den gespeicherten Einheit‑Identifier auf den angegebenen unitType zurück. Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden."
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Behalte den gleichen zugrunde liegenden gespeicherten Wert bei, setze jedoch die gespeicherte Einheitkennung auf den angegebenen unitType zurück. Objektattribute unitType, valueInSpecifiedUnits und valueAsString können als Ergebnis dieser Methode geändert werden.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unitType | UInt16 | Der Einheitstyp, zu dem gewechselt werden soll (z. B. SVG_ANGLETYPE_DEG). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Wird ausgelöst, wenn unitType SVG_ANGLETYPE_UNKNOWN ist oder kein gültiger Einheitstyp‑Konstantwert (einer der anderen SVG_ANGLETYPE_*‑Konstanten, die in diesem Interface definiert sind). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Ausgelöst, wenn der Winkel einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

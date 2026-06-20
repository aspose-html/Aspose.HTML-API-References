---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGLength-Methode. Bewahrt den gleichen zugrunde liegenden gespeicherten Wert, setzt jedoch den gespeicherten Einheit‑Identifikator auf den angegebenen unitType zurück. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden. Zum Beispiel, wenn der ursprüngliche Wert 0,5 cm war und die Methode aufgerufen wird, um in Millimeter zu konvertieren, dann wird unitType zu SVG_LENGTHTYPE_MM geändert, valueInSpecifiedUnits wird auf den numerischen Wert 5 gesetzt und valueAsString wird zu 5mm geändert."
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Behalte denselben zugrunde liegenden gespeicherten Wert bei, setze jedoch den gespeicherten Einheit-Identifikator auf den angegebenen unitType zurück. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden. Zum Beispiel, wenn der ursprüngliche Wert "0.5cm" war und die Methode aufgerufen wurde, um in Millimeter zu konvertieren, dann würde unitType zu SVG_LENGTHTYPE_MM geändert, valueInSpecifiedUnits würde auf den numerischen Wert 5 geändert und valueAsString würde zu "5mm" geändert.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unitType | UInt16 | Der Einheitstyp, zu dem gewechselt werden soll (z. B. SVG_LENGTHTYPE_MM). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Wird ausgelöst, wenn unitType SVG_LENGTHTYPE_UNKNOWN ist oder keine gültige Einheitstyp‑Konstante (eine der anderen SVG_LENGTHTYPE_* Konstanten, die in diesem Interface definiert sind). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) ausgelöst, wenn die Länge einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)

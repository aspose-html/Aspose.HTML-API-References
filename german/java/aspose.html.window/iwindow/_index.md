---
title: "IWindow-Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.window.IWindow Schnittstelle. Das Fensterobjekt stellt ein Fenster dar, das ein DOM-Dokument enthält."
type: docs

url: /de/java/com.aspose.html.window/iwindow/
---
## IWindow interface

Das window‑Objekt stellt ein Fenster dar, das ein DOM‑Dokument enthält.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) Das document-Attribut muss das neueste Document-Objekt des Window-Objekts zurückgeben. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) Das frameElement-Objekt eines Dokuments. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Gibt ein Storage-Objekt zurück, das es Ihnen ermöglicht, Schlüssel/Wert-Paare im User-Agent zu speichern. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Das location-Attribut der Window-Schnittstelle muss das Location-Objekt für das Document dieses Window-Objekts zurückgeben. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) Das opener-IDL-Attribut des Window-Objekts muss beim Lesen das WindowProxy-Objekt des Browsing‑Context zurückgeben, aus dem der aktuelle Browsing‑Context erstellt wurde (sein opener‑Browsing‑Context), falls ein solches existiert, noch verfügbar ist und der aktuelle Browsing‑Context seinen opener nicht verworfen hat; andernfalls muss null zurückgegeben werden. Beim Schreiben, wenn der neue Wert null ist, muss der aktuelle Browsing‑Context seinen opener verwerfen; ist der neue Wert etwas anderes, muss der User-Agent die interne Methode [[DefineOwnProperty]] des Window-Objekts aufrufen, den Eigenschaftsnamen "opener" als Schlüssel übergeben und den Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als Eigenschaftsbeschreibung verwenden, wobei value der neue Wert ist. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) Das parent-IDL-Attribut des Window-Objekts eines Dokuments in einem Browsing‑Context b muss das WindowProxy-Objekt des übergeordneten Browsing‑Context zurückgeben, falls ein solches existiert (d. h. wenn b ein Kind‑Browsing‑Context ist), andernfalls das WindowProxy-Objekt des Browsing‑Context b selbst (d. h. wenn es ein Top‑Level‑Browsing‑Context oder ein losgelöster verschachtelter Browsing‑Context ist). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Gibt das WindowProxy-Objekt des Browsing‑Context des Window-Objekts zurück. |
| [getTop](../../com.aspose.html.window/iwindow/top/) Das top-IDL-Attribut des Window-Objekts eines Dokuments in einem Browsing‑Context b muss das WindowProxy-Objekt seines top‑level Browsing‑Context zurückgeben (was sein eigenes WindowProxy-Objekt wäre, wenn es selbst ein top‑level Browsing‑Context wäre), falls ein solches existiert, andernfalls sein eigenes WindowProxy-Objekt (z. B. wenn es ein losgelöster verschachtelter Browsing‑Context war). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Gibt das WindowProxy-Objekt des Browsing‑Context des Window-Objekts zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Zeigt einen modalen Alarm mit der angegebenen Nachricht an und wartet, bis der Benutzer ihn schließt. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Nimmt die Eingabedaten in Form eines Unicode-Strings, der base64‑kodierte Binärdaten enthält, dekodiert sie und gibt einen String zurück, der aus Zeichen im Bereich U+0000 bis U+00FF besteht, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, das den jeweiligen Binärdaten entspricht. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Nimmt die Eingabedaten in Form eines Unicode-Strings, der nur Zeichen im Bereich U+0000 bis U+00FF enthält, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, und konvertiert sie in ihre base64‑Darstellung, die zurückgegeben wird. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Zeigt eine modale OK/Cancel‑Eingabeaufforderung mit der angegebenen Nachricht an, wartet, bis der Benutzer sie schließt, und gibt true zurück, wenn der Benutzer OK wählt, bzw. false, wenn er Abbrechen wählt. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Gibt ein neues MediaQueryList‑Objekt zurück, das verwendet werden kann, um zu bestimmen, ob das Dokument dem Media‑Query‑String entspricht, sowie um das Dokument zu überwachen und zu erkennen, wann es dem Media‑Query entspricht (oder nicht mehr entspricht). Siehe CSSOM View Module‑Spezifikation: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Zeigt eine modale Texteingabe‑Aufforderung mit der angegebenen Nachricht an, wartet, bis der Benutzer sie schließt, und gibt den vom Benutzer eingegebenen Wert zurück. Wenn der Benutzer die Eingabe abbricht, wird stattdessen null zurückgegeben. Ist ein zweites Argument vorhanden, wird der angegebene Wert als Vorgabe verwendet. |

### Siehe auch

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)

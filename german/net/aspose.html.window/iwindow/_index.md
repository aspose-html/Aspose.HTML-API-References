---
title: Interface IWindow
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Window.IWindow koppel. Das Fensterobjekt stellt ein Fenster dar das ein DOMDokument enthält.
type: docs
weight: 5850
url: /de/net/aspose.html.window/iwindow/
---
## IWindow interface

Das Fensterobjekt stellt ein Fenster dar, das ein DOM-Dokument enthält.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document/) { get; } | Das document-Attribut muss das neueste Document-Objekt des Window-Objekts zurückgeben. |
| [FrameElement](../../aspose.html.window/iwindow/frameelement/) { get; } | Das frameElement-Objekt eines Dokuments. |
| [Location](../../aspose.html.window/iwindow/location/) { get; } | Das Standortattribut der Fensterschnittstelle muss das Standortobjekt für das Dokument dieses Fensterobjekts zurückgeben. |
| [Name](../../aspose.html.window/iwindow/name/) { get; set; } | Das name-Attribut des Window-Objekts muss beim Abrufen den aktuellen Namen des Browsing-Kontexts zurückgeben und beim Setzen den Namen des Browsing-Kontexts auf den neuen Wert setzen. |
| [Opener](../../aspose.html.window/iwindow/opener/) { get; } | Das Opener-IDL-Attribut des Window-Objekts muss beim Abrufen das WindowProxy-Objekt des Browsing-Kontexts zurückgeben, aus dem der aktuelle Browsing-Kontext erstellt wurde (sein Opener-Browsing-Kontext), falls es einen gibt, ob er noch verfügbar ist und falls der aktuelle Browsing-Kontext hat seinen Öffner nicht verleugnet; andernfalls muss es null zurückgeben. Wenn der neue Wert bei der Einstellung null ist, muss der aktuelle Browsing-Kontext seinen Opener ablehnen; Wenn der neue Wert etwas anderes ist, muss der Benutzeragent die interne Methode [[DefineOwnProperty]] des Window-Objekts aufrufen und den Eigenschaftsnamen "Öffner" als Eigenschaftsschlüssel und den Eigenschaftsdeskriptor {[[Wert]]: value übergeben , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als Eigenschaftsdeskriptor, wobei value der neue Wert ist. |
| [Parent](../../aspose.html.window/iwindow/parent/) { get; } | Das übergeordnete IDL-Attribut des Window-Objekts eines Dokuments in einem Browsing-Kontext b muss das WindowProxy-Objekt des übergeordneten Browsing-Kontexts zurückgeben, falls vorhanden (dh wenn b ein untergeordneter Browsing-Kontext ist), oder das WindowProxy-Objekt des Browsing-Kontexts Kontext b selbst, andernfalls (dh wenn es sich um einen Browsing-Kontext der obersten Ebene oder um einen getrennten verschachtelten Browsing-Kontext handelt). |
| [Self](../../aspose.html.window/iwindow/self/) { get; } | Gibt das WindowProxy-Objekt des Browserkontexts des Window-Objekts zurück. |
| [Top](../../aspose.html.window/iwindow/top/) { get; } | Das oberste IDL-Attribut des Window-Objekts eines Dokuments in einem Browsing-Kontext b muss das WindowProxy-Objekt seines Top-Level-Browsing-Kontexts zurückgeben (das sein eigenes WindowProxy-Objekt wäre, wenn es selbst ein Top-Level-Browsing-Kontext wäre), wenn es hat ein oder sein eigenes WindowProxy-Objekt (z. B. wenn es sich um einen getrennten verschachtelten Browsing-Kontext handelt). |
| [Window](../../aspose.html.window/iwindow/window/) { get; } | Gibt das WindowProxy-Objekt des Browserkontexts des Window-Objekts zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert/)(string) | Zeigt eine modale Warnung mit der angegebenen Nachricht an und wartet darauf, dass der Benutzer sie verwirft |
| [Confirm](../../aspose.html.window/iwindow/confirm/)(string) | Zeigt eine modale OK/Abbrechen-Eingabeaufforderung mit der angegebenen Meldung an, wartet darauf, dass der Benutzer sie verwirft, und gibt „true“ zurück, wenn der Benutzer auf „OK“ klickt, und „false“, wenn der Benutzer auf „Abbrechen“ klickt. |
| [Prompt](../../aspose.html.window/iwindow/prompt/)(string, string) | Zeigt eine modale Textfeld-Eingabeaufforderung mit der angegebenen Nachricht an, wartet darauf, dass der Benutzer sie verwirft, und gibt den vom Benutzer eingegebenen Wert zurück. Wenn der Benutzer die Eingabeaufforderung abbricht, wird stattdessen null zurückgegeben. Wenn das zweite Argument vorhanden ist, wird der angegebene Wert als Standard verwendet. |

### Siehe auch

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namensraum [Aspose.Html.Window](../../aspose.html.window/)
* Montage [Aspose.HTML](../../)



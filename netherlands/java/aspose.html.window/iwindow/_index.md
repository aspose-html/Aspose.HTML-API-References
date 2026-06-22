---
title: "IWindow interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.window.IWindow interface. Het window‑object vertegenwoordigt een venster dat een DOM‑document bevat"
type: docs

url: /nl/java/com.aspose.html.window/iwindow/
---
## IWindow interface

Het window‑object vertegenwoordigt een venster dat een DOM‑document bevat.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) Het document‑attribuut moet het nieuwste Document‑object van het Window‑object retourneren. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) Het frameElement‑object van een Document. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Retourneert een Storage‑object dat u in staat stelt sleutel/waarde‑paren op te slaan in de user agent. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Het location‑attribuut van de Window‑interface moet het Location‑object voor het Document van dat Window‑object retourneren. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) Het opener‑IDL‑attribuut op het Window‑object moet bij het ophalen het WindowProxy‑object van de browsing‑context retourneren waaruit de huidige browsing‑context is gecreëerd (de opener‑browsing‑context), indien aanwezig, indien nog beschikbaar, en indien de huidige browsing‑context zijn opener niet heeft losgelaten; anders moet het null retourneren. Bij het instellen, als de nieuwe waarde null is, moet de huidige browsing‑context zijn opener loslaten; als de nieuwe waarde iets anders is, moet de user agent de interne methode [[DefineOwnProperty]] van het Window‑object aanroepen, waarbij de eigenschapsnaam "opener" als sleutel wordt doorgegeven, en de Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } als eigenschapsdescriptor, waarbij value de nieuwe waarde is. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) Het parent‑IDL‑attribuut op het Window‑object van een Document in een browsing‑context b moet het WindowProxy‑object van de bovenliggende browsing‑context retourneren, indien aanwezig (d.w.z. als b een child‑browsing‑context is), of het WindowProxy‑object van de browsing‑context b zelf, anders (d.w.z. als het een top‑level browsing‑context of een losgekoppelde geneste browsing‑context is). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Retourneert het WindowProxy‑object van de browsing‑context van het Window‑object. |
| [getTop](../../com.aspose.html.window/iwindow/top/) Het top‑IDL‑attribuut op het Window‑object van een Document in een browsing‑context b moet het WindowProxy‑object van de top‑level browsing‑context retourneren (wat zijn eigen WindowProxy‑object zou zijn als het zelf een top‑level browsing‑context was), indien aanwezig, of anders zijn eigen WindowProxy‑object (bijv. als het een losgekoppelde geneste browsing‑context was). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Retourneert het WindowProxy‑object van de browsing‑context van het Window‑object. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Toont een modale waarschuwing met het opgegeven bericht en wacht tot de gebruiker deze sluit. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Neemt de invoergegevens in de vorm van een Unicode‑string die base64‑gecodeerde binaire gegevens bevat, decodeert deze en retourneert een string bestaande uit tekens in het bereik U+0000 tot U+00FF, elk een binair byte met waarden 0x00 tot 0xFF respectievelijk, overeenkomend met die binaire gegevens. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Neemt de invoergegevens in de vorm van een Unicode‑string die alleen tekens bevat in het bereik U+0000 tot U+00FF, elk een binair byte met waarden 0x00 tot 0xFF respectievelijk, en zet deze om naar de base64‑representatie, die wordt geretourneerd. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Toont een modale OK/Cancel‑prompt met het opgegeven bericht, wacht tot de gebruiker deze sluit, en retourneert true als de gebruiker op OK klikt en false als de gebruiker op Annuleren klikt. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Retourneert een nieuw MediaQueryList‑object dat vervolgens kan worden gebruikt om te bepalen of het document overeenkomt met de media‑query‑string, evenals om het document te monitoren om te detecteren wanneer het overeenkomt (of stopt met overeenkomen) die media‑query. Zie CSSOM View Module-specificatie: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Toont een modale tekstveld‑prompt met het opgegeven bericht, wacht tot de gebruiker deze sluit, en retourneert de waarde die de gebruiker heeft ingevoerd. Als de gebruiker de prompt annuleert, wordt null geretourneerd. Als het tweede argument aanwezig is, wordt de opgegeven waarde als standaard gebruikt. |

### Zie ook

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)

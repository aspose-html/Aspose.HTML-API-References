---
title: "Interfaccia IWindow"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.window.IWindow. L'oggetto window rappresenta una finestra contenente un documento DOM"
type: docs

url: /it/java/com.aspose.html.window/iwindow/
---
## IWindow interface

L'oggetto window rappresenta una finestra contenente un documento DOM.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) L'attributo document deve restituire il più recente oggetto Document dell'oggetto Window. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) L'oggetto frameElement di un Document. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Restituisce un oggetto Storage che consente di salvare coppie chiave/valore nell'agente utente. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) L'attributo location dell'interfaccia Window deve restituire l'oggetto Location per il documento dell'oggetto Window. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) L'attributo IDL opener sull'oggetto Window, in lettura, deve restituire l'oggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente (il suo contesto di apertura), se esiste, se è ancora disponibile e se il contesto di navigazione corrente non ha rinunciato al suo opener; altrimenti, deve restituire null. In scrittura, se il nuovo valore è null il contesto di navigazione corrente deve rinunciare al suo opener; se il nuovo valore è diverso, l'agente utente deve chiamare il metodo interno [[DefineOwnProperty]] dell'oggetto Window, passando il nome della proprietà "opener" come chiave della proprietà, e il Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } come descrittore della proprietà, dove value è il nuovo valore. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) L'attributo IDL parent sull'oggetto Window di un Document in un contesto di navigazione b deve restituire l'oggetto WindowProxy del contesto di navigazione genitore, se esiste (cioè se b è un contesto di navigazione figlio), oppure l'oggetto WindowProxy del contesto di navigazione b stesso, altrimenti (cioè se è un contesto di navigazione di livello superiore o un contesto annidato separato). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Restituisce l'oggetto WindowProxy del contesto di navigazione dell'oggetto Window. |
| [getTop](../../com.aspose.html.window/iwindow/top/) L'attributo IDL top sull'oggetto Window di un Document in un contesto di navigazione b deve restituire l'oggetto WindowProxy del suo contesto di navigazione di livello superiore (che sarebbe il suo stesso oggetto WindowProxy se fosse un contesto di livello superiore), se ne ha uno, altrimenti il suo stesso oggetto WindowProxy (ad esempio se era un contesto annidato separato). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Restituisce l'oggetto WindowProxy del contesto di navigazione dell'oggetto Window. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Visualizza un avviso modale con il messaggio fornito e attende che l'utente lo chiuda. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Accetta i dati di input, sotto forma di stringa Unicode contenente dati binari codificati in base64, li decodifica e restituisce una stringa composta da caratteri nell'intervallo U+0000 a U+00FF, ciascuno dei quali rappresenta un byte binario con valori da 0x00 a 0xFF rispettivamente, corrispondenti a quei dati binari. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Accetta i dati di input, sotto forma di stringa Unicode contenente solo caratteri nell'intervallo U+0000 a U+00FF, ciascuno dei quali rappresenta un byte binario con valori da 0x00 a 0xFF rispettivamente, e lo converte nella sua rappresentazione base64, che restituisce. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Visualizza una finestra modale OK/Cancel con il messaggio fornito, attende che l'utente la chiuda e restituisce true se l'utente clicca OK e false se clicca Cancel. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Restituisce un nuovo oggetto MediaQueryList che può essere usato per determinare se il documento corrisponde alla stringa di query media, nonché per monitorare il documento e rilevare quando corrisponde (o smette di corrispondere) a tale query media. Vedi la specifica del modulo CSSOM View: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Visualizza una finestra modale con un campo di testo e il messaggio fornito, attende che l'utente la chiuda e restituisce il valore inserito dall'utente. Se l'utente annulla la finestra, restituisce null. Se è presente il secondo argomento, il valore fornito viene usato come predefinito. |

### Vedi anche

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)

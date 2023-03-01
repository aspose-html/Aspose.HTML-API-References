---
title: Enum Sandbox
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Sandbox enum. Un set di flag sandboxing è un insieme di zero o più dei seguenti flag utilizzati per limitare le capacità di risorse potenzialmente non attendibili.
type: docs
weight: 4560
url: /it/net/aspose.html/sandbox/
---
## Sandbox enumeration

Un set di flag sandboxing è un insieme di zero o più dei seguenti flag, utilizzati per limitare le capacità di risorse potenzialmente non attendibili.

```csharp
[Flags]
public enum Sandbox
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Nessun flag impostato, tutte le funzionalità sandbox sono accettate |
| Navigation | `1` | Questo flag impedisce al contenuto di navigare in contesti di navigazione diversi dal contesto di navigazione sandbox stesso (o contesti di navigazione ulteriormente nidificati al suo interno), contesti di navigazione ausiliari (che sono protetti dal flag del contesto di navigazione di navigazione ausiliario sandbox definito di seguito) e il flag di primo livello contesto di navigazione (che è protetto dal flag del contesto di navigazione di navigazione di primo livello in modalità sandbox definito di seguito). Se il flag del contesto di navigazione della navigazione ausiliaria in modalità sandbox non è impostato, in alcuni casi le restrizioni consentono comunque l'apertura di popup (nuovi contesti di navigazione di primo livello). Questi contesti di navigazione hanno sempre un navigatore sandbox consentito, impostato quando viene creato il contesto di navigazione, che consente al contesto di navigazione che li ha creati di navigarli effettivamente. (In caso contrario, il flag del contesto di navigazione della navigazione in modalità sandbox impedirebbe la navigazione anche se fossero aperti. |
| AuxiliaryNavigation | `2` | Questo flag impedisce al contenuto di creare nuovi contesti di navigazione ausiliari, ad esempio utilizzando l'attributo target o il metodo window.open(). |
| TopLevelNavigation | `4` | Questo flag impedisce al contenuto di navigare nel contesto di navigazione di primo livello e impedisce al contenuto di chiudere il contesto di navigazione di primo livello. Quando il flag del contesto di navigazione della navigazione di primo livello in modalità sandbox non è impostato, il contenuto può navigare nel suo contesto di navigazione di primo livello, ma altri contesti di navigazione sono comunque protetti dal flag del contesto di navigazione della navigazione in modalità sandbox ed eventualmente dal flag del contesto di navigazione della navigazione ausiliaria in modalità sandbox. |
| Plugins | `8` | Questo flag impedisce al contenuto di istanziare i plug-in, sia utilizzando l'elemento embed, l'elemento oggetto, l'elemento applet o attraverso la navigazione di un contesto di navigazione nidificato, a meno che tali plug-in non possano essere protetti. |
| Origin | `10` | Questo flag forza il contenuto in un'origine univoca, impedendogli così di accedere ad altri contenuti dalla stessa origine. |
| Forms | `20` | Questo flag blocca l'invio del modulo. |
| PointerLock | `40` | Questo flag disabilita l'API Pointer Lock. |
| Scripts | `80` | Questo flag blocca l'esecuzione dello script. |
| AutomaticFeatures | `100` | Questo flag blocca le funzionalità che si attivano automaticamente, come la riproduzione automatica di un video o la messa a fuoco automatica di un controllo del modulo. |
| Fullscreen | `200` | Questo flag impedisce al contenuto di utilizzare il metodo requestFullscreen(). |
| DocumentDomain | `400` | Questo flag impedisce al contenuto di utilizzare la funzione document.domain per modificare l'origine effettiva dello script. |
| Images | `800` | Questo flag disabilita il caricamento delle immagini. |

### Guarda anche

* spazio dei nomi [Aspose.Html](../../aspose.html/)
* assemblea [Aspose.HTML](../../)



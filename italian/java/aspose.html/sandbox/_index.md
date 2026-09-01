---
title: "Enum Sandbox"
second_title: "Aspose.HTML per Java Riferimento API"
description: "enum com.aspose.html.Sandbox. Un set di flag di sandbox è un insieme di zero o più dei seguenti flag che vengono usati per limitare le capacità delle risorse potenzialmente non attendibili"
type: docs

url: /it/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Un set di flag di sandbox è un insieme di zero o più dei seguenti flag, che vengono usati per limitare le capacità di risorse potenzialmente non attendibili.

```java
[Flags]
public enum Sandbox
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Nessun flag è impostato, tutte le funzionalità della sandbox sono accettate |
| Navigation | `1` | Questo flag impedisce al contenuto di navigare contesti di navigazione diversi dal contesto di navigazione sandboxed stesso (o da contesti di navigazione ulteriormente annidati al suo interno), contesti di navigazione ausiliari (che sono protetti dal flag sandboxed auxiliary navigation browsing context definito di seguito), e il contesto di navigazione di livello superiore (che è protetto dal flag sandboxed top-level navigation browsing context definito più sotto). Se il flag sandboxed auxiliary navigation browsing context non è impostato, in alcuni casi le restrizioni consentono comunque l'apertura di popup (nuovi contesti di navigazione di livello superiore). Questi contesti di navigazione hanno sempre un navigatore sandboxed consentito, impostato al momento della creazione del contesto di navigazione, che permette al contesto di navigazione che li ha creati di navigarli effettivamente. (Altrimenti, il flag sandboxed navigation browsing context impedirebbe loro di essere navigati anche se fossero aperti. |
| AuxiliaryNavigation | `2` | Questo flag impedisce al contenuto di creare nuovi contesti di navigazione ausiliari, ad es. usando l'attributo target o il metodo window.open(). |
| TopLevelNavigation | `4` | Questo flag impedisce al contenuto di navigare il proprio contesto di navigazione di livello superiore e impedisce al contenuto di chiudere il proprio contesto di navigazione di livello superiore. Quando il flag sandboxed top-level navigation browsing context non è impostato, il contenuto può navigare il proprio contesto di navigazione di livello superiore, ma gli altri contesti di navigazione sono comunque protetti dal flag sandboxed navigation browsing context e, eventualmente, dal flag sandboxed auxiliary navigation browsing context. |
| Plugins | `8` | Questo flag impedisce al contenuto di istanziare plugin, sia usando l'elemento embed, l'elemento object, l'elemento applet, o tramite la navigazione di un contesto di navigazione annidato, a meno che tali plugin non possano essere messi in sicurezza. |
| Origin | `10` | Questo flag costringe il contenuto a un'origine unica, impedendogli così di accedere ad altri contenuti della stessa origine. |
| Forms | `20` | Questo flag blocca l'invio del modulo. |
| PointerLock | `40` | Questo flag disabilita l'API Pointer Lock. |
| Scripts | `80` | Questo flag blocca l'esecuzione degli script. |
| AutomaticFeatures | `100` | Questo flag blocca le funzionalità che si attivano automaticamente, come la riproduzione automatica di un video o il focus automatico di un controllo di un modulo. |
| Fullscreen | `200` | Questo flag impedisce al contenuto di usare il metodo requestFullscreen(). |
| DocumentDomain | `400` | Questo flag impedisce al contenuto di usare la funzionalità document.domain per modificare l'origine effettiva dello script. |
| Images | `800` | Questo flag disabilita il caricamento delle immagini. |

### Vedi anche

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

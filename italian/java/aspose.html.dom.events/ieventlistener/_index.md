---
title: "IEventListener Interfaccia"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.events.IEventListener interfaccia. L'interfaccia è il metodo principale per gestire gli eventi. Gli utenti implementano l'interfaccia e registrano il loro listener utilizzando il metodo. Gli utenti dovrebbero anche rimuovere il loro listener dopo aver terminato di usarlo."
type: docs

url: /it/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

L'interfaccia è il metodo principale per gestire gli eventi. Gli utenti implementano l'interfaccia e registrano il loro listener su un oggetto usando il metodo. Gli utenti dovrebbero anche rimuovere il loro listener dopo aver terminato l'uso.

```java
public interface IEventListener
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Questo metodo viene chiamato ogni volta che si verifica un evento del tipo per cui l'interfaccia è stata registrata. |

## Osservazioni

Quando un Node viene copiato usando il metodo cloneNode, gli Event Listener collegati al Node di origine non vengono collegati al Node copiato. Se l'utente desidera che gli stessi Event Listener vengano aggiunti alla copia appena creata, l'utente deve aggiungerli manualmente.

### Vedi anche

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

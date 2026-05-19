---
title: "IWindow.Opener"
second_title: "Riferimento API Aspose.HTML per Java"
description: "IWindow property. L'attributo IDL opener sull'oggetto Window, in lettura, deve restituire l'oggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente (il suo contesto di apertura), se esiste, se è ancora disponibile e se il contesto di navigazione corrente non ha rinunciato al suo opener; altrimenti deve restituire null. In scrittura, se il nuovo valore è null, il contesto di navigazione corrente deve rinunciare al suo opener; se il nuovo valore è diverso da null, l'agente utente deve chiamare il metodo interno [[DefineOwnProperty]] dell'oggetto Window, passando il nome della proprietà \"opener\" come chiave della proprietà e il Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } come descrittore della proprietà, dove value è il nuovo valore."
type: docs

url: /it/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

L'attributo IDL opener sull'oggetto Window, in lettura, deve restituire l'oggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente (il suo contesto di apertura), se esiste, se è ancora disponibile e se il contesto di navigazione corrente non ha rinunciato al suo opener; altrimenti, deve restituire null. In scrittura, se il nuovo valore è null, il contesto di navigazione corrente deve rinunciare al suo opener; se il nuovo valore è diverso da null, l'agente utente deve chiamare il metodo interno [[DefineOwnProperty]] dell'oggetto Window, passando il nome della proprietà "opener" come chiave della proprietà e il Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } come descrittore della proprietà, dove value è il nuovo valore.

```java
public IWindow Opener { get; }
```

### Property Value

L'opener.

### Vedi anche

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

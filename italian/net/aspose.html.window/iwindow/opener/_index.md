---
title: IWindow.Opener
second_title: Aspose.HTML per riferimento API .NET
description: IWindow proprietà. Lattributo opener IDL sulloggetto Window al momento dellottenimento deve restituire loggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente il suo contesto di navigazione opener se presente se è ancora disponibile e se lattuale contesto di navigazione non ha rinnegato il suo apri in caso contrario deve restituire null. Allimpostazione se il nuovo valore è nullo il contesto di navigazione corrente deve rinnegare il suo apri se il nuovo valore è qualcosaltro lagente utente deve chiamare il metodo interno DefineOwnProperty delloggetto Window passando il nome della proprietà opener come chiave della proprietà e il descrittore della proprietà  Value valore  Writable true Enumerable true Configurable true  come descrittore della proprietà dove value è il nuovo valore.
type: docs
weight: 50
url: /it/net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

L'attributo opener IDL sull'oggetto Window, al momento dell'ottenimento, deve restituire l'oggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente (il suo contesto di navigazione opener), se presente, se è ancora disponibile e se l'attuale contesto di navigazione non ha rinnegato il suo apri; in caso contrario, deve restituire null. All'impostazione, se il nuovo valore è nullo, il contesto di navigazione corrente deve rinnegare il suo apri; se il nuovo valore è qualcos'altro, l'agente utente deve chiamare il metodo interno [[DefineOwnProperty]] dell'oggetto Window, passando il nome della proprietà "opener" come chiave della proprietà e il descrittore della proprietà { [[Value]]: valore , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } come descrittore della proprietà, dove value è il nuovo valore.

```csharp
public IWindow Opener { get; }
```

### Valore della proprietà

L'apri.

### Guarda anche

* interface [IWindow](../)
* spazio dei nomi [Aspose.Html.Window](../../iwindow/)
* assemblea [Aspose.HTML](../../../)



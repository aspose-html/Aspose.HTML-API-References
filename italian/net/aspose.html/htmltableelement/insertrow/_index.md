---
title: HTMLTableElement.InsertRow
second_title: Aspose.HTML per riferimento API .NET
description: HTMLTableElement metodo. Inserisce una nuova riga vuota nella tabella. La nuova riga viene inserita immediatamente prima e nella stessa sezione dellattuale indice esima riga della tabella. Seindice è 1 o uguale al numero di righe la nuova riga viene aggiunta. Inoltre quando la tabella è vuota la riga viene inserita in aTBODY che viene creato e inserito nella tabella. Una riga della tabella non può essere vuota secondo HTML 4.01 .
type: docs
weight: 220
url: /it/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Inserisce una nuova riga vuota nella tabella. La nuova riga viene inserita immediatamente prima e nella stessa sezione dell'attuale `indice` esima riga della tabella. Se`indice` è -1 o uguale al numero di righe, la nuova riga viene aggiunta. Inoltre, quando la tabella è vuota la riga viene inserita in a`TBODY` che viene creato e inserito nella tabella. Una riga della tabella non può essere vuota secondo [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Il numero di riga in cui inserire una nuova riga. Questo indice parte da 0 ed è relativo all'ordine logico (non all'ordine del documento) di tutte le righe contenute all'interno della tabella. |

### Valore di ritorno

La riga appena creata.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: generato se l'indice specificato è maggiore del numero di righe o se l'indice è un numero negativo diverso da -1. @version DOM Level 2 |

### Guarda anche

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* spazio dei nomi [Aspose.Html](../../htmltableelement/)
* assemblea [Aspose.HTML](../../../)



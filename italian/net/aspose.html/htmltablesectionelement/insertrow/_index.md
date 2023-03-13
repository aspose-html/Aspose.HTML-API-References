---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML per riferimento API .NET
description: HTMLTableSectionElement metodo. Inserisci una riga in questa sezione. La nuova riga viene inserita immediatamente prima della correnteindice esima riga in questa sezione. Se indice è 1 o uguale al numero di righe in questa sezione  la nuova riga viene aggiunta.
type: docs
weight: 70
url: /it/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Inserisci una riga in questa sezione. La nuova riga viene inserita immediatamente prima della corrente`indice` esima riga in questa sezione. Se `indice` è -1 o uguale al numero di righe in questa sezione , la nuova riga viene aggiunta.

```csharp
public HTMLElement InsertRow(int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Il numero di riga in cui inserire una nuova riga. Questo indice parte da 0 ed è relativo solo alle righe contenute all'interno di questa sezione, non a tutte le righe della tabella. |

### Valore di ritorno

La riga appena creata.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: generato se l'indice specificato è maggiore del numero di righe o se l'indice è un numero negativo diverso da -1. @version DOM Level 2 |

### Guarda anche

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* spazio dei nomi [Aspose.Html](../../htmltablesectionelement/)
* assemblea [Aspose.HTML](../../../)



---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo HTMLTableSectionElement. Inserisce una riga in questa sezione. La nuova riga è inserita immediatamente prima della riga corrente di indice indexth in questa sezione. Se l'indice è -1 o uguale al numero di righe in questa sezione, la nuova riga è aggiunta."
type: docs

url: /it/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Inserisci una riga in questa sezione. La nuova riga viene inserita immediatamente prima della riga corrente `index`-esima in questa sezione. Se `index` è -1 o uguale al numero di righe in questa sezione, la nuova riga viene aggiunta alla fine.

```java
public HTMLElement InsertRow(int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Il numero della riga dove inserire una nuova riga. Questo indice parte da 0 ed è relativo solo alle righe contenute in questa sezione, non a tutte le righe della tabella. |

### Valore di ritorno

La riga appena creata.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Generato se l'indice specificato è maggiore del numero di righe o se l'indice è un numero negativo diverso da -1. @version DOM Level 2 |

### Vedi anche

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

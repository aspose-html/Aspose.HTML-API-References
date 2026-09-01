---
title: "HTMLTableRowElement.InsertCell"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo HTMLTableRowElement. Inserisce una cella TD vuota in questa riga. Se l'indice è -1 o uguale al numero di celle, la nuova cella viene aggiunta."
type: docs

url: /it/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Inserisci una cella `TD` vuota in questa riga. Se `index` è -1 o uguale al numero di celle, la nuova cella viene aggiunta alla fine.

```java
public HTMLElement InsertCell(int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Il punto in cui inserire la cella, a partire da 0. |

### Valore di ritorno

La cella appena creata.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Generato se l'`index` specificato è maggiore del numero di celle o se l'indice è un numero negativo diverso da -1. @version DOM Level 2 |

### Vedi anche

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

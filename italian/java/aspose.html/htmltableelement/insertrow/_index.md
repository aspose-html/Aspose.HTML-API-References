---
title: "HTMLTableElement.InsertRow"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo HTMLTableElement. Inserisce una nuova riga vuota nella tabella. La nuova riga viene inserita immediatamente prima e nella stessa sezione della riga corrente con indice specificato nella tabella. Se l'indice è -1 o uguale al numero di righe, la nuova riga viene aggiunta alla fine. Inoltre, quando la tabella è vuota, la riga viene inserita in un TBODY che viene creato e inserito nella tabella. Una riga di tabella non può essere vuota secondo HTML 4.01"
type: docs

url: /it/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Inserisci una nuova riga vuota nella tabella. La nuova riga viene inserita immediatamente prima e nella stessa sezione della riga corrente `index`-esima della tabella. Se `index` è -1 o uguale al numero di righe, la nuova riga viene aggiunta alla fine. Inoltre, quando la tabella è vuota la riga viene inserita in un `TBODY` che viene creato e inserito nella tabella. Una riga di tabella non può essere vuota secondo [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

```java
public Node InsertRow(int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Il numero della riga in cui inserire una nuova riga. Questo indice parte da 0 ed è relativo all'ordine logico (non all'ordine del documento) di tutte le righe contenute nella tabella. |

### Valore di ritorno

La riga appena creata.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Generato se l'indice specificato è maggiore del numero di righe o se l'indice è un numero negativo diverso da -1. @version DOM Level 2 |

### Vedi anche

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

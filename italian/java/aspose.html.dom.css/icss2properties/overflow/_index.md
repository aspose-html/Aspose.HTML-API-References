---
title: "ICSS2Properties.Overflow"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà ICSS2Properties. Questa proprietà specifica se il contenuto di un elemento a livello di blocco viene ritagliato quando supera la scatola dell'elemento, che funge da blocco contenitore per il contenuto. I valori hanno i seguenti significati"
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

Questa proprietà specifica se il contenuto di un elemento a livello di blocco viene ritagliato quando supera la scatola dell'elemento (che funge da blocco contenitore per il contenuto). I valori hanno i seguenti significati:

visible - Questo valore indica che il contenuto non è ritagliato, cioè può essere renderizzato al di fuori della scatola del blocco. hidden - Questo valore indica che il contenuto è ritagliato e che non deve essere fornito alcun meccanismo di scorrimento per visualizzare il contenuto al di fuori della regione di ritaglio; gli utenti non avranno accesso al contenuto ritagliato. La dimensione e la forma della regione di ritaglio sono specificate dalla proprietà ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip). scroll - Questo valore indica che il contenuto è ritagliato e che, se l'agente utente utilizza un meccanismo di scorrimento visibile sullo schermo (come una barra di scorrimento o un panner), tale meccanismo dovrebbe essere mostrato per una scatola indipendentemente dal fatto che parte del suo contenuto sia ritagliato. Ciò evita problemi con le barre di scorrimento che appaiono e scompaiono in un ambiente dinamico. Quando questo valore è specificato e il mezzo di destinazione è 'print' o 'projection', il contenuto in eccesso dovrebbe essere stampato. auto - Il comportamento del valore 'auto' dipende dall'agente utente, ma dovrebbe causare la fornitura di un meccanismo di scorrimento per le scatole in eccesso.

```java
public String Overflow { get; set; }
```

### Valore di ritorno

proprietà overflow

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

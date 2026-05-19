---
title: "TypeInfo.IsDerivedFrom"
second_title: "Riferimento API Aspose.HTML per Java"
description: "metodo TypeInfo. Questo metodo restituisce se esiste una derivazione tra la definizione del tipo di riferimento, cioè il TypeInfo su cui viene chiamato il metodo, e l'altra definizione del tipo, cioè quella passata come parametro"
type: docs

url: /it/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Questo metodo restituisce se esiste una derivazione tra la definizione del tipo di riferimento, cioè il TypeInfo su cui il metodo è chiamato, e l'altra definizione di tipo, cioè quella passata come parametro.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeNamespaceArg | String | il pacchetto dell'altra definizione del tipo |
| typeNameArg | String | il nome dell'altra definizione del tipo. |
| derivationMethod | UInt64 | il tipo di derivazione e le condizioni applicate tra due tipi, come descritto nell'elenco di costanti fornito in questa interfaccia. |

### Valore di ritorno

Se lo schema del documento è un DTD o non è associato alcuno schema al documento, questo metodo restituirà sempre false. Se lo schema del documento è un XML Schema, il metodo restituirà true se la definizione del tipo di riferimento è derivata dall'altra definizione del tipo secondo il parametro di derivazione. Se il valore del parametro è 0 (nessun bit è impostato a 1 per il parametro derivationMethod), il metodo restituirà true se l'altra definizione del tipo può essere raggiunta ricorsivamente mediante qualsiasi combinazione di {base type definition}, {item type definition} o {member type definitions} dalla definizione del tipo di riferimento.

### Vedi anche

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

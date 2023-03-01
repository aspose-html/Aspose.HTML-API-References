---
title: TypeInfo.IsDerivedFrom
second_title: Aspose.HTML per riferimento API .NET
description: TypeInfo metodo. Questo metodo restituisce se esiste una derivazione tra la definizione del tipo di riferimento ovvero il TypeInfo su cui viene chiamato il metodo e laltra definizione del tipo ovvero quella passata come parametri.
type: docs
weight: 30
url: /it/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Questo metodo restituisce se esiste una derivazione tra la definizione del tipo di riferimento, ovvero il TypeInfo su cui viene chiamato il metodo, e l'altra definizione del tipo, ovvero quella passata come parametri.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeNamespaceArg | String | lo spazio dei nomi dell'altra definizione di tipo |
| typeNameArg | String | il nome dell'altra definizione di tipo. |
| derivationMethod | UInt64 | il tipo di derivazione e le condizioni applicate tra due tipi, come descritto nell'elenco di costanti fornito in questa interfaccia. |

### Valore di ritorno

Se lo schema del documento è un DTD o nessuno schema è associato al documento, questo metodo restituirà sempre false. Se lo schema del documento è uno schema XML, il metodo sarà true se la definizione del tipo di riferimento è derivata dall'altra definizione del tipo in base al parametro di derivazione. Se il valore del parametro è 0 (nessun bit è impostato su 1 per il parametro derivationMethod), il metodo restituirà true se l'altra definizione di tipo può essere raggiunta ricorrendo a qualsiasi combinazione di {base type definition}, {item type definition} o {definizioni del tipo di membro} dalla definizione del tipo di riferimento.

### Guarda anche

* class [TypeInfo](../)
* spazio dei nomi [Aspose.Html.Dom](../../typeinfo/)
* assemblea [Aspose.HTML](../../../)



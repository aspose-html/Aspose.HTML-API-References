---
title: Class TypeInfo
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.TypeInfo classe. TypeInfo rappresenta un tipo referenziato dai nodi Element o Attr specificato negli schemi associati al documento.
type: docs
weight: 2530
url: /it/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo rappresenta un tipo referenziato dai nodi Element o Attr, specificato negli schemi associati al documento.

```csharp
public class TypeInfo : DOMObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | Il nome di un tipo dichiarato per l'elemento o attributo associato oppure null se sconosciuto. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | Ottiene lo spazio dei nomi del tipo. Lo spazio dei nomi del tipo dichiarato per l'elemento o l'attributo associato oppure null se l'elemento non ha una dichiarazione o se non sono disponibili informazioni sullo spazio dei nomi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | Questo metodo restituisce se esiste una derivazione tra la definizione del tipo di riferimento, ovvero il TypeInfo su cui viene chiamato il metodo, e l'altra definizione del tipo, ovvero quella passata come parametri. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | Se lo schema del documento è un XML Schema [XML Schema Part 1], questa costante rappresenta la derivazione per estensione. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | Se lo schema del documento è un XML Schema [XML Schema Part 1], questa costante rappresenta l'elenco. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | Se lo schema del documento è un XML Schema [XML Schema Part 1], questa costante rappresenta la derivazione per restrizione se sono coinvolti tipi complessi, o una restrizione se sono coinvolti tipi semplici. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | Se lo schema del documento è un XML Schema [XML Schema Part 1], questa costante rappresenta l'unione se sono coinvolti tipi semplici. |

### Guarda anche

* class [DOMObject](../domobject/)
* spazio dei nomi [Aspose.Html.Dom](../../aspose.html.dom/)
* assemblea [Aspose.HTML](../../)



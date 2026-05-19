---
title: "Classe TypeInfo"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.TypeInfo. Il TypeInfo rappresenta un tipo referenziato da nodi Element o Attr specificati negli schemi associati al documento."
type: docs

url: /it/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

Il TypeInfo rappresenta un tipo referenziato da nodi Element o Attr, specificato negli schemi associati al documento.

```java
public class TypeInfo : DOMObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) Il nome di un tipo dichiarato per l'elemento o l'attributo associato, o null se sconosciuto. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Ottiene il pacchetto del tipo. Il pacchetto del tipo dichiarato per l'elemento o l'attributo associato o null se l'elemento non ha una dichiarazione o se non sono disponibili informazioni sul pacchetto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Questo metodo restituisce se esiste una derivazione tra la definizione del tipo di riferimento, cioè il TypeInfo su cui il metodo è chiamato, e l'altra definizione di tipo, cioè quella passata come parametro. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Se lo schema del documento è uno XML Schema [XML Schema Part 1], questa costante rappresenta la derivazione per estensione. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Se lo schema del documento è uno XML Schema [XML Schema Part 1], questa costante rappresenta l'elenco. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Se lo schema del documento è uno XML Schema [XML Schema Part 1], questa costante rappresenta la derivazione per restrizione se sono coinvolti tipi complessi, o una restrizione se sono coinvolti tipi semplici. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Se lo schema del documento è uno XML Schema [XML Schema Part 1], questa costante rappresenta l'unione se sono coinvolti tipi semplici. |

### Vedi anche

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

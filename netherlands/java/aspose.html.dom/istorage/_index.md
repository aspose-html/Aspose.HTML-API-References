---
title: "IStorage Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.IStorage interface. Deze interface van de Web Storage API biedt toegang tot de sessie- of lokale opslag van een bepaald domein. Zie de Web Storage-specificatie https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /nl/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Deze interface van de Web Storage API biedt toegang tot de sessie- of lokale opslag van een bepaald domein. Zie de Web Storage-specificatie: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Retourneert het aantal sleutel/waarde-paren. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Verwijdert alle sleutel/waarde-paren, indien aanwezig. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Retourneert de huidige waarde die aan de opgegeven sleutel is gekoppeld, of null als de opgegeven sleutel niet bestaat. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Retourneert de naam van de n-de sleutel, of null als n groter dan of gelijk is aan het aantal sleutel/waarde-paren. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Verwijdert het sleutel/waarde-paar met de opgegeven sleutel, als een dergelijk paar bestaat. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Stelt de waarde van het paar geïdentificeerd door sleutel in op waarde, en maakt een nieuw sleutel/waarde-paar aan als er eerder geen paar voor die sleutel bestond. |

### Zie ook

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

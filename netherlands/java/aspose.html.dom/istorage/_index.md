---
title: "IStorage Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.IStorage interface. Deze interface van de Web Storage‑API biedt toegang tot de sessie‑ of lokale opslag van een bepaald domein. Zie de Web Storage‑specificatie https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /nl/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Deze interface van de Web Storage‑API biedt toegang tot de sessie‑ of lokale opslag van een bepaald domein. Zie de Web Storage‑specificatie: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Retourneert het aantal sleutel/waarde‑paren. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Verwijdert alle key/value-paren, indien aanwezig. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Retourneert de huidige waarde die aan de opgegeven sleutel is gekoppeld, of null als de opgegeven sleutel niet bestaat. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Retourneert de naam van de n-de sleutel, of null als n groter dan of gelijk is aan het aantal key/value-paren. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Verwijdert het key/value-paar met de opgegeven sleutel, indien een key/value-paar met die sleutel bestaat. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Stelt de waarde van het paar geïdentificeerd door sleutel in op waarde, en maakt een nieuw key/value-paar aan als er eerder geen paar voor die sleutel bestond. |

### Zie ook

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

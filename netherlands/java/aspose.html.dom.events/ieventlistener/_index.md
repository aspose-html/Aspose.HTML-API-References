---
title: "IEventListener Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.IEventListener interface. De interface is de primaire methode voor het afhandelen van gebeurtenissen. Gebruikers implementeren de interface en registreren hun listener met behulp van de methode. De gebruikers moeten hun listener ook verwijderen nadat ze klaar zijn met het gebruik van de listener."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

De interface is de primaire methode voor het afhandelen van gebeurtenissen. Gebruikers implementeren de interface en registreren hun listener op een met behulp van de methode. De gebruikers moeten hun listener ook verwijderen van het object nadat ze klaar zijn met het gebruik van de listener.

```java
public interface IEventListener
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Deze methode wordt aangeroepen telkens wanneer een gebeurtenis van het type optreedt waarvoor de interface is geregistreerd. |

## Opmerkingen

Wanneer een Node wordt gekopieerd met behulp van de cloneNode-methode, worden de Event Listeners die aan de bron-Node zijn gekoppeld niet aan de gekopieerde Node gekoppeld. Als de gebruiker dezelfde Event Listeners aan de nieuw gemaakte kopie wil toevoegen, moet de gebruiker ze handmatig toevoegen.

### Zie ook

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)

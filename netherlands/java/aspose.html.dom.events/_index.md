---
title: "com.aspose.html.dom.events"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Het com.aspose.html.dom.events-pakket biedt objecten voor alle gebeurtenissen gerelateerd aan DOM-updates. Het omvat abonnement op specifieke contextuele informatie-observatie die aan een gebeurtenis is gekoppeld, evenals de constructie van aangepaste gebeurtenissen."
type: docs

url: /nl/java/com.aspose.html.dom.events/
---
Het **com.aspose.html.dom.events**-pakket levert objecten voor alle gebeurtenissen gerelateerd aan DOM‑updates. Het omvat abonnementen op specifieke contextuele informatie‑observaties die aan een gebeurtenis zijn gekoppeld, evenals de constructie van aangepaste gebeurtenissen.

## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [CustomEvent](./customevent/) | Gebeurtenissen die de CustomEvent-interface gebruiken kunnen worden gebruikt om aangepaste gegevens te dragen. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Het DocumentLoadErrorEvent treedt op wanneer de gevraagde bron niet beschikbaar is. |
| [DOMEventHandler](./domeventhandler/) | Stelt een generieke callback-delegate voor voor Document Object Model (DOM)-gebeurtenisafhandeling. |
| [ErrorEvent](./errorevent/) | De ErrorEvent biedt contextuele informatie over fouten die zich tijdens runtime hebben voorgedaan. |
| [Event](./event/) | De wordt gebruikt om contextuele informatie over een gebeurtenis aan de handler die de gebeurtenis verwerkt te bieden. |
| [FocusEvent](./focusevent/) | De FocusEvent-interface biedt specifieke contextuele informatie die verband houdt met focusgebeurtenissen. |
| [InputEvent](./inputevent/) | Invoergebeurtenissen worden als meldingen verzonden wanneer de DOM wordt bijgewerkt. |
| [KeyboardEvent](./keyboardevent/) | De KeyboardEvent-interface biedt specifieke contextuele informatie die verband houdt met toetsenbordapparaten. Elke toetsenbordgebeurtenis verwijst naar een toets met behulp van een waarde. Toetsenbordgebeurtenissen worden doorgaans gericht op het element dat de focus heeft. |
| [MouseEvent](./mouseevent/) | De MouseEvent-interface biedt specifieke contextuele informatie die verband houdt met muisgebeurtenissen. |
| [UIEvent](./uievent/) | De UIEvent-interface biedt specifieke contextuele informatie die verband houdt met gebruikersinterfacegebeurtenissen. |
| [WheelEvent](./wheelevent/) | De WheelEvent-interface biedt specifieke contextuele informatie die verband houdt met wielgebeurtenissen. Om een instantie van de WheelEvent-interface te maken, gebruik de WheelEvent-constructor en geef een optioneel WheelEventInit-woordenboek door. |
## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | De DocumentEvent-interface biedt een mechanisme waarmee de gebruiker een gebeurtenis van een type kan creëren dat door de implementatie wordt ondersteund. Er wordt verwacht dat de DocumentEvent-interface wordt geïmplementeerd op hetzelfde object dat de Document-interface implementeert in een implementatie die het gebeurtenismodel ondersteunt. |
| [IEventListener](./ieventlistener/) | De interface is de primaire methode voor het afhandelen van gebeurtenissen. Gebruikers implementeren de interface en registreren hun luisteraar met behulp van de methode. De gebruikers moeten hun luisteraar ook verwijderen nadat ze klaar zijn met het gebruik ervan. |
| [IEventTarget](./ieventtarget/) | De EventTarget-interface wordt geïmplementeerd door alle knooppunten in een implementatie die het DOM-gebeurtenismodel ondersteunt. Daarom kan deze interface worden verkregen door bindingspecifieke castmethoden te gebruiken op een instantie van de Node-interface. De interface maakt registratie en verwijdering van Event Listeners op een en het verzenden van gebeurtenissen naar die toe mogelijk. |

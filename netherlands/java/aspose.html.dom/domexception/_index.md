---
title: "DOMException Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.DOMException klasse. De DOMException-interface vertegenwoordigt een abnormale gebeurtenis genaamd een uitzondering die optreedt als gevolg van het aanroepen van een methode of het benaderen van een eigenschap van een web‑API. Dit is in wezen hoe foutcondities worden beschreven in web‑API's."
type: docs

url: /nl/java/com.aspose.html.dom/domexception/
---
## DOMException class

De DOMException-interface vertegenwoordigt een abnormale gebeurtenis (een uitzondering genoemd) die optreedt als gevolg van het aanroepen van een methode of het benaderen van een eigenschap van een web‑API. Dit is in wezen hoe foutcondities worden beschreven in web‑API's.

```java
public class DOMException : PlatformException
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Initialiseert een nieuw exemplaar van de `DOMException` klasse. |
| [DOMException](domexception/#constructor_1)(String, String) | Initialiseert een nieuw exemplaar van de `DOMException` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Retourneert een waarde die een van de foutcode‑constanten bevat, of 0 als geen enkele overeenkomt. Dit veld wordt om historische redenen gebruikt. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Retourneert een String die een bericht of beschrijving weergeeft die is gekoppeld aan de opgegeven foutnaam. |
| [getName](../../com.aspose.html.dom/domexception/name/) Retourneert een String die een van de Strings bevat die geassocieerd zijn met een foutnaam. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | De bewerking werd afgebroken. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | Het object kan niet worden gekloond. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Als het opgegeven tekstbereik niet in een DOMString past. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Als een Node ergens wordt ingevoegd waar het niet thuishoort. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Als index of grootte negatief is, of groter dan de toegestane waarde. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Als er geprobeerd wordt een attribuut toe te voegen dat al ergens anders in gebruik is. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Als een parameter of bewerking niet wordt ondersteund door het onderliggende object. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Als een ongeldig of illegaal teken wordt opgegeven, bijvoorbeeld in een XML‑naam. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | De expressie bevat een syntaxisfout of is anderszins geen geldige expressie volgens de regels van de specifieke XPathEvaluator, of bevat gespecialiseerde extensiefuncties of variabelen die niet worden ondersteund door deze implementatie. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Als er geprobeerd wordt het type van het onderliggende object te wijzigen. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | Het opgegeven node is onjuist of heeft een onjuiste ouder voor deze bewerking. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Als er een poging wordt gedaan om een object te gebruiken dat niet, of niet langer, bruikbaar is. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Als er een poging wordt gedaan om een object te maken of te wijzigen op een manier die onjuist is met betrekking tot pakketten. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Er is een netwerkfout opgetreden. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Als er een poging wordt gedaan om een Node te refereren in een context waarin deze niet bestaat. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Als de implementatie het gevraagde type object of bewerking niet ondersteunt. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Als er gegevens worden opgegeven voor een Node die geen gegevens ondersteunt. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Als er een poging wordt gedaan om een object te wijzigen waar wijzigingen niet zijn toegestaan. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | De quota is overschreden. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | De bewerking is onveilig. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Als er een ongeldige of illegale String is opgegeven. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | De bewerking heeft een time-out. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | De expressie kan niet worden geconverteerd om het opgegeven type te retourneren. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Als het type van een object niet compatibel is met het verwachte type van de parameter die aan het object is gekoppeld. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | De opgegeven URL komt niet overeen met een andere URL. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Als een aanroep van een methode zoals insertBefore of removeChild de Node ongeldig zou maken met betrekking tot \"gedeeltelijke geldigheid\", zou deze uitzondering worden opgegooid en zou de bewerking niet worden uitgevoerd. Deze code wordt gebruikt in [DOM Level 3 Validation]. Raadpleeg deze specificatie voor meer informatie. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Als een Node wordt gebruikt in een ander document dan het document dat het heeft gemaakt (dat het niet ondersteunt). |

### Zie ook

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

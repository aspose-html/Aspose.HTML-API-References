---
title: Class DOMException
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.DOMException klas. De DOMExceptioninterface vertegenwoordigt een abnormale gebeurtenis uitzondering genoemd die optreedt als gevolg van het aanroepen van een methode of het openen van een eigenschap van een webAPI. Dit is eigenlijk hoe foutcondities worden beschreven in webAPIs.
type: docs
weight: 640
url: /nl/net/aspose.html.dom/domexception/
---
## DOMException class

De DOMException-interface vertegenwoordigt een abnormale gebeurtenis (uitzondering genoemd) die optreedt als gevolg van het aanroepen van een methode of het openen van een eigenschap van een web-API. Dit is eigenlijk hoe foutcondities worden beschreven in web-API's.

```csharp
public class DOMException : PlatformException
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | Initialiseert een nieuw exemplaar van het`DOMException` klasse. |
| [DOMException](domexception/#constructor_1)(string, string) | Initialiseert een nieuw exemplaar van het`DOMException` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | Retourneert een waarde die een van de foutcodeconstanten bevat, of 0 als er geen overeenkomen. Dit veld wordt om historische redenen gebruikt. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | Retourneert een tekenreeks die een bericht of beschrijving vertegenwoordigt die is gekoppeld aan de opgegeven foutnaam. |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | Retourneert een tekenreeks die een van de tekenreeksen bevat die zijn gekoppeld aan een foutnaam. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | De bewerking is afgebroken. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | Het object kan niet worden gekloond. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | Als het opgegeven tekstbereik niet in een DOMString past. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | Als een knooppunt ergens is ingevoegd, hoort het niet thuis. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | Als index of grootte negatief is, of groter dan de toegestane waarde. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | Als er wordt geprobeerd een attribuut toe te voegen dat al elders in gebruik is. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | Als een parameter of een bewerking niet wordt ondersteund door het onderliggende object. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | Als een ongeldig of ongeldig teken is opgegeven, zoals in een XML-naam. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | De expressie bevat een syntaxisfout of is anderszins geen legale expressie volgens de regels van de specific XPathEvaluator of bevat gespecialiseerde uitbreidingsfuncties of variabelen die niet worden ondersteund door deze implementatie. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | Als er wordt geprobeerd het type van het onderliggende object te wijzigen. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | Het opgegeven knooppunt is onjuist of heeft een onjuiste voorouder voor deze bewerking. |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | Als er wordt geprobeerd een object te gebruiken dat niet (meer) bruikbaar is. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | Als er wordt geprobeerd een object te maken of te wijzigen op een manier die onjuist is met betrekking tot naamruimten. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | Er is een netwerkfout opgetreden. |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | Als een poging wordt gedaan om naar een knooppunt te verwijzen in een context waar het niet bestaat. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | Als de implementatie het gevraagde type object of bewerking niet ondersteunt. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | Als gegevens zijn opgegeven voor een knooppunt dat geen gegevens ondersteunt. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | Als er wordt geprobeerd een object te wijzigen waar wijzigingen niet zijn toegestaan. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | Het quotum is overschreden. |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | De bewerking is onveilig. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | Als een ongeldige of ongeldige tekenreeks is opgegeven. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | Er is een time-out opgetreden voor de bewerking. |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | De uitdrukking kan niet worden geconverteerd om het opgegeven type te retourneren. |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | Als het type van een object niet compatibel is met het verwachte type van de parameter die aan het object is gekoppeld. |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | De opgegeven URL komt niet overeen met een andere URL. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | Als een aanroep van een methode zoals insertBefore of removeChild de Node ongeldig zou maken met betrekking tot "gedeeltelijke geldigheid", zou deze uitzondering worden gegenereerd en zou de bewerking niet worden uitgevoerd. Deze code wordt gebruikt in [DOM Level 3 Validation]. Raadpleeg deze specificatie voor meer informatie. |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | Als een Node wordt gebruikt in een ander document dan degene die het heeft gemaakt (dat ondersteunt het niet). |

### Zie ook

* class [PlatformException](../../aspose.html/platformexception/)
* naamruimte [Aspose.Html.Dom](../../aspose.html.dom/)
* montage [Aspose.HTML](../../)



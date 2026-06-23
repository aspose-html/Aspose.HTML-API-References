---
title: "DOMException-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.DOMException-klass. DOMException‑gränssnittet representerar en onormal händelse kallad ett undantag som uppstår som ett resultat av att anropa en metod eller komma åt en egenskap i ett webb‑API. Detta är i princip hur felvillkor beskrivs i webb‑API:er."
type: docs

url: /sv/java/com.aspose.html.dom/domexception/
---
## DOMException class

DOMException-gränssnittet representerar en onormal händelse (kallad ett undantag) som uppstår som resultat av att anropa en metod eller komma åt en egenskap i ett webb‑API. Detta är i princip hur felvillkor beskrivs i webb‑API:er.

```java
public class DOMException : PlatformException
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Initierar en ny instans av `DOMException`-klassen. |
| [DOMException](domexception/#constructor_1)(String, String) | Initierar en ny instans av `DOMException`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Returnerar ett värde som innehåller en av felkodskonstanterna, eller 0 om ingen matchar. Detta fält används av historiska skäl. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Returnerar en Sträng som representerar ett meddelande eller en beskrivning kopplad till det angivna felnamnet. |
| [getName](../../com.aspose.html.dom/domexception/name/) Returnerar en Sträng som innehåller en av de Strängar som är associerade med ett felnamn. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | Operationen avbröts. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | Objektet kan inte klonas. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Om det angivna textintervallet inte får plats i en DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Om någon Node infogas på en plats där den inte hör hemma. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Om index eller storlek är negativt, eller större än det tillåtna värdet. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Om ett försök görs att lägga till ett attribut som redan används någon annanstans. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Om en parameter eller en operation inte stöds av det underliggande objektet. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Om ett ogiltigt eller otillåtet tecken anges, till exempel i ett XML‑namn. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | Uttrycket har ett syntaxfel eller är på annat sätt inte ett giltigt uttryck enligt reglerna för den specifika XPathEvaluator eller innehåller specialiserade extensionsfunktioner eller variabler som inte stöds av denna implementation. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Om ett försök görs att ändra typen på det underliggande objektet. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | Den angivna noden är felaktig eller har en felaktig förfader för denna operation. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Om ett försök görs att använda ett objekt som inte är, eller inte längre är, användbart. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Om ett försök görs att skapa eller ändra ett objekt på ett sätt som är felaktigt med avseende på paket. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Ett nätverksfel inträffade. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Om ett försök görs att referera till en Node i ett sammanhang där den inte finns. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Om implementationen inte stöder den begärda typen av objekt eller operation. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Om data anges för en Node som inte stödjer data. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Om ett försök görs att modifiera ett objekt där ändringar inte är tillåtna. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | Kvoten har överskridits. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | Operationen är osäker. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Om en ogiltig eller otillåten sträng anges. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | Operationen har gått ut i tidsgränsen. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | Uttrycket kan inte konverteras för att returnera den angivna typen. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Om typen av ett objekt är inkompatibel med den förväntade typen av parametern som är associerad med objektet. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | Den angivna URL:en matchar inte en annan URL. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Om ett anrop till en metod såsom insertBefore eller removeChild skulle göra Node ogiltig med avseende på "partial validity", skulle detta undantag kastas och operationen skulle inte utföras. Denna kod används i [DOM Level 3 Validation]. Se denna specifikation för ytterligare information. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Om en Node används i ett annat dokument än det som skapade den (som inte stödjer den). |

### Se även

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

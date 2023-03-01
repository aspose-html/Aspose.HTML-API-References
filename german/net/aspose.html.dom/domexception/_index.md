---
title: Class DOMException
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.DOMException klas. Die DOMExceptionSchnittstelle stellt ein anormales Ereignis dar das als Ausnahme bezeichnet wird das als Ergebnis des Aufrufs einer Methode oder des Zugriffs auf eine Eigenschaft einer WebAPI auftritt. So werden im Grunde Fehlerbedingungen in WebAPIs beschrieben.
type: docs
weight: 640
url: /de/net/aspose.html.dom/domexception/
---
## DOMException class

Die DOMException-Schnittstelle stellt ein anormales Ereignis dar (das als Ausnahme bezeichnet wird), das als Ergebnis des Aufrufs einer Methode oder des Zugriffs auf eine Eigenschaft einer Web-API auftritt. So werden im Grunde Fehlerbedingungen in Web-APIs beschrieben.

```csharp
public class DOMException : PlatformException
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | Initialisiert eine neue Instanz von`DOMException` Klasse. |
| [DOMException](domexception/#constructor_1)(string, string) | Initialisiert eine neue Instanz von`DOMException` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | Gibt einen Wert zurück, der eine der Fehlercodekonstanten enthält, oder 0, wenn keine übereinstimmen. Dieses Feld wird aus historischen Gründen verwendet. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | Gibt eine Zeichenfolge zurück, die eine Meldung oder Beschreibung darstellt, die dem angegebenen Fehlernamen zugeordnet ist. |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | Gibt eine Zeichenfolge zurück, die eine der Zeichenfolgen enthält, die einem Fehlernamen zugeordnet sind. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | Der Vorgang wurde abgebrochen. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | Das Objekt kann nicht geklont werden. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | Wenn der angegebene Textbereich nicht in einen DOMString passt. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | Wenn ein Knoten irgendwo eingefügt wird, gehört er nicht dazu. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | Wenn Index oder Größe negativ oder größer als der zulässige Wert ist. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | Wenn versucht wird, ein Attribut hinzuzufügen, das bereits an anderer Stelle verwendet wird. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | Wenn ein Parameter oder eine Operation vom zugrunde liegenden Objekt nicht unterstützt wird. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | Wenn ein ungültiges oder unzulässiges Zeichen angegeben wird, z. B. in einem XML-Namen. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | Der Ausdruck hat einen Syntaxfehler oder ist gemäß den Regeln des Specific XPathEvaluator kein zulässiger Ausdruck oder enthält spezialisierte Erweiterungsfunktionen oder Variablen, die von dieser Implementierung nicht unterstützt werden. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | Wenn versucht wird, den Typ des zugrunde liegenden Objekts zu ändern. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | Der angegebene Knoten ist falsch oder hat einen falschen Vorgänger für diese Operation. |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | Wenn versucht wird, ein Objekt zu verwenden, das nicht oder nicht mehr verwendet werden kann. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | Wenn versucht wird, ein Objekt auf eine bezüglich Namespaces falsche Weise anzulegen oder zu ändern. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | Ein Netzwerkfehler ist aufgetreten. |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | Wenn versucht wird, einen Knoten in einem Kontext zu referenzieren, in dem er nicht existiert. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | Wenn die Implementierung den angeforderten Objekt- oder Vorgangstyp nicht unterstützt. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | Wenn Daten für einen Knoten angegeben werden, der keine Daten unterstützt. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | Wenn versucht wird, ein Objekt zu ändern, an dem Änderungen nicht zulässig sind. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | Das Kontingent wurde überschritten. |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | Der Vorgang ist unsicher. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | Wenn eine ungültige oder unzulässige Zeichenfolge angegeben wird. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | Zeitüberschreitung beim Vorgang. |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | Der Ausdruck kann nicht konvertiert werden, um den angegebenen Typ zurückzugeben. |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | Wenn der Typ eines Objekts nicht mit dem erwarteten Typ des dem Objekt zugeordneten Parameters kompatibel ist. |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | Die angegebene URL stimmt mit keiner anderen URL überein. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | Wenn ein Aufruf einer Methode wie insertBefore oder removeChild den Node hinsichtlich "Teilgültigkeit" ungültig machen würde, würde diese Ausnahme ausgelöst und die Operation nicht durchgeführt werden. Dieser Code wird in [DOM Level 3 Validation] verwendet. Weitere Informationen finden Sie in dieser Spezifikation. |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | Wenn ein Knoten in einem anderen Dokument verwendet wird als dem, das ihn erstellt hat (das es nicht unterstützt). |

### Siehe auch

* class [PlatformException](../../aspose.html/platformexception/)
* namensraum [Aspose.Html.Dom](../../aspose.html.dom/)
* Montage [Aspose.HTML](../../)



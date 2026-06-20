---
title: "DOMException Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.DOMException Klasse. Das DOMException‑Interface stellt ein abnormalen Ereignis namens Ausnahme dar, das als Ergebnis des Aufrufs einer Methode oder des Zugriffs auf eine Eigenschaft einer Web‑API auftritt. So werden Fehlersituationen im Wesentlichen in Web‑APIs beschrieben."
type: docs

url: /de/java/com.aspose.html.dom/domexception/
---
## DOMException class

Die DOMException‑Schnittstelle repräsentiert ein abnormalen Ereignis (eine Ausnahme), das als Ergebnis des Aufrufs einer Methode oder des Zugriffs auf eine Eigenschaft einer Web‑API auftritt. So werden Fehlersituationen in Web‑APIs grundsätzlich beschrieben.

```java
public class DOMException : PlatformException
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Initialisiert eine neue Instanz der `DOMException` Klasse. |
| [DOMException](domexception/#constructor_1)(String, String) | Initialisiert eine neue Instanz der `DOMException` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Gibt einen Wert zurück, der eine der Fehlercode‑Konstanten enthält, oder 0, falls keine zutrifft. Dieses Feld wird aus historischen Gründen verwendet. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Gibt einen String zurück, der eine Nachricht oder Beschreibung enthält, die mit dem angegebenen Fehlernamen verknüpft ist. |
| [getName](../../com.aspose.html.dom/domexception/name/) Gibt einen String zurück, der einen der mit einem Fehlernamen verknüpften Strings enthält. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | Der Vorgang wurde abgebrochen. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | Das Objekt kann nicht geklont werden. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Falls der angegebene Textbereich nicht in einen DOMString passt. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Falls ein beliebiger Knoten an einer Stelle eingefügt wird, an der er nicht hingehört. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Falls Index oder Größe negativ ist oder den zulässigen Wert überschreitet. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Falls versucht wird, ein Attribut hinzuzufügen, das bereits an anderer Stelle verwendet wird. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Falls ein Parameter oder eine Operation vom zugrunde liegenden Objekt nicht unterstützt wird. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Falls ein ungültiges oder illegales Zeichen angegeben wird, wie z. B. in einem XML‑Namen. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | Der Ausdruck hat einen Syntaxfehler oder ist anderweitig kein gültiger Ausdruck gemäß den Regeln des jeweiligen XPathEvaluator oder enthält spezialisierte Erweiterungsfunktionen oder Variablen, die von dieser Implementierung nicht unterstützt werden. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Falls versucht wird, den Typ des zugrunde liegenden Objekts zu ändern. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | Der bereitgestellte Knoten ist ungültig oder hat einen falschen Vorgänger für diese Operation. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Wenn versucht wird, ein Objekt zu verwenden, das nicht oder nicht mehr verwendbar ist. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Wenn versucht wird, ein Objekt in einer Weise zu erstellen oder zu ändern, die in Bezug auf Pakete inkorrekt ist. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Ein Netzwerkfehler ist aufgetreten. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Wenn versucht wird, einen Node in einem Kontext zu referenzieren, in dem er nicht existiert. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Wenn die Implementierung den angeforderten Objekttyp oder die Operation nicht unterstützt. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Wenn Daten für einen Node angegeben werden, der keine Daten unterstützt. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Wenn versucht wird, ein Objekt zu ändern, bei dem Änderungen nicht erlaubt sind. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | Das Kontingent wurde überschritten. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | Der Vorgang ist unsicher. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Wenn eine ungültige oder illegale Zeichenkette angegeben wird. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | Der Vorgang hat ein Zeitlimit überschritten. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | Der Ausdruck kann nicht in den angegebenen Typ konvertiert werden. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Wenn der Typ eines Objekts nicht mit dem erwarteten Typ des mit dem Objekt verbundenen Parameters kompatibel ist. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | Die angegebene URL stimmt nicht mit einer anderen URL überein. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Wenn ein Aufruf einer Methode wie insertBefore oder removeChild den Node in Bezug auf "partial validity" ungültig machen würde, wird diese Ausnahme ausgelöst und der Vorgang wird nicht ausgeführt. Dieser Code wird in [DOM Level 3 Validation] verwendet. Weitere Informationen finden Sie in dieser Spezifikation. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Wenn ein Node in einem anderen Dokument verwendet wird als dem, das ihn erstellt hat (das ihn nicht unterstützt). |

### Siehe auch

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

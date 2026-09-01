---
title: "Classe DOMException"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.dom.DOMException. L'interfaccia DOMException rappresenta un evento anomalo chiamato eccezione che si verifica a seguito della chiamata a un metodo o dell'accesso a una proprietà di una web API. Questo è fondamentalmente il modo in cui le condizioni di errore sono descritte nelle web API."
type: docs

url: /it/java/com.aspose.html.dom/domexception/
---
## DOMException class

L'interfaccia DOMException rappresenta un evento anomalo (chiamato eccezione) che si verifica a seguito della chiamata a un metodo o dell'accesso a una proprietà di una web API. Questo è fondamentalmente il modo in cui le condizioni di errore sono descritte nelle web API.

```java
public class DOMException : PlatformException
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Inizializza una nuova istanza della classe `DOMException`. |
| [DOMException](domexception/#constructor_1)(String, String) | Inizializza una nuova istanza della classe `DOMException`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Restituisce un valore che contiene una delle costanti di codice errore, o 0 se nessuna corrisponde. Questo campo è usato per ragioni storiche. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Restituisce una Stringa che rappresenta un messaggio o una descrizione associata al nome dell'errore fornito. |
| [getName](../../com.aspose.html.dom/domexception/name/) Restituisce una Stringa che contiene una delle Stringhe associate a un nome di errore. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | L'operazione è stata annullata. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | L'oggetto non può essere clonato. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Se l'intervallo di testo specificato non rientra in una DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Se un Node viene inserito da qualche parte dove non appartiene. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Se l'indice o la dimensione sono negativi, o superiori al valore consentito. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Se si tenta di aggiungere un attributo già in uso altrove. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Se un parametro o un'operazione non è supportato dall'oggetto sottostante. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Se viene specificato un carattere non valido o illegale, ad esempio in un nome XML. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | L'espressione presenta un errore di sintassi o non è altrimenti un'espressione valida secondo le regole del specifico XPathEvaluator o contiene funzioni di estensione specializzate o variabili non supportate da questa implementazione. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Se si tenta di modificare il tipo dell'oggetto sottostante. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | Il nodo fornito è errato o ha un antenato non corretto per questa operazione. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Se si tenta di utilizzare un oggetto che non è, o non è più, utilizzabile. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Se si tenta di creare o modificare un oggetto in modo non corretto rispetto ai pacchetti. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Si è verificato un errore di rete. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Se si tenta di fare riferimento a un Nodo in un contesto in cui non esiste. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Se l'implementazione non supporta il tipo di oggetto o l'operazione richiesti. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Se vengono specificati dati per un Nodo che non supporta i dati. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Se si tenta di modificare un oggetto dove le modifiche non sono consentite. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | La quota è stata superata. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | L'operazione non è sicura. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Se viene specificata una stringa non valida o illegale. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | L'operazione è scaduta. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | L'espressione non può essere convertita per restituire il tipo specificato. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Se il tipo di un oggetto è incompatibile con il tipo previsto del parametro associato all'oggetto. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | L'URL fornito non corrisponde a un altro URL. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Se una chiamata a un metodo come insertBefore o removeChild rendesse il Nodo non valido rispetto alla "validità parziale", questa eccezione verrebbe sollevata e l'operazione non verrebbe eseguita. Questo codice è utilizzato in [DOM Level 3 Validation]. Fare riferimento a questa specifica per ulteriori informazioni. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Se un Nodo viene utilizzato in un documento diverso da quello che lo ha creato (che non lo supporta). |

### Vedi anche

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

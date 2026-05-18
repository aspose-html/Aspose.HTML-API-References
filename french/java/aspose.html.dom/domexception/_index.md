---
title: "Classe DOMException"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.DOMException. L’interface DOMException représente un événement anormal appelé exception qui se produit suite à l’appel d’une méthode ou à l’accès à une propriété d’une API web. C’est essentiellement ainsi que les conditions d’erreur sont décrites dans les API web."
type: docs

url: /fr/java/com.aspose.html.dom/domexception/
---
## DOMException class

L'interface DOMException représente un événement anormal (appelé exception) qui se produit suite à l'appel d'une méthode ou à l'accès à une propriété d'une API web. C'est essentiellement ainsi que les conditions d'erreur sont décrites dans les API web.

```java
public class DOMException : PlatformException
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Initialise une nouvelle instance de la classe `DOMException`. |
| [DOMException](domexception/#constructor_1)(String, String) | Initialise une nouvelle instance de la classe `DOMException`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Retourne une valeur contenant l’une des constantes de code d’erreur, ou 0 si aucune ne correspond. Ce champ est utilisé pour des raisons historiques. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Retourne une chaîne représentant un message ou une description associée au nom d’erreur donné. |
| [getName](../../com.aspose.html.dom/domexception/name/) Retourne une chaîne contenant l’une des chaînes associées à un nom d’erreur. |

## Champs

| Nom | Description |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | L’opération a été interrompue. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | L’objet ne peut pas être cloné. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Si la plage de texte spécifiée ne tient pas dans un DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Si un nœud est inséré quelque part où il n’appartient pas. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Si l’index ou la taille est négatif, ou supérieur à la valeur autorisée. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Si une tentative est faite d’ajouter un attribut déjà utilisé ailleurs. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Si un paramètre ou une opération n’est pas pris en charge par l’objet sous‑jacent. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Si un caractère invalide ou illégal est spécifié, comme dans un nom XML. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | L’expression comporte une erreur de syntaxe ou n’est pas une expression légale selon les règles du XPathEvaluator spécifique, ou contient des fonctions d’extension spécialisées ou des variables non prises en charge par cette implémentation. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Si une tentative est faite de modifier le type de l’objet sous‑jacent. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | Le nœud fourni est incorrect ou possède un ancêtre incorrect pour cette opération. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Si une tentative est faite d'utiliser un objet qui n'est pas, ou n'est plus, utilisable. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Si une tentative est faite de créer ou de modifier un objet d'une manière incorrecte par rapport aux packages. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Une erreur réseau s'est produite. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Si une tentative est faite de référencer un nœud dans un contexte où il n'existe pas. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Si l'implémentation ne prend pas en charge le type d'objet ou l'opération demandée. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Si des données sont spécifiées pour un nœud qui ne prend pas en charge les données. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Si une tentative est faite de modifier un objet où les modifications ne sont pas autorisées. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | Le quota a été dépassé. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | L'opération n'est pas sécurisée. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Si une chaîne invalide ou illégale est spécifiée. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | L'opération a expiré. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | L'expression ne peut pas être convertie pour renvoyer le type spécifié. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Si le type d'un objet est incompatible avec le type attendu du paramètre associé à l'objet. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | L'URL fournie ne correspond pas à une autre URL. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Si un appel à une méthode telle que insertBefore ou removeChild rend le nœud invalide par rapport à \"partial validity\", cette exception serait levée et l'opération ne serait pas effectuée. Ce code est utilisé dans [DOM Level 3 Validation]. Référez-vous à cette spécification pour plus d'informations. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Si un nœud est utilisé dans un document différent de celui qui l'a créé (qui ne le prend pas en charge). |

### Voir aussi

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

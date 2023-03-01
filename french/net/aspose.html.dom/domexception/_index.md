---
title: Class DOMException
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.DOMException classe. Linterface DOMException représente un événement anormal appelé une exception qui se produit à la suite de lappel dune méthode ou de laccès à une propriété dune API Web. Cest essentiellement ainsi que les conditions derreur sont décrites dans les API Web.
type: docs
weight: 640
url: /fr/net/aspose.html.dom/domexception/
---
## DOMException class

L'interface DOMException représente un événement anormal (appelé une exception) qui se produit à la suite de l'appel d'une méthode ou de l'accès à une propriété d'une API Web. C'est essentiellement ainsi que les conditions d'erreur sont décrites dans les API Web.

```csharp
public class DOMException : PlatformException
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | Initialise une nouvelle instance du`DOMException` classe. |
| [DOMException](domexception/#constructor_1)(string, string) | Initialise une nouvelle instance du`DOMException` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | Renvoie une valeur qui contient l'une des constantes de code d'erreur, ou 0 si aucune ne correspond. Ce champ est utilisé pour des raisons historiques. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | Renvoie une chaîne représentant un message ou une description associée au nom d'erreur donné. |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | Renvoie une chaîne contenant l'une des chaînes associées à un nom d'erreur. |

## Des champs

| Nom | La description |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | L'opération a été abandonnée. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | L'objet ne peut pas être cloné. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | Si la plage de texte spécifiée ne rentre pas dans un DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | Si un nœud est inséré quelque part, il n'appartient pas. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | Si l'index ou la taille est négatif ou supérieur à la valeur autorisée. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | En cas de tentative d'ajout d'un attribut déjà utilisé ailleurs. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | Si un paramètre ou une opération n'est pas pris en charge par l'objet sous-jacent. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | Si un caractère invalide ou illégal est spécifié, comme dans un nom XML. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | L'expression a une erreur de syntaxe ou n'est pas une expression légale selon les règles du specific XPathEvaluator ou contient des fonctions d'extension spécialisées ou des variables non prises en charge par cette implémentation. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | En cas de tentative de modification du type de l'objet sous-jacent. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | Le nœud fourni est incorrect ou a un ancêtre incorrect pour cette opération. |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | En cas de tentative d'utilisation d'un objet qui n'est pas ou plus utilisable. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | En cas de tentative de création ou de modification d'un objet d'une manière incorrecte en ce qui concerne les espaces de noms. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | Une erreur réseau s'est produite. |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | Si une tentative est faite pour référencer un nœud dans un contexte où il n'existe pas. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | Si l'implémentation ne prend pas en charge le type d'objet ou d'opération demandé. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | Si des données sont spécifiées pour un nœud qui ne prend pas en charge les données. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | Si une tentative est faite pour modifier un objet où les modifications ne sont pas autorisées. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | Le quota a été dépassé. |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | L'opération n'est pas sécurisée. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | Si une chaîne invalide ou illégale est spécifiée. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | L'opération a expiré. |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | L'expression ne peut pas être convertie pour renvoyer le type spécifié. |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | Si le type d'un objet est incompatible avec le type attendu du paramètre associé à l'objet. |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | L'URL donnée ne correspond pas à une autre URL. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | Si un appel à une méthode telle que insertBefore ou removeChild rendait le Node invalide par rapport à la "validité partielle", cette exception serait levée et l'opération ne serait pas effectuée. Ce code est utilisé dans [DOM Level 3 Validation]. Reportez-vous à cette spécification pour plus d'informations. |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | Si un nœud est utilisé dans un document différent de celui qui l'a créé (qui ne le prend pas en charge). |

### Voir également

* class [PlatformException](../../aspose.html/platformexception/)
* espace de noms [Aspose.Html.Dom](../../aspose.html.dom/)
* Assemblée [Aspose.HTML](../../)



---
title: DOMException
second_title: Referencia de API de Aspose.HTML para .NET
description: La interfaz DOMException representa un evento anormal llamado excepción que ocurre como resultado de llamar a un método o acceder a una propiedad de una API web. Básicamente así es como se describen las condiciones de error en las API web.
type: docs
weight: 650
url: /es/net/aspose.html.dom/domexception/
---
## DOMException class

La interfaz DOMException representa un evento anormal (llamado excepción) que ocurre como resultado de llamar a un método o acceder a una propiedad de una API web. Básicamente, así es como se describen las condiciones de error en las API web.

```csharp
public class DOMException : PlatformException
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DOMException](domexception#constructor)(string) | Inicializa una nueva instancia del[`DOMException`](../domexception) clase. |
| [DOMException](domexception#constructor_1)(string, string) | Inicializa una nueva instancia del[`DOMException`](../domexception) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code) { get; } | Devuelve un valor que contiene una de las constantes del código de error, o 0 si ninguna coincide. Este campo se utiliza por razones históricas. |
| override [Message](../../aspose.html.dom/domexception/message) { get; } | Devuelve una cadena que representa un mensaje o descripción asociada con el nombre de error dado. |
| [Name](../../aspose.html.dom/domexception/name) { get; } | Devuelve una cadena que contiene una de las cadenas asociadas con un nombre de error. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err) | Se anuló la operación. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err) | No se puede clonar el objeto. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err) | Si el rango de texto especificado no cabe en un DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err) | Si se inserta algún Nodo en algún lugar al que no pertenece. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err) | Si el índice o el tamaño es negativo o mayor que el valor permitido. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err) | Si se intenta agregar un atributo que ya está en uso en otro lugar. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err) | Si un parámetro o una operación no es compatible con el objeto subyacente. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err) | Si se especifica un carácter no válido o ilegal, como en un nombre XML. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err) | La expresión tiene un error de sintaxis o no es una expresión legal de acuerdo con las reglas del XPathEvaluator específico o contiene funciones de extensión especializadas o variables no admitidas por esta implementación. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err) | Si se intenta modificar el tipo del objeto subyacente. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err) | El nodo proporcionado es incorrecto o tiene un ancestro incorrecto para esta operación. |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err) | Si se intenta usar un objeto que no es o ya no es usable. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err) | Si se intenta crear o cambiar un objeto de forma incorrecta con respecto a los espacios de nombres. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err) | Ocurrió un error de red. |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err) | Si se intenta referenciar un Nodo en un contexto donde no existe. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err) | Si la implementación no admite el tipo de objeto u operación solicitado. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err) | Si se especifican datos para un nodo que no admite datos. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err) | Si se intenta modificar un objeto donde no se permiten modificaciones. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err) | Se ha excedido la cuota. |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err) | La operación es insegura. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err) | Si se especifica una cadena no válida o ilegal. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err) | Se agotó el tiempo de espera de la operación. |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err) | La expresión no se puede convertir para devolver el tipo especificado. |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err) | Si el tipo de un objeto es incompatible con el tipo esperado del parámetro asociado al objeto. |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err) | La URL dada no coincide con otra URL. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err) | Si una llamada a un método como insertBefore o removeChild hiciera que el nodo no fuera válido con respecto a la "validez parcial", esta excepción se generaría y la operación no se realizaría. Este código se utiliza en [Validación de nivel 3 de DOM]. Consulte esta especificación para obtener más información. |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err) | Si se usa un Nodo en un documento diferente al que lo creó (que no lo soporta). |

### Ver también

* class [PlatformException](../../aspose.html/platformexception)
* espacio de nombres [Aspose.Html.Dom](../../aspose.html.dom)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->

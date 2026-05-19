---
title: "Clase DOMException"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.DOMException. La interfaz DOMException representa un evento anormal llamado excepción que ocurre como resultado de llamar a un método o acceder a una propiedad de una API web. Básicamente, así se describen las condiciones de error en las APIs web."
type: docs

url: /es/java/com.aspose.html.dom/domexception/
---
## DOMException class

La interfaz DOMException representa un evento anormal (llamado excepción) que ocurre como resultado de llamar a un método o acceder a una propiedad de una API web. Básicamente, así se describen las condiciones de error en las APIs web.

```java
public class DOMException : PlatformException
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Inicializa una nueva instancia de la clase `DOMException`. |
| [DOMException](domexception/#constructor_1)(String, String) | Inicializa una nueva instancia de la clase `DOMException`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Devuelve un valor que contiene una de las constantes de código de error, o 0 si ninguna coincide. Este campo se usa por razones históricas. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Devuelve una cadena que representa un mensaje o descripción asociado con el nombre de error dado. |
| [getName](../../com.aspose.html.dom/domexception/name/) Devuelve una cadena que contiene una de las cadenas asociadas con un nombre de error. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | La operación fue abortada. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | El objeto no puede ser clonado. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Si el rango de texto especificado no cabe en un DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Si algún Nodo se inserta en un lugar donde no pertenece. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Si el índice o el tamaño es negativo, o mayor que el valor permitido. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Si se intenta agregar un atributo que ya está en uso en otro lugar. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Si un parámetro o una operación no es compatible con el objeto subyacente. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Si se especifica un carácter inválido o ilegal, como en un nombre XML. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | La expresión tiene un error de sintaxis o de otro modo no es una expresión válida según las reglas del XPathEvaluator específico o contiene funciones de extensión especializadas o variables no compatibles con esta implementación. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Si se intenta modificar el tipo del objeto subyacente. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | El nodo suministrado es incorrecto o tiene un ancestro incorrecto para esta operación. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Si se intenta usar un objeto que no es, o ya no es, utilizable. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Si se intenta crear o modificar un objeto de una manera que es incorrecta con respecto a los paquetes. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Se produjo un error de red. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Si se intenta referenciar un Nodo en un contexto donde no existe. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Si la implementación no admite el tipo de objeto u operación solicitada. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Si se especifican datos para un Nodo que no admite datos. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Si se intenta modificar un objeto donde no se permiten modificaciones. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | Se ha superado la cuota. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | La operación es insegura. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Si se especifica una cadena inválida o ilegal. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | La operación expiró. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | La expresión no se puede convertir para devolver el tipo especificado. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Si el tipo de un objeto es incompatible con el tipo esperado del parámetro asociado al objeto. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | La URL proporcionada no coincide con otra URL. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Si una llamada a un método como insertBefore o removeChild hiciera que el Nodo fuera inválido respecto a la "validez parcial", se lanzaría esta excepción y la operación no se realizaría. Este código se usa en [DOM Level 3 Validation]. Consulte esta especificación para obtener más información. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Si un Nodo se usa en un documento diferente al que lo creó (que no lo admite). |

### Ver también

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

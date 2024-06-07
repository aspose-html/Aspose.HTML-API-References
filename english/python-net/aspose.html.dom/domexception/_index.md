---
title: DOMException class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 50
url: /aspose.html.dom/domexception/
is_root: false
---

## DOMException class

The DOMException interface represents an abnormal event (called an exception) which occurs as a result of calling a method or accessing a property of a web API. This is basically how error conditions are described in web APIs.



**Inheritance:** [`DOMException`](/html/python-net/aspose.html.dom/domexception) → 
[`PlatformException`](/html/python-net/aspose.html/platformexception)



The DOMException type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.dom/domexception/__init__/#str) | Initializes a new instance of the [`DOMException`](/html/python-net/aspose.html.dom/domexception) class. |
| [__init__](/html/python-net/aspose.html.dom/domexception/__init__/#str-str) | Initializes a new instance of the [`DOMException`](/html/python-net/aspose.html.dom/domexception) class. |


### Properties
| Property | Description |
| :- | :- |
| [code](/html/python-net/aspose.html.dom/domexception/code) | Returns a value that contains one of the error code constants, or 0 if none match. This field is used for historical reasons. |
| [name](/html/python-net/aspose.html.dom/domexception/name) | Returns a string that contains one of the strings associated with an error name. |
| [INDEX_SIZE_ERR](/html/python-net/aspose.html.dom/domexception/index_size_err) | If index or size is negative, or greater than the allowed value. |
| [DOMSTRING_SIZE_ERR](/html/python-net/aspose.html.dom/domexception/domstring_size_err) | If the specified range of text does not fit into a DOMString. |
| [HIERARCHY_REQUEST_ERR](/html/python-net/aspose.html.dom/domexception/hierarchy_request_err) | If any Node is inserted somewhere it doesn't belong. |
| [WRONG_DOCUMENT_ERR](/html/python-net/aspose.html.dom/domexception/wrong_document_err) | If a Node is used in a different document than the one that created it (that doesn't support it). |
| [INVALID_CHARACTER_ERR](/html/python-net/aspose.html.dom/domexception/invalid_character_err) | If an invalid or illegal character is specified, such as in an XML name. |
| [NO_DATA_ALLOWED_ERR](/html/python-net/aspose.html.dom/domexception/no_data_allowed_err) | If data is specified for a Node which does not support data. |
| [NO_MODIFICATION_ALLOWED_ERR](/html/python-net/aspose.html.dom/domexception/no_modification_allowed_err) | If an attempt is made to modify an object where modifications are not allowed. |
| [NOT_FOUND_ERR](/html/python-net/aspose.html.dom/domexception/not_found_err) | If an attempt is made to reference a Node in a context where it does not exist. |
| [NOT_SUPPORTED_ERR](/html/python-net/aspose.html.dom/domexception/not_supported_err) | If the implementation does not support the requested type of object or operation. |
| [INUSE_ATTRIBUTE_ERR](/html/python-net/aspose.html.dom/domexception/inuse_attribute_err) | If an attempt is made to add an attribute that is already in use elsewhere. |
| [INVALID_STATE_ERR](/html/python-net/aspose.html.dom/domexception/invalid_state_err) | If an attempt is made to use an object that is not, or is no longer, usable. |
| [SYNTAX_ERR](/html/python-net/aspose.html.dom/domexception/syntax_err) | If an invalid or illegal string is specified. |
| [INVALID_MODIFICATION_ERR](/html/python-net/aspose.html.dom/domexception/invalid_modification_err) | If an attempt is made to modify the type of the underlying object. |
| [NAMESPACE_ERR](/html/python-net/aspose.html.dom/domexception/namespace_err) | If an attempt is made to create or change an object in a way which is incorrect with regard to namespaces. |
| [INVALID_ACCESS_ERR](/html/python-net/aspose.html.dom/domexception/invalid_access_err) | If a parameter or an operation is not supported by the underlying object. |
| [VALIDATION_ERR](/html/python-net/aspose.html.dom/domexception/validation_err) | If a call to a method such as insertBefore or removeChild would make the Node invalid with respect to "partial validity", this exception would be raised and the operation would not be done. This code is used in [DOM Level 3 Validation]. Refer to this specification for further information. |
| [TYPE_MISMATCH_ERR](/html/python-net/aspose.html.dom/domexception/type_mismatch_err) | If the type of an object is incompatible with the expected type of the parameter associated to the object. |
| [SECURITY_ERR](/html/python-net/aspose.html.dom/domexception/security_err) | The operation is insecure. |
| [NETWORK_ERR](/html/python-net/aspose.html.dom/domexception/network_err) | A network error occurred. |
| [ABORT_ERR](/html/python-net/aspose.html.dom/domexception/abort_err) | The operation was aborted. |
| [URL_MISMATCH_ERR](/html/python-net/aspose.html.dom/domexception/url_mismatch_err) | The given URL does not match another URL. |
| [QUOTA_EXCEEDED_ERR](/html/python-net/aspose.html.dom/domexception/quota_exceeded_err) | The quota has been exceeded. |
| [TIMEOUT_ERR](/html/python-net/aspose.html.dom/domexception/timeout_err) | The operation timed out. |
| [INVALID_NODE_TYPE_ERR](/html/python-net/aspose.html.dom/domexception/invalid_node_type_err) | The supplied node is incorrect or has an incorrect ancestor for this operation. |
| [DATA_CLONE_ERR](/html/python-net/aspose.html.dom/domexception/data_clone_err) | The object can not be cloned. |
| [INVALID_EXPRESSION_ERR](/html/python-net/aspose.html.dom/domexception/invalid_expression_err) | The expression has a syntax error or otherwise is not a legal expression according to the rules of the specific<br/>XPathEvaluator or contains specialized extension functions or variables not supported by this implementation. |
| [TYPE_ERR](/html/python-net/aspose.html.dom/domexception/type_err) | The expression cannot be converted to return the specified type. |



### See Also
* module [`aspose.html.dom`](..)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`PlatformException`](/html/python-net/aspose.html/platformexception)

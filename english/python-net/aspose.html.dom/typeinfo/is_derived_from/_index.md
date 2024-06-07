---
title: is_derived_from method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.html.dom/typeinfo/is_derived_from/
is_root: false
---

## is_derived_from {#str-str-int}

This method returns if there is a derivation between the reference type definition, i.e. the TypeInfo on which the method is being called, and the other type definition, i.e. the one passed as parameters.


### Returns 


If the document's schema is a DTD or no schema is associated with the document, this method will always return false. If the document's schema is an XML Schema, the method will true if the reference type definition is derived from the other type definition according to the derivation parameter. If the value of the parameter is 0 (no bit is set to 1 for the derivationMethod parameter), the method will return true if the other type definition can be reached by recursing any combination of {base type definition}, {item type definition}, or {member type definitions} from the reference type definition.


```python
def is_derived_from(self, type_namespace_arg, type_name_arg, derivation_method):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type_namespace_arg | str | the namespace of the other type definition |
| type_name_arg | str | the name of the other type definition. |
| derivation_method | int | the type of derivation and conditions applied between two types, as described in the list of constants provided in this interface. |



### See Also
* module [`aspose.html.dom`](../../)
* class [`TypeInfo`](/html/python-net/aspose.html.dom/typeinfo)

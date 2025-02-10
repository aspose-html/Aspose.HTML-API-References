---
title: IStorage Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.IStorage interface. This interface of the Web Storage API provides access to a particular domains session or local storage. See Web Storage specification https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage
type: docs
weight: 1110
url: /java/com.aspose.html.dom/istorage/
---
## IStorage interface

This interface of the Web Storage API provides access to a particular domain's session or local storage. See Web Storage specification: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Properties

| Name | Description |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Returns the number of key/value pairs. |

## Methods

| Name | Description |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Removes all key/value pairs, if there are any. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Returns the current value associated with the given key, or null if the given key does not exist. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Returns the name of the nth key, or null if n is greater than or equal to the number of key/value pairs. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Removes the key/value pair with the given key, if a key/value pair with the given key exists. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Sets the value of the pair identified by key to value, creating a new key/value pair if none existed for key previously. |

### See Also

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)

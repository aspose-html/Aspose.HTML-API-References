---
title: IFile Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.IO.IFile interface. A File object is a Blob object with a name attribute which is a String it can be created within the web application via a constructor or is a reference to a byte sequence from a file from the underlying OS file system
type: docs
weight: 3740
url: /java/com.aspose.html.io/ifile/
---
## IFile interface

A File object is a Blob object with a name attribute, which is a String; it can be created within the web application via a constructor, or is a reference to a byte sequence from a file from the underlying (OS) file system.

```java
public interface IFile : IBlob
```

## Properties

| Name | Description |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) The last modified date of the file. On getting, if user agents can make this information available, this must return a long long set to the time the file was last modified as the number of milliseconds since the Unix Epoch. |
| [getName](../../com.aspose.html.io/ifile/name/) The name of the file. On getting, this must return the name of the file as a String. |

### See Also

* interface [IBlob](../iblob/)
* package [com.aspose.html.IO](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)

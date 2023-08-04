---
title: License Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.License class. Provides methods to license the component
type: docs
weight: 3830
url: /java/com.aspose.html/license/
---
## License class

Provides methods to license the component.

```java
public class License
```

## Constructors

| Name | Description |
| --- | --- |
| [License](license/)() | Initializes a new instance of this class. |

## Methods

| Name | Description |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Licenses the component. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Licenses the component. |

## Examples

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

the component jar file:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### See Also

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

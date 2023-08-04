---
title: License.SetLicense
second_title: Aspose.HTML for Java API Reference
description: License method. Licenses the component
type: docs
weight: 20
url: /java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Licenses the component.

```java
public void SetLicense(String licenseName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | String | Can be a full or short file name or name of an embedded resource. Use an empty String to switch to evaluation mode. |

## Remarks

Tries to find the license in the following locations:

1. Explicit path.

2. The folder that contains the Aspose component assembly.

3. The folder that contains the client's calling assembly.

4. The folder that contains the entry (startup) assembly.

5. An embedded resource in the client's calling assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit path.

2. An embedded resource in the client's calling assembly.

2. The folder that contains the Aspose component JAR file.

3. The folder that contains the client's calling JAR file.

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

* class [License](../)
* package [com.aspose.html](../../license/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Licenses the component.

```java
public void SetLicense(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream that contains the license. |

## Remarks

Use this method to load a license from a stream.

## Examples

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### See Also

* class [License](../)
* package [com.aspose.html](../../license/)
* package [Aspose.HTML](../../../)

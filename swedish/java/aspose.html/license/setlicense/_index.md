---
title: "License.SetLicense"
second_title: "Aspose.HTML för Java API-referens"
description: "License-metod. Licensierar komponenten"
type: docs

url: /sv/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Licensierar komponenten.

```java
public void SetLicense(String licenseName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | String | Kan vara ett fullständigt eller kort filnamn eller namn på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge. |

## Anmärkningar

Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen som innehåller Aspose-komponentens assembly.

3. Mappen som innehåller klientens anropande assembly.

4. Mappen som innehåller entry (startup)-assemblyn.

5. En inbäddad resurs i klientens anropande assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit sökväg.

2. En inbäddad resurs i klientens anropande assembly.

2. Mappen som innehåller Aspose-komponentens JAR-fil.

3. Mappen som innehåller klientens anropande JAR-fil.

## Exempel

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för startsammanställningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

komponent‑jar‑filen:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Se även

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Licensierar komponenten.

```java
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | En ström som innehåller licensen. |

## Anmärkningar

Använd denna metod för att läsa in en licens från en ström.

## Exempel

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Se även

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

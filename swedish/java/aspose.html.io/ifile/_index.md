---
title: "IFile-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.io.IFile‑gränssnitt. Ett File‑objekt är ett Blob‑objekt med ett name‑attribut som är en String; det kan skapas i webbapplikationen via en konstruktor eller är en referens till en byte‑sekvens från en fil i det underliggande OS‑filsystemet."
type: docs

url: /sv/java/com.aspose.html.io/ifile/
---
## IFile interface

Ett File-objekt är ett Blob-objekt med ett name-attribut, som är en sträng; det kan skapas i webbapplikationen via en konstruktor, eller är en referens till en byte-sekvens från en fil i det underliggande (OS) filsystemet.

```java
public interface IFile : IBlob
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) Det senaste modifieringsdatumet för filen. Vid hämtning, om användaragenter kan göra denna information tillgänglig, måste den returnera ett long long som är satt till tiden då filen senast modifierades som antalet millisekunder sedan Unix‑epoken. |
| [getName](../../com.aspose.html.io/ifile/name/) Filens namn. Vid hämtning måste detta returnera filens namn som en String. |

### Se även

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)

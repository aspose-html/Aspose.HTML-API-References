---
title: "IFile interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.io.IFile interface. Een File-object is een Blob-object met een name‑attribuut dat een String is; het kan binnen de webapplicatie via een constructor worden aangemaakt of is een verwijzing naar een byte‑reeks van een bestand uit het onderliggende OS‑bestandssysteem."
type: docs

url: /nl/java/com.aspose.html.io/ifile/
---
## IFile interface

Een File-object is een Blob-object met een name‑attribuut, dat een String is; het kan binnen de webapplicatie worden aangemaakt via een constructor, of is een verwijzing naar een byte‑reeks uit een bestand van het onderliggende (OS) bestandssysteem.

```java
public interface IFile : IBlob
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) De datum van laatste wijziging van het bestand. Bij ophalen, als user agents deze informatie beschikbaar kunnen maken, moet dit een long long retourneren die is ingesteld op het tijdstip waarop het bestand voor het laatst is gewijzigd, uitgedrukt in milliseconden sinds de Unix‑epoch. |
| [getName](../../com.aspose.html.io/ifile/name/) De naam van het bestand. Bij ophalen moet dit de naam van het bestand retourneren als een String. |

### Zie ook

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)

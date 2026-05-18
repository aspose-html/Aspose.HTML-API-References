---
title: "IFile Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.io.IFile Schnittstelle. Ein File-Objekt ist ein Blob-Objekt mit einem Namensattribut, das ein String ist; es kann innerhalb der Webanwendung über einen Konstruktor erstellt werden oder ist ein Verweis auf eine Bytesequenz aus einer Datei des zugrunde liegenden Betriebssystem-Dateisystems."
type: docs

url: /de/java/com.aspose.html.io/ifile/
---
## IFile interface

Ein File‑Objekt ist ein Blob‑Objekt mit einem Namensattribut, das ein String ist; es kann innerhalb der Webanwendung über einen Konstruktor erstellt werden oder ist ein Verweis auf eine Byte‑Sequenz aus einer Datei des zugrunde liegenden (OS‑)Dateisystems.

```java
public interface IFile : IBlob
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) Das Datum der letzten Änderung der Datei. Beim Abrufen, falls User Agents diese Information bereitstellen können, muss ein long long zurückgegeben werden, das auf die Zeit gesetzt ist, zu der die Datei zuletzt geändert wurde, angegeben als Anzahl der Millisekunden seit dem Unix-Epoch. |
| [getName](../../com.aspose.html.io/ifile/name/) Der Name der Datei. Beim Abrufen muss dieser den Namen der Datei als String zurückgeben. |

### Siehe auch

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)

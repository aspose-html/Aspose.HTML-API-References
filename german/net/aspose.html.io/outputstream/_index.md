---
title: Class OutputStream
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.IO.OutputStream klas. Ein SurrogatStream umschließt den echten Ausgabestream und steuert den Zugriff darauf. OutputStream enthält URIDaten die den Speicherort des Ausgabestreams beschreiben.
type: docs
weight: 3750
url: /de/net/aspose.html.io/outputstream/
---
## OutputStream class

Ein Surrogat-Stream umschließt den echten Ausgabestream und steuert den Zugriff darauf. `OutputStream` enthält URI-Daten, die den Speicherort des Ausgabestreams beschreiben.

```csharp
public class OutputStream : Stream
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | Initialisiert eine neue Instanz von`OutputStream` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | Ruft einen Wert ab, der angibt, ob der umschlossene Ausgabestream das Lesen unterstützt. |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | Ruft einen Wert ab, der angibt, ob der umschlossene Ausgabestream die Suche unterstützt. |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | Ruft einen Wert ab, der angibt, ob der umschlossene Ausgabestream das Schreiben unterstützt. |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | Ruft die Länge des verpackten Ausgabestroms in Byte ab. |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | Ruft die Position innerhalb des umschlossenen Ausgabestroms ab oder legt sie fest. |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | Ruft den URI des Stream-Speicherorts ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | Schließt den umschlossenen Ausgabestream und den aktuellen Stream. |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | Löscht alle Puffer für den verpackten Ausgabestrom und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | Liest eine Folge von Bytes aus dem umschlossenen Ausgabestream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes. |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | Legt die Position innerhalb des umschlossenen Ausgabestreams fest. |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | Legt die Länge des umschlossenen Ausgabestreams fest. |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | Schreibt eine Folge von Bytes in den umschlossenen output Stream und erhöht die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |

### Siehe auch

* namensraum [Aspose.Html.IO](../../aspose.html.io/)
* Montage [Aspose.HTML](../../)



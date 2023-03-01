---
title: Class License
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.License classe. Fornisce metodi per concedere in licenza il componente.
type: docs
weight: 3810
url: /it/net/aspose.html/license/
---
## License class

Fornisce metodi per concedere in licenza il componente.

```csharp
public class License
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [License](license/)() | Inizializza una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense)(Stream) | Concede in licenza il componente. |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense_1)(string) | Concede in licenza il componente. |

### Esempi

In questo esempio, verrà effettuato un tentativo di trovare un file di licenza denominato MyLicense.lic nella cartella che contiene  il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di entrata e poi nelle risorse embedded dell'assembly chiamante.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

il file jar del componente:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Guarda anche

* spazio dei nomi [Aspose.Html](../../aspose.html/)
* assemblea [Aspose.HTML](../../)



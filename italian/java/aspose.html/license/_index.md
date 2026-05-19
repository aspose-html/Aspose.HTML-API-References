---
title: "License Classe"
second_title: "Riferimento API Aspose.HTML per Java"
description: "com.aspose.html.License classe. Fornisce metodi per licenziare il componente"
type: docs

url: /it/java/com.aspose.html/license/
---
## License class

Fornisce metodi per licenziare il componente.

```java
public class License
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [License](license/)() | Inizializza una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Licenzia il componente. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Licenzia il componente. |

## Esempi

In questo esempio, si cercherà di trovare un file di licenza denominato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

il file jar del componente:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Vedi anche

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

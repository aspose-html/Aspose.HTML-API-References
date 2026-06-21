---
title: "License.SetLicense"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo License. Concede la licenza al componente"
type: docs

url: /it/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Licenzia il componente.

```java
public void SetLicense(String licenseName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | String | Può essere un nome file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

## Osservazioni

Cerca di trovare la licenza nei seguenti percorsi:

1. Percorso esplicito.

2. La cartella che contiene l'assembly del componente Aspose.

3. La cartella che contiene l'assembly chiamante del client.

4. La cartella che contiene l'assembly di ingresso (avvio).

5. Una risorsa incorporata nell'assembly chiamante del client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Percorso esplicito.

2. Una risorsa incorporata nell'assembly chiamante del client.

2. La cartella che contiene il file JAR del componente Aspose.

3. La cartella che contiene il file JAR chiamante del client.

## Esempi

In questo esempio, si cercherà di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.

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

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Licenzia il componente.

```java
public void SetLicense(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Uno stream che contiene la licenza. |

## Osservazioni

Usa questo metodo per caricare una licenza da uno stream.

## Esempi

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Vedi anche

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

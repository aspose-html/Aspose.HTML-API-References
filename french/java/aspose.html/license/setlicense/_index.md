---
title: "License.SetLicense"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode License. Licence le composant"
type: docs

url: /fr/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Licence le composant.

```java
public void SetLicense(String licenseName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | String | Peut être un nom de fichier complet ou court ou le nom d'une ressource incorporée. Utilisez une chaîne vide pour passer en mode d'évaluation. |

## Remarques

Essaie de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier contenant l'assembly du composant Aspose.

3. Le dossier contenant l'assembly appelant du client.

4. Le dossier contenant l'assembly d'entrée (démarrage).

5. Une ressource incorporée dans l'assembly appelant du client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Chemin explicite.

2. Une ressource incorporée dans l'assembly appelant du client.

2. Le dossier contenant le fichier JAR du composant Aspose.

3. Le dossier contenant le fichier JAR appelant du client.

## Exemples

Dans cet exemple, une tentative sera effectuée pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

le fichier JAR du composant :

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Voir aussi

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Licence le composant.

```java
public void SetLicense(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Un flux qui contient la licence. |

## Remarques

Utilisez cette méthode pour charger une licence à partir d'un flux.

## Exemples

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Voir aussi

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

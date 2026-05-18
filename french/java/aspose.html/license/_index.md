---
title: "Classe License"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.License. Fournit des méthodes pour licencier le composant"
type: docs

url: /fr/java/com.aspose.html/license/
---
## License class

Fournit des méthodes pour licencier le composant.

```java
public class License
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [License](license/)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Licence le composant. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Licence le composant. |

## Exemples

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

le fichier JAR du composant :

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Voir aussi

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

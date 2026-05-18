---
title: "Licence"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Constructeur de Licence. Initialise une nouvelle instance de cette classe"
type: docs

url: /fr/java/com.aspose.html/license/license/
---
## License constructor

Initialise une nouvelle instance de cette classe.

```java
public License()
```

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

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

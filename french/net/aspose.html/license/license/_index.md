---
title: License.License
second_title: Référence de l'API Aspose.HTML pour .NET
description: License constructeur. Initialise une nouvelle instance de cette classe.
type: docs
weight: 10
url: /fr/net/aspose.html/license/license/
---
## License constructor

Initialise une nouvelle instance de cette classe.

```csharp
public License()
```

### Exemples

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier qui contient  le composant, dans le dossier qui contient l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources embarquées de l'assembly appelant.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

le fichier jar du composant :

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Voir également

* class [License](../)
* espace de noms [Aspose.Html](../../license/)
* Assemblée [Aspose.HTML](../../../)



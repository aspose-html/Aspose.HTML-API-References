---
title: Class Metered
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Metered classe. Fournit des méthodes pour définir la clé mesurée.
type: docs
weight: 3830
url: /fr/net/aspose.html/metered/
---
## Metered class

Fournit des méthodes pour définir la clé mesurée.

```csharp
public class Metered
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Metered](metered/)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | Définit la clé publique et privée mesurée. Si vous achetez une licence mesurée, lorsque vous démarrez l'application, cette API doit être appelée, normalement, cela suffit. Cependant, si vous ne parvenez toujours pas à télécharger les données de consommation et dépassez 24 heures, la licence sera définie sur le statut d'évaluation, pour éviter un tel cas, vous devez vérifier régulièrement le statut de la licence, s'il s'agit du statut d'évaluation, appelez à nouveau cette API. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | Obtient un crédit de consommation |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | Obtient la taille du fichier de consommation |

### Exemples

Dans cet exemple, une tentative sera faite pour définir des clés publiques et privées mesurées

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

le fichier jar du composant :

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Voir également

* espace de noms [Aspose.Html](../../aspose.html/)
* Assemblée [Aspose.HTML](../../)



---
title: "Classe Metered"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.Metered. Fournit des méthodes pour définir la clé mesurée"
type: docs

url: /fr/java/com.aspose.html/metered/
---
## Metered class

Fournit des méthodes pour définir la clé mesurée.

```java
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered/)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Définit la clé publique et privée mesurée. Si vous achetez une licence mesurée, lors du démarrage de l'application, cette API doit être appelée, normalement cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation ; pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, et si elle est en statut d'évaluation, appeler à nouveau cette API. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Obtient le crédit de consommation |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Obtient la taille du fichier de consommation |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Vérifier si le mode mesuré est licencié |

## Exemples

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée du mode mesuré

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

le fichier JAR du composant :

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Voir aussi

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

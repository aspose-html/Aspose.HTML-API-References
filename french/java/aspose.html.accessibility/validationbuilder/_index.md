---
title: "ValidationBuilder Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.accessibility.ValidationBuilder classe. La classe ValidationBuilder fournit des implémentations concrètes des étapes de configuration. Définit les méthodes et les paramètres pour la classe ValidationSettings"
type: docs

url: /fr/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

La classe ValidationBuilder fournit des implémentations concrètes des étapes de configuration. Définit les méthodes et les paramètres pour la classe ValidationSettings.

```java
public class ValidationBuilder
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) Inclut tous les niveaux et tous les paramètres de technologies |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) Paramètres par défaut : seules les technologies Générales sont utilisées et pour le niveau de critère le plus bas |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) Paramètres Aucun - aucun des paramètres n'est spécifié. |

## Méthodes

| Nom | Description |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | Une méthode qui définit tous les niveaux de critères. Et indique que le document sera vérifié selon les critères des trois niveaux. |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | Une méthode qui définit toutes les technologies pour tester le critère |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | Liste des balises html à vérifier. Si les balises ne sont pas spécifiées explicitement, alors le tableau de balises est vide et la vérification passe à toutes. |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | Une méthode qui inclut les technologies CSS dans un ensemble de règles |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | Une méthode qui inclut les Échecs dans un ensemble de règles |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | Une méthode qui inclut les technologies Générales dans un ensemble de règles |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Utiliser le niveau le plus élevé AAA du critère dans les règles |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | Une méthode qui inclut les technologies HTML dans un ensemble de règles |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Utiliser le niveau le plus bas A du critère dans les règles |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Utiliser le niveau moyen AA du critère dans les règles |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | Une méthode qui inclut les technologies ClientSideScript dans un ensemble de règles |

### Voir aussi

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)

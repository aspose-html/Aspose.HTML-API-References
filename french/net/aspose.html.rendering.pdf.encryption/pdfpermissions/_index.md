---
title: Enum PdfPermissions
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions énumération. Cette énumération représente les autorisations de lutilisateur pour un pdf.
type: docs
weight: 4420
url: /fr/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Cette énumération représente les autorisations de l'utilisateur pour un pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| PrintDocument | `4` | (gestionnaires de sécurité de la révision 2) Imprimez le document. (Gestionnaires de sécurité de révision 3 ou supérieure) Imprimez le document (éventuellement pas au niveau de qualité le plus élevé, selon que PrintingQuality est également défini). |
| ModifyContent | `8` | Modifier le contenu du document par des opérations autres que celles contrôlées par ModifyTextAnnotations, FillForm et 11. |
| ExtractContent | `10` | Gestionnaires de sécurité de la révision 2) Copier ou extraire le texte et les graphiques du document, y compris l'extraction de texte et de graphiques (pour faciliter l'accessibilité aux utilisateurs handicapés ou à d'autres fins). (Gestionnaires de sécurité de la révision 3 ou supérieure) Copier ou autrement extraire du texte et des graphiques du document par des opérations autres que celles contrôlées par ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Ajoutez ou modifiez des annotations de texte, remplissez des champs de formulaire interactifs et, si ModifyContent est également défini, créez ou modifiez des champs de formulaire interactifs (y compris des champs de signature). |
| FillForm | `100` | (Gestionnaires de sécurité de révision 3 ou supérieure) Remplissez les champs de formulaire interactifs existants (y compris les champs de signature), même si ModifyTextAnnotations est clair. |
| ExtractContentWithDisabilities | `200` | (Gestionnaires de sécurité de révision 3 ou supérieure) Extraire du texte et des graphiques (pour faciliter l'accessibilité aux utilisateurs handicapés ou à d'autres fins). |
| AssembleDocument | `400` | (Gestionnaires de sécurité de révision 3 ou supérieure) Assemblez le document (insérez, faites pivoter ou supprimez des pages et créez des signets ou des images miniatures), même si ModifyContent est clair. |
| PrintingQuality | `800` | (Gestionnaires de sécurité de la révision 3 ou supérieure) Imprimez le document dans une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit 3 est défini), l'impression est limitée à un faible -représentation au niveau de l'apparence, éventuellement de qualité dégradée. |

### Voir également

* espace de noms [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* Assemblée [Aspose.HTML](../../)



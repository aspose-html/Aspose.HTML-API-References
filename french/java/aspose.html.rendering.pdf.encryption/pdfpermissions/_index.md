---
title: "PdfPermissions Enum"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions enum. Cet enum représente les autorisations des utilisateurs pour un PDF."
type: docs

url: /fr/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Cette énumération représente les permissions de l'utilisateur pour un PDF.

```java
[Flags]
public enum PdfPermissions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| PrintDocument | `4` | (Gestionnaires de sécurité de la révision 2) Imprimer le document. (Gestionnaires de sécurité de la révision 3 ou supérieure) Imprimer le document (possiblement pas au niveau de qualité le plus élevé, selon que PrintingQuality est également défini). |
| ModifyContent | `8` | Modifier le contenu du document par des opérations autres que celles contrôlées par ModifyTextAnnotations, FillForm et 11. |
| ExtractContent | `10` | (Gestionnaires de sécurité de la révision 2) Copier ou extraire autrement le texte et les graphiques du document, y compris l'extraction du texte et des graphiques (dans le cadre de l'accessibilité pour les utilisateurs en situation de handicap ou à d'autres fins). (Gestionnaires de sécurité de la révision 3 ou supérieure) Copier ou extraire autrement le texte et les graphiques du document par des opérations autres que celles contrôlées par ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Ajouter ou modifier des annotations de texte, remplir les champs de formulaire interactifs et, si ModifyContent est également défini, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature). |
| FillForm | `100` | (Gestionnaires de sécurité de la révision 3 ou supérieure) Remplir les champs de formulaire interactifs existants (y compris les champs de signature), même si ModifyTextAnnotations est désactivé. |
| ExtractContentWithDisabilities | `200` | (Gestionnaires de sécurité de la révision 3 ou supérieure) Extraire le texte et les graphiques (dans le cadre de l'accessibilité pour les utilisateurs en situation de handicap ou à d'autres fins). |
| AssembleDocument | `400` | (Gestionnaires de sécurité de la révision 3 ou supérieure) Assembler le document (insérer, faire pivoter ou supprimer des pages et créer des signets ou des images miniatures), même si ModifyContent est désactivé. |
| PrintingQuality | `800` | (Gestionnaires de sécurité de la révision 3 ou supérieure) Imprimer le document vers une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit 3 est activé), l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée. |

### Voir aussi

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)

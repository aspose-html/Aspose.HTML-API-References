---
title: Class Dimension
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Drawing.Dimension classe. Fournit la classe de base pour les dimensions. Le terme général dimension fait référence à un nombre avec une unité qui lui est attachée et sont désignés parUnitType .
type: docs
weight: 2660
url: /fr/net/aspose.html.drawing/dimension/
---
## Dimension class

Fournit la classe de base pour les dimensions. Le terme général "dimension" fait référence à un nombre avec une unité qui lui est attachée, et sont désignés par[`UnitType`](../unittype/) .

```csharp
public abstract class Dimension : Numeric
```

## Propriétés

| Nom | La description |
| --- | --- |
| [UnitType](../../aspose.html.drawing/unit/unittype/) { get; } | Obtient le type d'unité du[`Unit`](../unit/) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [CompareTo](../../aspose.html.drawing/numeric/compareto/)(Numeric) | Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou apparaît à la même position dans l'ordre de tri que l'autre objet. |
| override [Equals](../../aspose.html.drawing/unit/equals/)(object) | Détermine si la valeur spécifiéeObject , est égal à cette instance. |
| override [Equals](../../aspose.html.drawing/numeric/equals/)(Unit) | Détermine si la valeur spécifiée[`Unit`](../unit/) , est égal à cette instance. |
| override [GetHashCode](../../aspose.html.drawing/numeric/gethashcode/)() | Renvoie un code de hachage pour cette instance. |
| [GetValue](../../aspose.html.drawing/numeric/getvalue/)() | Obtient la valeur unitaire. |
| [GetValue](../../aspose.html.drawing/numeric/getvalue/)(UnitType) | Obtient la valeur convertie en valeur spécifiée[`UnitType`](../unittype/) . |
| override [ToString](../../aspose.html.drawing/dimension/tostring/)() | Renvoie unString qui représente cette instance. |

### Voir également

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* espace de noms [Aspose.Html.Drawing](../../aspose.html.drawing/)
* Assemblée [Aspose.HTML](../../)



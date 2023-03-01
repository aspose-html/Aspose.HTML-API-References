---
title: IWindow.Opener
second_title: Référence de l'API Aspose.HTML pour .NET
description: IWindow propriété. Lattribut IDL opener sur lobjet Window lors de lobtention doit retourner lobjet WindowProxy du contexte de navigation à partir duquel le contexte de navigation courant a été créé son contexte de navigation opener sil y en a un sil est toujours disponible et si le contexte de navigation actuel na pas renié son ouvreur  sinon il doit retourner null. Au paramétrage si la nouvelle valeur est nulle alors le contexte de navigation courant doit renier son ouvreur  si la nouvelle valeur est autre chose lagent utilisateur doit appeler la méthode interne DefineOwnProperty de lobjet Window en transmettant le nom de la propriété opener comme clé de propriété et le Property Descriptor  Value value  Writable  true Enumerable  true Configurable  true  comme descripteur de propriété où value est la nouvelle valeur.
type: docs
weight: 50
url: /fr/net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

L'attribut IDL opener sur l'objet Window, lors de l'obtention, doit retourner l'objet WindowProxy du contexte de navigation à partir duquel le contexte de navigation courant a été créé (son contexte de navigation opener), s'il y en a un, s'il est toujours disponible, et si le contexte de navigation actuel n'a pas renié son ouvreur ; sinon, il doit retourner null. Au paramétrage, si la nouvelle valeur est nulle alors le contexte de navigation courant doit renier son ouvreur ; si la nouvelle valeur est autre chose, l'agent utilisateur doit appeler la méthode interne [[DefineOwnProperty]] de l'objet Window, en transmettant le nom de la propriété "opener" comme clé de propriété, et le Property Descriptor { [[Value]]: value , [[Writable]] : true, [[Enumerable]] : true, [[Configurable]] : true } comme descripteur de propriété, où value est la nouvelle valeur.

```csharp
public IWindow Opener { get; }
```

### Valeur de la propriété

L'ouvreur.

### Voir également

* interface [IWindow](../)
* espace de noms [Aspose.Html.Window](../../iwindow/)
* Assemblée [Aspose.HTML](../../../)



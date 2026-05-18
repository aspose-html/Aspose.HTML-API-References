---
title: "IWindow.Opener"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété IWindow. L'attribut IDL opener sur l'objet Window, lors de la lecture, doit renvoyer l'objet WindowProxy du contexte de navigation à l'origine du contexte de navigation actuel (son contexte de navigation d'ouverture) s'il existe, s'il est encore disponible et si le contexte de navigation actuel n'a pas renoncé à son ouvreur ; sinon il doit renvoyer null. Lors de l'écriture, si la nouvelle valeur est null, le contexte de navigation actuel doit renoncer à son ouvreur ; si la nouvelle valeur est autre, l'agent utilisateur doit appeler la méthode interne DefineOwnProperty de l'objet Window en passant le nom de propriété \"opener\" comme clé de propriété et le Descripteur de Propriété { Value: value, Writable: true, Enumerable: true, Configurable: true } comme descripteur, où value est la nouvelle valeur."
type: docs

url: /fr/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

L'attribut IDL opener sur l'objet Window, lors de la lecture, doit renvoyer l'objet WindowProxy du contexte de navigation à partir duquel le contexte de navigation actuel a été créé (son contexte de navigation d'ouverture), s'il existe, s'il est encore disponible, et si le contexte de navigation actuel n'a pas renoncé à son ouvreur ; sinon il doit renvoyer null. Lors de l'écriture, si la nouvelle valeur est null, le contexte de navigation actuel doit renoncer à son ouvreur ; si la nouvelle valeur est autre, l'agent utilisateur doit appeler la méthode interne [[DefineOwnProperty]] de l'objet Window, en passant le nom de propriété "opener" comme clé de propriété, et le Descripteur de Propriété { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } comme descripteur, où value est la nouvelle valeur.

```java
public IWindow Opener { get; }
```

### Property Value

L'ouvreur.

### Voir aussi

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)

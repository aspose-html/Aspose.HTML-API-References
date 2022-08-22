---
title: Navigate
second_title: Référence de l'API Aspose.HTML pour .NET
description: Charge le document à lURL Uniform Resource Locator spécifiée dans linstance actuelle en remplaçant le contenu précédent.
type: docs
weight: 1010
url: /fr/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

Charge le document à l'URL (Uniform Resource Locator) spécifiée dans l'instance actuelle, en remplaçant le contenu précédent.

```csharp
public void Navigate(string address)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| address | String | L'adresse du document. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |

### Voir également

* class [Document](../../document)
* espace de noms [Aspose.Html.Dom](../../document)
* Assemblée [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Charge le document à l'URL (Uniform Resource Locator) spécifiée dans l'instance actuelle, en remplaçant le contenu précédent.

```csharp
public void Navigate(Url url)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | L'URL du document. |

### Voir également

* class [Url](../../../aspose.html/url)
* class [Document](../../document)
* espace de noms [Aspose.Html.Dom](../../document)
* Assemblée [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

Charge le document à partir du contenu spécifié et utilise baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent.

```csharp
public void Navigate(string content, string baseUri)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| content | String | Le contenu des documents. |
| baseUri | String | L'URI de base pour résoudre les ressources relatives. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` est`nul`. |

### Voir également

* class [Document](../../document)
* espace de noms [Aspose.Html.Dom](../../document)
* Assemblée [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

Charge le document à partir du contenu spécifié et utilise baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent.

```csharp
public void Navigate(string content, Url baseUri)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| content | String | Le contenu des documents. |
| baseUri | Url | L'URI de base pour résoudre les ressources relatives. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` est`nul`. |

### Voir également

* class [Url](../../../aspose.html/url)
* class [Document](../../document)
* espace de noms [Aspose.Html.Dom](../../document)
* Assemblée [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

Charge le document à partir du contenu spécifié et utilise baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. Le chargement du document commence à partir de la position actuelle dans le flux.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| content | Stream | Le contenu des documents. |
| baseUri | String | L'URI de base pour résoudre les ressources relatives. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` est`nul`. |

### Voir également

* class [Document](../../document)
* espace de noms [Aspose.Html.Dom](../../document)
* Assemblée [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Charge le document à partir du contenu spécifié et utilise baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. Le chargement du document commence à partir de la position actuelle dans le flux.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| content | Stream | Le contenu des documents. |
| baseUri | Url | L'URI de base pour résoudre les ressources relatives. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` est`nul`. |

### Voir également

* class [Url](../../../aspose.html/url)
* class [Document](../../document)
* espace de noms [Aspose.Html.Dom](../../document)
* Assemblée [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Charge le document en fonction de l'objet de requête spécifié, en remplaçant le contenu précédent.

```csharp
public void Navigate(RequestMessage request)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| request | RequestMessage | Objet de requête utilisé pour charger le contenu du document. |

### Voir également

* class [RequestMessage](../../../aspose.html.net/requestmessage)
* class [Document](../../document)
* espace de noms [Aspose.Html.Dom](../../document)
* Assemblée [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->

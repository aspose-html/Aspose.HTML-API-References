---
title: "Document.Navigate"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. Charge le document à l’URL Uniform Resource Locator spécifiée dans l’instance actuelle en remplaçant le contenu précédent."
type: docs

url: /fr/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Charge le document à l'Uniform Resource Locator (URL) spécifié dans l'instance actuelle, en remplaçant le contenu précédent.

```java
public void Navigate(String address)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| adresse | String | L’adresse du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |

### Voir aussi

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Charge le document à l'Uniform Resource Locator (URL) spécifié dans l'instance actuelle, en remplaçant le contenu précédent.

```java
public void Navigate(Url url)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | L'URL du document. |

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Charge le document à partir du contenu spécifié en utilisant baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent.

```java
public void Navigate(String content, String baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Le contenu du document. |
| baseUri | String | L’URI de base pour résoudre les ressources relatives. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` est `null`. |

### Voir aussi

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Charge le document à partir du contenu spécifié en utilisant baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent.

```java
public void Navigate(String content, Url baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Le contenu du document. |
| baseUri | Url | L’URI de base pour résoudre les ressources relatives. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` est `null`. |

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Charge le document à partir du contenu spécifié en utilisant baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. Le chargement du document commence à la position actuelle dans le flux.

```java
public void Navigate(Stream content, String baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | Flux | Le contenu du document. |
| baseUri | String | L’URI de base pour résoudre les ressources relatives. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` est `null`. |

### Voir aussi

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Charge le document à partir du contenu spécifié en utilisant baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. Le chargement du document commence à la position actuelle dans le flux.

```java
public void Navigate(Stream content, Url baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | Flux | Le contenu du document. |
| baseUri | Url | L’URI de base pour résoudre les ressources relatives. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` est `null`. |

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Charge le document en fonction de l'objet de requête spécifié, en remplaçant le contenu précédent.

```java
public void Navigate(RequestMessage request)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| requête | RequestMessage | L’objet request utilisé pour charger le contenu du document. |

### Voir aussi

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

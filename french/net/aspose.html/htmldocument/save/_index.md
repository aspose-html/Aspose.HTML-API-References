---
title: HTMLDocument.Save
second_title: Référence de l'API Aspose.HTML pour .NET
description: HTMLDocument méthode. Enregistre le document dans le fichier local spécifié parURL Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent dont le nom sera construit comme  output_file_name  _files.
type: docs
weight: 130
url: /fr/net/aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Enregistre le document dans le fichier local spécifié par`URL` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(Url url)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`URL` n'est pas une URL de fichier local valide. |

### Voir également

* class [Url](../../url/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

Enregistre le contenu et les ressources du document dans le stockage de sortie.

```csharp
public void Save(IOutputStorage outputStorage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStorage | IOutputStorage | Le stockage de sortie[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |

### Voir également

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(string) {#save_10}

Enregistre le document dans le fichier local spécifié par`chemin` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès local au fichier de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`chemin` n'est pas un chemin de fichier local valide. |

### Voir également

* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveFormat) {#save_11}

Enregistre le document dans le fichier local spécifié par`chemin` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès local au fichier de sortie. |
| saveFormat | HTMLSaveFormat | Format dans lequel le document est enregistré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`chemin` n'est pas un chemin de fichier local valide. |

### Voir également

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Enregistre le document dans le fichier local spécifié par`URL` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |
| saveFormat | HTMLSaveFormat | Format dans lequel le document est enregistré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`URL` n'est pas une URL de fichier local valide. |

### Voir également

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveFormat) {#save_1}

Enregistre le contenu et les ressources du document dans le stockage de sortie.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveFormat saveFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStorage | IOutputStorage | Le stockage de sortie[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | HTMLSaveFormat | Format dans lequel le document est enregistré. |

### Voir également

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveOptions) {#save_12}

Enregistre le document dans le fichier local spécifié par`chemin` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès local au fichier de sortie. |
| saveOptions | HTMLSaveOptions | Options d'enregistrement HTML. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`chemin` n'est pas un chemin de fichier local valide. |

### Voir également

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Enregistre le document dans le fichier local spécifié par`URL` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |
| saveOptions | HTMLSaveOptions | Options d'enregistrement HTML. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`URL` n'est pas une URL de fichier local valide. |

### Voir également

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveOptions) {#save_2}

Enregistre le contenu et les ressources du document dans le stockage de sortie.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStorage | IOutputStorage | Le stockage de sortie[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | HTMLSaveOptions | Options d'enregistrement HTML. |

### Voir également

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(string, MarkdownSaveOptions) {#save_13}

Enregistre le document dans le fichier local spécifié par`chemin` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès local au fichier de sortie. |
| saveOptions | MarkdownSaveOptions | Options de sauvegarde Markdown. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`chemin` n'est pas un chemin de fichier local valide. |

### Voir également

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Enregistre le document dans le fichier local spécifié par`URL` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |
| saveOptions | MarkdownSaveOptions | Options de sauvegarde Markdown. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`URL` n'est pas une URL de fichier local valide. |

### Voir également

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MarkdownSaveOptions) {#save_3}

Enregistre le contenu et les ressources du document dans le stockage de sortie.

```csharp
public void Save(IOutputStorage outputStorage, MarkdownSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStorage | IOutputStorage | Le stockage de sortie[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MarkdownSaveOptions | Options de sauvegarde Markdown. |

### Voir également

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(string, MHTMLSaveOptions) {#save_14}

Enregistre le document dans le fichier local spécifié par`chemin` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès local au fichier de sortie. |
| saveOptions | MHTMLSaveOptions | Options d'enregistrement MHTML. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`chemin` n'est pas un chemin de fichier local valide. |

### Voir également

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Enregistre le document dans le fichier local spécifié par`URL` Toutes les ressources utilisées dans ce document seront enregistrées dans dans le dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |
| saveOptions | MHTMLSaveOptions | Options d'enregistrement MHTML. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Déclenché si le spécifié`URL` n'est pas une URL de fichier local valide. |

### Voir également

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MHTMLSaveOptions) {#save_4}

Enregistre le contenu et les ressources du document dans le stockage de sortie.

```csharp
public void Save(IOutputStorage outputStorage, MHTMLSaveOptions saveOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStorage | IOutputStorage | Le stockage de sortie[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MHTMLSaveOptions | Options d'enregistrement MHTML. |

### Voir également

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* espace de noms [Aspose.Html](../../htmldocument/)
* Assemblée [Aspose.HTML](../../../)



---
title: "Classe Configuration"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.Configuration. Représente l'objet de contexte de configuration utilisé pour définir les paramètres d'environnement de l'application. En gérant la configuration, vous pouvez remplacer le style du document en appliquant une feuille de style utilisateur personnalisée ou gérer toutes les requêtes web de l'application ainsi que configurer la politique des scripts. Les détails sont dans le guide Configuration de l'environnement"
type: docs

url: /fr/java/com.aspose.html/configuration/
---
## Configuration class

Représente l'objet de contexte de configuration utilisé pour définir les paramètres d'environnement de l'application. En gérant la configuration, vous pouvez remplacer le style du document en appliquant une feuille de style utilisateur personnalisée, ou gérer les requêtes web de l'application ainsi que configurer la politique des scripts. Les détails sont dans le [guide de configuration de l'environnement](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Configuration](configuration/)() | Initialise une nouvelle instance de la `class`. |

## Propriétés

| Nom | Description |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Créez et configurez l'instance de l'objet Configuration. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Créez et configurez l'instance de l'objet Configuration. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Obtient le service demandé. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Obtient le service demandé. |

## Remarques

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Ce gestionnaire de messages affiche un message concernant le début et la fin du traitement de la requête
    public class LogMessageHandler : MessageHandler
    {
      // Redéfinissez la méthode Invoke()
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Appelez le gestionnaire de messages suivant dans la chaîne
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Créer une instance de la classe Configuration
      using var configuration = new Configuration();

      // Ajouter le LogMessageHandler à la chaîne des gestionnaires de messages existants
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Préparer le chemin vers un fichier de document source
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Initialiser un document HTML avec la configuration spécifiée
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.net;
import com.aspose.html.saving;
import com.aspose.html.services;
import System;
import System.Collections.Generic;
import System.IO;
import System.Net;
import System.Text;

public void SandboxingSample()
    {
      // Préparez le code HTML et enregistrez-le dans un fichier
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Créer une instance de Configuration
      using (var configuration = new Configuration())
      {
        // Marquer 'scripts' comme une ressource non fiable
        configuration.Security |= Sandbox.Scripts;

        // Initialiser un document HTML avec la configuration spécifiée
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // Convertir HTML en PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### Voir aussi

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)

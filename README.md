# Table 2
## Developper tools - dotnet CLI & git CLI

### ⏱ 15' 

### 🃏 NO INTERNET SEARCH

### Votre mission
🔨 Votre mission (je vous passe le "toute fois si vous l'acceptez", ou pas) est de créer/versionner/héberger le code source d'un nouveau projet .NET à l'aide des différentes CLIs (Command Line Interfaces).

Connaissez-vous le CLI dotnet, le CLI github, et le CLI git ?

#### Pour vous aidez à démarrer, voici 3 clés ! (rappel : recherches internet non autorisée)

🔑 ```dotnet --help```

🔑 ```gh --help```

🔑 ```git --help```

⭐⭐⭐ Les différents outils CLIs sont déjà installés sur la machine (dotnet --help, gh --help, git --help)

⭐⭐⭐ Un compte github est déjà mappé localement, votre publication se fera donc automatiquement. 

---


### 💻 Let's code !
### Instructions détaillées:
- Créez un repository GitHub qui porte le nom de votre équipe (sans créer de folder en local)
- Créez un projet .NET de type "console", avec le language "C#", qui porte le nom de votre équipe.
- Initialisez votre projet en tant que repo git
- Stagez vos changements en cours
- Créez un commit avec le message "Création de mon projet à l'aide des CLIs"
- Initialisez votre mapping de repo en publiant avec la commande suivante ```git remote add origin https://github.com/Torreele/{nom-de-votre-repo}.git``` 

**Bonus**
- Créez un fichier README.md à l'aide de la commande ```"echo "" > README.md```
- Le première ligne du fichier contient le titre de votre projet avec un style "titre 1"
- Stagez votre ajout de vos modifications
- Créez un commit avec le message "Ajout README.md"
- Publiez

---

### Discussion ouverte
Qu'avez-vous pensé de cette expérience?
- Etait-ce plus rapide que d'ouvrir les différentes GUI (Visual Studio, GitHub, git)?
- Quel est votre ressenti après avoir utilisé les mode CLI?
- Utilisez vous des GUIs chez vos clients? Si oui lesquels?

### Pour aller plus loin
Vous pouvez jouer avec le cli dotnet afin d'explorer les différentes solutions existantes:

🔑 ```dotnet new --list```

En fonction du projet que vous choisirez, vous verrez que les options sont différentes (ex: choix du framework)

Exemples:

```dotnet new console --help```

```dotnet new mvc --help```


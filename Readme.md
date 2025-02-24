# Wiki Selfwise 
Documentation / Ressource / Blog

## Introduction
Ce dépôt contient la documentation et les ressources Selfwise sous forme d'un wiki Obsidian. Il héberge l'ensemble des ressources de la plateforme ainsi que les articles du blog. L'utilisation d'Obsidian permet une navigation intuitive entre les différentes ressources grâce aux liens bidirectionnels et une organisation flexible du contenu.

## Prérequis
Pour contribuer à ce wiki, vous aurez besoin de :
- Git installé sur votre machine
- Un compte GitHub avec accès au dépôt
- Obsidian installé sur votre ordinateur
- Optionnel: *un éditeur de texte (VS Code recommandé), pratique pour voir les diffs et faire des find-and-replace*

## Installation d'Obsidian
1. Rendez-vous sur le site officiel d'Obsidian : https://obsidian.md/
2. Téléchargez la version correspondant à votre système d'exploitation
3. Lancez l'installation en suivant les instructions à l'écran
4. Une fois installé, lancez Obsidian

## Configuration du dépôt

## Modification de ce wiki
#### 1. Installez Obsidian
https://obsidian.md/

#### 2. Clonez le dépôt
`git clone git@github.com:Selfwise/selfwise-wiki.git` ou utilisez le client GitHub

#### 3. Ouvrez le dossier dans Obsidian
![Ouverture du dossier dans Obsidian](assets/readme/Pasted%20image%2020250223155349.png)

#### 4. Activez les plugins communautaires
Cliquez sur l'icône de roue dentée (paramètres) en bas à gauche.
![Activation des plugins communautaires](assets/readme/Pasted%20image%2020250223155537.png)

#### 5. Activez le plugin Git
![Installation du plugin Git](assets/readme/Pasted%20image%2020250223155726.png)
Recherchez "git", cliquez sur la carte, cliquez sur installer, puis sur activer.

### Bonnes pratiques
- Utilisez des liens bidirectionnels ([[lien]]) pour connecter les ressources
- Ajoutez des tags appropriés (#tag) pour faciliter la recherche
- Incluez des métadonnées "property" en début de fichier
- Respectez la structure des dossiers existante
- Optimisez les images avant de les ajouter

### Publication

- Pour publier une page, assurez vous de mettre la propriété **Public** à **True**.
- Syncronisez avec le repo principal (hébergé sur github)
- Regénérez les articles avec un script, et les déployer sur le `backend-api` afin qu'elle deviennent disponible sur le site.

### Limitations actuelles
- Les liens d'images Obsidian ne sont pas supportés pour l'instant. Uniquement la syntax MD.
- Les images locales ne sont pas hébergées, ça viendra aussi.


## Notes de sécurité
- Ne stockez jamais d'informations sensibles dans le wiki
- Évitez les tokens d'accès ou mots de passe
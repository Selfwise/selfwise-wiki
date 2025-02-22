# Wiki Selfwise 
Documentation / Ressource / Blog

## Introduction

Ce dépôt contient la documentation et les ressources Selfwise sous forme d'un wiki Obsidian. Il héberge l'ensemble des ressources de la plateforme ainsi que les articles du blog. L'utilisation d'Obsidian permet une navigation intuitive entre les différentes ressources grâce aux liens bidirectionnels et une organisation flexible du contenu.

## Prérequis

Pour contribuer à ce wiki, vous aurez besoin de :
- Git installé sur votre machine
- Un compte GitHub avec accès au dépôt
- Obsidian installé sur votre ordinateur
- Un éditeur de texte (VS Code recommandé)

## Installation d'Obsidian

1. Rendez-vous sur le site officiel d'Obsidian : https://obsidian.md/
2. Téléchargez la version correspondant à votre système d'exploitation
3. Lancez l'installation en suivant les instructions à l'écran
4. Une fois installé, lancez Obsidian

## Configuration du dépôt

Pour commencer à travailler avec le wiki :

1. Ouvrez un terminal et clonez le dépôt :
```bash
git clone https://github.com/selfwise/selfwise-wiki.git
cd wiki
```

1. Dans Obsidian :
   - Cliquez sur "Ouvrir un autre coffre"
   - Sélectionnez "Ouvrir le dossier comme coffre"
   - Naviguez jusqu'au dossier du dépôt cloné
   - Sélectionnez le dossier

## Structure du wiki

Le wiki est organisé selon la structure suivante :

```
wiki/
├── ressources/           # Documentation technique et ressources
│   ├── guides/          # Guides d'utilisation
│   ├── api/            # Documentation API
│   └── tutoriels/      # Tutoriels pas à pas
├── blog/                # Articles du blog
│   ├── publies/        # Articles publiés
│   └── brouillons/     # Articles en cours de rédaction
├── assets/              # Images et fichiers média
└── templates/           # Modèles de documents
```

## Contribution au wiki

### Avant de commencer

1. Créez une nouvelle branche pour vos modifications :
```bash
git checkout -b feature/nom-de-votre-modification
```

1. Synchronisez régulièrement votre branche avec main :
```bash
git pull origin main
```

### Création de contenu

Pour créer un nouveau document :

1. Dans Obsidian, utilisez le raccourci Ctrl/Cmd + N
2. Choisissez le template approprié depuis le dossier templates/
3. Suivez la structure de nommage :
   - Ressources : `YYYYMMDD-nom-de-la-ressource.md`
   - Articles : `YYYYMMDD-titre-de-larticle.md`

### Bonnes pratiques

- Utilisez des liens bidirectionnels ([[lien]]) pour connecter les ressources
- Ajoutez des tags appropriés (#tag) pour faciliter la recherche
- Incluez des métadonnées YAML en début de fichier
- Respectez la structure des dossiers existante
- Optimisez les images avant de les ajouter

### Validation des modifications

1. Vérifiez vos modifications :
```bash
git status
git diff
```

1. Committez vos changements :
```bash
git add .
git commit -m "Description claire des modifications"
```

1. Poussez vers le dépôt distant :
```bash
git push origin feature/nom-de-votre-modification
```

1. Créez une Pull Request sur GitHub

## Recherche et navigation

Obsidian offre plusieurs outils pour naviguer efficacement :

- Recherche rapide : Ctrl/Cmd + P
- Recherche dans les fichiers : Ctrl/Cmd + Shift + F
- Vue graphique : Ctrl/Cmd + G
- Explorateur de tags : Dans le panneau de droite

## Plugins recommandés

Les plugins suivants sont recommandés pour améliorer votre expérience :

1. Git
   - Synchronisation automatique
   - Suivi des modifications

2. Dataview
   - Création de requêtes
   - Organisation dynamique du contenu

3. Templater
   - Utilisation avancée des templates
   - Automatisation de la création de contenu

## Support

Pour toute question ou problème :

1. Consultez les ressources existantes dans le wiki
2. Créez une issue sur GitHub
3. Contactez l'équipe technique via Slack

## Mise à jour du wiki

Pour maintenir le wiki à jour :

1. Synchronisez régulièrement votre dépôt local :
```bash
git pull origin main
```

1. Mettez à jour Obsidian quand une nouvelle version est disponible
2. Vérifiez les mises à jour des plugins installés

## Notes de sécurité

- Ne stockez jamais d'informations sensibles dans le wiki
- Évitez les tokens d'accès ou mots de passe
- Respectez les règles de confidentialité de Selfwise


--


# totoro

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Déployer un projet **Flutter Web** sur **GitHub Pages**


Quand on git push origin main
|     Étape           |Commande / Action                         
|----------------|-------------------------------|
|Build Flutter Web|`flutter build web`          |
|Déploiement manuel         |Push de `build/web` dans `gh-pages`           |
|Déploiement automatique          |Utiliser GitHub Actions (`peaceiris/actions-gh-pages`)|

# Troubleshoot

### Activer les permissions sur le dépôt

Voici ce que tu dois faire :

1.  Va sur **GitHub > ton repo > Settings**
2.  Dans le menu de gauche : **Actions > General**
3.  Descends à la section **Workflow permissions**
4.  Coche :  
    ✅ `Read and write permissions`
5.  Clique sur **Save** en bas de page

### Vérifie ta version locale Flutter`
Voici ce que tu dois faire :
1.  Vérifie ta version locale Flutter :  flutter --version
2. Modifie ton fichier `deploy.ym`

![codecov](https://codecov.io/gh/obione94/flutterWeb/branch/main/graph/badge.svg)

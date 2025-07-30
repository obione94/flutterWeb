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


Au `push origin main`
|     Étape           |Commande / Action                         
|----------------|-------------------------------|
|Déploiement test          |`flutter test --coverage`|
|Build Flutter Web|`flutter build web`          |
|Déploiement automatique App        |Push de `build/web` dans `gh-pages`    publish/       |
|Déploiement automatique Coverage        |Push de `coverage/html` dans `gh-pages`   publish/coverage/        |

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

### Vérifie ta couverture de test`
Voici ce que tu dois faire :
1.  install genhtml : **sudo apt install lcov**
2. run les tests : **flutter test --coverage**
3. deploye le coverage: **genhtml coverage/lcov.info -o coverage/html**

![Coverage](https://github.com/obione94/flutterWeb/coverage/coverage_badge.svg?sanitize=true)


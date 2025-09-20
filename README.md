# note-repo


D'accord, voici un plan étape par étape très clair :

🗑️ ÉTAPE 1 : SUPPRIMER ces fichiers
❌ lib/screens/articles/articles_screen_safe.dart
❌ lib/screens/articles/components/article_filters_safe.dart
❌ lib/screens/dashboard/dashboard_screen.dart (l'ancien avec le FAB problématique)

Copy

Insert

📝 ÉTAPE 2 : RENOMMER ces fichiers
📁 lib/screens/dashboard/
dashboard_screen_new.dart → dashboard_screen.dart

Copy

Insert

⚙️ ÉTAPE 3 : AJUSTER ces fichiers
1. Dans lib/controllers/screen_manager.dart :

Changer ArticlesScreenSafe → ArticlesScreen
Changer DashboardScreenNew → DashboardScreen
Changer l'import dashboard_screen_new.dart → dashboard_screen.dart
2. Dans lib/screens/articles/articles_screen.dart :

Changer l'import article_filters_safe.dart → article_filters.dart
Changer ArticleFiltersSafe → ArticleFilters
📋 Résumé
Supprimer : 3 fichiers obsolètes
Renommer : 1 fichier
Ajuster : 2 fichiers (imports et noms de classes)

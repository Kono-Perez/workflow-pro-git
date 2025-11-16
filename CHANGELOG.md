# Tout ce qu'on a fait tout au long de notre exercice est :
Partie 1 — Initialisation du projet
1. Créer un nouveau dépôt GitHub nommé : workflow-pro-git.
o Public
o Sans README (on le fera localement)
2. Créer le dossier local et lier le dépôt
## Partie 2 — Création des branches principales
- Créer les branches suivantes à partir de main (je dis bien a partir de main):
- develop : branche de développement général.
- feature : branche pour ajouter une nouvelle fonctionnalité.
- fix : branche pour corriger un bug.
- test : branche pour tester avant le merge final.
* Astuce : Chaque branche représente une étape du cycle de vie d’un projet.*
## Partie 3 — Simuler un vrai développement
1. Étape 1 : Ajouter une nouvelle fonctionnalité
- Bascule sur la branche feature :
- Crée un fichier app.md et ajoute ce contenu :
("Bienvenue dans mon application version 1.0 ");
Commit et push dans la branche feature:
2. Étape 2 : Corriger un bug sur une autre branche
- Passe sur la branche fix :
- Crée un fichier bugfix.txt et écris une explication du bug et sa solution.
Commit et push :
3. Étape 3 : Tester avant la mise en production
- Passe sur la branche test :
Crée un fichier test-report.md avec un résumé des tests (ce que vous
avez corrigé et ajouté).
Commit et push :

## Partie 4 — Fusionner les branches (Merges)
- Fusionner feature → develop
- Vérifiez que app.md est bien intégré.
- Fusionner fix → develop
- Vérifiez que bugfix.txt est bien ajouté.
- Fusionner develop → test
- Vérifiez que tout fonctionne avant la mise en production.
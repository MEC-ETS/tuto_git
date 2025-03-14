# Tuto GIT - Résumé

test test

## 1. Contexte
Git est un système de gestion de version permettant de suivre les modifications d’un projet, collaborer et revenir à des versions précédentes si nécessaire.

## 2. Cloner un Répertoire
- Installer Git : [Télécharger ici](https://git-scm.com/downloads)
- Cloner un dépôt existant :
  ```sh
  git clone <lien vers le répertoire distant>
  ```

## 3. Modifier un Répertoire Local
- Vérifier l’état actuel du dépôt :
  ```sh
  git status
  ```
- Mettre à jour la copie locale :
  ```sh
  git pull
  ```
- Apporter des modifications aux fichiers du projet.

## 4. Mettre à Jour un Répertoire Distant
- Ajouter les modifications à la zone de staging :
  ```sh
  git add . ou git add <nom du fichier>
  ```
- Créer un commit :
  ```sh
  git commit -m "ton message"
  ```
- Envoyer les modifications sur le dépôt distant :
  ```sh
  git push
  ```

## 5. Gestion des Branches
- Changer de branche :
  ```sh
  git checkout <nom de la branche>
  ```
- Fusionner une branche dans `main` :
  ```sh
  git merge nom-de-la-branche
  ```

## 6. Commandes Utiles

| Commande | Description |
|----------|------------|
| `git clone <lien vers le répertoire distant>` | Clone un répertoire distant dans un dossier local |
| `git pull` | Mettre à jour le répertoire local à partir du répertoire distant |
| `git status` | Voir tous les changements apportés au répertoire local |
| `git add .` ou `git add <nom du fichier>` | Ajoute les fichiers modifiés dans l’état « staged for commit » |
| `git commit -m "ton message"` | Créer un commit avec les modifications « staged for commit » |
| `git push` | Envoyer un commit sur le répertoire distant |
| `git log` | Affiche la liste des derniers commits |
| `git diff` | Affiche les changements apportés au répertoire local |
| `git reset --hard` | Supprime tous les changements effectués sur le répertoire local, revient à l’ancien commit |
| `git checkout <nom de la branche>` | Changer de branche (faire un “git fetch” avant au besoin) |

---

**Ce résumé couvre les principales commandes et concepts pour bien débuter avec Git ! 🚀**


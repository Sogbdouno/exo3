# Exercice 3 : Git Worktrees

## Introduction

Les Git worktrees permettent de gérer plusieurs branches d'un même dépôt Git simultanément en utilisant des répertoires de travail distincts. Cela permet de travailler sur plusieurs aspects du code sans avoir à cloner le dépôt plusieurs fois.

## Concepts de Base

- **Worktree** : Répertoire de travail associé à une branche Git spécifique.
- **Commandes principales** :
  - `git worktree add` : Crée un nouveau worktree.
  - `git worktree list` : Liste tous les worktrees.
  - `git worktree remove` : Supprime un worktree.

## Exemple Pratique

### 1. Créer un Nouveau Worktree

```bash
# Crée un worktree pour la branche 'feature-branch'
git worktree add ../feature-branch feature-branch

# Change de répertoire pour entrer dans le nouveau worktree
cd ../feature-branch

# Affiche tous les worktrees
git worktree list

# Supprime le worktree
git worktree remove ../feature-branch


## Conclusion

Les Git worktrees facilitent la gestion de plusieurs branches en parallèle et optimisent le processus de développement en permettant de travailler efficacement sur plusieurs aspects du code.

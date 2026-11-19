# Journal des commandes — README et Stack technique

Ce fichier contient les principales commandes exécutées pendant la mission.

## 1. Vérification de la branche Git

```powershell
git switch sprint1
git branch
git status
```

## 2. Création de l'arborescence

```powershell
mkdir .agents, docs, issues, tutoriels, presentations, rapport, sprints
```

## 3. Création des fichiers Scrum

```powershell
code sprints/sprints.md
code sprints/README.md
```

## 4. Création du README principal

```powershell
code README.md
```

## 5. Vérification des fichiers

```powershell
dir sprints
dir README.md
Get-Content README.md -Encoding utf8 -TotalCount 5
```

## 6. Création du journal des commandes

```powershell
New-Item -ItemType Directory -Force -Path "tutoriels/realisation-projet/initialisation/readme-stack-technique"
```
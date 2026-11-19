
# Publication GitHub — Journal des commandes

## Étape 1 : Vérification de l'authentification

```bash
gh auth status
```

## Étape 2 : Initialisation du projet

```bash
mkdir blog-des-laureats
cd blog-des-laureats
touch .gitignore
git init
```

## Étape 3 : Création de la branche

```bash
git checkout -b sprint1
```

## Étape 4 : Création de l'arborescence

```bash
mkdir -p tutoriels/realisation-projet/initialisation/publication-github
```

## Étape 5 : Publication

```bash
git add .gitignore tutoriels/realisation-projet/initialisation/publication-github/publication-github.command.md
git commit -m "feat: initialisation du projet et journal des commandes"
gh repo create
```

# Réponses aux questions ouvertes

## Exercice 1
- Diagramme de contexte : voir screenshot
- Flowchart : voir screenshot
- Dictionnaire de données : voir screenshot

## Exercice 2

### User Story (voir Word)
En tant qu'utilisateur inscrit, je veux souscrire à un abonnement Premium
afin d'accéder à un nombre illimité de messages et aux fonctionnalités avancées.

### Commandes Git
git checkout -b feature-premium-subscription
git add .
git commit -m "feat: add premium subscription system"
git push origin feature-premium-subscription
git checkout main
git pull origin main
git tag v1.0.0
git push origin v1.0.0

## Exercice 3

### Où configurer le secret sur GitHub
Settings → Secrets and variables → Actions → New repository secret

### Syntaxe pour injecter le secret dans le YAML
env:
  OPENAI_API_KEY: ${{ secrets.OPENAI_API_KEY }}
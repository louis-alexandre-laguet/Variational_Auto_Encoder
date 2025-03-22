# Implémentation d'Autoencodeurs et de Variational Autoencoders (VAE)

Ce repository contient trois notebooks implémentant des autoencodeurs et des autoencodeurs variationnels (VAE) sur les datasets Fashion MNIST et CelebA. Ces exercices permettent d'explorer les concepts de compression, reconstruction d'images et génération de nouvelles images grâce aux autoencodeurs.

## Contenu du repository

### 1. Autoencodeurs sur Fashion MNIST
**Objectifs :**
- Charger et visualiser le dataset Fashion MNIST.
- Construire un autoencodeur en utilisant des couches convolutionnelles.
- Entraîner l'autoencodeur et évaluer ses performances.
- Extraire et visualiser les embeddings latents.
- Réaliser la reconstruction des images et en générer de nouvelles.

### 2. Autoencodeurs Variationnels (VAE) sur Fashion MNIST
**Objectifs :**
- Charger le dataset Fashion MNIST et redimensionner les images de 28x28 à 32x32.
- Créer des DataLoaders pour l'entraînement et la validation.
- Visualiser un échantillon d'images pour vérifier l'intégrité des données.
- Comprendre l'importance du padding et des transformations comme la normalisation.
- Gérer l'organisation des batchs pour un entraînement efficace.
- Implémenter et entraîner un VAE pour la reconstruction et la génération d'images.

### 3. Autoencodeurs Variationnels (VAE) sur CelebA
**Objectifs :**
- Obtenir et organiser le dataset CelebA.
- Préparer les images : redimensionnement en 32x32, conversion en tenseurs et normalisation.
- Créer un DataLoader avec `batch_size` et `shuffle=True` pour un entraînement optimal.
- Visualiser un batch d'images pour s'assurer du bon chargement des données.
- Implémenter un VAE pour apprendre la distribution des visages humains et générer de nouvelles images.


# -Reconnaissance-de-Caract-res-Manuscrits
Ce rapport présente les améliorations apportées à un modèle existant de reconnaissance de caractères manuscrits. L’objectif principal était de réduire le surapprentissage et d’améliorer la précision, notamment en intégrant un meilleur prétraitement des images et l’utilisation de la webcam pour la reconnaissance en temps réel.
## Fichiers inclus

- `my_model.h5` : poids du modèle entraîné.
- `TP.py` : script principal pour entraîner, évaluer et utiliser la reconnaissance en temps réel.
- `handwritten-characters.zip` : dataset initial des caractères manuscrits.
- `handwriting-recognition.zip` : dataset ou ressources complémentaires.

## Usage

- Lancer `TP.py` pour entraîner le modèle, évaluer ou utiliser la webcam pour la reconnaissance en temps réel.

## Télécharger les datasets Kaggle :

Pour utiliser les datasets provenant de Kaggle, vous devez générer une clé API depuis votre compte Kaggle :

- Connectez-vous à votre compte Kaggle.
- Allez dans "My Account" > "API" > cliquez sur "Create New API Token".
- Un fichier `kaggle.json` sera téléchargé.
- Placez ce fichier dans le dossier `~/.kaggle/` (Linux/Mac) ou `%USERPROFILE%\.kaggle\` (Windows).
- Assurez-vous que les permissions du fichier sont sécurisées (ex : `chmod 600 ~/.kaggle/kaggle.json` sous Linux).

Ensuite, vous pouvez télécharger les datasets avec la commande :
kaggle datasets download -d <nom-du-dataset>
ou en utilisant les scripts fournis.
## Améliorations possibles

- Optimiser le prétraitement en temps réel.
- Ajouter la reconnaissance d’écriture cursive.
- Support multi-langues.

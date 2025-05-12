📝 Description pour le modèle ResNet50V2 (classification ECG sur images)

Ce projet met en œuvre un modèle de classification d’ECG basé sur ResNet50V2, une architecture de réseau de neurones convolutifs profonde et optimisée pour la reconnaissance d’images. Le modèle est appliqué à des images ECG à deux dérivations afin d’identifier automatiquement 4 types d’anomalies :HMI, MI, AHB et Normal .

Grâce à la profondeur de ResNet50V2 et à l’utilisation de residual connections améliorées, cette architecture permet d'apprendre des représentations complexes tout en évitant le problème de dégradation des performances observé dans les réseaux très profonds.

Les objectifs du projet incluent :

L'utilisation d’images ECG nettoyées et augmentées pour l’apprentissage.

L’adaptation de l’architecture ResNet50V2 à une classification à 6 classes.

L’analyse détaillée des performances à travers des métriques médicales et des visualisations.

L'intégration du modèle dans une chaîne d'entraînement reproductible via notebooks.

Le dépôt est structuré comme suit :

📁 résultats : visualisations des performances (courbes, matrices de confusion, classification report).

📁 entrainement et évaluation du modéle : code Python et notebooks pour la définition, l’entraînement et l’évaluation du modèle.

📌 Remarque importante sur le fichier .h5
Le fichier .h5 du modèle ResNet50V2 n’est pas présent dans ce dépôt car il n’a pas été sauvegardé ou généré lors de l’entraînement.

Pour obtenir le modèle, veuillez exécuter les notebooks d’entraînement fournis dans le dossier entrainement et évaluation du modéle 
ou Me contacter directement à l’adresse : raedbenaissa80@gmail.com


✍️ Signature personnelle
Réalisé dans le cadre de mon projet de fin d'études par :
Raed Ben Aissa
Année universitaire : 2024–2025
Encadré par : LT COL Mohamed Hachemi Jeridi et DR Mouna Azaiz

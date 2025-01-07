# Classification-automatique-de-biens-de-consommation

L’objectif de ce projet est d'étudier la faisabilité d'un moteur de classification automatique d'articles sur une plateforme d'e-commerce, en utilisant à la fois le texte (description produit) et les images (photo produit). L’automatisation de cette tâche est cruciale pour améliorer l’expérience utilisateur des vendeurs et des acheteurs sur la marketplace.

Étapes du projet :

    Prétraitement des données :
        Textes : Nettoyage et tokenisation des descriptions produits.
        Images : Prétraitement des images pour l’extraction de features.

    Extraction de features :
        Images : Utilisation d'algorithmes de détection de points d'intérêt comme SIFT/ORB, ainsi que des modèles de CNN (Transfer Learning) pour extraire des caractéristiques des images.
        Textes : Approches classiques comme Bag-of-Words et TF-IDF, ainsi que des modèles plus avancés comme Word2Vec, BERT et USE pour transformer les descriptions en vecteurs sémantiques.

    Réduction de dimensions :
        Visualisation des produits dans un espace 2D à l’aide de techniques de réduction de dimensions (ex : PCA).

    Analyse et évaluation de la faisabilité :
        Analyse visuelle pour détecter des regroupements naturels de produits similaires.
        Mesure de la similarité entre les catégories réelles et les clusters identifiés à l’aide de métriques comme la similarité cosinus.

Ce projet permet de démontrer la faisabilité de regrouper automatiquement des produits similaires en fonction de leur description et de leur image, facilitant ainsi l’automatisation de l’attribution de catégories sur la marketplace.

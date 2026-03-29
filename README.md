# CIFAR-10 Image Classifier (CNN)

> **Projet de Computer Vision : Classification multiclasse d'images 32x32 en 10 catégories distinctes.**

Ce projet démontre l'utilisation des **Réseaux de Neurones Convolutifs (CNN)** pour identifier des objets et des animaux à partir du dataset de référence CIFAR-10.

#cifar 10 n'est pas fournit,vous pouvez y accéder via un google drive:( https://drive.google.com/file/d/15EnFJA1SGnkI6gzkgWP0PElY-rjQgGL3/view?usp=sharing )
---

## Objectif du Projet
Développer un modèle capable de généraliser l'identification visuelle sur 10 classes : avion, automobile, oiseau, chat, cerf, chien, grenouille, cheval, bateau et camion. 

L'enjeu principal ici est la **gestion de la basse résolution (32x32 pixels)**, ce qui demande une architecture précise pour ne pas perdre l'information spatiale.

---

## Stack Technique & Architecture

* **Framework :** TensorFlow / Keras
* **Architecture :** **CNN (Convolutional Neural Network)**
    * **Couches de Convolution :** Pour l'extraction des caractéristiques (bords, textures, formes).
    * **MaxPooling :** Pour réduire la dimensionnalité et conserver les traits les plus importants.
    * **Dropout :** Technique de régularisation utilisée pour éviter l'**Overfitting** (sur-apprentissage).
    * **Dense Layers :** Couches finales pour la classification via une activation `softmax`.



---

## Performance & Entraînement

* **Dataset :** 60 000 images colorées (RGB).
* **Preprocessing :** Normalisation des pixels (mise à l'échelle entre 0 et 1) pour accélérer la convergence de l'algorithme.
* **Optimiseur :** Adam / SGD (selon tes tests).

---

## Compétences validées
* Prétraitement de données d'imagerie (Image Augmentation, Normalisation).
* Conception d'architectures CNN.
* Analyse des courbes de Loss et d'Accuracy pour optimiser les hyperparamètres.

---
**Développé par Wassim** 

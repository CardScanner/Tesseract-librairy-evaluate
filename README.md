déffinition de Tesseract :

    Tesseract est un moteur OCR open-source qui extrait le texte imprimé ou écrit des images.

les bibliothques qui peuvent etre couple avec Tesseract :

    PYOCR – permet plus d’options pour la détection des phrases, des chiffres et des mots

    Textract – permet l’extraction de données PDF pour les fichiers et paquets volumineux

    OpenCV – bibliothèque open-source de fonctions de programmation centrées sur la vision d’ordinateur (CV) en temps réel

    Leptonica – permet des fonctions de traitement d’images et des applications d’analyse d’images avec sa bibliothèque d’imagerie

    Pillow – une autre bibliothèque d’imagerie Python, qui prend en charge l’ouverture, la manipulation et l’enregistrement d’une liste étendue de formats de fichiers d’image

Architecture de processus de Tesseract :

 ![tesseracte-removebg-preview](https://github.com/CardScanner/Tesseract-librairy-evaluate/assets/127212498/209d78b2-c607-4b6e-8c2b-8f1c14945b45)


Les modes de segmentation de page de Tesseract :

       1. Détection uniquement de l'orientation et du script (OSD)
       2. Segmentation automatique de la page avec OSD
       3. Segmentation automatique de la page sans OSD, OCR inclus
       4. Segmentation entièrement automatique de la page sans OSD
       5. Supposer une seule colonne de texte de tailles variables
       6. Supposer un seul bloc uniforme de texte aligné verticalement
       7. Supposer un seul bloc uniforme de texte
       8. Traiter l'image comme une seule ligne de texte
       9. Traiter l'image comme un seul mot
      10. Traiter l'image comme un seul mot dans un cercle
      11. Traiter l'image comme un seul caractère
      12. Texte épars. Trouver autant de texte que possible sans ordre particulier 
      13. Texte épars avec OSD
      14. Ligne brute. Traiter l'image comme une seule ligne de texte en   contournant les hacks spécifiques à Tesseract.


Les modes de OCR engine :

     1. Moteur Legacy uniquement
     2. Moteur Neural nets LSTM (Réseaux de neurones à mémoire à court terme)
     3. Moteurs Legacy + LSTM
     4. Paramètre par défaut
     

      

🐧 Tutoriel Linux : Gestion des fichiers et dossiers
Ce guide rapide vous apprend à créer des dossiers, éditer des fichiers et analyser la structure de votre projet via le terminal.


## 1. Gestion des Dossiers
Apprenez à créer et organiser vos répertoires.

* mkdir A : Crée un dossier nommé A.
* mkdir -p A/B : Crée le dossier B à l'intérieur de A. L'option -p crée les dossiers parents s'ils n'existent pas.
* mkdir -p B/C/D : Crée une structure imbriquée de plusieurs sous-dossiers en une seule fois.
* rm -r A : Supprime le dossier A et tout son contenu de manière récursive. (Attention : rmdir ne fonctionne que sur les dossiers vides, utilisez rm -r pour forcer la suppression).

## 2. Création et Édition de Fichiers
Générez des fichiers textes et découvrez comment les modifier avec deux éditeurs populaires.

* touch mytext.txt : Crée un fichier vide nommé mytext.txt.
* touch mytext1.txt : Crée un second fichier vide nommé mytext1.txt.

## Option A : Utiliser Nano (Simple)

* nano mytext.txt : Ouvre l'éditeur dans le terminal.
* Écrire : Tapez votre texte directement.
   * Sauvegarder : Pressez Ctrl + O puis Entrée.
   * Quitter : Pressez Ctrl + X.

## Option B : Utiliser Vim (Avancé)

* vi mytext1.txt : Ouvre l'éditeur Vim.
* Écrire : Appuyez sur la touche i pour passer en mode insertion.
   * Quitter le mode écriture : Appuyez sur la touche Échap.
   * Sauvegarder et quitter : Tapez :wq puis Entrée.

## 3. Visualisation de l'Arborescence
Vérifiez l'organisation de votre espace de travail.

* tree : Affiche graphiquement toute la structure de vos dossiers et fichiers.
* ls : Liste simplement les fichiers et dossiers du répertoire actuel.
* ls *.txt : Filtre l'affichage pour voir uniquement les fichiers avec l'extension .txt.
* ls mytext.* : Filtre l'affichage pour voir les fichiers nommés mytext peu importe leur extension.
* ls -R : Liste de manière récursive tous les dossiers et le contenu de leurs sous-dossiers.
* ls -R * : Variante qui force l'affichage détaillé du contenu de chaque élément visible.

## 4. Redirection de flux (Sauvegarder l'affichage)
Envoyez le résultat de vos commandes directement dans un fichier texte.

* tree > mytext.txt : Écrit l'arborescence dans le fichier. Écrase et efface le contenu précédent du fichier.
* tree >> mytext.txt : Ajoute l'arborescence à la fin du fichier. Conserve le texte déjà existant.




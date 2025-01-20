# ODIN
## Observation des Doublons Intellectuels Numériques
### Installation et Pré-requis

Avant d'exécuter ODIN, assurez-vous d'avoir téléchargé l'exécutable correspondant à votre système. Vous n'avez pas besoin de Python si vous utilisez l'exécutable.

### Utilisation :

1. Lancez l'exécutable : Double-cliquez sur odin.exe. Si vous préférez une interaction avec l'invite de commande, ouvrez un terminal et exécutez odin.exe via la ligne de commande.

2. Chargement initial : Après le lancement, un message s'affichera pour vous informer que le programme charge les données. Patientez quelques secondes, ce processus peut prendre un peu de temps en fonction de la taille des fichiers à analyser.

3. Sélection des dossiers :
Après avoir appuyé sur Entrée, une fenêtre s'ouvrira. Utilisez-la pour sélectionner les dossiers contenant les fichiers à analyser.

4. Choix du taux de ressemblance :
Une fois les dossiers sélectionnés, l'application vous demandera de saisir le taux de similarité minimum. Par exemple, si vous voulez détecter des fichiers ayant au moins 60% de similarité, tapez "60" puis appuyez sur Entrée.

5. Sélection du répertoire pour sauvegarder le fichier CSV :
Vous devrez ensuite spécifier un répertoire où enregistrer le fichier CSV d'audit. Ce fichier contiendra une comparaison des fichiers analysés.

6. Résultats :
Le fichier CSV sera créé rapidement une fois le processus terminé. Il contient trois colonnes :
- Le chemin du premier fichier comparé
- Le chemin du deuxième fichier comparé
- Le taux de proximité textuelle entre les deux fichiers

Exemple de sortie dans le fichier CSV :

C:\documents\fichier1.txt, C:\documents\fichier2.txt, 75.42
C:\documents\fichier3.txt, C:\documents\fichier4.txt, 80.15

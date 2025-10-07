# Libraries KiCAD ENAC Robotique

Clonez ce repo : `git clone https://github.com/ENACRobotique/kicad_libs_ENAC.git`

Ouvrez KiCAD et ajouter les librairies de symboles et d'empreintes :

- Préférences -> Configurer les librairies de Symboles...
    - Ajouter une librairie existante (2ème bouton en bas à gauche)
    - Sélectionnez les fichiers .kicad_sym dans le dossier symbols
- Préférences -> Configurer les librairies d'Empreintes...
    - Ajouter une librairie existante (2ème bouton en bas à gauche)
    - Sélectionnez le dossier ENAC_robotique.pretty

Ajoutez le chemin vers les modèles 3D:
- Préférences -> Configurer les chemins...
- Ajouter une variable "ENAC_3D_MODELS" avec comme valeur le chemin vers dossier "packages3d".


Vous êtes prêts !

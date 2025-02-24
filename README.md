# Configuration Karabiner-Elements pour Corsair K60 Pro TKL AZERTY sur macOS

## Description

Ce dépôt contient une **configuration personnalisée de Karabiner-Elements** pour le clavier **Corsair K60 Pro TKL AZERTY** sur **macOS**. Cette configuration inclut des mappages pour les touches multimédia, les touches **F1-F12**, la touche **IMPR ÉCRAN**, la touche **Menu**, ainsi que les touches avec **Shift**, **Alt Gr**, et d'autres actions courantes comme **Forcer à quitter** et **Capture d'écran**.

## Fonctionnalités

- **Menu (Touche Application)** : **Simule un clic droit** (button2 de la souris)
- **F1** : Verrouille la session avec **Cmd + Ctrl + Q**
- **F3 et F4** : Contrôle de la luminosité du clavier (Baisse/augmentation)
- **F5** : **Mute** (Coupe le son)
- **F7** : **Volume down** (Diminue le volume)
- **F8** : **Volume up** (Augmente le volume)
- **F9** : **Cmd + Option + Esc** (Forcer à quitter une application bloquée)
- **F10** : **Rewind** (Précédent pour la musique/vidéo)
- **F11** : **Play/Pause** (Lecture ou pause pour la musique/vidéo)
- **F12** : **Next Track** (Suivant pour la musique/vidéo)
- **IMPR ÉCRAN** : **Cmd + Shift + 3** (Capture d'écran sélective)
- **Shift et Alt Gr** mappés pour des caractères spéciaux conformément aux touches physiques du clavier.

## Installation

1. **Télécharger et installer Karabiner-Elements** à partir de [Karabiner Elements](https://github.com/pqrs-org/Karabiner-Elements).
   
2. **Télécharger ce fichier JSON** :  
   - Copie le fichier `corsair-k60-tkl-azerty-macOS-config.json` dans le répertoire suivant de macOS :
     ```
     ~/.config/karabiner/assets/complex_modifications/
     ```

3. **Ouvrir Karabiner-Elements** et aller dans l'onglet **Complex Modifications**.
   
4. **Cliquer sur "Import Rules"**, sélectionner le fichier téléchargé et l'activer.

## Structure du dépôt GitHub

```plaintext
karabiner-corsair-k60-tkl-azerty-macOS/
├── configs/
│   └── corsair-k60-tkl-azerty-macOS-config.json
├── README.md
└── LICENSE
```

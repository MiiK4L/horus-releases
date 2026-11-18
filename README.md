# Horus

App macOS de maintenance et de surveillance du Mac, en Liquid Glass : nettoyage, optimisation, applications, démarrage, mises à jour, espace disque, tendances (processeur, mémoire, températures, ventilateurs, réseau, batterie), sécurité, écrans, et un assistant IA au choix (Apple Intelligence, modèle local ou API en ligne). Construite sur [Mole](https://github.com/tw93/Mole).

Ce dépôt contient uniquement les versions publiées et le flux de mises à jour de l'app.

## Installer

1. Téléchargez le dernier **Horus-x.y.dmg** dans les [Releases](https://github.com/MiiK4L/horus-releases/releases/latest).
2. Ouvrez-le et glissez **Horus** dans **Applications**.
3. Premier lancement : macOS ne peut pas vérifier l'app (elle n'est pas notarisée). Allez dans **Réglages Système › Confidentialité et sécurité** et cliquez **« Ouvrir quand même »**. Si ça bloque encore : `xattr -dr com.apple.quarantine /Applications/Horus.app`
4. Installez Mole : `brew install mole`

Configuration requise : Mac avec puce Apple, macOS 26 ou plus récent.

## Mises à jour

Horus vérifie lui-même ce dépôt chaque jour et propose « Installer et relancer ». Chaque version est signée : l'app refuse toute mise à jour qui n'a pas été signée par son auteur. Réglages dans **Horus › Réglages › Mises à jour de Horus**.

---
Créé par [MiiK4L](https://github.com/MiiK4L) · © 2026

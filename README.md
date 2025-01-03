# Projet de Cybersécurité : Keylogger, IP Logger et Détection de Mouvement

## 🔒 Description du Projet

Ce projet combine plusieurs techniques de cybersécurité, y compris un keylogger pour enregistrer les frappes clavier, un système d'envoi d'e-mails pour transmettre les données collectées, un IP logger pour la géolocalisation, et un module de détection de mouvement utilisant la webcam. Ce projet est destiné à des fins éducatives dans le cadre d'un cours de cybersécurité.

## 🚀 Fonctionnalités Principales

1. **Keylogger (`keylogger.py`)** :
   - Enregistre les frappes clavier de l'utilisateur.
   - Stocke les informations saisies dans un fichier `.txt`.

2. **Sendmail** :
   - Envoie le fichier `.txt` contenant les données du keylogger par e-mail.
   - Intègre une fonctionnalité d'IP logger pour récupérer la localisation GPS.

3. **Activation Webcam** :
   - Capture vidéo en temps réel et détecte les mouvements.
   - Prend des photos lorsque des mouvements sont détectés.

## 🛠️ Prérequis Techniques

- Python 3.8+
- Bibliothèques :
  - `pynput` (pour le keylogger)
  - `smtplib` (pour l'envoi d'e-mails)
  - `opencv-python` (pour la détection de mouvement)
  - `geocoder` (pour la géolocalisation)

## 📦 Installation


## 🔍 Utilisation

1. **Lancer le Keylogger** :
   
2. **Envoyer les données par e-mail** :
Assurez-vous que le fichier `sendmail.py` est configuré avec vos informations d'identification et exécutez-le :

3. **Activer la Webcam pour la détection de mouvement** :

4. **Quittez avec la touche 'q' dans la fenêtre de détection de mouvement.**

## 🔐 Avertissement Éthique

Ce projet est strictement académique et destiné à des fins éducatives en cybersécurité. Toute utilisation malveillante est formellement interdite. Assurez-vous d'avoir l'autorisation explicite des utilisateurs avant d'exécuter ce type de logiciel sur leurs systèmes.

## 📝 Licence

Projet académique - Cours de Cybersécurité

## 👥 Contributeurs

- RDout2




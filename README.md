# 📚 Webdocumentaire : Le Défi des Étudiants

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 📖 Description

Webdocumentaire interactif explorant **la gestion du budget étudiant à l'IUT de Meaux**. Ce projet met en lumière les défis financiers auxquels font face les étudiants et présente les ressources disponibles pour les accompagner.

## ✨ Fonctionnalités

- 🎬 **Vidéo de présentation** en arrière-plan
- 📱 **Design responsive** adapté à tous les écrans
- 🖼️ **Galerie interactive** avec témoignages étudiants
- 📊 **Visualisations** de la situation financière étudiante
- 🎨 **Interface moderne** avec animations fluides
- 🔊 **Contenus audio** pour une expérience immersive

## 📁 Structure du projet

```
site_webdoc/
├── index.html                              # Page d'accueil
├── accueil.html                            # Page d'accueil alternative
├── galerie.html                            # Galerie de témoignages
├── portrait_yannis.html                    # Portrait étudiant
├── le_crous_soutien_étudiant.html         # Article sur le CROUS
├── la_situation_financière_étudiante.html # Analyse financière
├── l'aide_précieuse_sociaux.html          # Aide sociale
├── css/                                    # Feuilles de style
│   ├── style_webdoc.css
│   ├── style_accueil.css
│   ├── style_galerie.css
│   └── ...
├── img/                                    # Images et photos
│   ├── frigo/                             # Photos de frigos étudiants
│   └── diapo_de_fou/                      # Diaporama
├── video/                                  # Vidéos (gérées par Git LFS)
├── sound/                                  # Fichiers audio
└── README.md
```

## 🚀 Installation

### Prérequis

- Un navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Un serveur web local (optionnel mais recommandé)

### Lancement local

1. **Cloner le repository**
   ```bash
   git clone https://github.com/yoh4nyo/Webdocumentaire-etudiant-meaux.git
   cd Webdocumentaire-etudiant-meaux
   ```

2. **Installer Git LFS** (pour les fichiers vidéo)
   ```bash
   git lfs install
   git lfs pull
   ```

3. **Lancer le projet**
   
   Ouvrez simplement `index.html` dans votre navigateur, ou utilisez un serveur local :
   
   ```bash
   # Avec Python
   python -m http.server 8000
   
   # Avec PHP
   php -S localhost:8000
   
   # Avec Node.js (http-server)
   npx http-server
   ```

4. **Accéder au site**
   
   Ouvrez votre navigateur à l'adresse : `http://localhost:8000`

## 🛠️ Technologies utilisées

- **HTML5** - Structure des pages
- **CSS3** - Styles et animations
- **JavaScript** - Interactivité
- **Bootstrap 5.3.3** - Framework CSS responsive
- **Font Awesome** - Icônes
- **Git LFS** - Gestion des fichiers volumineux

## 👥 Contributeurs

- **Yohan SOM** - Développeur principal

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 📧 Contact

Pour toute question ou suggestion :
- Email : yohan.som77@gmail.com
- GitHub : [@yoh4nyo](https://github.com/yoh4nyo)

---

*Projet réalisé dans le cadre d'un travail académique à l'IUT de Meaux*

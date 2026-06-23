# 🌌 Aura AI

**Aura AI** est une interface utilisateur de chat IA moderne, élégante et entièrement statique, conçue pour offrir une expérience utilisateur haut de gamme (inspirée du style *glassmorphism* et du thème sombre). 

Ce projet s'exécute entièrement côté client (dans votre navigateur) et intègre des fonctionnalités avancées de gestion de documents, d'OCR et de visualisation de code via un panneau d'**Artefacts**.

---

## ✨ Fonctionnalités clés

* **💬 Chat Interactif Moderne** : Une interface de discussion fluide, épurée et animée avec gestion de l'historique dans la barre latérale.
* **📦 Système d'Artefacts** (similaire à Claude.ai) :
  * Affichage en temps réel du code généré, des pages web interactives (HTML/JS/CSS dans une iframe), des images SVG et des tableaux de données.
  * Visualisation dynamique de schémas et graphiques grâce au moteur **Mermaid.js**.
  * Possibilité de copier le code ou de télécharger directement l'artefact généré.
* **📎 Analyse de Documents & Fichiers** :
  * **PDF** : Lecture et extraction de texte directement dans le navigateur (via `pdf.js`).
  * **Word (.docx)** : Conversion et extraction de documents Word (via `mammoth.js`).
  * **Excel (.xlsx)** : Lecture et affichage de feuilles de calcul (via `SheetJS/xlsx`).
  * **Images & OCR** : Extraction automatique de texte à partir de captures d'écran ou d'images (via `tesseract.js`).
* **⚙️ Multi-fournisseurs d'API** : Configuration directe de vos clés d'API et modèles préférés (avec stockage sécurisé dans le `localStorage` du navigateur).
* **🔌 Simulation Hors-ligne** : Mode de repli hors-ligne en cas de problème de connexion pour tester l'interface de manière autonome.

---

## 🛠️ Technologies utilisées

Pour des performances maximales et une légèreté absolue, ce projet a été construit sans framework lourd :
* **HTML5** (Structure sémantique)
* **Vanilla CSS** (Thème sombre sur mesure, variables CSS avancées, flous de verre liquide et animations fluides)
* **Vanilla JavaScript** (Logique applicative modulaire et réactive)
* **Bibliothèques externes (chargées via CDN)** :
  * [Marked.js](https://github.com/markedjs/marked) : Pour le rendu du Markdown.
  * [PDF.js](https://mozilla.github.io/pdf.js/) : Pour la lecture des fichiers PDF.
  * [Mammoth.browser.js](https://github.com/mvoloskov/mammoth.js) : Pour l'import de documents Word.
  * [SheetJS (XLSX)](https://sheetjs.com/) : Pour l'import de fichiers Excel.
  * [Tesseract.js](https://tesseract.projectnaptha.com/) : Pour l'OCR (reconnaissance optique de caractères sur les images).
  * [Mermaid.js](https://mermaid.js.org/) : Pour la génération de diagrammes.

---

## 🚀 Démarrage rapide

Comme il s'agit d'une **page web statique**, aucune installation de serveur ou de dépendances n'est requise !

1. Téléchargez ou clonez ce dépôt :
   ```bash
   git clone https://github.com/VOTRE_NOM_D_UTILISATEUR/aura-ai.git
   ```
2. Ouvrez simplement le fichier `index.html` dans votre navigateur Web préféré (Double-clic sur le fichier).

*💡 **Astuce** : Pour une meilleure expérience de développement (rechargement automatique), vous pouvez utiliser l'extension **Live Server** sur VS Code.*

---

## 📄 Licence

Ce projet est sous licence **MIT**. Vous êtes libre de l'utiliser, de le modifier et de le distribuer à condition de conserver la mention de copyright originale et le lien vers ce projet.

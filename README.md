# ⚡ GitSwipe

**GitSwipe** est une interface exploratoire au style **néo-brutaliste** permettant de découvrir les pépites de GitHub avec l'ergonomie d'une application de rencontre. Swippez, découvrez, et archivez les dépôts les plus "trending" du moment.

---

## 🛠️ Fonctionnalités

* **Stream de découverte :** Accès direct aux dépôts les plus étoilés créés au cours des 30 derniers jours.
* **Interface Swipe :** * **Swipe Droite (ou bouton ❤️) :** Ajoute le dépôt à votre Vault (coffre-fort).
    * **Swipe Gauche (ou bouton ✘) :** Ignore le dépôt et passe au suivant.
* **Système de Vault :** Visualisez vos dépôts sauvegardés. Fonctionne en mode local (localStorage) ou synchronisé avec votre compte GitHub.
* **Aperçu README :** Rendu Markdown en temps réel directement sur la carte pour comprendre un projet sans quitter l'app.
* **Bouton Undo :** Permet d'annuler le dernier swipe en cas d'erreur de manipulation.
* **Connexion GitHub :** Intégrez un Token (PAT) pour starrer réellement les dépôts sur votre profil GitHub depuis l'interface.

---

## 🚀 Installation & Lancement

Le projet est "Self-contained" : un seul fichier HTML regroupe toute la logique, le style et les assets.

1.  Clonez le dépôt :
    ```bash
    git clone [https://github.com/votre-username/gitswipe.git](https://github.com/votre-username/gitswipe.git)
    ```
2.  Ouvrez `index.html` dans n'importe quel navigateur moderne.
3.  (Optionnel) Configurez votre Token GitHub via l'icône ⚙️ pour dépasser les limites de l'API (60 requêtes/heure).

---

## ⚙️ Configuration du Token GitHub

Pour une expérience optimale :
1.  Créez un **Personal Access Token (classic)** sur GitHub.
2.  Attribuez-lui le scope `public_repo`.
3.  Collez le token dans le menu **System_Config** de l'application.
> **Note :** Votre token est stocké uniquement dans votre `localStorage` navigateur. Aucun serveur tiers n'y a accès.

---

## 🎨 Design System (Brutalist.bin)

L'application utilise une esthétique radicale :
* **Typographie :** `Space Mono` pour un look terminal/système.
* **Contraste :** Fond blanc, texte noir, accents vert fluo `#00FF00`.
* **Bordures :** 4px solid black avec des ombres portées rigides (Hard Shadows).
* **Animations :** Transitions fluides basées sur les gestes tactiles et la souris.

---

## 🗂️ Stack Technique

* **Logic :** Vanilla JavaScript (ES6+)
* **Style :** Tailwind CSS
* **Markdown :** [Marked.js](https://marked.js.org/)
* **API :** GitHub REST API v3
* **Font :** Google Fonts (Space Mono)
* [APK](https://appilix.com/account/)


# A implementer:
* La creation de smart tags en analysant les repo stars
* Boutton settings

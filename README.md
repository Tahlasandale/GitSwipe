# ⚡ GitSwipe - Ultimate.bin

> **Découvrez du code. Swipez pour Star. Discutez avec l'IA.**
>
> Une interface brutale et efficace pour explorer l'univers GitHub.

GitSwipe transforme la découverte de dépôts GitHub en une expérience fluide et addictive. Ne perdez plus de temps dans des listes interminables : **une carte, un choix.**

---

## 💾 Fonctionnalités Principales

### 1. 👆 Mécanique de Swipe
* **Droite (Green) :** Ajoute une Star ⭐ au dépôt (Sync GitHub ou Local).
* **Gauche (Red) :** Ignore et passe au suivant.
* **Undo :** Une erreur ? Revenez en arrière.

### 2. 🧠 Repo Analyzer (Powered by Gemini)
Ne lisez plus le code seul. Ouvrez le chat intégré pour discuter directement avec le code source du dépôt.
* L'IA scanne l'arborescence et lit les fichiers clés.
* Posez des questions techniques (*"Comment fonctionne l'auth ?", "Explique ce fichier Python"*).
* Réponses formatées en Markdown.

### 3. 🎲 Modes de Découverte
* **Trending :** Les dépôts les plus populaires du dernier mois.
* **Random Chaos :** Exploration aléatoire basée sur vos tags préférés (Rust, AI, CLI, Ricing...).
* **Search.exe :** Recherche précise par mots-clés ou dépôt spécifique (`user/repo`).

### 4. 🗄️ Le Coffre (Vault)
Visualisez vos dépôts favoris.
* Fonctionne en mode **Local** (sans compte GitHub) ou **Sync** (avec Token).
* L'IA peut analyser vos stars pour générer automatiquement de nouveaux tags d'intérêt ("Chaos Matrix").

---

## 🚀 Installation & Utilisation

Ce projet est conçu pour être ultra-portable (**Single File Application**).

### Prérequis
Un navigateur web moderne (Chrome, Firefox, Edge, Safari) ou un smartphone Android.

---

## ⚙️ Configuration (Config.sys)

Pour débloquer toute la puissance de GitSwipe, cliquez sur l'icône **Settings** en haut à droite.

| Paramètre | Description | Requis pour... |
| :--- | :--- | :--- |
| **GitHub Token** | Token d'accès personnel (Classic). | Synchroniser les Stars avec votre compte GitHub réel et augmenter les limites de l'API (Rate Limit). |
| **Gemini API Key** | Clé API Google AI Studio. | Utiliser le Chat (Repo Analyzer) et la génération automatique de tags. |

> **Note de sécurité :** Vos clés sont stockées uniquement dans le `localStorage` de votre navigateur. Elles ne sont jamais envoyées vers un serveur tiers autre que les APIs officielles (GitHub et Google).

---

## 🛠️ Stack Technique

* **Frontend :** HTML5 natif.
* **Style :** Tailwind CSS (via CDN).
* **Scripting :** Vanilla JavaScript (ES6+).
* **Rendu Markdown :** Marked.js.
* **Syntax Highlighting :** Highlight.js.
* **Polices :** Space Mono (Google Fonts).

---

## ⌨️ Raccourcis / Astuces

* **Navigation Tactile :** L'interface est optimisée pour le mobile. Swipez avec le pouce.
* **Recherche avancée :** Vous pouvez taper `language:rust` ou `topic:react` dans la barre de recherche.
* **Tags IA :** Dans le menu "Chaos Matrix", cliquez sur `AI_SCAN_FAVORITES` pour que Gemini analyse vos goûts et suggère des tags de recherche.

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
* MAJ readme

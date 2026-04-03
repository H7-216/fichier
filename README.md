# 🚀 Déploiement Rapide - Répertoire Scolaire

## ⚡ SOLUTION RAPIDE (1 fichier uniquement)

### 📄 Fichier à uploader

Télécharge le fichier **`index.html`** (version inline avec tout inclus).

---

## 📤 Étapes pour GitHub Pages

### 1. Créer un repository GitHub

1. Va sur [github.com](https://github.com)
2. Clique sur **"New repository"**
3. Nom : `mon-repertoire-scolaire` (ou ce que tu veux)
4. **IMPORTANT :** Coche **"Add a README file"**
5. Clique sur **"Create repository"**

---

### 2. Uploader le fichier

#### Méthode A : Drag & Drop (la plus simple)

1. Dans ton repository, clique sur **"Add file"** → **"Upload files"**
2. **Glisse-dépose** le fichier `index.html`
3. Clique sur **"Commit changes"**

#### Méthode B : Édition directe

1. Dans ton repository, clique sur **"Add file"** → **"Create new file"**
2. Nom du fichier : `index.html`
3. Copie-colle le contenu du fichier `index.html`
4. Clique sur **"Commit new file"**

---

### 3. Activer GitHub Pages

1. Va dans l'onglet **"Settings"** (en haut)
2. Dans le menu de gauche, clique sur **"Pages"**
3. Section **"Build and deployment"**
4. Source : **"Deploy from a branch"**
5. Branch : **"main"** / **"/(root)"**
6. Clique sur **"Save"**

---

### 4. Ajouter tes fichiers PDF et images

1. Dans ton repository, clique sur **"Add file"** → **"Upload files"**
2. Sélectionne tes fichiers :
   - 📄 Fichiers PDF (cours, TP, TD...)
   - 🖼️ Images (PNG, JPG, JPEG...)
3. Clique sur **"Commit changes"**

---

### 5. Voir ton site 🎉

1. Retourne dans **Settings** → **Pages**
2. Tu verras l'URL de ton site :
   ```
   https://ton-username.github.io/mon-repertoire-scolaire/
   ```
3. Clique sur le lien ou attends 2-3 minutes que ça se déploie

---

## 📁 Structure finale de ton repository

```
mon-repertoire-scolaire/
├── 📄 index.html          ← Le site (OBLIGATOIRE)
├── 📄 README.md           ← Ce fichier (optionnel)
│
├── 📄 cours-maths.pdf     ← Tes fichiers
├── 📄 tp-info.pdf
├── 🖼️ diagramme.png
├── 🖼️ photo.jpg
└── ...
```

---

## ❌ Problèmes courants

### Page blanche ?

| Cause | Solution |
|-------|----------|
| Mauvais fichier uploadé | Utilise le fichier `index.html` (pas `index-inline.html`) |
| Fichier corrompu | Re-télécharge le fichier |
| GitHub Pages pas activé | Vérifie Settings → Pages → Source = "Deploy from a branch" |

### Fichiers pas détectés ?

1. Vérifie que tes PDF/images sont bien uploadés
2. Rafraîchis la page (F5)
3. Attends 1-2 minutes que GitHub Pages mette à jour

---

## 🔗 Lien Snapchat

Pour modifier le lien Snapchat, édite le fichier `src/sections/Footer.tsx` dans le code source, ou contacte-moi.

---

**Bonne chance ! 🎓**

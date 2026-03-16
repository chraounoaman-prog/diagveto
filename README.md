# 🚀 DiagVeto — Guide de déploiement Vercel

## Ce que tu vas obtenir
- Ton site en ligne sur une vraie URL (ex: diagveto.vercel.app)
- Ta clé API Anthropic cachée et sécurisée
- Gratuit, sans carte bancaire

---

## Étape 1 — Créer un compte GitHub (si pas déjà fait)
1. Va sur https://github.com
2. Clique "Sign up" → crée un compte gratuit

---

## Étape 2 — Mettre les fichiers sur GitHub
1. Connecte-toi à GitHub
2. Clique le bouton **"+"** en haut à droite → **"New repository"**
3. Nom du repo : `diagveto`
4. Laisse tout par défaut → clique **"Create repository"**
5. Sur la page suivante, clique **"uploading an existing file"**
6. Glisse-dépose ces fichiers :
   - `index.html`
   - le dossier `api/` avec `diagnose.js` dedans
7. Clique **"Commit changes"**

---

## Étape 3 — Déployer sur Vercel
1. Va sur https://vercel.com
2. Clique **"Sign up"** → connecte-toi avec ton compte GitHub
3. Clique **"Add New Project"**
4. Sélectionne ton repo `diagveto`
5. Clique **"Deploy"** (laisse tout par défaut)
6. Attends 1 minute → ton site est en ligne ! 🎉

---

## Étape 4 — Ajouter ta clé API (IMPORTANT)
Sans ça, le diagnostic ne fonctionnera pas.

1. Dans Vercel, va dans ton projet → onglet **"Settings"**
2. Dans le menu gauche : **"Environment Variables"**
3. Ajoute :
   - **Name** : `ANTHROPIC_API_KEY`
   - **Value** : ta clé (commence par `sk-ant-...`)
4. Clique **"Save"**
5. Va dans l'onglet **"Deployments"** → clique les **3 points** → **"Redeploy"**

---

## C'est tout ! 🐾
Ton site est maintenant sécurisé et en ligne.
Ta clé API n'est plus visible dans le code source.

---

## Où trouver ta clé Anthropic ?
→ https://console.anthropic.com/settings/keys

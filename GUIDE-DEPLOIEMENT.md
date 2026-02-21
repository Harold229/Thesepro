# Déployer ThèsePro sur Vercel — Guide pas à pas

## Ce que vous aurez à la fin
Une URL publique du type **thesepro.vercel.app** accessible sur n'importe quel téléphone ou navigateur, gratuitement.

---

## Étape 1 — Créer un compte GitHub (si pas encore fait)
1. Aller sur **github.com**
2. Cliquer **Sign up** → renseigner email + mot de passe
3. Vérifier votre email

---

## Étape 2 — Créer le dépôt GitHub

1. Une fois connecté, cliquer le **+** en haut à droite → **New repository**
2. Remplir :
   - Repository name : `thesepro`
   - Visibility : **Public** ✓
   - Cocher **Add a README file**
3. Cliquer **Create repository**

---

## Étape 3 — Uploader vos 2 fichiers

Dans votre nouveau dépôt GitHub :

1. Cliquer **Add file** → **Upload files**
2. Glisser-déposer les 2 fichiers téléchargés :
   - `index.html`
   - `vercel.json`
3. En bas, cliquer **Commit changes**

Votre dépôt doit maintenant contenir 3 fichiers : `README.md`, `index.html`, `vercel.json`

---

## Étape 4 — Créer un compte Vercel

1. Aller sur **vercel.com**
2. Cliquer **Sign Up** → choisir **Continue with GitHub**
3. Autoriser Vercel à accéder à vos dépôts GitHub

---

## Étape 5 — Déployer

1. Sur Vercel, cliquer **Add New Project**
2. Sélectionner votre dépôt `thesepro` → cliquer **Import**
3. Laisser tous les paramètres par défaut
4. Cliquer **Deploy**

⏱️ Attendre 30 à 60 secondes…

🎉 Votre site est en ligne ! Vercel vous donne une URL du type :
**https://thesepro-xxxx.vercel.app**

---

## Étape 6 — Personnaliser l'URL (optionnel)

Dans Vercel → votre projet → **Settings** → **Domains**

Vous pouvez changer l'URL en quelque chose comme :
**thesepro-afrique.vercel.app**

---

## Mettre à jour l'application plus tard

Quand vous voulez modifier l'app :
1. Retourner sur GitHub → votre dépôt
2. Cliquer sur `index.html` → icône crayon ✏️ (Edit)
3. Modifier → **Commit changes**

Vercel redéploie automatiquement en moins de 30 secondes. ✓

---

## Résumé des fichiers à uploader

| Fichier | Rôle |
|---------|------|
| `index.html` | L'application complète |
| `vercel.json` | Configuration Vercel |

---

*En cas de problème : vercel.com/docs ou github.com/support*

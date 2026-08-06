# Journal d'une Classe Multiniveaux — guide de mise en ligne

Ce dossier contient tout le site. Suis ces étapes dans l'ordre, ça prend une dizaine de minutes.

## 1. Créer un compte GitHub (gratuit)
Va sur github.com, crée un compte. C'est là que vivront les fichiers du site.

## 2. Créer un nouveau dépôt (repository)
- Clique sur "New repository"
- Donne-lui un nom, par exemple `journal-classe-multi`
- Laisse-le en "Public"
- Crée-le, puis mets en ligne (upload) tous les fichiers de ce dossier dedans (glisser-déposer fonctionne)

## 3. Créer un compte Netlify (gratuit)
Va sur netlify.com, crée un compte (tu peux te connecter directement avec ton compte GitHub, c'est plus rapide).

## 4. Connecter le site à Netlify
- Sur Netlify, clique sur "Add new site" → "Import an existing project"
- Choisis GitHub, puis sélectionne le dépôt `journal-classe-multi`
- Laisse les réglages par défaut, clique sur "Deploy"
- Ton site est en ligne ! Netlify te donne une adresse type `nom-au-hasard.netlify.app`

## 5. Activer Netlify Identity (pour te connecter à l'admin)
- Dans le tableau de bord Netlify de ton site, va dans "Site configuration" → "Identity"
- Clique sur "Enable Identity"
- Toujours dans Identity, va dans "Services" → active "Git Gateway"
- Retourne dans Identity → "Invite users" → invite-toi avec ton propre email

## 6. Se connecter à l'admin
- Va sur `tonsite.netlify.app/admin/`
- Accepte l'invitation reçue par email, crée ton mot de passe
- Tu arrives sur l'interface d'administration : c'est là que tu ajoutes tes articles, sans avoir besoin de moi

## 7. (Plus tard) Nom de domaine personnalisé
Si tu veux remplacer `tonsite.netlify.app` par un nom à toi, ça se fait dans "Domain settings" sur Netlify, une fois que tu auras acheté un nom de domaine (~12€/an).

---

Une fois que tout ça est fait, dis-le moi — je peux vérifier avec toi que tout fonctionne bien, et on enchaîne sur la rédaction des premiers vrais articles.

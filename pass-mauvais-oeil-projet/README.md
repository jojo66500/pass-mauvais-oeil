# Pass Mauvais Œil — Mettre l'application en ligne

Ce guide explique, sans aucune connaissance technique, comment publier ton
application sur Internet et comment y ajouter tes images. **Aucune ligne de
commande n'est nécessaire** : tout se fait depuis le site de GitHub et celui de
Vercel.

Le principe : **GitHub** garde ton projet (le code + les images), et **Vercel**
transforme ce projet en vrai site web accessible par un lien, et le met à jour
tout seul à chaque changement.

---

## Ce que contient ce dossier

```
pass-mauvais-oeil-projet/
├── index.html            ← page d'accueil technique (ne pas modifier)
├── package.json          ← liste des outils (ne pas modifier)
├── vite.config.js        ← réglage de construction (ne pas modifier)
├── .gitignore            ← fichiers à ignorer (ne pas modifier)
├── src/
│   ├── main.jsx          ← démarrage de l'app (ne pas modifier)
│   └── PassMauvaisOeil.jsx ← TOUTE ton application est ici
└── public/
    └── images/           ← C'EST ICI que tu déposes tes images
        └── .gitkeep      ← petit fichier pour garder le dossier (ne pas supprimer)
```

Le seul fichier que tu modifieras vraiment un jour, c'est
`src/PassMauvaisOeil.jsx`. Et le seul dossier que tu rempliras, c'est
`public/images/`.

---

## Étape 1 — Créer un compte GitHub (une seule fois)

1. Va sur **https://github.com** et clique sur **Sign up**.
2. Choisis un identifiant, un e-mail, un mot de passe. C'est gratuit.

## Étape 2 — Créer le dépôt (le « tiroir » du projet)

1. Une fois connecté, clique sur le **+** en haut à droite → **New repository**.
2. **Repository name** : `pass-mauvais-oeil`
3. Laisse-le en **Public** (ou Private si tu préfères, ça marche aussi).
4. Ne coche rien d'autre, clique sur **Create repository**.

## Étape 3 — Déposer les fichiers du projet

1. **Décompresse** l'archive `pass-mauvais-oeil-projet.zip` sur ton ordinateur.
   Tu obtiens le dossier `pass-mauvais-oeil-projet` avec tout ce qu'il contient.
2. Sur la page de ton dépôt GitHub tout juste créé, clique sur le lien
   **uploading an existing file** (ou **Add file → Upload files**).
3. Ouvre le dossier décompressé, **sélectionne tout ce qu'il y a à l'intérieur**
   (les fichiers `index.html`, `package.json`, etc. **et** les dossiers `src` et
   `public`) et **fais-les glisser** dans la zone d'upload de GitHub.
   > Important : glisse le *contenu* du dossier, pas le dossier lui-même.
4. En bas, clique sur le bouton vert **Commit changes**.

Ton code est maintenant sur GitHub. 🎉

## Étape 4 — Mettre le site en ligne avec Vercel

1. Va sur **https://vercel.com** et clique sur **Sign Up**, puis choisis
   **Continue with GitHub** (connexion avec ton compte GitHub, plus simple).
2. Sur ton tableau de bord Vercel, clique sur **Add New… → Project**.
3. Vercel affiche tes dépôts GitHub. À côté de `pass-mauvais-oeil`, clique sur
   **Import**.
4. Vercel reconnaît tout seul qu'il s'agit d'un projet « Vite ». **Ne change
   rien**, clique simplement sur **Deploy**.
5. Attends une minute… et voilà : Vercel t'affiche un lien du type
   `pass-mauvais-oeil.vercel.app`. **C'est ton application en ligne**, tu peux
   l'ouvrir sur ton téléphone.

> Plus tard, pour un nom personnalisé comme `passmauvaisoeil.fr`, ça se règle
> dans Vercel → onglet **Domains**.

---

## Ajouter tes images

Tes emplacements d'images sont déjà tous branchés dans l'application. Il te suffit
de déposer les fichiers **au bon nom** dans le dossier `public/images/`.

### Les noms de fichiers à respecter (très important)

Le nom doit être **exactement** celui attendu, tout en **minuscules**. Exemples :
- l'emplacement `IMG-02` attend le fichier **`img-02.jpg`**
- l'emplacement `IMG-A` attend **`img-a.jpg`**
- l'emplacement `IMG-27` attend **`img-27.jpg`**
- le talisman du Soleil recto attend **`img-sol-r.png`**, verso **`img-sol-v.png`**

(La liste complète des 45 noms est dans ton autre document,
« pass-mauvais-oeil-GUIDE-IMAGES ».)

### Comment les déposer sur GitHub

1. Sur ton dépôt GitHub, entre dans le dossier **`public`**, puis **`images`**.
2. Clique sur **Add file → Upload files**.
3. Fais glisser tes images (bien renommées) dans la zone.
4. Clique sur **Commit changes**.
5. **Vercel se met à jour tout seul** en une minute environ. Rafraîchis ton site :
   l'image est apparue à sa place.

Tu peux y aller **image par image**, sans rien casser : tant qu'une image n'est
pas déposée, son emplacement reste affiché sous forme de cadre pointillé.

---

## Modifier un texte de l'application

1. Sur GitHub, va dans `src/PassMauvaisOeil.jsx`.
2. Clique sur l'icône **crayon** (Edit) en haut à droite du fichier.
3. Modifie ton texte, puis **Commit changes** en bas.
4. Vercel republie tout seul en une minute.

---

## Si un jour tu veux la méthode « développeur » (facultatif)

Sur ton ordinateur, avec Node.js installé, dans le dossier du projet :

```
npm install       # installe les outils (une seule fois)
npm run dev        # ouvre l'app en local pour tester
npm run build      # prépare la version finale
```

Puis tu envoies tes changements avec `git add .`, `git commit`, `git push`.
Mais pour démarrer, la méthode par le site GitHub ci-dessus suffit largement.

---

## Récapitulatif

1. Compte GitHub → nouveau dépôt `pass-mauvais-oeil`.
2. Upload du contenu de ce dossier → Commit.
3. Vercel → Import du dépôt → Deploy → lien en ligne.
4. Images : upload dans `public/images/` au bon nom → Vercel republie seul.

La prochaine grande étape sera la base de données Supabase, pour rendre les codes
d'activation réellement uniques et infalsifiables.

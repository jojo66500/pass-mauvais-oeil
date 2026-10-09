# Pass Mauvais Œil — Site prêt pour GitHub Pages

Cette version fonctionne **directement sur GitHub**, sans Vercel, sans
construction, sans réglage. Tu déposes les fichiers, tu actives GitHub Pages,
et c'est en ligne.

---

## Ce que contient ce dossier

```
index.html      ← la page (petite, lisible, modifiable)
app.js          ← toute l'application (généré, ne pas modifier à la main)
.nojekyll       ← fichier technique indispensable, ne pas supprimer
images/         ← C'EST ICI que tu déposes tes images
  .gitkeep      ← petit fichier pour garder le dossier, ne pas supprimer
README.md       ← ce guide
```

---

## Mise en ligne — 5 minutes

### 1. Repartir sur un dépôt propre

Pour éviter les restes de l'ancienne tentative, le plus simple est de créer un
dépôt neuf :

1. Sur **github.com**, clique sur le **+** en haut à droite → **New repository**.
2. **Repository name** : `pass-mauvais-oeil-app`
3. Laisse en **Public** (obligatoire pour GitHub Pages gratuit).
4. **Create repository**.

### 2. Déposer les fichiers

1. Décompresse l'archive sur ton ordinateur.
2. Sur la page du dépôt, clique **uploading an existing file**.
3. Ouvre le dossier décompressé et **sélectionne tout ce qu'il y a dedans**
   (`index.html`, `app.js`, `.nojekyll`, le dossier `images`, `README.md`).
   > Glisse le **contenu** du dossier, jamais le dossier lui-même.
   > C'est l'erreur qui a tout bloqué la dernière fois.
4. Clique le bouton vert **Commit changes**.

Après l'upload, tu dois voir `index.html` et `app.js` **directement** dans la
liste, sans avoir à cliquer sur un sous-dossier. Si tu vois un dossier à ouvrir,
c'est raté : recommence en glissant le contenu.

> Le fichier `.nojekyll` commence par un point : certains systèmes le cachent.
> Si tu ne le vois pas, active l'affichage des fichiers cachés, ou crée-le
> directement sur GitHub (**Add file → Create new file**, nomme-le `.nojekyll`,
> laisse vide, **Commit**).

### 3. Activer GitHub Pages

1. Dans ton dépôt, onglet **Settings** (en haut).
2. Menu de gauche → **Pages**.
3. Sous **Source**, choisis **Deploy from a branch**.
4. **Branch** : `main` — et dossier : `/ (root)`.
5. Clique **Save**.

Attends 1 à 2 minutes, recharge la page : GitHub affiche ton adresse, du type

```
https://jojo66500.github.io/pass-mauvais-oeil-app/
```

**C'est cette adresse que tu inscriras dans la puce NFC du pendentif.**

---

## Ajouter tes images

Tous les emplacements sont déjà câblés. Il suffit de déposer les fichiers au bon
nom dans le dossier `images`.

### Déposer sur GitHub

1. Dans ton dépôt, clique sur le dossier **`images`**.
2. **Add file → Upload files**.
3. Glisse tes images (bien renommées), puis **Commit changes**.
4. Attends une minute, recharge ton site : l'image est en place.

Tu peux y aller **image par image**. Tant qu'une image manque, son emplacement
reste un cadre pointillé — rien ne casse.

### Les noms de fichiers (à respecter exactement, tout en minuscules)

**Ambiance et produit (JPG, 1200 px de large)**

| Fichier | Où | Sujet |
|---|---|---|
| `img-01.jpg` | Écran d'activation | Le pendentif œil bleu avec sa puce, sur velours sombre |
| `img-a.jpg` | Accueil | Table de grimoire vue du dessus |
| `img-b.jpg` | Rituels | Mains allumant l'encens à l'allumette en bois |
| `img-c.jpg` | Ma Carte | Le pendentif tenu en main près d'un téléphone |
| `img-27.jpg` | Almanach → Fumées | Coupelles d'encens et de myrrhe |

**Chapitres du grimoire (JPG, 1200 × 675 px)**

`img-02.jpg` origines · `img-03.jpg` signes · `img-04.jpg` rite de l'huile ·
`img-05.jpg` sortilèges · `img-06.jpg` sel · `img-07.jpg` gestes protecteurs ·
`img-08.jpg` amulettes · `img-09.jpg` talismans · `img-10.jpg` pentacles ·
`img-11.jpg` bouclier de la pensée · `img-12.jpg` purification ·
`img-13.jpg` plantes · `img-14.jpg` animaux · `img-15.jpg` coup en retour ·
`img-16.jpg` neutralisation · `img-17.jpg` vampirisme ·
`img-18.jpg` corps éthérique · `img-19.jpg` eau salée · `img-20.jpg` Pharaon ·
`img-21.jpg` mantras · `img-22.jpg` magie angélique · `img-23.jpg` blanche/noire ·
`img-24.jpg` vaudou · `img-25.jpg` wicca · `img-26.jpg` superstitions ·
`img-28.jpg` art du talisman

**Talismans planétaires (PNG, 800 × 800 px)** — à scanner depuis ton livre

`img-sol-r.png` / `img-sol-v.png` (Soleil) · `img-lun-r.png` / `img-lun-v.png` (Lune) ·
`img-mar-r.png` / `img-mar-v.png` (Mars) · `img-mer-r.png` / `img-mer-v.png` (Mercure) ·
`img-jup-r.png` / `img-jup-v.png` (Jupiter) · `img-ven-r.png` / `img-ven-v.png` (Vénus) ·
`img-sat-r.png` / `img-sat-v.png` (Saturne)

**Bonus** : `favicon.png` (512 × 512) — la petite icône de l'onglet et de
l'écran d'accueil du téléphone. Mets-y ton œil nazar.

---

## Le pendentif NFC

Une fois ton adresse GitHub Pages obtenue, programme la puce avec une
application d'écriture NFC (NFC Tools, par exemple) :

1. Ouvre l'app, onglet **Écrire** → **Ajouter un enregistrement** → **URL**.
2. Saisis ton adresse, par exemple
   `https://jojo66500.github.io/pass-mauvais-oeil-app/`
3. Approche le pendentif, valide l'écriture.
4. **Verrouille la puce** (option « Verrouiller la balise ») pour qu'un client
   ne puisse pas réécrire dessus.

Au contact du pendentif, le téléphone ouvre directement le grimoire.

---

## À savoir honnêtement

Avec GitHub Pages seul, **les codes d'activation ne sont pas encore
infalsifiables** : ils sont contenus dans l'application, donc un acheteur averti
pourrait partager le lien. C'est suffisant pour tes premiers pendentifs et pour
tester le marché — l'adresse n'est pas devinable et le pendentif reste l'objet
de valeur.

Pour un vrai verrou (chaque code utilisable une seule fois, lié à un appareil),
il faudra plus tard une base de données en ligne. Ça se branchera sur cette même
version sans tout refaire.

---

## Modifier un texte plus tard

Les textes sont dans `app.js`, mais ce fichier est compressé et illisible.
Pour toute modification de contenu, reviens me voir avec la demande : je te
régénère un `app.js` à remplacer (upload du nouveau fichier par-dessus l'ancien,
GitHub garde le même nom, le site se met à jour tout seul).

# Portfolio — Vanelle Ayonta Ndjoutse

Portfolio d'une seule page, autonome (tout est dans `index.html`), dans le même style
que le CV (bleu marine + gris, police Lato). Prêt à publier gratuitement.

---

## 🚀 Publier sur GitHub Pages (adresse : `vanelle-ayonta.github.io`)

> Pour obtenir l'adresse racine `https://VOTRE-PSEUDO.github.io`, le dépôt doit
> **impérativement** s'appeler `VOTRE-PSEUDO.github.io`.

1. Sur GitHub : **New repository**.
   - Nom du dépôt : `vanelle-ayonta.github.io` (remplacez par votre vrai pseudo GitHub).
   - Cochez **Public**.
2. Téléversez le fichier **`index.html`** (et `cv.pdf` si vous l'avez ajouté) à la racine
   du dépôt — bouton **Add file → Upload files** → glissez-déposez → **Commit**.
3. **Settings → Pages** : vérifiez que la source est la branche `main`, dossier `/ (root)`.
4. Patientez ~1 minute : votre portfolio est en ligne sur
   **`https://vanelle-ayonta.github.io`** 🎉

### Alternative encore plus simple (Netlify Drop)
Allez sur **app.netlify.com/drop** et glissez-déposez le dossier `portfolio/`.
Le site est en ligne en 10 secondes sur une adresse `…netlify.app`.

---

## ✏️ À personnaliser AVANT de publier

Ouvrez `index.html` et remplacez ces 3 éléments (recherchez les commentaires `⚠️`) :

1. **Lien du CV** — déposez votre PDF dans ce dossier sous le nom **`cv.pdf`**
   (le bouton « Télécharger mon CV » pointe déjà dessus).
2. **LinkedIn** — remplacez `https://www.linkedin.com/in/vanelle-ayonta` par votre vraie URL.
3. **GitHub** — remplacez `https://github.com/vanelle-ayonta` par votre vraie URL.

L'e-mail (`vanelleayonta@gmail.com`) est déjà renseigné à deux endroits.

---

## 🎨 Modifier le contenu ou les couleurs

- **Couleurs** : en haut du `<style>`, bloc `:root { --navy: …; --accent: …; }`.
  Ce sont exactement les couleurs de votre CV.
- **Textes / projets** : chaque section est balisée par un commentaire
  (`<!-- =================== PROJETS =================== -->`, etc.).
  Pour ajouter un projet, copiez un bloc `<article class="card"> … </article>`.
- **Police** : changez `Lato` dans le lien Google Fonts (`<head>`) et dans
  `font-family` du `body`.

---

## 🔗 Relier le portfolio au CV

Une fois l'adresse connue (ex. `vanelle-ayonta.github.io`), donnez-la-moi :
je mets à jour `\cvPortfolioURL` dans le `settings.tex` du CV pour que le lien
« Portfolio » y soit correct et cliquable.

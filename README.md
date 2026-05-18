# Site — Politique de confidentialité

Page statique `index.html` à mettre en ligne pour obtenir l'URL exigée par le
formulaire instantané Meta (et future landing page).

## ⚠️ À vérifier / remplacer dans `index.html` avant publication

| Cherche | Remplace par |
|---|---|
| `Ozanie` | Le **nom légal exact** de ton entreprise (raison sociale enregistrée, ex. « Ozanie inc. ») |
| `confidentialite@ozanie.com` | Un **courriel réellement surveillé** pour les demandes d'accès/retrait |
| `Offres Internet & Mobile Québec` | (laisser tel quel si c'est bien le nom de ta Page) |

Si le nom légal et la marque sont identiques, laisse `Ozanie` partout.

## Mettre en ligne — Option A : GitHub Pages (gratuit)

```bash
cd site
git init
git add .
git commit -m "Politique de confidentialité"
# crée un repo sur github.com puis :
git remote add origin https://github.com/<toi>/<repo>.git
git push -u origin main
```
Puis sur GitHub : **Settings → Pages → Source: branch `main` / root**.
URL obtenue : `https://<toi>.github.io/<repo>/`

## Mettre en ligne — Option B : Vercel (gratuit, custom domain facile)

```bash
cd site
npx vercel        # suit les invites, déploie le dossier
```
URL obtenue : `https://<projet>.vercel.app/`

## L'URL à coller dans Meta

Une fois en ligne, l'URL de la politique = la racine du site (ex.
`https://<toi>.github.io/<repo>/`). Colle-la dans le champ
**Lien de politique de confidentialité** du formulaire instantané.

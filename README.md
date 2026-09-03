# Luxury Club — refonte visuelle

Site principal basé sur le **style** moderne de [911 Rennsport](https://www.911rennsport.co.uk), avec le **contenu** métier de [Luxury Club](https://www.luxury-club.fr).

## Structure

| Emplacement | Rôle |
|-------------|------|
| `/` (racine) | Site principal (template Webflow Rennsport + contenus Luxury Club) |
| `archive/luxury-club-fr/` | Miroir archivé de l’ancien site (référence) |
| `assets/` | Logo / favicon Luxury Club |

## Mapping des pages

| Page style (ex-Rennsport) | Contenu Luxury Club |
|---------------------------|---------------------|
| `index.html` | Accueil |
| `current-stock.html` | Location voiture de luxe (+ fiches dans `current-stock/`) |
| `models.html` | Marques |
| `about-us.html` | À propos |
| `contact.html` | Contact |
| `faqs.html` | FAQ |
| `bespoke-builds.html` | Séjours de luxe |
| `projects.html` | Location de yacht |
| `upgrades.html` | Voiture avec chauffeur |
| `restoration.html` | Conciergerie & gardiennage |
| `gallery.html` | Références |
| `terms-conditions.html` | Mentions / confidentialité |
| `location-voiture-mariage.html` | Mariage |
| `evenementiel-automobile.html` | Événementiel |
| `location-voiture-de-collection.html` | Collection |
| `automobile-club.html` | Automobile Club |
| `location-{paris,cannes,nice,monaco}.html` | Pages villes |

## Notes

- Le CSS/JS du design reste servi via le CDN Webflow (le style n’a pas été modifié).
- Les images véhicules pointent vers l’archive locale ou le site Luxury Club.
- Certains assets de l’ancien site ont pu manquer au miroir (erreurs 503).
<<<<<<< HEAD


## GitHub Pages

URL prévue : **https://mb-studioweb.github.io/luxury-club/**

1. Repo → **Settings** → **Pages**
2. Source : **Deploy from a branch** → branche `gh-pages` → dossier `/` (ou **GitHub Actions** si tu préfères le workflow)
3. Enregistrer — le site est en ligne en ~1 min
=======
>>>>>>> origin/main

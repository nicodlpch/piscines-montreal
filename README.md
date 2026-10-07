# Piscines Montréal — PWA

Application web installable basée sur les horaires du fichier Excel.

## Tester localement

Dans ce dossier :

```bash
python -m http.server 8000
```

Puis ouvrir http://localhost:8000

## Publier gratuitement sur GitHub Pages

1. Créer un dépôt GitHub (par exemple `piscines-montreal`).
2. Ajouter tous les fichiers de ce dossier à la racine du dépôt.
3. Dans GitHub : Settings → Pages → Source : Deploy from a branch → `main` / root.
4. Attendre l’URL `https://VOTRE-NOM.github.io/piscines-montreal/`.
5. Sur iPhone : ouvrir l’URL dans Safari → Partager → Ajouter à l’écran d’accueil.

## Données

Les horaires sont dans `data.json`. Les sources officielles de la Ville de Montréal sont conservées pour chaque piscine/créneau.

## Fonctionnalités V1

- jour + heure ;
- priorité couloirs de nage ;
- carte OpenStreetMap interactive ;
- piscines disponibles / indisponibles ;
- recommandation ;
- géolocalisation (sur HTTPS) ;
- distance à vol d’oiseau ;
- lien Google Maps ;
- installation PWA.

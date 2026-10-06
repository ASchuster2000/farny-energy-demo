# Farny Energy — Démo GitHub Pages

Démo statique du futur site institutionnel de Farny Energy.

## Contenu
- `index.html` : page unique
- `styles.css` : design responsive
- `script.js` : navigation mobile, animations et formulaire de démonstration
- `assets/` : logo et photographies fournies pour le projet

## Lancer localement
Ouvrir simplement `index.html`, ou utiliser un petit serveur local :

```bash
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## GitHub Pages
1. Dans **Settings → Pages**, sélectionner **Deploy from a branch**.
2. Choisir la branche `main` et le dossier `/ (root)`.
3. Enregistrer.

Le site contient volontairement :
```html
<meta name="robots" content="noindex,nofollow">
```
pour éviter l'indexation de la démo. À retirer avant la mise en production publique.

## Important
Le formulaire de devis est uniquement visuel dans cette V1 : aucune donnée n'est envoyée ni stockée.

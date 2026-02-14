# Signature Visuelle — Version Administrateur

## Objectif
Gérer vos réalisations sans coder, puis alimenter automatiquement le site public.

## Fichiers
- index.html : site public (charge projects.json OU localStorage)
- admin.html : interface admin (ajout/édition/suppression)
- projects.json : données (si présent en ligne → utilisé en priorité)
- tour-*.html : démos (peuvent être remplacées par vos vrais liens)

## Workflow PRO (recommandé)
1) Ouvrez admin.html sur votre PC
2) Ajoutez vos projets
3) Cliquez “Exporter projects.json”
4) Uploadez projects.json à côté de index.html sur votre hébergeur
✅ Le site public affichera vos projets sur tous les appareils (TV incluse)

## Workflow rapide (sur le même PC uniquement)
- Si vous n’uploadez pas projects.json, le site lira la liste stockée dans le navigateur (localStorage).
- Attention : ça ne se synchronise pas entre appareils.

## Sécurité
Le mot de passe admin est une protection simple côté navigateur. Pour une vraie sécurité, protégez admin.html via l’hébergeur.

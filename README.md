# Répertoire des signes pour 🦐

Petite application web pour découvrir la langue des signes pour bébé.
68 signes du quotidien, chacun illustré par une vidéo issue du dictionnaire [Elix LSF](https://dico.elix-lsf.fr/).

## Utilisation

Ouvrir [index.html](index.html) dans un navigateur, ou consulter la version en ligne déployée sur Cloudflare Pages.

Les signes sont organisés en :
- **3 niveaux de priorité** (Premiers signes, À venir, Plus tard)
- **7 catégories** (Repas, Sommeil & soins, Personnes & lieux, Émotions & ressenti, Activités & jeu, Communication & politesse, Consignes & sécurité)

Une barre de recherche et des filtres par catégorie permettent de retrouver rapidement un signe.

## Installation sur mobile

L'app est progressive (PWA) : sur iOS ou Android, ouvrir le site dans le navigateur puis « Ajouter à l'écran d'accueil ». Elle s'ouvre alors comme une application native.

## Déploiement

Site 100 % statique, aucun build requis. Déployable sur :
- **Cloudflare Pages** (recommandé) — connecter le repo GitHub, build command vide, output `/`
- GitHub Pages, Netlify, Vercel, ou n'importe quel hébergeur de fichiers statiques

## Structure

```
index.html              Application complète (HTML + CSS + JS inline)
manifest.webmanifest    Configuration PWA
icon-192.png            Icône 192×192
icon-512.png            Icône 512×512
_headers                Headers Cloudflare Pages (cache, sécurité)
signes-marius.xlsx      Export tableur des signes (référence)
```

## Crédits

- Vidéos LSF : [Elix](https://dico.elix-lsf.fr/) — dictionnaire collaboratif de la langue des signes française
- Icône shrimp : [OpenMoji](https://openmoji.org/) (CC BY-SA 4.0)
- Inspiration des signes : livret « bébé signe » de la crèche Roger-Michel (Frontignan)

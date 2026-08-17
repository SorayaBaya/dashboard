# Portfolio — Reporting & analyse de données immobilières

Site vitrine présentant deux modèles de tableaux de bord Excel construits sur des
données **fictives**, pour illustrer un savoir-faire en reporting financier et
immobilier.

## Contenu

- `index.html`, `assets/style.css`, `assets/script.js` — le site (une seule page).
- `projets/Dashboard_Agences.xlsx` — tableau de bord de suivi d'une régie
  immobilière multi-agences (Suisse romande).
- `projets/Dashboard_Fonds.xlsx` — tableau de bord de suivi d'un fonds
  immobilier (NAV, LTV, taux d'occupation, cash-flow).
- `assets/CV_Prenom_Nom.pdf` — à remplacer par votre propre CV.

## À personnaliser avant publication

1. Remplacer **"Prénom Nom"** partout dans `index.html` (titre, `<h1>`, footer).
2. Remplacer l'e-mail et le lien LinkedIn dans la section `<header class="masthead">`
   et dans `#contact`.
3. Ajouter votre CV réel dans `assets/CV_Prenom_Nom.pdf`.
4. Remplacer les blocs `.dossier-preview` (actuellement un simple encadré en
   pointillés) par une vraie capture d'écran de chaque tableau de bord :
   - dans Excel, ouvrez l'onglet "Dashboard"/"KPI", `Fichier > Exporter > Modifier
     la taille du fichier PDF` ou une simple capture d'écran (Win+Maj+S / Cmd+Maj+4),
   - enregistrez en `.png` dans `assets/`,
   - remplacez le `<div class="dossier-preview">…</div>` par
     `<img src="assets/apercu-agences.png" alt="Aperçu du tableau de bord régie">`.
5. Vérifier que les chiffres du bandeau "ticker" (ex. "5 agences · ~1 240 lots
   gérés") correspondent bien à vos données au moment de la publication.

## Publier avec GitHub Pages

Voir les instructions détaillées données dans la conversation. En résumé :
créer un dépôt public, y pousser ces fichiers, puis activer GitHub Pages
(Settings → Pages → Branch: main → dossier `/root`).

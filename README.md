# Portfolio cybersécurité — 3 projets interactifs

Site statique en HTML, CSS et JavaScript, sans dépendances ni serveur.

## Lancer le site

Ouvrir `index.html` dans Chrome, Edge ou Firefox. Les trois démonstrations sont intégrées à la section « Laboratoire interactif ».

## Projets

1. **Analyseur de mots de passe** : vérification locale de cinq critères simples, conseils et indicateur de robustesse. Ne pas tester de vrais mots de passe.
2. **Analyseur d'URL** : analyse de quelques indices structurels (HTTP, adresse IP, Punycode, `@`, longueur, sous-domaines, termes sensibles). Aucun accès réseau et aucune vérification de réputation.
3. **Quiz cybersécurité** : cinq questions sur phishing, MFA, correctifs, HTTPS et mots de passe ; correction et score.

Ces outils sont des démonstrations pédagogiques, pas des solutions de sécurité professionnelles. Ils ne remplacent pas un audit ou une analyse spécialisée.

## Personnaliser

- Modifier le texte de présentation dans `index.html` (chercher « Étudiant en informatique »).
- Ajouter son nom et son adresse de contact dans la section `id="contact"`.
- Modifier les couleurs dans `style.css` (`:root`).
- Adapter les questions du quiz dans `script.js` (`questions`).

## Publier gratuitement sur GitHub Pages

1. Ouvrir **Settings → Pages** dans ce dépôt.
2. Sélectionner **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`.
3. Enregistrer avec **Save**.
4. Après publication, ouvrir l'adresse indiquée par GitHub Pages (généralement `https://renato1245.github.io/cyber-portfolio/`).

## Vérifications conseillées

- Ouvrir les trois projets et vérifier les résultats.
- Vérifier l'affichage sur mobile.
- Ne pas inclure de secrets, vrais mots de passe ou données personnelles dans le dépôt.

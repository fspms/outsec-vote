# OutSec — page de vote (téléphone)

Page statique unique (`docs/index.html`) qui permet au public de voter depuis son téléphone
pendant une présentation OutSec. Elle se connecte à une salle via un code de 5 caractères
(`?r=CODE`, fourni par QR code).

- Aucune donnée personnelle collectée, aucune analytique, aucun cookie.
- Un identifiant technique anonyme (Supabase Auth) et un jeton aléatoire stocké sur l'appareil
  servent uniquement à limiter chaque appareil à un vote par question.
- Ce dépôt ne contient que cette page construite ; elle est régénérée, ne pas l'éditer ici.

Publication : GitHub Pages, branche `main`, dossier `/docs`.

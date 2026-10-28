# marhaba — guide d'usage du logo

**Idée :** une arche marocaine dont les deux pieds sont des points. Deux villes, un seul passage d'accueil.

## Fichiers
| Fichier | Usage |
|---|---|
| `marhaba-symbol.svg` | Symbole en couleurs (usage principal) |
| `marhaba-symbol-small.svg` | Version petite taille (trait épaissi), pour moins de 32 px |
| `marhaba-horizontal.svg` | Logo horizontal : symbole + nom |
| `marhaba-stacked.svg` | Logo empilé : symbole au-dessus du nom |
| `marhaba-wordmark.svg` | Nom seul |
| `minimal/marhaba-app-icon.svg` / `-1024.png` | Icône d'application officielle : fond bleu uni, arche blanche unie, points safran, une seule ombre douce |
| `minimal/marhaba-app-icon-flat.svg` | Même icône sans ombre (impression, broderie) |
| `marhaba-app-icon.svg` | Ancienne icône plate sans ombre |
| `export/` | Noir, blanc, une couleur, favicon, icônes web, manifeste |

Le nom est dessiné en tracés (police Geist Bold, licence SIL OFL : usage logo autorisé). Aucun fichier ne dépend d'une police installée.

## Couleurs
| Rôle | Nom | HEX | RGB |
|---|---|---|---|
| Arche | Bleu Majorelle | `#2D4BE0` | 45, 75, 224 |
| Points | Safran | `#E39A12` | 227, 154, 18 |
| Nom | Nuit | `#0E1630` | 14, 22, 48 |

Versions : couleurs, noir, blanc ou une couleur (`#2D4BE0`). Sur fond sombre dans l'app, l'arche passe à `#8C9EFF`.
Valeurs CMYK et Pantone à faire valider par un imprimeur avant tout tirage.

## Zone de protection
Garder autour du logo un espace libre égal à **la largeur d'un point (52 unités sur 256, soit ≈ 20 % de la hauteur du symbole)**. Rien d'autre ne doit y entrer.

## Tailles minimales
- Symbole : 24 px en écran (utiliser `marhaba-symbol-small.svg` sous 32 px), 8 mm en impression.
- Logo horizontal : 96 px de large en écran.

## À faire / à éviter
- Utiliser uniquement les fichiers fournis.
- Fonds clairs : version couleurs. Fonds sombres ou photos : version blanche.
- Ne pas étirer, pivoter, ajouter d'ombre ou de contour.
- Ne pas changer les couleurs des points ni les inverser avec l'arche.
- Ne pas redessiner le nom dans une autre police.

## Limites connues
- Pas de recherche d'antériorité de marque : faire vérifier le nom et le symbole par un professionnel avant dépôt.
- Les traits des SVG sont déjà des surfaces, mais aucune union booléenne n'a été faite (pas d'éditeur vectoriel) : pour la découpe vinyle ou la broderie, faire passer le fichier par « Unir » dans un éditeur.

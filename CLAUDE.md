# Instructions pour le projet "Cours Religion"

## Mise à jour du glossaire (`fiqh/glossaire.md`)

Le glossaire recense tout le vocabulaire arabe écrit en phonétique (alphabet latin) présent dans les fichiers du dossier `fiqh/`.

### Quand mettre à jour

Après chaque ajout ou modification d'un fichier `.md`, `.txt` ou `.mmd` dans `fiqh/`, vérifier si de nouveaux termes arabes en phonétique apparaissent et les ajouter au glossaire.

### Structure du fichier

Le glossaire contient 3 sections, chacune sous forme de tableau Markdown :

1. **`## Vocabulaire général`** — termes arabes courants (concepts juridiques, actes rituels, catégories légales, etc.)
   - Colonnes : `Terme` | `Définition`
   - Trié par ordre alphabétique (les termes commençant par `3` sont classés au début)
2. **`## Noms propres (savants, imams, compagnons)`** — personnes historiques citées
   - Colonnes : `Nom` | `Identité`
   - Trié par ordre alphabétique
3. **`## Termes géographiques/historiques`** — lieux et termes historiques
   - Colonnes : `Terme` | `Définition`
   - Trié par ordre alphabétique

### Comment ajouter un terme

1. **Scanner** les fichiers nouveaux ou modifiés dans `fiqh/` pour repérer les mots arabes en translittération. Indices : mots contenant `3` (pour ع), `â`, `î`, `û`, ou des termes islamiques connus (ex : salat, wudu, fiqh, haram).
2. **Vérifier** que le terme n'existe pas déjà dans le glossaire (chercher aussi les variantes orthographiques).
3. **Dériver la définition** à partir du contexte du fichier source — ne pas inventer de définition qui ne serait pas appuyée par le contenu des cours.
4. **Insérer** le terme à la bonne position alphabétique dans la bonne section.
5. **Respecter le formatage** : le terme en **gras** (`**terme**`), colonnes alignées avec le reste du tableau.

### Conventions de translittération

- Le chiffre `3` représente la lettre arabe ع (ayn).
- Les accents circonflexes (`â`, `î`, `û`) indiquent des voyelles longues.
- Conserver la graphie phonétique telle qu'elle apparaît dans les fichiers sources.
- Si un même terme apparaît avec des variantes (ex : `shari3ah` / `sharî'a`), les regrouper dans une seule entrée séparée par ` / `.

### Ce qu'il ne faut pas faire

- Ne pas ajouter de termes qui n'apparaissent pas dans les fichiers du dossier `fiqh/`.
- Ne pas modifier les définitions existantes sans raison (sauf correction d'erreur factuelle).
- Ne pas supprimer de termes sauf s'ils ont été retirés de tous les fichiers sources.
- Ne pas ajouter de colonne "source" — le glossaire reste un document de référence concis.

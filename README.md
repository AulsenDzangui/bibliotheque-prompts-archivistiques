# Bienvenue dans la Bibliothèque de Prompts archivistiques

Ce projet a pour vocation de construire et de maintenir une collection de prompts de haute qualité, spécifiquement conçus pour assister les archivistes dans leurs tâches quotidiennes grâce à l'intelligence artificielle.

## Notre approche : la méthodologie "Prompts par activité métier"

Le cœur de notre démarche est de décomposer le métier d'archiviste en un ensemble d'activités fondamentales. Chaque activité se voit ensuite attribuer un ou plusieurs prompts dédiés, chacun visant un objectif précis.

Cette approche modulaire permet de créer des outils ciblés et performants.

`Métier (Archiviste) -> Activités (Classement, Description, etc.) -> Prompts Spécifiques`

### Deux rôles pour l'IA : une distinction essentielle

Chaque prompt est conçu pour que l'IA endosse l'un des deux rôles suivants :

| Rôle | Objectif Principal | Type de Livrable |
| :--- | :--- | :--- |
| 💡 **Consultant** | Aider à la décision, analyser, recommander. | Rapport d'analyse, étude comparative, aide-mémoire. |
| ✍️ **Exécutant** | Produire un livrable concret et directement utilisable. | Document formaté (JSON, XML), script, plan de classement finalisé. |

Cette distinction clarifie l'intention de chaque prompt et assure que le résultat soit aligné avec les attentes de l'utilisateur.

### Ancrage dans les processus métier

Chaque prompt est conçu en s'inspirant des processus et procédures réels du métier d'archiviste. Cela garantit que les livrables sont non seulement pertinents, mais aussi directement intégrables dans un flux de travail professionnel.

### Supervision humaine

L'IA est un assistant, pas un substitut. La responsabilité professionnelle et légale impose une **revue humaine systématique** de tous les livrables produits par l'IA. Chaque prompt doit idéalement mentionner les points de contrôle nécessitant une validation humaine.

## La structure d'un prompt : l'assistant expert supervisé

Chaque prompt suit une structure en 9 points qui transforme l'IA en assistant expert :

1. **Rôle et contexte** d'intervention
2. **Glossaire** des termes archivistiques
3. **Objectif** principal
4. **Principes** et normes à respecter
5. **Méthodologie** étape par étape
6. **Flux de travail** avec l'utilisateur
7. **Livrables** attendus
8. **Comportement** (ton, style, confidentialité)
9. **Exemples** pour plus de précisions

## Gouvernance et amélioration continue

### Versioning

Chaque prompt dispose d'un système de versioning simple (ex: v1.0, v1.1, v2.0) indiqué dans sa fiche technique. Les prompts évolueront avec les retours d'expérience et les progrès des modèles d'IA.

### Retours d'expérience

La contribution la plus précieuse est le retour sur l'efficacité (ou l'inefficacité) d'un prompt. Les utilisateurs sont invités à créer des issues sur le dépôt GitHub du projet pour signaler les succès, les échecs et proposer des améliorations.

## Comment utiliser et contribuer ?

1. **Explorez** : Naviguez dans le dossier `/prompts` pour découvrir les prompts classés par catégorie.
2. **Consultez** : Chaque prompt finalisé est composé d'une version markdown qui est la version de travail avec l'IA (sans références) et d'une version PDF accompagnée d'une fiche technique décrivant le prompt.
3. **Contribuez** : Pour proposer un nouveau prompt, veuillez tout simplement suivre la structure proposée ci-dessus. Vous êtes libre d'adapter la méthodologie à votre besoin.

## Licence

Cette œuvre est mise à disposition selon les termes de la
[licence Creative Commons Attribution - Partage dans les Mêmes Conditions 4.0 International][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/deed.fr
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

---
*Modèles de licence inspirés de [santisoler/cc-licenses](https://github.com/santisoler/cc-licenses)*

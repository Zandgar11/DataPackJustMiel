#Ce README n'est plus à jour - 20/01

# Datapack JustMielzAndGar

Ce datapack ajoute des recettes personnalisées ainsi que des effets spécifiques liés à des consommables comme de la drogue et des alcools dans Minecraft. Il est compatible avec la dernière version du jeu.

## Installation

1. Téléchargez le dossier du datapack.
2. Placez-le dans le répertoire suivant : `saves/<nom_de_votre_monde>/datapacks/`.
3. Lancez Minecraft et chargez votre monde.
4. Entrez la commande `/reload` pour activer le datapack.

## Structure du Datapack

Voici la structure des fichiers et dossiers du datapack :

justmielzandgar/ ├── pack.mcmeta ├── data/ │ ├── minecraft/ │ │ └── tags/ │ │ └── function/ │ │ ├── load.json │ │ └── tick.json │ └── justmielzandgar/ │ ├── function/ │  ├── loop.mcfunction │ │ └── load.mcfunction │ ├── recipe/ │ │ ├── biere_blanche.json │ │ ├── punch.json │ │ └── drugs.json

shell
Copier le code

## Recettes

### Bière Blanche

Pattern : B WHW B

B = Wheat (blé) W = Water Bucket (seau d'eau) H = Glass Bottle (bouteille en verre)

shell
Copier le code

### Punch

Pattern : F SHS F

F = Sugar (sucre) S = Sweet Berries (baies sucrées) H = Glass Bottle (bouteille en verre)

shell
Copier le code

### Drogue

Pattern : SSS SBS SSS

S = Sugar (sucre) B = Glass Bottle (bouteille en verre)

markdown
Copier le code

## Effets des Consommables

- **Bière Blanche** : Faiblesse 1, Résistance 1.
- **Punch** : Force 2, Poison.
- **Drogue** : Nausée, Faiblesse 2, Vision nocturne, Résistance 1.

## Debugging

Pour vérifier si le datapack fonctionne correctement :
- Vérifiez dans le chat si le message suivant s'affiche : `[Justmielzandgar] Le datapack fonctionne correctement !`
- Utilisez la commande `/datapack list` pour voir si le datapack est activé.

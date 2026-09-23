# pse-expert-reseau

Révision des fascicules de préparation PSE Expert Réseau (systèmes, réseaux, sécurité, SI de l'État).

57 modules, consultables depuis l'application de révision
https://guiraudjb.github.io/PSE25-27/ (ce dépôt en fournit les données via GitHub Pages).

## Séries

- **09** : Fascicules PSE Expert Réseau

## Contenu par module

Chaque module `<nom>` dispose de : `fiche/<nom>.txt`, `quizz/<nom>.csv`,
`flashcard/<nom>.csv`, éventuellement `tp/<nom>.csv`, et des médias
`podcast/<nom>.m4a`, `infographie/<nom>.png`, `chanson/<nom>.mp3` (+ paroles
`.txt`) et `fiche_audio/<nom>.mp3` (narration de la fiche). La liste des
modules est dans `modules.json`.

## Jeu Batocera

`batocera/pse-expert-reseau/` contient le jeu pygame jouable à la manette, déployé par
`batocera/deploy.py`. Le moteur est commun à tous les dépôts : il se modifie
dans le modèle de l'espace de travail puis se synchronise, jamais ici.

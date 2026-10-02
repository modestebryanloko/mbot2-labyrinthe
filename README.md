# 🤖 mBot2 — Résolution d'un labyrinthe

## Présentation
Projet d'assemblage et de programmation d'un robot mBot2 capable de détecter des obstacles et de se déplacer dans un labyrinthe jusqu'à sa sortie.

## Objectif
- Détecter les obstacles
- Éviter les collisions
- Adapter la trajectoire
- Rechercher la sortie du labyrinthe

## Matériel
- mBot2 / kit Makeblock
- Châssis, moteurs et roues
- Contrôleur mBot2
- Capteur ultrasonique
- Capteur de ligne
- Batterie et câbles

## Étapes
1. Identifier les pièces.
2. Assembler le châssis, les moteurs et les roues.
3. Installer les capteurs.
4. Effectuer le câblage.
5. Programmer avec mBlock.
6. Tester le déplacement dans le labyrinthe.

## Logique de navigation

```text
Début
  ↓
Avancer
  ↓
Obstacle détecté ?
  ├── Non → Continuer
  └── Oui → Arrêter → Tourner → Chercher un passage
                                      ↓
                                   Continuer
```

## Technologies
- Makeblock mBot2
- mBlock
- Programmation par blocs
- Robotique
- Capteurs et automatisation

## Structure

```text
mbot2-labyrinthe/
├── README.md
├── docs/
│   └── assemblage-et-programmation.md
├── images/
│   └── assemblage-mbot2.png
└── src/
    └── logique_labyrinthe.txt
```

## Perspectives
Amélioration de l'algorithme de résolution, mémorisation du parcours, ajout de capteurs et optimisation des mouvements.

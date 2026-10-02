# Assemblage et programmation du mBot2

## 1. Assemblage
Fixer les moteurs et les roues au châssis, puis installer le contrôleur et les différents éléments du robot.

## 2. Installation des capteurs
Placer le capteur ultrasonique à l'avant du robot pour mesurer la distance aux obstacles. Le capteur de ligne peut fournir une information complémentaire.

## 3. Câblage
Connecter les moteurs et les capteurs au contrôleur conformément au montage du kit.

## 4. Programmation avec mBlock
Le comportement peut être représenté par la logique suivante :

```text
SI obstacle proche
    arrêter
    tourner
SINON
    avancer
```

## 5. Résolution du labyrinthe
Le robot avance jusqu'à détecter un obstacle, puis recherche une direction libre avant de continuer.

## 6. Résultat attendu
Le mBot2 doit pouvoir progresser dans le labyrinthe, éviter les murs et atteindre la sortie.

[English](README.md) | [Deutsch](README.de.md) | [Français](README.fr.md)

# Solveur numérique RK4 pour les équations différentielles ordinaires (EDO) raides et non raides de la cinétique chimique

## Aperçu
Un solveur numérique en Python utilisant la méthode de Runge-Kutta d'ordre 4 (RK4) pour intégrer des systèmes d'équations différentielles ordinaires (EDO) régissant la cinétique chimique. Il est appliqué au mécanisme réduit de Westbrook-Dryer pour la combustion du méthane, avec une structure modulaire permettant de définir des systèmes d'EDO personnalisés et de les résoudre avec le même moteur RK4.

*Remarque : ce dépôt n'est qu'un aperçu de quelques résultats obtenus avec le solveur numérique RK4 développé sur mesure en langage Python.*

## Méthode
- Schéma d'intégration de Runge-Kutta d'ordre 4 (RK4).
- Application et résolution du mécanisme réduit de Westbrook-Dryer pour la combustion du méthane, en tenant compte du comportement en deux étapes de ce mécanisme (diminution du CO et augmentation simultanée du CO₂).
- Conception modulaire permettant de définir des systèmes d'EDO personnalisés, résolus avec le solveur RK4 principal.

## Résultats

<p align="center">
  <img src="images/Solved_Westbrook_Dryer_Methane_Combustion_reduced_mechanism_Oxidation.png" alt="Mécanisme réduit de Westbrook-Dryer pour la combustion du méthane, résolu" width="600">
</p>


<p align="center">
  <img src="images/Custom_chemical_reaction_ODE_mechanism_solved_used_the_RK4_solver.png.png" alt="Mécanisme réactionnel chimique personnalisé sous forme d'EDO, résolu avec le solveur RK4" width="600">
</p>

## Compétences
Python · Méthodes numériques · Cinétique chimique raide · Modélisation de la combustion · Calcul scientifique

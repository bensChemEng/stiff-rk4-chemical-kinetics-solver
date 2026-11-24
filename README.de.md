[English](README.md) | [Deutsch](README.de.md) | [Français](README.fr.md)

# Numerischer RK4-Löser für steife und nicht-steife gewöhnliche Differentialgleichungen der chemischen Kinetik

## Übersicht
Ein Python-basierter numerischer Löser, der das Runge-Kutta-Verfahren 4. Ordnung (RK4) verwendet, um Systeme gewöhnlicher Differentialgleichungen (DGL) zu integrieren, die die chemische Kinetik beschreiben. Er wird auf den reduzierten Westbrook-Dryer-Mechanismus für die Methanverbrennung angewendet und ist modular aufgebaut, sodass benutzerdefinierte DGL-Systeme definiert und mit demselben RK4-Kern gelöst werden können.

*Hinweis: Dieses Repository ist lediglich eine Vorschau einiger Ergebnisse, die mit dem eigens in der Programmiersprache Python entwickelten numerischen RK4-Löser erzielt wurden.*

## Methode
- Integrationsschema: Runge-Kutta-Verfahren 4. Ordnung (RK4).
- Der reduzierte Westbrook-Dryer-Mechanismus für die Methanverbrennung wurde angewendet und gelöst, wobei das zweistufige Verhalten des Mechanismus berücksichtigt wird (Abnahme von CO bei gleichzeitiger Zunahme von CO₂).
- Modularer Aufbau, der benutzerdefinierte DGL-Systeme unterstützt, die mit dem zentralen RK4-Löser gelöst werden.

## Ergebnisse

<p align="center">
  <img src="images/Solved_Westbrook_Dryer_Methane_Combustion_reduced_mechanism_Oxidation.png" alt="Gelöster reduzierter Westbrook-Dryer-Mechanismus der Methanverbrennung" width="600">
</p>


<p align="center">
  <img src="images/Custom_chemical_reaction_ODE_mechanism_solved_used_the_RK4_solver.png.png" alt="Benutzerdefinierter chemischer Reaktionsmechanismus als DGL-System, gelöst mit dem RK4-Löser" width="600">
</p>

## Kompetenzen
Python · Numerische Methoden · Steife chemische Kinetik · Verbrennungsmodellierung · Wissenschaftliches Rechnen

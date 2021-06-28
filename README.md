# Bachelor Thesis: Stochastic Gradient Descent and its Application for Parametrized Boundary Value Problems under Uncertainties

## Abstract
In this thesis we want to give a theoretical and practical introduction to stochastic gradient descent (SGD) 
methods. In the theoretical part, we prove two fundamental
convergence results that hold under certain assumptions, like a strongly convex objective function. The 
first result covers the convergence
behaviour of SGD running with a fixed step size sequence and is expanded to the second result, which deals with SGD running with a diminishing 
step size sequence. For both cases, we provide an upper bound for the expected optimality gap. At the expense of a concrete convergence rate, we 
then generalize both results to non-convex objective functions.

The practical part of this thesis deals with the application of SGD as a convincing and stable optimizer for parametrized boundary value problems 
under uncertainties. Firstly, we discretize an ordinary differential equation (ODE)
Dirichlet problem using finite differences (FD) and improve the results by
using preconditioning techniques and a weighted norm. Secondly, we generalize the results to an elliptic partial differential equation (PDE) 
Dirichlet problem and aim for a weak solution using a finite element (FE) discretization. For both problems, the SGD algorithm convinces with stable
results and provides convergence in expectation.

## Zusammenfassung
Diese Arbeit behandelt eine theoretische und praktische Einführung in das stochastische Gradientenverfahren. Im theoretischen Teil zeigen wir zwei
wichtige Konvergenzaussagen, welche unter gewissen Bedingung, z.~B. einer stark konvexen Zielfunktion, gelten. 
Zunächst beweisen wir ein allgemeines Konvergenzresultat, welches eine obere Schranke für den erwarteten Fehler
unter der Verwendung einer konstanten Schrittweite bereitstellt. In einem 
zweiten Schritt wird dieses Resultat auf eine Strategie mit kleiner werdender Schrittweite verbessert.
Beide Resultate werden auf Kosten der Konvergenzgeschwindigkeit auf nicht-konvexe Zielfunktionen verallgemeinert.

Der praktische Teil behandelt die Anwendung des stochastischen Gradientenverfahrens für parametrisierte Randwertprobleme unter Unsicherheiten.
Zuerst wenden wir eine Finite-Differenzen-Diskretisierung auf eine gewöhnliche Differentialgleichung mit Dirichlet-Randwerten an.
Durch die Verwendung eines Vorkonditionierers und einer gewichteten Norm verbessern wir die Ergebnisse. Anschließend werden die Resultate auf eine 
elliptische partielle Differentialgleichung, welche mit einem Finite-Elemente-Verfahren diskretisiert wird, verallgemeinert. In beiden Fällen erweist
sich das stochastische Gradientenverfahren als sehr stabiles Optimierungsverfahren, welches Konvergenz im Erwartungswert liefert.


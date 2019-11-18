# WindingHomology
Computes the winding homology, the Turaev polynomial, and the Khovanov homology of knotoids.

Knotoids are written in the planar diagram (PD) notation, see http://katlas.org/wiki/Planar_Diagrams .
Example: K=PD[X[3, 1, 4, 2], X[2, 4, 3, 5]] is a bifoil knotoid.

Evaluate the Mathematica notebook to run the commands below:

JonesKnotoid[K] computes the Jones polynomial of K.

KhKnotoid[K] computes the Poincare polynomial of the Khovanov homology of K.

Turaev[K] computes the Turaev polynomial of K.

Winding[K] computes the Poincare polynomial of the winding homology of K.

KnotToKnotoid[L] returns the PD code of the knotoid obtained from the knot L by applying a single Omega move.

KnotToKnotoidLv2[L] returns the PD code of the knotoid obtained from the knot L by applying a double Omega move.

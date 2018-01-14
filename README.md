# sha256-circuit
An efficient circuit implementation of SHA256. 

All the circuits are already in a format compatible with [SCAPI](https://github.com/cryptobiu/scapi).

These circuits were generated using a circuit building library designed by Steven Goldfeder (link to be added) that optimized total size and number of AND gates. The latter is desirable in MPC applications.
The circuits were built as part of a work on "Zero Knowledge Contingent Service Payments (ZKCSP)" by Campanelli, Gennaro, Goldfeder and Nizzardo (paper at [this link](https://eprint.iacr.org/2017/566)).


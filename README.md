Nagual_MLFT is an electronic structure software based
on an unrestricted hartree fock method which is capable
to add into a central atom, the potential of a crytal field
expressed as a finite multipole expansion of the 1/r operator.

In such a way, the correct splitting and labeling
for the term-symbols in the Russel-Saunders scheme is produced.

Also, Tanabe-Sugano like diagrams can be obtained from the methodology

Installation:

tar -zxvf Nagual_MLFT.tar.gz
cd src
./configure
make

Dependencies:

lapack libraries 3.5 or larger versions
build-essential package in ubuntu/debian based distros
make
gfortran compilers

Running an example:
cd Nagual_MLFT
verify the basis set files Nagual.bas.1 and Nagual.bas.2 are there
run the binary

./bin Nagual.inp

After some minutes the .log and .out files are produced which contain
convergence of scf steps in the spin configurations, and the term-symbols splitting
respectively.

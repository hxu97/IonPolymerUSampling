# IonPolymerUSampling
1D and 2D umbrella samplings of ion transport through polyamide membranes

Mem0: The hypothetical membrane has no Coulomb interactions
Memdelta: Neutral membrane
Mem-: Charged membrane

How to run:
1. Select initial configuration, generate the corresponding ndx file, and select the target ion.
2. Pull the ion across the membrane.
3. Prepare initial configuration for each sampling window.
4. Copy umbrella sampling files, assign them to each window, and change XXX in the file to target value. (1D umbrella sampling: ion-membrane distance; 2D umbrella sampling: ion-membrane distance and ion hydration number).
5. Run simulation. Note that for 2D umbrella sampling, GROMCAS should be compiled with PLUMED.

Please report any bugs or issues on GitHub, or contact: hxu489@wisc.edu

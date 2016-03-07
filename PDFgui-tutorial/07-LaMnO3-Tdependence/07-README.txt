Modeling 300K-1100K LaMnO3 series using Pnma settings 
=====================================================

LaMnO3 refinement information:
==============================

Space group:			Pnma
lattice a:				5.74 Angstroms
lattice b:				7.71 Angstroms
lattice c:				5.54 Angstroms
Fractional coordinates:		La	(0.05,0.25,0.99)
					Mn 	(0.50,0.00,0.00)
					O1	(0.49,0.25,0.07)
					O2	(0.31,0.04,0.73)

Uiso: all				0.005
Qmax:					32.0 Inv. Angstroms
Qdamp:				0.012

Data: Neutron data for LaMnO3 in 300K-1100K range obtained at NPDF at LANSCE (300K.gr, 550K.gr, 650K.gr, 700K.gr, 720K.gr, 730K.gr, 740K.gr, 
750K.gr, 800K.gr, 880K.gr, 980K.gr, 1050K.gr, 1100K.gr, 1150K.gr)

GOAL: Familiarize further with setting up a complex unit cell and T-dependent sequential fit

TASKS:
1) Use macro for T-dependent refinement
2) Set up a sequence of refinements of LaMnO3 data for temperatures in 300-1100K range
3) Make sure that the data you load in the macro is in proper T-sequence, as the fits will be linked (output of a refinement at preceding temperature serves as an input of the next temperature dataset)!
4) Plot refined parameters vs T and observe which of these indicate 2 structural phase transitions that happen in this material on heating



# Direct-CO2-dissociation-in-zeolite-encapsulated-single-atom-catalysts
This repository contains the geometries of Reactants, Products and TSs in the 29 TM1@S-1 structures studied in the work "Determining the activity of zeolite encapsulated single atom catalysts for CO2 conversion". Those reactions are:

   - CO2     --> CO + O  
   - H2      --> H  + H
   - CO2 + H --> COOH
   - CO2 + H --> m-HCOO --> b-HCOO
     
The files for each TM are in the "Optimized Geometries" folder and they are organized according to their periodic table group (e.g., the CONTCARs related to Au can be found in "Optimized Geometries/Group\_11/Au/")

Each TM folder contains a VASP CONTCAR file with the TM1@S-1 structure without any adatom and a set of folders (one per reaction) with the geometry of the Reactants, TS and Products. Those are labeled as:
   - *CONTCAR-Surface : The TM1@S-1 structure without any adatom.*
   - *CONTCAR-Reactant: The global minimum energy configuration of the Reactants + TM1@S-1.*
   - *CONTCAR-Product:  The global minimum energy configuration of the Products + TM1@S-1.*
   - *CONTCAR-TS:       The located transition state for the Transition State + TM1@S-1.*

However, in some reactions, the direct product yiels a local minimum different from the absolute CONTCAR-Product. This local minimum was used as a final image to locate the TS within the NEB scheme, and is given as CONTCAR-Product-Post-Reaction. The geometry of the TS that connects the CONTCAR-Product-Post-Reaction with the CONTCAR-Product is also included, when relevant, as CONTCAR-TS-Product-Reposition
   - *CONTCAR-Product-Post-Reaction: The local minimum energy configuration found directly after each reaction (only if it differs from the global energy configuration shown in CONTCAR-Product)*
   -  *CONTCAR-Product-Reposition: The TS that connects CONTCAR-Product-Post-Reaction with CONTCAR-Product*

# Citing this work
Please, if you use any of the optimized CONTCAR files in this repository cite the original work where they were located:
- *G. Alonso, E. López, F. Huarte, R. Sayós, H. Prats, P. Gamallo. Direct CO2 dissociation in zeolite-encapsulated single-atom catalysts. Manuscript under preparation*

If you use any of the CONTCAR-Surface files (without gas) also cite:
- *[H. Prats, G. Alonso, R. Sayós, P. Gamallo. Transition metal atoms encapsulated within microporous Silicalite-1 zeolite: A systematic computational study. Micropor. Mesopor. Mat., 308 (2020) 110462:1-8.](https://www.sciencedirect.com/science/article/abs/pii/S1387181120304649?via%3Dihub)*
``` 

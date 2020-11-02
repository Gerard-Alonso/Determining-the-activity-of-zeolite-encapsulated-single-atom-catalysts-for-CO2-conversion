# Determining-the-activity-of-zeolite-encapsulated-single-atom-catalysts-for-CO2-conversion
This repository contains the geometries of all species in the CO2 --> CO + O reaction (i.e., CO2 as reactant, CO + O as product and the CO-O transition state) in the 29 TM{Sub}1{/Sub}@S-1 structures studied in the work "Determining the activity of zeolite encapsulated single atom catalysts for CO2 conversion".

The files for each TM are in the "Optimized Geometries" folder and they are organized in according to their periodic table group (e.g., the CONTCARs related to Au can be found in "Optimized Geometries/Group 11/Au/")

Each TM folder contains at least the following 4 VASP CONTCAR files:
   - *CONTCAR-Surface : The TM1@S-1 structure without any adatom.*
   - *CONTCAR-Reactant: The global minimum energy configuration of the CO2 + TM1@S-1.*
   - *CONTCAR-Product:  The global minimum energy configuration of the CO + O + TM1@S-1.*
   - *CONTCAR-TS:       The located transition state for the CO-O + TM1@S-1.*

However, in some reactions, the CO-O cleavage yielded a local CO + O minimum different from CONTCAR-Product. This local minimum was used as a final image to locate the TS within the NEB scheme, and is given as CONTCAR-Product-Post-Reaction.
   - *CONTCAR-Product-Post-Reaction: The local minimum energy configuration found after the CO-O cleavage (only if it differs from the global energy configuration shown in CONTCAR-Product)*

# Citing this work
Please, if you use any of the optimized CONTCAR files in this repository cite the original work where they were located:
- *G. Alonso, E. López, F. Huarte, R. Sayós, H. Prats, P. Gamallo, Determining the activity of zeolite-encapsulated single-atom catalysts for CO2 conversion. Manuscript under preparation*

If you use any of the CONTCAR-Surface files also cite:
- *[H. Prats, G. Alonso, R. Sayós, P. Gamallo, Transition metal atoms encapsulated within microporous Silicalite-1 zeolite: A systematic computational study. Micropor. Mesopor. Mat., 308 (2020) 110462:1-8.](https://www.sciencedirect.com/science/article/abs/pii/S1387181120304649?via%3Dihub)*

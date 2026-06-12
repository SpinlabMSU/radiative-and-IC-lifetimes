# Radiative and IC lifetimes calculator/plotter

This Python code calculates and plots radiative lifetime, internal conversion lifetime, and internal conversion coefficient as a function of state energy, for an isotope with A=229 and given a value of B(E1).

The first version of this code, `plot-th-lifetimes.ipynb`, was written by JTS.

A new version of this code (to be written soon by MJT) will extend functionality to include "exclusion plots", which will show the overlap between areas of the energy-lifetime phase space and possible experimental approaches (including Pa-229 production methods and techniques for potentially detecting a low-lying state).

Description of original code written by JTS in [elog:Pa22/203](https://elog.frib.msu.edu/Pa229/203), copied verbatim below:

> Based on a study of these refefences:
> 
>    https://www.nature.com/articles/nature12073 (Gaffney 2013 Nature paper)
>    https://www.sciencedirect.com/science/article/pii/0375947493901987 (Nuclear Physics A562 (1993) 241-259)
>    https://www.sciencedirect.com/science/article/pii/037594749390351W (Nuclear Physics A556 (1993) 26I-280)
>
> B(E1) in Wu in the actinide region are about 3E-4 or 3/10000 with a range of +/- a full order of magnitude - see table of values here: https://docs.google.com/spreadsheets/d/1TrwNQHgHIiYhsZTGh7T0TBzqi3ZvMmkrdaPF\_JgtDTU/edit?usp=sharing
> 
> I have updated my python code here with this new revised estimate for B(E1) in Wu: https://www.dropbox.com/scl/fi/utbe3hlrwmrq66a4u3x2t/plot-th-lifetimes.ipynb?rlkey=zv28ds083nh4n7781xke770t2\&dl=0
> 
> The new lifetime values at 60 eV for A=229 for B(E1) = 3/10000 are:
>
>    4 seconds for the radiative decay mode
>    0.25 ns for the internal conversion mode (ICC = 1.6E10 assuming Th-229 M1 kappa factor can be used for the Pa-229 E1 kappa factor)
> 
> updated plots:
> 
>     attachment 1: ICC vs. energy (this one should be the same as before since the ICC ratio should not depend on B(E1)
>    attachment 2: IC lifetime vs. energy
>    attachment 3: radiative lifetime vs. energy
>
> next steps: talk to experts to see if this B(E1) is more realistic and also double check units for B(E1) in the papers cited above to make sure that we didn't miss a factor of alpha = 1/137


# In Vivo and In Silico Evaluation of Sodium Benzoate Induced Ocular Toxicity In Male and Female Wistar Rats
## Question
Does sodium benzoate cause ocular toxicity in male and female Wistar rats, and do the effects differ by sex? Can molecular docking against ocular proteins (lysozyme, PSD-95 and rhodopsin) help explain any interactions?
## Methods
**In silico (MOE)**
- Prepared structures: QuickPrep, energy minimization, protonation, removed waters and extra chains.
- Located the binding site with Site Finder.
- Prepared sodium benzoate as a ligand database and docked it.
  
**Validation**
- Redocked native ligands for each target.
- PSD-95: no native ligand in the structure, so no redocking was possible.

**In vivo**
- Wistar rats, both sexes, 4 per group for oth sexes(control, low dose, high dose);(one control male escaped it's enclosure during week 3 of administration and was not recovered; no termina data was obtained.
- GFAP measured by ELISA in eye tissue.

## Results
- Sodium benzoate showed weak binding scores across all targets (Lysozyme: -3.74kcal/mol, Rhodopsin: -4.54kcal/mol, and PSD-95: -4.05kcal/mol)
- GFAP showed a dose dependent increase in both sexes, including sex-dependent differences withthe males have a higher absolute increase at all dose levels compared to the females.

## Limitations
- Weak docking scores, so binding is unlikely to be strong.
- PSD-95 docking couldn't be validated.
- Sample size was relatively small with a total for both sexes being n=24, both sexes together.
- The unequal group size due to a loss that was unrelated to the treatment
- Only ELISA was done because of equipment, power and funding limits.

## What I'd do next
- Try to reprodue the same results in silico using AutoDock Vina and compare to MOE.
- Improve knowledge on software used in the experiment.
- Given the chance, to reproduce this experiment with a larger sample size.

## Author
Loren Samuels, BSc Biochemistry, Ajayi Crowther Univeristy.

# Q5 PCR and homebrew 2X master mix

### Homebrew Recipe for 2X Q5 Master Mix

| Component | For 50 reactions | For 500 reactions | Concentration in 2x MM |
|---|---|---|---|
| Q5 Hot-Start Polymerase (2000 U/mL) (M0493L) | 12.5 µL | 125 µL | 40 U/mL (0.04 U/uL) |
| 10 mM each dNTP<br>(N0447L) | 25 µL | 250 µL | 400 uM each |
| 5X Q5 reaction buffer | 250 µL | 2.5 mL | 2X |
| 20% Glycerol stock | 312.5 µL | 3.125 mL | 10% |
| MPW | 25 uL | 250 µL |  |
| Total Volume | 625 µL | 6.25 mL |  |

Dispense into aliquots of 104 uL in 1.5 mL microcentrifuge tubes; store at -20’C

### General Recipe for Q5 PCR

| Component | For 50 reactions | Final Concentration |
|---|---|---|
| 2x Q5 Master Mix | 12.5 µL | 1x |
| 10 uM forward primer | 1.25 µL | 0.5 uM |
| 10 uM reverse primer | 1.25 µL | 0.5 uM |
| Template DNA | 1 µL |  |
| MPW | 9 µL |  |
| Total Volume | 25 µL |  |

*Amount of template to use:* For plasmids, typically 1 ng will be good (range: 1 pg – 1 ng).

For genomic DNA, typically 10 ng will be good (range: 1 ng – 1 ug).

### General Protocol for Most Q5 PCRs

| # Cycles | Step | Temperature (‘C) | Time |
|---|---|---|---|
|  | Initial Denaturation | 98 | 30 sec |
| 25 – 35 | Denaturation | 98 | 10 sec |
| 25 – 35 | Annealing | 50 – 72 | 15 sec |
| 25 – 35 | Elongation | 72 | 30 sec/kb |
|  | Final Extension | 72 | 2 min |
|  | Hold | 4 |  |

### Troubleshooting

If high GC-content: Use 5uL high-GC buffer

If having problems with secondary structure: Use 5-10% DMSO

Can also add different amounts of MgCl2 (this does not normally help as much!)

Other possibility is to try Touchdown PCR, this involves starting at 5˚C above the primer Tm on the first cycle, and going down 0.5˚C on each cycle until you are at 5˚C before the primer Tm  on the 20th cycle.

Primer concentrations: If there is an issue with primer dimerization, I would go to lower primer concentration (start with decreasing by 2-fold) and also increase template concentration (start with increasing by 2-fold).

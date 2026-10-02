# Yeast knock-in

### Day -14 to -7

### Gene block design

1. Download yeast genome sequence from SGD (https://www.yeastgenome.org/).
2. Locate the place where you want to knock-in/knock-out.

   For the knock-in, gene block should include your target gene and the gene coded for the expression of a specific selectable marker.

   For the knock-out, you can replace the gene you would like to knock out with gene of a selectable marker, and the expression of the selectable marker can be controlled under the original gene’s promoter and terminator.

   *The yeast strain that we commonly use is BY4741 strain: MATa his3Δ1 leu2Δ0 met15Δ0 ura3Δ0.

   After deciding the main gene block, add around 50-bp overhangs that are homologous to the 3’- and 5’-end genomic site where the modification happens.

3. Order the gene block from IDT or Twist (much cheaper). At the same time order primers for gene block amplification as well as colony pcr screening:

   Gene block primers anneal to the 5’ and 3’ end of our final gene block construct with lengths around 15-25 nt ends with C/G (Tm around 55-65°C, do not exceed extension temperature of the polymerase that you will be using; Tm of forward and reverse primers should not differ more than 5°C ).

   Colony pcr primers anneal to the upstream and downstream ~50 nt of the knock-in/out place with lengths around 15-25 nt ends with C/G

### D-Day

### After receiving the gene block and primers

1. pcr amplification of your ordered gene block.

   *If you are using NEB master mix, you can calculate the suggested Tm for different polymerase system on their website:[https://tmcalculator.neb.com/#!/main](https://tmcalculator.neb.com/#!/main)

2. Run 1% agarose gel to confirm the length of your pcr product, then use a DNA clean-up kit to remove enzymes and salts in the pcr product according to manufacturer’s protocol.
1. Yeast cells (S288C strain, BY4741) were grown in 5 mL of YPD from saturated overnight cultures with a starting OD<sub>600</sub> of 0.05 in 15 mL round-bottom falcon tubes.

   * YPD: yeast extract peptone dextrose medium.

2. Cells were cultured at 30°C with agitation (200 rpm) to log phase at a final OD<sub>600</sub> of 0.4, before being collected by centrifugation at 3000 x g for 5 mins at 4°C.

   * To get logarithmic phase cells for transformation, which gives higher efficiencies.

3. The supernatant was removed, and the cell pellet was resuspended with 1 mL of 1X TE-LiOAc and transferred to a fresh 1.5 mL microfuge tube and centrifuged again at 3000 x g for 5 min at 4°C.

   1X TE-LiOAc:

   10 mM Tris pH 8.0

   1 mM EDTA pH 8.0

   0.1 M LiOAc

   *Made from 10X TE and 10X LiOAc:

   10X TE:

   100 mM Tris pH 8.0

   10 mM EDTA pH 8.0

   10X LiOAc:

   1 M LiOAc

4. Supernatants were removed and cells were resuspended in 100 μL of 1X TE-LiOAc. Add the following components sequentially and mixed thoroughly between each addition:

   · 10 μL of denatured salmon sperm DNA (denatured at 95°C for 10 mins, followed by quick chill on ice for ≥ 5 min)

   · ≤ 25 μL of 100 ng/μL pcr amplified gene block

   · 800 μL of 1X PEG-TE-LiOAc

   1X PEG-TE-LiOAc:

   10 mM Tris pH 8.0

   1 mM EDTA pH 8.0

   0.1 M LiOAc

   40% PEG (3350 mw))

   * For best efficiency, use carrier DNA that is freshly boiled and avoid repeated boiling/cooling cycles.

   * Positively charged lithium cation can neutralize both negatively charged yeast membrane and DNA.

5. Cells were incubated at 30°C for 30 mins with agitation (300 rpm) in a thermomixer and then heat-shocked 30 mins in a 42°C water-bath.
6. Cells were then harvested by centrifugation at 14,000 x g for 30 sec. The supernatants were removed, and cells were washed with 1 mL of water and then pelleted at 3000 x g for 5 mins.
7. Washed cell pellets were then resuspended in 50 μL of water before being plated on a selectable media agar plate and allowed to grow for 2-3 days at 30°C.

### Day 3/4

### Colony pcr

1. pick 3-6 colonies and resuspend them in 50 μL water or drop-out media. Take 25 μL into pcr tubes, heat denature to release genomic DNA at 95°C for 10 min. Save the other half for agar plate re-striking.

   *For optimal efficiency, it is recommended to extract genomic DNA of potential targets for pcr amplification: inoculate 3-6 colonies in 1.5 mL drop-out media and grow at 30°C till media looks turbid, use yeast genomic DNA extraction kit according to manufacturer’s protocol to extract each genomic DNA and use this for pcr amplification.

2. use colony pcr primers to amplify the potentially knocked-in gene block, check product using 1% agarose gel first, then send seemingly-correct ones for Genewiz sequencing.

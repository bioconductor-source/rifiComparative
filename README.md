# Comparative data set from Rifi framework

## About

Rifi framework comparative Data is a comparative output from Rifi framework
(https://github.com/CyanolabFreiburg/rifi). Rifi_comparative_data compares 
two outputs, gene based, from 2 different conditions of the same organism 
(Figure. 1). A dataframe is created assembling annotation and their
corresponding log2FC half-life and log2FC intensity from data +/- treatment. 
The corresponding P_value from statistical tests and P_value adjusted are 
included. Events are gathered together for comparison. 
rifi comparative data provides as well visualization of all segments 
generated by Rifi of both conditions.

<br/>
<p align="center">
  <img src="log2FC.png" alt="drawing" width="500"/>
</p>

<sub>
<b>Figure 1:</b> a heatscatter visualization of log2FC(half-life(cdt1/cdt2) vs 
log2FC(intensity(cdt1/cdt2)). Red to blue colors show high and low density
respectively. Correlation between both measurement is provided (cor).
</sub>

<br/>
<p align="center">
  <img src="log2FC_synthesisRate_vs_decayRate.png" alt="drawing" width="500"/>
</p>
<br/>
<sub>
<b>Figure 2:</b> a heatscatter visualization of log2FC(half-life rate (cdt1/cdt2) vs 
log2FC(synthesis rate (cdt1/cdt2)). Yellow to yellow pale colors show high and 
low density respectively. Correlation between both measurement is provided (cor).
</sub>

# Installation 

### Dependencies

Rifi framework comparative data has the following dependencies. Make sure the 
requirements are satisfied by your system. 

  
  [dplyr](https://www.rdocumentation.org/packages/dplyr/versions/0.7.8) (>= 1.0.7)
  
  [LSD](https://www.rdocumentation.org/packages/ScottKnott/versions/1.3-0/) (>= 1.3.0)
  
  [ggplot2](https://ggplot2.tidyverse.org/) (>= 3.3.5)
  
  [writexl](https://www.rdocumentation.org/packages/writexl/versions/1.4.0/) (>= 1.4.0)
  
  [egg](https://www.rdocumentation.org/packages/scales/versions/0.4.1) (>= 0.4.1)
    
  [data.table](https://www.rdocumentation.org/packages/msSPChelpR/versions/0.8.7/)(>= 0.8.7)
  
  [ggrepel](https://www.rdocumentation.org/packages/ggrepel/versions/0.9.1/) (>= 0.9.1) 
  
  [stats](https://rdocumentation.org/packages/stats/versions/3.6.2) (>= 3.6.2) 
  
  [grid](https://www.rdocumentation.org/packages/graphics/versions/3.6.2/topics/grid) (>= 3.6.2) 

  [rtracklayer](https://www.rdocumentation.org/packages/rtracklayer/versions/1.32.1) (>= 1.32.1) 

# Troubleshooting

contact jens.georg@biologie.uni-freiburg.de or create an issue

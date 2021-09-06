## c-elegans vibrotaxis
This is a new method for improving C. elegans deteccion, and it is described in research article [1].
This method uses code and hardware developed for vision system inspection [2] and for c-elegans detection [3]

### Research article [1]
[1] Puchalt JC, Layana Castro PE, Sánchez-Salmerón A-J. Reducing Results Variance in Lifespan Machines: An Analysis of the Influence of Vibrotaxis on Wild-Type Caenorhabditis elegans for the Death Criterion. Sensors. 2020; 20(21):5981. https://doi.org/10.3390/s20215981

### Research article [2]
[2] Puchalt JC, Sánchez-Salmerón AJ, Martorell Guerola P, Genovés Martínez S (2019) Active backlight for automating visual monitoring: An analysis of a lighting control technique for Caenorhabditis elegans cultured on standard Petri plates. PLOS ONE 14(4): e0215548. https://doi.org/10.1371/journal.pone.0215548

### Research article [3]
[3] Puchalt, J.C., Sánchez-Salmerón, A., Ivorra, E. et al. Improving lifespan automation for Caenorhabditis elegans by using image processing and a post-processing adaptive data filter. Sci Rep 10, 8729 (2020). https://doi.org/10.1038/s41598-020-65619-4

#### Hardware and code description on [2]
* It is described in document https://github.com/JCPuchalt/c-elegans_smartLight

#### Code description on [3]
* It is described in document https://github.com/AntonioJoseSanchezSalmeron/lifespan

#### Hardware description on [1]
In this repository are the .stl files to print in 3D printer. 
* elasticPiece.stl (print with elastic material)
* motorHolder.stl (print with PLA)
* rigidPiece.stl (print with PLA)

Then assemby vibration system and adjust to vision system as follow https://github.com/JCPuchalt/vibrotaxis/blob/master/Vibrator%20assemby.pdf

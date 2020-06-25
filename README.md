# SPOTNetworks

## Author: Jacob Cram
## Date: 25 June 2020

This is a repository containing data and analysis from two manuscripts.

Cram JA, Xia LC, Needham DM, Sachdeva R, Sun F, Fuhrman JA. Cross-depth analysis of marine bacterial networks suggests downward propagation of temporal changes. ISME J. 2015 May 19;9(12):2573–86. 

Ai D, Li X, Pan H, Chen J, Cram JA, Xia LC. Explore mediated co-varying dynamics in microbial community using integrated local similarity and liquid association analysis. BMC Genomics. 2019 Apr 4;20(Suppl 2):185. 

The `Data` subdirectory contains ARISA data and environmental data used in the network analyis. I do not guerentee the accuracy of any of this data. The most up to date data can be found on BCO-DMO

Environmental data
https://www.bco-dmo.org/dataset/537137
Microbial relative abundances
https://www.bco-dmo.org/dataset/535915
Information about teach of the microbes reported in the microbial relative abundances dataset
https://www.bco-dmo.org/dataset/535915

The `FullDepthProfileInteractions` diectory contains one `.cys` file that can be opened with `Cytoscape`. It contains the file that I used to generate most of the fitures in the Cram et al. 2015 manuscript.

The `LiquidAnalyis` dirctory contains one `.cys` file that was used to generate figures in the Ai et al. 2019 manuscript.

I have not located the node and edge attribute files needed to generate these .cys files, but the nodes, edges, and graphical settings files can be extracted from the `.cys` files.
# Biophysics-With-Code

Welcome to Biophysics with Code!

## Project 1: Quorum Sensing in _V. Fischeri_

**Citation for originial paper**: James, S., Nilsson, P., James, G., Kjelleberg, S. & Fagerström, T. (2000) 'Luminescence control in the marine bacterium _Vibrio Fischeri_: an analysis of the dynamics of lux regulation', _Journal of Molecular Biology_, 296(4), Pages 1127-1137 [doi:10.1006/jmbi.1999.3484](https://pubmed.ncbi.nlm.nih.gov/10686109/).

**Brief Summary**: Quorum sensing (QS) is a cell-cell bacterial communication mechanism that allows the bacterial species to cooperatively regulate specific gene expressions in response to changes in their local population density. The term 'quorum' in QS is used in its most literal sense to denote the fact that the gene expression in a bacterial population is strongly induced only when the 'quorum' threshold requirement is met. In this paper, James et al have attempted to model the phenotypic on-off switch of bioluminescence in _V. fischeri_ using a general chemical kinetics approach of lux regulatory system that controls the production of light in the bacteria. A key finding of the research is that, even though the overall mechanism of cell-cell communication in _Vibrio Fischeri_ is through the QS, there exists a certain range of conditions, where a single free marine bacterial cell can also luminesce light.

**Programming Language**: Wolfram Mathematica 

**Report**: Available 

**Highlights**: 

<p>
<img src="Project_1_Highlight_a.png" width="480"> 
<img src="Project_1_Highlight_b.PNG" width="480">
</p>

The top figure above shows the key principles behind QS mechanism in _Vibrio Fischeri_ [source](http://photobiology.info/Lin.html). The bottom figure shows the switch-like behavior of the gene to induce photoluminiscence depending upon values of the system variables defined in the original paper. Shading scale is shown as a legend, where the numbers correspond the time it takes for the system to asymptotically reach either of the two stable steady states - on and off.  

## Project 2: Force-Dependent Adhesion of Malaria-Infected Red Blood Cells with ICAM-1 and CD36

**Citation for originial paper**: Lim Y. B., Thingna J., Cao J. & Lim C. T. (2017), 'Single molecule and multiple bond characterization of catch bond associated cytoadhesion in malaria' _Scientic Reports_ 7(1).
[doi:10.1038/s41598-017-04352-x](https://www.nature.com/articles/s41598-017-04352-x)

**Brief Summary**: Patients of malaria show abnormally high levels of infected red blood cell (iRBC) adhesion to the membrane proteins expressed in the endothelial vessels. This is one of the main causes that lead to severe disease pathology in malarial patients like multiple organ failure and cerebral malaria. In this study, the authors have taken a biophysical approach to study the interactions between iRBCs and specific endothelial receptor proteins - CD36 and ICAM-1. The method described in this paper is very elegant as it is used to simultaneously study protein-ligand adhesive interactions at single-molecule and single-cell scale. The highlight of this study is the result that even though the dissociation rates of ICAM-1 and CD-36 are similar to each other in magnitude, the catch-bond like behavior and a high re-association rates of ICAM-1 make its adhesion to iRBCs much more significant. 

**Programming Language**: R (compiled and verified in RStudio)

**Report**: Available 

**Highlights**: 

<p>
<img src="Project_1_Highlight_b.png" width="480"> 
</p>

The figure above shows the bond lifetimes of the two endothelial proteins to iRBC cells - CD36 (left) which shows a slip-like behavior and ICAM-1 (right) which shows a catch-like behavior at single molecule protein-ligand interaction. According to the figure result above, both theory and experiments suggest that even in multiple bond case, the behavior remains the same - which is an impressive finding! 

**Additional note**: For this parameter-fit analysis, you will need to have access to the experimental data. I was able to obtain the data by contacting the corresponding author as mentioned on the publication. If you would like to follow through the parameter-fit analysis, I would recommend emailing the corresponding author directly.

## Project 3: Image Segmentation of Fluorescent _E. Coli_ Cells flowing in a Wide Mother Machine using a U-Net Architecture

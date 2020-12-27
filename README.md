#suremapp #dataset #mammograms #manually-annotated #mammography

Publicly Available SuReMaPP (Suspicious Regions on Mammograms from Palermo Polyclinic) 

The SuReMaPP dataset consists of 343 mammograms hand-labeled by expert radiologists dealing with the identification of suspicious regions such as abnormalities (benignant and malignant) and calcifications. 
SuReMa contains mammograms with high spatial resolutions depending on the mammography device used (in order, GIOTTO IMAGE SDL/W generates images with spatial resolution of 3584 x 2816 pixels, FUJIFILM FCR PROFECT CS generates images with spatial resolution of 5928 x 4728). 
We want to share SuReMa hand-labeled dataset with the scientific community to be used as "Gold Standard" for biomedical imaging methods and algorithms. We used SuReMa to validate and assess the performance of our method "An Integrated Solution for detecting suspicious regions in Mammogram Images". 
You are free to use the database in your scientific research but you must abide by the license agreement when using the images
The case studies in question are anonymised.

To make access to SuReMaPP go to link down below:

http://www1.unipa.it/dibimel/mammodb/

Details related to SuReMaPP images are given as follows:
1st column
SuReMaPP database reference number.

2nd column
Laterality Image : 
CC_DX 
CC_SX 
OL_DX 
OL_SX 

3rd column: 
Character of background tissue
FA - Fatty 
FG - Fatty-Glandular 

4rd column 
Class of abnormality present: 
OVA - Oval opacity 
CIRC - Circular opacity
NOD - No Defined
MISC - Other 
ASYM - Asymmetry 
NORM - Normal

5rd column 
Contour : 
REG - regular	
NON_REG - regular
SFU - faded
POL - polilobati	
ND - Non definiti 

6th column 
Severity of abnormality : 
B - Benign 
M -  Malignant 
N -  No Defined 

7th, 8th columns 
x,y image-coordinates of centre of abnormality.

9th column 
Approximate radius (in pixels) of a circle enclosing the abnormality. 

If you use SuReMaPP Dataset, please cite the scientific paper as down below (bibtex reference format):

@article{bruno2020novel,
  title={A novel solution based on scale invariant feature transform descriptors and deep learning for the detection of suspicious regions in mammogram images},
  author={Bruno, Alessandro and Ardizzone, Edoardo and Vitabile, Salvatore and Midiri, Massimo},
  journal={Journal of Medical Signals and Sensors},
  volume={10},
  number={3},
  pages={158},
  year={2020},
  publisher={Wolters Kluwer--Medknow Publications}
}


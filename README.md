APOGEE's Galaxy activity used for University of Florida's AST 4300, Galactic Astronomy, in Fall 2023. 
This was a class for upper division (senior and junior) astronomy majors that covered stellar structure,
stellar evolution, and the Local Group. This activity uses data from SDSS APOGEE DR17 to make maps of 
the galaxy's chemistry, structure, etc and uses a simple neural network to estimate ages from a seismic
training set. 


Files include:

Project3_APOGEEsGalaxy_Blank.ipynb:  the blank workbook given to students and used for this activity. 
There is also a pdf version in case they want be able to glance at it or use something other than a jupyter notebook for the activity

APOKASC705_AGE_short.fits: Data file of ages from my maximum mass loss run of Pinsonneault et al. in prep, from SDSS internal version 7.0.5.
Used as training data in the notebook. Will be superseeded by the final APOKASC-3 ages eventually.

 I wrote up part of the exercise as AAS Research Note "The Importance of Neural Network Hyperparameters in Determining Age Inference Quality"
 https://iopscience.iop.org/article/10.3847/2515-5172/ad16d3 

The files used for that were (students should not need these):

fitresults.txt: Table of results from varying the hyperparameters and training the network including input from all the researchers.

Project3_AST4300_Paperplots.ipynb: version of the notebook that I modified to read in fitresults.txt and make the plots for the paper. 
 
The text when assigning this project was:

In this assignment, I want you to get some experience with exploring real spectroscopic data sets of the Milky Way Galaxy, 
compare them to the work you've read about, and try the sorts of machine learning experiments that have become popular 
in the field. I have created a jupyter notebook to walk you through the project (including some starter code to give 
you a sense of what the functions look like) but you are not required to use python for this project. If you prefer to
use something else (or python but some other framework), you can answer the same questions in the pdf version. 

Please submit a pdf version ofthe notebook with the answers filled in (print preview, save as pdf, etc), or the equivalent in
whatever framework you decide to use- I do not intend to try to run any of your code during the grading process. Note that this 
notebook seemed to run fine in google colab if you are running into problems on your own computer.

In the later parts of this, you will also need this file with the asteroseismic ages to train on: APOKASC705_AGE_short.fits

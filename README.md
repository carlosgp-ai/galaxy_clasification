# Automatic Similarity Detection between Galaxies with Deep Learning
<p align="center">
  <img src="https://github.com/carlosgp-ai/galaxy_clasification/blob/master/GRANTECAN_Starry_Night_Van_Gogh.png" width="500" title="GRANTECAN y Starry Night"> 
</p>
<p align="center">
<b>Gran Telescopio de Canarias - Starry Night (Van Gogh) mixed with Neural Style Transfer</b>
</p>

## Abstract
Today there is a great revolution in the Astronomy world, the power of the current telescopes is leading to great discoveries such as the first images of black holes or the discovery of exoplanets. In collaboration with the Canarias Astrophysical Institute, a solution based on Artificial Intelligence has been proposed to facilitate the identification of twin Galaxies and thus carry out studies between Galaxies that have the active nucleus (AGN) and their selected twins that do not. Deep Learning, one area of Artificial Intelligence, will allow us to perform, through computer vision and more specifically through the algorithms of Convolutional Neural Networks (CNN), a ranking of twin galaxies of the chosen AGNs. Finally, as a future and innovative study we will use another algorithm, the Siamese Neural Networks, which is currently used mainly for facial recognition and we will try to adapt it to obtain the ranking of galaxies similarity.

The content of the shared folder is:
- TFM_Classification Dataset Preparation.ipynb: Dataset preparation notebook used locally to prepare the 3 and 4 Class Morphological Classification Dataset.
- FITS_Reader.ipynb: notebook to read the FITS astronomy file provided by the IAC, from this reading we prepare the previous Dataset.
- TFM_Exploration and Preparation of Dataset.ipynb: Dataset preparation notebook using mainly the Augmentor library to increase its size.
- TFM Max_Clarity_Compare.ipynb: very simple notebook used at the beginning to test different techniques of computational perception.
- Results TFM_Dataset_Galaxias_Clasificacion_4_Clases_iter1.ipynb, TFM_Dataset_Galaxias_Clasificacion_4_Clases_Iter2_240.ipynb and TFM_Dataset_Galaxias_Clasificacion_4_Clases.ipynC_Dataset_Galaxias_Clasificacion_4_Clases_BNB and TFM_Dataset_Galaxias_Clasificacion_BB and TFM_Dataset_Galaxias_Different Classification_Model tests.
- TFM_Dataset_Galaxias_Clasificacion_8_Clases.ipynb: 8 Class morphological classification notebook.
- TFM_Dataset_Galaxias_Clasificacion_N_Clases.ipynb: notebook that tests the Classification model with N Classes, each Galaxy corresponds to a different class.
- TFM_Neural_Siamese_Network.ipynb: Test of the application of the Siamese neural network to our Galaxies Dataset still under development

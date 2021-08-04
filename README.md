## Summary
-	Developed multiple unsupervised data compression algorithms, which are robust to outliers.
-	Compared the proposed data compression methods with widely used separable algorithms using Yale face datasets, Olivetti Research Laboratory (ORL) face dataset, and Centre for Biological and Computational Learning (CBCL) face datasets.
-	Improved the relative approximation quality of the existing separable classification method by 5% on average.

## Skills /Tools: 
- Data Compression (PCA, SVD, Non-Negative Matrix Factorization), Optimization, MATLAB, MOSEK, LaTeX. 



# Image-datasets
Yale face dataset: Yale university is made up image faces of 38 people, each of which as 64 frontal face images with various occlusions incurred by different light conditions (The dataset is available in https://www.dropbox.com/s/5wx9feng2ot38is/GS-NMF%20v2.zip?dl=0&file_subpath=%2FGS-NMF+v2). The images of size 192x168 are downsampled to 48x42. Then, 10 face images from each individual are randomly selected to obtain 380 images. Finally, the pixel-by-face matrix has dimension 2016x380. 

ORL face dataset:This dataset consists of a series of face images taken between April 1992 and April 1994 by Olivetti laboratory in Cambridge, UK. The dataset contains 40 objects of different ages, genders and races. From each individual, ORL has 10 different images of size 112x92, which downsampled to obtain images of size 23x19. The pixel-by-face matrix has dimension 437x400. ( The dataset is availabe here http://web.mit.edu/emeyers/www/face_databases.html)

CBCL face dataset: CBCL is a public database for research usage provided by the MIT center for Biological and Computation Learning ( The dataset can be found using the following URL http://www.ai.mit.edu/courses/6.899/lectures/faces.tar.gz). This dataset consists 2429 face images of size 19$\times$19 so that the input pixel-by-face matrix has dimension 361x2429.

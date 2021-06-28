# Data Compression/Dimensionality Reduction

#### Summary 
In this project, three new Non-Negative Matrix Factorization (NNMF) algorithms based on solution methods for the MAX FS problem
have been developed. The introduced new NNMF algorithms (Feasible Subset Matrix Factorization (FSMF), Fast Feasible Subset Matrix Factorization Algorithm (FFSMF), and Feasible Subset Matrix Factorization - Partitioned (FSMF-P)) do not require any initialization method in contrast to most of the existing NNMF methods. The performance of the proposed methods has investigated considering different set of synthetic and real-world datasets.

## Objective
Develop and apply new optimization algorithms for dimensionality reduction. The optimization algorithms developed   
The Proposed NNMF algorithms do NOT require 
The initialization step
Prespecified rank (P)
![image](https://user-images.githubusercontent.com/59096353/114217556-521f5180-9936-11eb-88a6-4e42f6c64bd6.png)




Non-Negative Matrix Factorization (NNMF) for Dimensionality Reduction 
Non-negative matrix factorization is an unsupervised dimension reduction method which determines a lower rank approximation of a given non-negative matrix V. 

![NNMF Def](https://user-images.githubusercontent.com/59096353/114217351-08cf0200-9936-11eb-8bd8-9385596c88ce.png)





# Image-datasets
Yale face dataset: Yale university is made up image faces of 38 people, each of which as 64 frontal face images with various occlusions incurred by different light conditions (The dataset is available in https://www.dropbox.com/s/5wx9feng2ot38is/GS-NMF%20v2.zip?dl=0&file_subpath=%2FGS-NMF+v2). The images of size 192x168 are downsampled to 48x42. Then, 10 face images from each individual are randomly selected to obtain 380 images. Finally, the pixel-by-face matrix has dimension 2016x380. 

ORL face dataset:This dataset consists of a series of face images taken between April 1992 and April 1994 by Olivetti laboratory in Cambridge, UK. The dataset contains 40 objects of different ages, genders and races. From each individual, ORL has 10 different images of size 112x92, which downsampled to obtain images of size 23x19. The pixel-by-face matrix has dimension 437x400. ( The dataset is availabe here http://web.mit.edu/emeyers/www/face_databases.html)

CBCL face dataset: CBCL is a public database for research usage provided by the MIT center for Biological and Computation Learning ( The dataset can be found using the following URL http://www.ai.mit.edu/courses/6.899/lectures/faces.tar.gz). This dataset consists 2429 face images of size 19$\times$19 so that the input pixel-by-face matrix has dimension 361x2429.

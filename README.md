# Data Compression/Dimensionality Reduction
## Summary
-	Designed and developed multiple unsupervised data compression algorithms that are resilient to outliers, resulting in significant improvements in data compression quality.
-	Conducted comparative analysis of the proposed data compression methods with widely used separable algorithms using multiple face datasets, including Yale, Olivetti Research Laboratory (ORL), and Centre for Biological and Computational Learning (CBCL), demonstrating the superiority of the developed algorithms in terms of accuracy and robustness. 
-	Optimized the relative approximation quality of the existing separable classification method by an average of 5%, using the developed algorithms and techniques.

## Skills /Tools: 
- Data Compression (PCA, SVD, Non-Negative Matrix Factorization), Optimization, MATLAB, MOSEK, LaTeX. 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
##### Some information about the developed algorithm, datasets, and experimental results are summarised in below. 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Non-Negative Matrix Factorization (NNMF)
![image](https://user-images.githubusercontent.com/59096353/128291454-2ee0fcbd-9c97-47ad-9421-3965ed3314f9.png)

# New Developed Data Compression/Dimensionality Reduction Algorithms
![image](https://user-images.githubusercontent.com/59096353/128288959-afcee4bb-95b0-47bc-830d-c9e13bbc3296.png)

# Dataset
### Synthetic datasets:
In this set of experiemtns, we considered P=10, m=50, and n=200. Each entry of \mathbf{V}_{m\times n} is generated randomly. We generated 100 such matrices. 
### Synthetic dataset with outliers
 ![image](https://user-images.githubusercontent.com/59096353/128291338-69a480a2-04ad-48d4-a123-b117861b4ba2.png)
### Image-datasets
Yale face dataset: Yale university is made up image faces of 38 people, each of which as 64 frontal face images with various occlusions incurred by different light conditions (The dataset is available in https://www.dropbox.com/s/5wx9feng2ot38is/GS-NMF%20v2.zip?dl=0&file_subpath=%2FGS-NMF+v2). The images of size 192x168 are downsampled to 48x42. Then, 10 face images from each individual are randomly selected to obtain 380 images. Finally, the pixel-by-face matrix has dimension 2016x380. 

ORL face dataset:This dataset consists of a series of face images taken between April 1992 and April 1994 by Olivetti laboratory in Cambridge, UK. The dataset contains 40 objects of different ages, genders and races. From each individual, ORL has 10 different images of size 112x92, which downsampled to obtain images of size 23x19. The pixel-by-face matrix has dimension 437x400. ( The dataset is availabe here http://web.mit.edu/emeyers/www/face_databases.html)

CBCL face dataset: CBCL is a public database for research usage provided by the MIT center for Biological and Computation Learning ( The dataset can be found using the following URL http://www.ai.mit.edu/courses/6.899/lectures/faces.tar.gz). This dataset consists 2429 face images of size 19$\times$19 so that the input pixel-by-face matrix has dimension 361x2429.

# Summary of Experimental Results
![image](https://user-images.githubusercontent.com/59096353/128288672-5268becc-c860-4559-a605-a20c63db3a5c.png)

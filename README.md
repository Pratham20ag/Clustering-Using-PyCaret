# Clustering-Using-PyCaret
Using PyCaret to compare different Clustering Algorithms on the Iris Dataset. The Species column was removed.
#### Metrics Used
**1. Silhouette Score**: This measures how well data points are assigned to their clusters by considering both intra-cluster distance (similarity) and inter-cluster distance (dissimilarity). It ranges from -1 to 1, with higher values indicating better clustering.     
       
**2. Calinski-Harabasz Index**: This compares the average distance between clusters to the average distance within clusters. Higher values indicate better separation between clusters. 
           
**3. Davies-Bouldin Index**: This measures the ratio of the within-cluster distance to the between-cluster distance. Lower values indicate tighter and better-separated clusters.     
         
### 1.Without PreProcessing
![image](https://github.com/Pratham20ag/Clustering-Using-PyCaret/assets/124654924/cba59248-0257-400a-8860-b31c7adaa8ef)

### 2.With Normalization 
![image](https://github.com/Pratham20ag/Clustering-Using-PyCaret/assets/124654924/0aa13d38-1a34-447e-a297-bc10fdab3327)

### 3.With Transformation
![image](https://github.com/Pratham20ag/Clustering-Using-PyCaret/assets/124654924/e9485cf0-abad-44bc-9b3a-8fa6cc1bbe82)

### 4. With PCA
![image](https://github.com/Pratham20ag/Clustering-Using-PyCaret/assets/124654924/d8f65b95-e5e9-4ee6-8569-b2c8f608a063)

### 5. Using Transformation and Normalization
![image](https://github.com/Pratham20ag/Clustering-Using-PyCaret/assets/124654924/cc07e8a6-3450-4a21-a6fd-61752c097bb2)

### 6. Using Transformation, Normalization and PCA
![image](https://github.com/Pratham20ag/Clustering-Using-PyCaret/assets/124654924/3b0ab1c6-98e7-469d-a01c-99ca79197f8c)

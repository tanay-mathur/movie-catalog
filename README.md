# movie-catalog
Dataset: https://grouplens.org/datasets/movielens/25m/

Steps to follow:

Order to run the files:
1. Upload the data to a Google Drive location that can be accessed through the code
2. `Clustering_models.ipynb`
   - For each input DataFrame, replace "/content/drive/MyDrive/Project-Building-a-Movie-Catalog/ml-25m/*" with the updated drive location that contains the raw data
   - Replace "/content/drive/Shared drives/Project-Building-a-Movie-Catalog/Clustering_by_tags/*" with the updated drive location. Models will be saved here and imported in `Movie_Catalog.ipynb`
3. `Movie_Catalog.ipynb`
   - For each input DataFrame, replace "/content/drive/Shareddrives/Project-Building-a-Movie-Catalog/ml-25m/" with the updated drive location that contains the raw data
   - Replace "/content/drive/Shared drives/Project-Building-a-Movie-Catalog/Clustering_by_tags/*" with the path from the above file where the models were saved 

## References
<a id="1">[1]</a> 
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872

<a id="1">[2]</a> 
Jesse Vig, Shilad Sen, and John Riedl. 2012. The Tag Genome: Encoding Community Knowledge to Support Novel Interaction. ACM Trans. Interact. Intell. Syst. 2, 3: 13:1–13:44. https://doi.org/10.1145/2362394.2362395

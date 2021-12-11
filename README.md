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

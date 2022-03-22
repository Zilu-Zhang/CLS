# Expert_Graded_Datasets

Each folder in this directory contains a raw dataset (.csv) and a dozen of analysis graphs, including:

  1. Coverage threshold;
  2. Dataset composition;
  3. PCA/t-SNE clustering results, feature-based PCA and feature-based t-SNE plots of:
  markup: * original values;
    > scaled values (transformed using Min-Max Scaling where all values are scaled to the same level of [0,1]);
    
    * standardized values (transformed using Z score where distributions of all features are equally centered at 0 with a standard deviation of 1);
    
    * hybrid values (apply standardization only on non-binary features)

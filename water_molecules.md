# machine_learning

### TASKS
- Download the water.csv. It is a file consisting 1001 snapshots of 250 water molecules. i.e. each line has coordinates of 750 atoms( making total 2250 columns) and 2251st column is called a flag which is not relevant in the begining.
- Since they are coordinates, I reshaped the feature vector of dim 2250 into 750 X 3 matrix. Essentially making it a 750 dimensional array of 3d vectors.
- I ran clustering algorithm on 1001 feature vectors of sim 2250. Performed elbow and sihoutte analysis and identified distinct clusters in 1001 snapshots.
- The 2251st column represnts a flag corresponding to the type of ice or liquid state for a particular snapshot. I discussed how well the clustering analysis identifies physical state of the water snapshot.
- 
Extensive documentation is included in the notebook.

You should download the water.csv file. Ensure notebook and file are in the same directory.

You might have to install the yellowbrick package (it's a fairly common python package for visualizing ML algorithms).

Contained in the notebook is an extensive description (justification) of clustering algorithms suitable for unsupervised learning of water molecules

# machine_learning

### TASKS
- Download the water.csv. It is a file consisting 1001 snapshots of 250 water molecules. i.e. each line has coordinates of 750 atoms( making total 2250 columns) and 2251st column is called a flag which is not relevant in the begining.
- Since they are coordinates, I reshaped the feature vector of dim 2250 into 750 X 3 matrix. Essentially making it a 750 dimensional array of 3d vectors.
- I ran clustering algorithm on 1001 feature vectors of sim 2250. Performed elbow and sihoutte analysis and identified distinct clusters in 1001 snapshots.
- The 2251st column represnts a flag corresponding to the type of ice or liquid state for a particular snapshot. I discussed how well the clustering analysis identifies physical state of the water snapshot.

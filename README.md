# Air-Quality-IoT-Analytics

**[ipynb] Anomaly Detection using TRAFAIR Air Quality Dataset.ipynb**: We have run 12 unsupervised anomaly detection algorithms such as Angle-base Outlier Detection, Isolation Forest, clustering-Based Local Outlier, and other algorithms on the [TRAFAIR](https://www.dati.gov.it/view-dataset?Cerca=&tags_set=trafair&tags=trafair&ordinamento=&sort=Invia) air quality dataset. The anomaly score of each model type is provided along with the T-distributed Stochastic Neighbor Embedding (3D) and Uniform Manifold Approximation and Projection (2D) plots. 

**[html] Anomaly Detection using TRAFAIR Air Quality Dataset.html**: Is IPython notebook converted/exported to HTML.

Download the [html] file and open it via browser. The [ipynb] file can be loaded and viewed from the Github page, but it needs to be reloaded as the file is large. Hence, it is best to download and open via Google Colab or Jupyter Notebook.

### Unsupervised anomaly detection models

The following anomaly detection models are created using PyCaret and trained using a part of TRAFAIR dataset.

![alt text](https://github.com/bharathsudharsan/Air-Quality-IoT-Analytics/blob/main/Model_names.PNG)

### Assign anomaly labels to dataset

The two columns 'Label' and 'Score are added towards the end. 0 stands for inliers and 1 for outliers/anomalies. Score is the values computed by the algorithm. Outliers are assigned with larger anomaly scores.

![alt text](https://github.com/bharathsudharsan/Air-Quality-IoT-Analytics/blob/main/Assign_a_model.PNG)

### Uniform manifold approximation and projection (umap) for outliers

Plot that can be used to analyze the anomaly detection model over different aspects.

![alt text](https://github.com/bharathsudharsan/Air-Quality-IoT-Analytics/blob/main/umap_plot_for_outliers.png)
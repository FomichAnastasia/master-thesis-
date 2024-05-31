<h1> Identifying Points of Interest and Customer Segmentation in Telecommunications </h1>

<h3> Research description - goals, tasks, main results </h3>
The goal of this research is to develop an approach to customer segmentation based on geospatial data using machine learning.

To achieve this goal, within this research we need to solve the following tasks:
1.	Analyze the existing methods of customer segmentation based on ML in geospatial data;
2.	Conduct an Exploratory Data Analysis (EDA) on the provided dataset and pre-process the data to identify useful patterns;
3.	Perform feature transformations and clustering to generate new features for the dataset;
4.	Provide hypotheses about customer behavior based on received clusters and features;
5.	Estimate financial effects from implementation of the deliverables.

The main results of the study are represented by the obtained clusters, which describe people in terms of their movements within Saint Petersburg, as well as from the perspective of their interests. Additional results included new variables obtained during clustering and econometric analysis. 

<h3>Files description</h3>

1. main file

The file contains pre-processing steps, EDA and some feature generation steps. It requires the results of POIs-parsing code.  

2. POIs-parsing cod

The code for POIs of Saint-Petersburg generation process. Contains both parsing and pre-processing steps.

3. heatmap creation code

The process of 28T pictures generation for SOM method. Resulted pictures are needed to be added in archive. Dataset with features from "main file" is required.

4. SOM

Part of heatmaps clusterization with SOM. Archive with heatmaps from previous code is required. Dataset with features from "main file" is required.

5. DBSCAN

Identification of settlement levels, their clusterization, identification of stable geolocations for IDs, identification of stable geolocations for different time periods of day. Dataset with features from "main file" is required.

6. High level clusterization

Customer clusterization according to interests with PCA.  Dataset with features from "main file" is required.



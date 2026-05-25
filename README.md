# WK2-Project-ADVML-Customer-Segmentation


<h3><span style="text-decoration: underline;"><strong>Option 1: Music Clustering Project </strong></span></h3>
<h4 data-pm-slice="1 3 []"><strong>Project Description</strong></h4>
Music streaming platforms like Spotify generate vast amounts of data related to song characteristics, user preferences, and listening habits. Understanding patterns in this data can help in tasks such as music recommendation, playlist generation, and genre discovery. In this project you are to focus on using clustering techniques to group songs based on their audio features, uncovering hidden structures in the dataset. By analyzing these clusters, one can gain insights into different music styles and potentially enhance recommendation systems.
<h4><strong>Dataset</strong></h4>
The dataset to be used in this project is supposed to be obtained from the Spotify Platform, once you obtain the Developer API Key. Alternatively, if you are not able to connect to Spotify, you can use<a href="https://wagon-public-datasets.s3.amazonaws.com/Machine%20Learning%20Datasets/ML_spotify_data.csv"> this data</a>.  Ideally, the dataset should contain various audio features for songs, including:
<ul data-spread="false">
 	<li><strong>Acousticness</strong>: A measure of acoustic sound in a track</li>
 	<li><strong>Danceability</strong>: How suitable a track is for dancing</li>
 	<li><strong>Energy</strong>: Intensity and activity level of a song</li>
 	<li><strong>Instrumentalness</strong>: The presence of vocals in a track</li>
 	<li><strong>Liveness</strong>: Detects the presence of a live audience</li>
 	<li><strong>Loudness</strong>: The overall loudness of a track</li>
 	<li><strong>Speechiness</strong>: The presence of spoken words in a track</li>
 	<li><strong>Tempo</strong>: The beats per minute (BPM) of a song</li>
 	<li><strong>Valence</strong>: The musical positiveness of a track</li>
</ul>
The dataset may require preprocessing steps such as handling missing values, normalizing features, and removing duplicates before applying clustering models.
<h4><strong>Models</strong></h4>
To perform clustering, experiment with the following unsupervised learning algorithms:
<ol start="1" data-spread="false">
 	<li><strong>K-Means Clustering</strong>: A centroid-based clustering algorithm that partitions data into k groups based on similarity.</li>
 	<li><strong>Hierarchical Clustering</strong>: A tree-based clustering method that groups songs into a hierarchy.</li>
 	<li><strong>DBSCAN (Density-Based Spatial Clustering of Applications with Noise)</strong>: A density-based algorithm useful for identifying clusters of varying shapes and sizes while filtering out noise.</li>
 	<li><strong>Gaussian Mixture Model (GMM)</strong>: A probabilistic clustering method that assumes the data is generated from multiple Gaussian distributions.</li>
</ol>
Dimensionality reduction techniques such as <strong>Principal Component Analysis (PCA)</strong> may be used to visualize high-dimensional data and improve clustering performance.
<h4><strong>Model Evaluation</strong></h4>
Evaluating clustering models is challenging as there are no ground truth labels. You will use the following metrics and techniques:
<ul data-spread="false">
 	<li><strong>Elbow Method &amp; Silhouette Score (for K-Means)</strong>: To determine the optimal number of clusters.</li>
 	<li><strong>Dendrogram Analysis (for Hierarchical Clustering)</strong>: To analyze the hierarchy of clusters.</li>
 	<li><strong>Cluster Distribution &amp; Interpretability</strong>: Analyzing cluster characteristics to ensure meaningful segmentation.</li>
 	<li><strong>Visualization</strong>: Using t-SNE and PCA to visualize the clusters in 2D space.</li>
</ul>
<h4><strong>References </strong></h4>
<ul>
 	<li><span style="text-decoration: underline;"><a href="https://www.youtube.com/watch?v=goUzHd7cTuA">Analysis of Spotify Music Data Talk</a></span></li>
</ul>
<h2></h2>
<h3><span style="text-decoration: underline;"><strong>Option 2: Customer Segmentation </strong></span></h3>
<h4><strong>Project Description</strong></h4>
In this project, you will use a clustering algorithm to perform customer segmentation on a dataset. Customer segmentation is a common technique used in marketing to divide customers into groups based on similar characteristics, such as purchasing behavior or demographics. By segmenting customers, businesses can gain valuable insights to tailor their marketing strategies, product offerings, and customer service.
<h4><strong>Dataset</strong></h4>
You can pick any relevant dataset. Choose a dataset that contains relevant features such as customer demographics (age, gender, location), transaction history (purchase amounts, frequency), and any other information that you think might be useful for customer segmentation. Ensure that the dataset is preprocessed and cleaned before applying the algorithm.

Some options
<ul>
 	<li><a href="https://www.kaggle.com/datasets/yasserh/customer-segmentation-dataset">Retail</a></li>
 	<li><a href="https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis">Customer personality</a></li>
</ul>
Make sure you perform cluster analysis and interpretation:
<ol>
 	<li style="list-style-type: none;">
<ol>
 	<li>Evaluate the quality of the clusters formed using appropriate metrics like the within-cluster sum of squares (WCSS) or silhouette score.</li>
 	<li>Analyze and interpret the characteristics of each customer cluster, identifying meaningful patterns and insights.</li>
 	<li>Visualize the clusters using scatterplots or other suitable visualization techniques to understand the separation.</li>
</ol>
</li>
</ol>
Remember to document your process, explain your decisions, and present your results effectively. Good luck with your project!

&nbsp;
<h3><strong><span style="text-decoration: underline;">Your Feedback Matters!</span></strong></h3>
At Zindua School, we are committed to continuously improving your learning experience. Each week, we provide a short feedback form to understand what’s working well and where we can improve.

By sharing your thoughts, you help us refine our content, enhance support, and ensure a better learning experience for both you and future students. The form takes just a minute to complete, and your insights are invaluable in shaping the program.

???? <strong>Please take a moment to fill out this week's feedback form here:</strong> <a href="https://base.zinduaschool.com/form/Djt-J9trbBxjODiX5VQQ6y7wvTD5Xy7GcYsgGwPSkOI">Weekly Feedback Form</a>

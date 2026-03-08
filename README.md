<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>

<body>

<div class="container">

<h1>Dubai Traffic Accident Severity Prediction</h1>

<p>
This project analyzes <b>Dubai traffic incident data</b> and applies machine learning techniques to 
predict <b>accident severity</b> based on time and location features.
</p>

<p>
The system processes open government data using <b>PySpark for big data processing</b> and 
<b>Scikit-Learn for machine learning modeling</b>.
</p>

<h2>Dataset</h2>

<p>
The dataset is sourced from the <b>Dubai Pulse Open Data Platform</b>.
</p>

<p>Features included in the dataset:</p>

<ul>
<li>Accident ID</li>
<li>Accident Time</li>
<li>Accident Description</li>
<li>Latitude</li>
<li>Longitude</li>
<li>Accident Severity</li>
</ul>


<h2>Technologies Used</h2>

<div class="badge">Python</div>
<div class="badge">PySpark</div>
<div class="badge">Pandas</div>
<div class="badge">NumPy</div>
<div class="badge">Scikit-Learn</div>
<div class="badge">SMOTE</div>


<h2>Project Workflow</h2>

<h3>1. Data Collection</h3>
<p>
Traffic incident data is downloaded from Dubai Pulse and loaded into a Spark DataFrame.
</p>

<h3>2. Data Preprocessing</h3>
<ul>
<li>Removing missing values</li>
<li>Renaming columns for clarity</li>
<li>Converting timestamps to datetime format</li>
</ul>

<h3>3. Feature Engineering</h3>

<p>Additional features are extracted from the accident timestamp:</p>

<ul>
<li>Hour of accident</li>
<li>Day of the week</li>
<li>Latitude</li>
<li>Longitude</li>
</ul>

<p>
These features help capture <b>temporal and spatial patterns</b> in traffic incidents.
</p>

<h3>4. Feature Scaling</h3>

<p>
Numerical features are standardized using <b>StandardScaler</b> to improve machine learning performance.
</p>

<h3>5. Handling Imbalanced Data</h3>

<p>
Traffic severity classes are imbalanced. The project uses 
<b>SMOTE (Synthetic Minority Oversampling Technique)</b> to balance the dataset.
</p>

<h2>Machine Learning Models</h2>

<h3>Support Vector Machine (SVM)</h3>

<p>
Kernel: Radial Basis Function (RBF)
</p>

<p>
SVM finds the optimal boundary separating accident severity classes.
</p>

<h3>K-Nearest Neighbors (KNN)</h3>

<p>
Neighbors used: 5
</p>

<p>
KNN predicts accident severity based on similar historical accident records.
</p>


<h2>Model Evaluation</h2>

<p>The models are evaluated using the following metrics:</p>

<ul>
<li>Accuracy</li>
<li>Precision</li>
<li>Recall</li>
<li>F1 Score</li>
<li>Confusion Matrix</li>
</ul>

<p>
These metrics help measure how effectively the models classify accident severity.
</p>

<p>
<b>Muhammed Raihan</b><br>
Computer Science Graduate – Artificial Intelligence & Big Data<br>
</p>

<div class="footer">
</div>

</div>

</body>
</html>

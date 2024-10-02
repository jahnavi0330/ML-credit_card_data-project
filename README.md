# ML-credit_card_data-project
<h1>Credit Card Data Model Development</h1>

<h2>Table of Contents</h2>
<ul>
  <li><a href="#project-overview">Project Overview</a></li>
  <li><a href="#dataset">Dataset</a></li>
  <li><a href="#project-structure">Project Structure</a></li>
  <li><a href="#data-preprocessing">Data Preprocessing</a></li>
  <li><a href="#feature-engineering">Feature Engineering</a></li>
  <li><a href="#model-development">Model Development</a></li>
  <li><a href="#model-evaluation">Model Evaluation</a></li>
  <li><a href="#results">Results</a></li>
</ul>

<h2>Project Overview</h2>
<p>This project involves the development of an end-to-end machine learning model using <strong>credit card data</strong>. The goal is to predict customer behavior. The entire workflow includes <strong>data cleaning</strong>, <strong>feature engineering</strong>, <strong>model building</strong>, and <strong>evaluation</strong>.</p>


<h2 id="dataset">Dataset</h2>
<p>The dataset after cleaning,it consists of features such as:</p>
<ul>
  <li><strong>Number_Of_Open_Credit_Lines_And_Loans</strong></li>
  <li><strong>Number_RealEstate_Loans_Or_Lines</strong></li>
  <li><strong>Monthly_Income</strong></li>
  <li><strong>Number_Of_Dependents</strong></li>
  <li><strong>Region_Central</strong></li>
  <li><strong>Region_East</strong></li>
  <li><strong>Region_North</strong></li>			
  <li><strong>Region_West</strong></li>	
  <li><strong>Education</strong></li>	
  <li><strong>Good_or_Bad</strong></li>
	
</ul>


<h2 id="project-structure">Project Structure</h2>
<pre>
credit-card-model/
│
├── data/                   # Raw and processed data
├── src/                    # Source code for data preprocessing, feature engineering, and model development
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_building.py
├── models/                 # Saved machine learning models
├── reports/                # Analysis reports
│   ├── model_performance.png
└── results/                # Output results such as evaluation metrics, plots, etc.
</pre>


<h2 id="data-preprocessing">Data Preprocessing</h2>
<p>The data preprocessing pipeline involves the following steps:</p>
<ul>
  <li><strong>Handling Missing Values</strong>: Imputation of missing values where necessary.</li>
  <li><strong>Removing Duplicates</strong>: Ensuring that duplicate features are removed.</li> 
  <li><strong>Categorical Encoding</strong>: Converting categorical variables (e.g., merchant category) into numerical values using <em>One-Hot Encoding and OrdinalEncoder </em>.</li>
  <li><strong>Normalization</strong>: Standardizing numerical features to improve model performance.</li>
</ul>


<h2 id="feature-engineering">Feature Engineering</h2>
<p>Key feature engineering steps:</p>
<ul>
  <li><strong>1.Handling_missing_values</strong></li>
  <li><strong>2.convertig categorical data to numerical data</strong></li>
  <li><strong>3.Handling outliers</strong></li>
  <li><strong>4.variable transformation</strong></li>
  <li><strong>5.Feature scaling</strong></li
</ul>

<h2 id="model-development">Model Development</h2>
<p>Several machine learning models were trained and evaluated to predict credit card risk and behavior, including:</p>
<ul>
  <li><strong>KNN_algorithm</strong></li>
  <li><strong>Logistic Regression</strong></li>
  <li><strong>Naive Baye's</strong></li>
  <li><strong>DecisionTree_algorithm</strong></li>
</ul>
<p>The models were tuned using <em>GridSearchCV</em> to optimize hyperparameters.</p>


<h2 id="model-evaluation">Model Evaluation</h2>
<p>The models were evaluated using key performance metrics:</p>
<ul>
  <li><strong>accuracy_score</strong></li>
  <li><strong>confusion_matrix</strong></li>
  <li><strong>classification_report</strong></li>
  <li><strong>F1-Score</strong></li>
  <li><strong>ROC-AUC Score</strong></li>
</ul>
<p>The Logistic Regression model performed the best with AUC and an accuracy score of 0.66.
<h2 id="results">Results</h2>
<ul>
  <li><strong>Customer Risk Prediction</strong>: The model successfully predicts customer behavior based on features with high accuracy.</li>
  <li><strong>Key Insights</strong>: Visualizations and insights into customer behavior can be found<a 

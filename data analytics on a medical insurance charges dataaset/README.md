# Project Scenario
<p>You have to perform data analytics on a medical insurance charges dataaset. This is a filtered and modified version of the <a href="https://www.kaggle.com/datasets/harishkumardatalab/medical-insurance-price-prediction?resource=download" target="_blank" rel="noopener noreferrer" title="Medical Insurance Price Prediction">Medical Insurance Price Prediction</a> dataset, available under the <a href="https://creativecommons.org/publicdomain/zero/1.0/legalcode" target="_blank" rel="noopener noreferrer" title="CC0 1.0 Universal License">CC0 1.0 Universal License</a> on the <a href="https://www.kaggle.com/" target="_blank" rel="noopener noreferrer" title="Kaggle">Kaggle</a> website.</p>

# Parameters
The parameters used in the dataset are:

| Parameter |Description| Content type |
|---|----|---|
|age| Age in years| integer |
|gender| Male or Female|integer (1 or 2)|
| bmi | Body mass index | float |
|no_of_children| Number of children | integer|
|smoker| Whether smoker or not | integer (0 or 1)|
|region| Which US region - NW, NE, SW, SE | integer (1,2,3 or 4 respectively)| 
|charges| Annual Insurance charges in USD | float|

<ol>
<li><p><strong>Age</strong><br>Age of the insured. Integer quantity.</p>
</li><li><p><strong>Gender</strong><br>Gender of the insured. This parameter has been mapped to numerical values in the following way.</p>
<table>
<thead>
<tr>
<th>Gender</th>
<th>Assigned Value</th>
</tr>
</thead>
<tbody><tr>
<td>Female</td>
<td>1</td>
</tr>
<tr>
<td>Male</td>
<td>2</td>
</tr>
</tbody></table>
</li><li><p><strong>BMI</strong><br>Body Mass Index of the insured. Float value quantity.</p>
</li><li><p><strong>No_of_Children</strong><br>Number of children the insured person has. Integer quantity.</p>
</li><li><p><strong>Smoker</strong><br>Whether the insured person is a smoker or not. This parameter has been mapped to numerical values in the following way.</p>
<table>
<thead>
<tr>
<th>Smoker</th>
<th>Assigned Value</th>
</tr>
</thead>
<tbody><tr>
<td>Smoker</td>
<td>1</td>
</tr>
<tr>
<td>Non smoker</td>
<td>2</td>
</tr>
</tbody></table>
</li><li><p><strong>Region</strong><br>Which region of the USA does the insured belong to. This parameter has been mapped to numerical values in the following way.</p>
<table>
<thead>
<tr>
<th>Region</th>
<th>Assigned Value</th>
</tr>
</thead>
<tbody><tr>
<td>Northwest</td>
<td>1</td>
</tr>
<tr>
<td>Northeast</td>
<td>2</td>
</tr>
<tr>
<td>Southwest</td>
<td>3</td>
</tr>
<tr>
<td>Southeast</td>
<td>4</td>
</tr>
</tbody></table>
</li><li><p><strong>Charges</strong><br>Charges for the insurance in USD. Floating value quantity.</p>
</li></ol>

# Objectives
In this project, you will:
<ul>
<li>Load the data as a pandas dataframe</li><li>Clean the data, taking care of the blank entries</li><li>Run exploratory data analysis and identify the attributes that most affect the charges</li><li>Develop single variable and multi variable Linear Regression models for predicting the charges</li><li>Use Ridge regression to refine the performance of Linear regression models.</li></ul>

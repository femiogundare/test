# A Machine Learning Approach to Precise Renal Cancer Subtyping using RNA-seq Gene Expression Data

## Objective 

Cancer remains a significant global health challenge, with early detection and accurate classification being critical for effective treatment. In this repository, we develop an approach to detect the three most common subtypes of renal cancer — chromophobe renal cell carcinoma, clear cell renal cell carcinoma, and papillary renal cell carcinoma – by leveraging machine learning algorithms applied to RNA-seq gene expression data. 


## Results

| Model | Accuracy | Precision | Recall | Specificity | F1 | AUC |
| :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| Logistic Regression | 94.81 | 93.70 | 82.53 | 94.63 | 86.58 | 97.78 |
| Naive Bayes | 95.56 | 87.69 | 90.27 | 95.89 | 88.83 | 98.06 |
| kNN |  |  |  |  |  |  |
| SVM |  |  |  |  |  |  |
| Decision Tree |  |  |  |  |  |  |
| Random Forest |  |  |  |  |  |  |
| Extra Trees |  |  |  |  |  |  |
| Bagging Classifier |  |  |  |  |  |  |
| Gradient Boosting Machine |  |  |  |  |  |  |



<h2>Classifier Performance Measures</h2>

<table>
  <thead>
    <tr>
      <th rowspan="2">Classifier</th>
      <th colspan="7">Performance Metrics</th>
    </tr>
    <tr>
        <th>Class</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>Specificity</th>
      <th>F1 Score</th>
      <th>AUC</th>
    </tr>
  </thead>
  <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Logistic Regression</td>
      <td>KICH</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
    
    <tr>
      <td rowspan="3">Logistic Regression</td>
      <td>KICH</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    
    <tr>
      <td rowspan="3">Class 3</td>
    </tr>
  </tbody>
</table>

</body>
</html>

# A Machine Learning Approach to Precise Renal Cancer Subtyping using RNA-seq Gene Expression Data

## Objective 

Cancer remains a significant global health challenge, with early detection and accurate classification being critical for effective treatment. In this repository, we develop an approach to detect the three most common subtypes of renal cancer — chromophobe renal cell carcinoma, clear cell renal cell carcinoma, and papillary renal cell carcinoma – by leveraging machine learning algorithms applied to RNA-seq gene expression data. 


## Results

| Model | Accuracy | Precision | Recall | Specificity | F1 | AUC |
| :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| Logistic Regression | 94.81 | 93.70 | 82.53 | 94.63 | 86.58 | 97.78 |
| Naive Bayes | 95.56 | 87.69 | 90.27 | 95.89 | 88.83 | 98.06 |
| K-Nearest Neighbors | 97.41 | 96.75 | 88.53 | 97.43 | 91.68 | 92.98 |
| Support Vector Machine | 97.04 | 96.74 | 85.63 | 96.69 | 89.64 | 98.23 |
| Decision Tree | 95.56 | 86.81 | 93.21 | 96.44 | 89.51 | 96.82 |
| Random Forest Classifier | 97.04 | 89.98 | 93.12 | 98.09 | 91.42 | 99.14 |
| Extra Trees Classifier |  |  |  |  |  |  |
| Bagging Classifier |  |  |  |  |  |  |
| Gradient Boosting Machine |  |  |  |  |  |  |


<h2>Results per class</h2>
<i>Note: KICH stands for chromophobe renal cell carcinoma, KIRC stands for clear cell renal cell carcinoma, KIRP stands for papillary renal cell carcinoma.</i>
<br>
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
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Class 1</td>
      <td>Classifier 1</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>Classifier 2</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
      <td>0.92</td>
    </tr>
    <tr>
      <td>Classifier 3</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
      <td>0.93</td>
    </tr>
  </tbody>
</table>
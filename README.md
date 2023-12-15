# A Machine Learning Approach to Precise Renal Cancer Subtyping using RNA-seq Gene Expression Data

## Objective 

Cancer remains a significant global health challenge, with early detection and accurate classification being critical for effective treatment. In this repository, we develop an approach to detect the three most common subtypes of renal cancer — chromophobe renal cell carcinoma, clear cell renal cell carcinoma, and papillary renal cell carcinoma – by leveraging machine learning algorithms applied to RNA-seq gene expression data. 


## Results
The overall predictive performance of the machine learning methods based on ANOVA feature selection.
| Model | Accuracy | Precision | Recall | Specificity | F1 Score | AUC |
| :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| Logistic Regression | 94.81 | 93.70 | 82.53 | 94.63 | 86.58 | 97.78 |
| Naive Bayes | 95.56 | 87.69 | 90.27 | 95.89 | 88.83 | 98.06 |
| K-Nearest Neighbors | 97.41 | 96.75 | 88.53 | 97.43 | 91.68 | 92.98 |
| Support Vector Machine | 97.04 | 96.74 | 85.63 | 96.69 | 89.64 | 98.23 |
| Decision Tree | 95.56 | 86.81 | 93.21 | 96.44 | 89.51 | 96.82 |
| Random Forest Classifier | 97.04 | 89.98 | 93.12 | 98.09 | 91.42 | 99.14 |
| Extra Trees Classifier | 96.30 | 87.88 | 92.20 | 97.38 | 89.84 | 98.49 |
| Bagging Classifier | 95.93 | 92.12 | 84.42 | 95.72 | 87.43 | 99.16 |
| Gradient Boosting Machine |  |  |  |  |  |  |


<h2>Results per class</h2>
The predictive performance of the machine learning methods per-class based on ANOVA feature selection.
<br>
<br>
<i>Note: KICH stands for chromophobe renal cell carcinoma, KIRC stands for clear cell renal cell carcinoma, and KIRP stands for papillary renal cell carcinoma.</i>
<br>
<br>
<table>
  <thead>
    <tr>
      <th rowspan="2">Classifier</th>
      <th colspan="6">Performance Metrics</th>
    </tr>
    <tr>
        <th>Class</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>Specificity</th>
      <th>F1 Score</th>
    </tr>
  </thead>
  <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Logistic Regression</td>
      <td>KICH</td>
      <td>97.22</td>
      <td>100.00</td>
      <td>61.54</td>
      <td>100.00</td>
      <td>76.19</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>94.44</td>
      <td>94.07</td>
      <td>97.37</td>
      <td>89.39</td>
      <td>95.69</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>92.78</td>
      <td>87.04</td>
      <td>88.68</td>
      <td>94.49</td>
      <td>87.85</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Naive Bayes</td>
      <td>KICH</td>
      <td>96.67</td>
      <td>73.33</td>
      <td>84.62</td>
      <td>97.60</td>
      <td>78.57</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>94.44</td>
      <td>95.61</td>
      <td>95.61</td>
      <td>92.42</td>
      <td>95.61</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>95.56</td>
      <td>94.12</td>
      <td>90.57</td>
      <td>97.64</td>
      <td>92.31</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">K-Nearest Neighbor</td>
      <td>KICH</td>
      <td>97.78</td>
      <td>100.00</td>
      <td>69.23</td>
      <td>100.00</td>
      <td>81.82</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>97.22</td>
      <td>97.39</td>
      <td>98.25</td>
      <td>95.45</td>
      <td>97.82</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>97.22</td>
      <td>92.86</td>
      <td>98.11</td>
      <td>96.85</td>
      <td>95.41</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Support Vector Machine</td>
      <td>KICH</td>
      <td>97.22</td>
      <td>100.00</td>
      <td>61.54</td>
      <td>100.00</td>
      <td>76.19</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>96.67</td>
      <td>95.76</td>
      <td>99.12</td>
      <td>92.42</td>
      <td>97.41</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>97.22</td>
      <td>94.44</td>
      <td>96.23</td>
      <td>97.64</td>
      <td>95.33</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Decision Tree Classifier</td>
      <td>KICH</td>
      <td>96.67</td>
      <td>70.59</td>
      <td>92.31</td>
      <td>97.01</td>
      <td>80.00</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>93.89</td>
      <td>97.25</td>
      <td>92.98</td>
      <td>95.45</td>
      <td>95.07</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>96.11</td>
      <td>92.59</td>
      <td>94.34</td>
      <td>96.85</td>
      <td>93.46</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Random Forest Classifier</td>
      <td>KICH</td>
      <td>97.22</td>
      <td>78.57</td>
      <td>84.62</td>
      <td>98.20</td>
      <td>81.48</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>96.67</td>
      <td>100.00</td>
      <td>97.74</td>
      <td>100.00</td>
      <td>97.30</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>97.22</td>
      <td>91.38</td>
      <td>100.00</td>
      <td>96.06</td>
      <td>95.50</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Extra Trees Classifier</td>
      <td>KICH</td>
      <td>96.67</td>
      <td>73.33</td>
      <td>84.62</td>
      <td>97.60</td>
      <td>78.57</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>95.56</td>
      <td>99.07</td>
      <td>93.86</td>
      <td>98.48</td>
      <td>96.40</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>96.67</td>
      <td>91.23</td>
      <td>98.11</td>
      <td>96.06</td>
      <td>94.55</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Bagging Classifier</td>
      <td>KICH</td>
      <td>96.67</td>
      <td>88.89</td>
      <td>61.54</td>
      <td>99.40</td>
      <td>72.73</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>95.00</td>
      <td>94.87</td>
      <td>97.37</td>
      <td>90.91</td>
      <td>96.10</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>96.11</td>
      <td>92.59</td>
      <td>94.34</td>
      <td>96.85</td>
      <td>93.46</td>
    </tr>
  </tbody>
    <tbody>
    <!-- Replace the placeholder values with your actual data -->
    <tr>
      <td rowspan="3">Gradient Boosting Machine</td>
      <td>KICH</td>
      <td>0.85</td>
      <td>0.78</td>
      <td>0.92</td>
      <td>0.89</td>
      <td>0.82</td>
    </tr>
    <tr>
      <td>KIRC</td>
      <td>0.90</td>
      <td>0.85</td>
      <td>0.88</td>
      <td>0.91</td>
      <td>0.87</td>
    </tr>
    <tr>
      <td>KIRP</td>
      <td>0.88</td>
      <td>0.80</td>
      <td>0.94</td>
      <td>0.87</td>
      <td>0.89</td>
    </tr>
  </tbody>
</table>



<!DOCTYPE html>
    <html>
    <head>
      <meta charset=utf-8 />
      <title></title>
      <style>
        div.container {
          display:inline-block;
        }
    
        p {
          text-align:center;
        }
      </style>
    </head>
    <body>
      <div class="container">
        <img src="http://placehold.it/350x150" height="200" width="200" />
        <p>This is image 1</p>
      </div>
      <div class="container">
        <img class="middle-img" src="http://placehold.it/350x150"/ height="200" width="200" />
        <p>This is image 2</p>
      </div>
      <div class="container">
        <img src="http://placehold.it/350x150" height="200" width="200" />
        <p>This is image 3</p>
      </div>
    </div>
    </body>
    </html>
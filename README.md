# Mod-2-Project

#### Amir Edris, Ben Inoyatov
---

## Introduction
---
We used a dataset from UCI Machine Learning Repository ( [link](https://archive.ics.uci.edu/ml/datasets/Student+Performance#) ) to understand how Portugese students performed in two classes: Math and Portugese. In addition to students' grades, the data sets included social and familial attributes like time spent going out with friends and the quality of the relationship at home. There were a total of 32 original attributes that we worked with in addition to some features that we created. The data was, thankfully, very clean. 
Most visualizations were done using ``` seaborn ``` and ``` matplotlib ```. For statistical tests, we used ``` scipy.stats ``` and for regression we used ``` sklearn ```, ``` pandas ``` and ``` numpy ```.

For more detailed visualizations and exploratory analysis refer to these notebooks:
```eda_visualization_testing
   data_cleaning
   regression```

### Our Question 
---
What gives a student the most chance of success in school? We started this project with a few assumptions about what *we* thought was the answer to that question and were suprised with our results. 

###  Select Observations/Findings and Conclusions
---
![g3_distplot](https://user-images.githubusercontent.com/44031998/93031539-a0b37a00-f5f9-11ea-82f5-30e32783a261.png)
- Our target variable distribution

![g3_studytime](https://user-images.githubusercontent.com/44031998/93031557-cd679180-f5f9-11ea-8acd-46db0b2a5bdb.png)
- Conclusion: Generally, the more study time you had in the week, the better your test scores did. There is a slight decrease in average scores when looking at >10 hrs. We inferred that those   who might find these classes hard to begin with might need more study time. 

![g3_medufedu](https://user-images.githubusercontent.com/44031998/93031600-220b0c80-f5fa-11ea-8682-4aadcfb3051d.png)
- Conclusion: We failed to reject that education level of your parents had affect on your overall grade. 

![g3_failures](https://user-images.githubusercontent.com/44031998/93031624-5aaae600-f5fa-11ea-9077-11253d1a85b5.png)
- Conclusion: Having 1 or more failures led to a signifcant decrease in your final scores. (t_stat of 33, p-val of 1.1e-8)

![g3_higheredu](https://user-images.githubusercontent.com/44031998/93031665-a9f11680-f5fa-11ea-9265-6c2e959ec00f.png)
- Conclusion: Wanting to go on to higher education led to a signifcant increase in average final scores. (t-stat of 8.9, pval of 3.5e-9)

###  Recommendations 
---
- Due to the nature of this data, we recommend a classification approach in addition to regression on the target variable. We are excited to explore Module 3 and 4 in the Flatiron Data Science Immersive Bootcamp Course to bridge the gaps. 
## Links 

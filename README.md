# Portfolio
Data science and analytics projects, 2019-2021
# [Project 1: Machine Learning Classifiers on Traditional and Modern Tobacco Use](https://github.com/alisamao09/Machine-Learning-Classifiers-on-Traditional-and-Modern-Tobacco-Use)
* Tobacco use has an evidence-based association with many chronic diseases such as cancer, cardiovascular disease, mental disorders, etc. Although combustible
cigarette use has declined in the US, the percentage of some users of modern tobacco products such as e-cigarette users who initiated at a young age is 3 times
higher in 2018 than 2014. Therefore, more attention should be focused on modern tobacco products with increasing prevalence. 
* However, most machine learning papers only focus on traditional combustible cigarette use. This motivated us to use machine learning methods to classify an individuals use status of modern tobacco products (Never user, Former user, and Current user) based on their use of other tobacco products combined with sociodemographic factors including age, ethnicity, and marital status. 
* Our results show that the Kernel Ridge Regression yields the best performance when compared with other machine learning methods when evaluated using MSE and AUC scores. Future work includes the application of these machine learning methods to a more balanced dataset and the inclusion of more information-rich features.
# [Project 2: Cervical Cancer Prediction Based on Machine Learning Algorithms](https://github.com/alisamao09/Cervical-Cancer-Prediction-Based-on-Machine-Learning-Algorithms)
* One of the main fatal diseases that threats women’s health is Cervical Cancer, which usually does not present any symptoms in early stages. When some symptoms appear, the patients’ condition might have been worsened and the cancer may have become metastatic. Therefore, early diagnosis of Cervical cancer risk factors can stop its tracks and reduce the mortality rate and the associated complications. 
* To seek for more accurate earlier diagnosis, we proposed a study of Cervical cancer diagnosis based on machine learning classification using Support Vector Classifier, Kernel Ridge regression, Logistic Regression, Lasso Regression, Random Forest Classifier, Gradient Boosting Classifier, and Multilayer Perceptron. The dataset has around 30 variables describing over 800 patients’ demographic information, habits, and historic medical records. It includes four targets (Hinselmann, Schiller, Cytology, and Biopsy). The four targets are used as the measurement for cancer predictions in this project. We also used SMOTE method to handle the imbalanced dataset. Evaluation metrics include Mean Squared Error, R squared, precision, recall, F1 score, and Area Under Curve. 
* Our results show that the Multilayer Perceptron yields the best performance for Hinselmann, and the Gradient Boosting Classifier yields the best performance for the other three targets when compared with other machine learning methods. Future work includes the application of these machine learning methods to a more balanced and real large scale hospital dataset and the inclusion of more informationrich features.
# [Project 3: Classifying students' open-ended responses in large class](https://github.com/alisamao09/research-project-1)
* Tested multiple training and test filters to filter out non-answers, with a success rate above 90%
* Pre-processed text data by stemming words, removing stop words and punctuations, making lowercase, and including "tuples"
* Calculated word frequency by TFIDF
* Explored multiple unsupervised clustering algorithms such as K-means, affinity clustering, and GMM etc.
* Projected clusterings to 2D space and printed out N important terms for each cluster
# [Project 4: Is systolic blood pressure reading related to gender, age, poverty, weight, sleep trouble, and smoking habit? American population-based study](https://github.com/alisamao09/STA302)
* Constructed multiple linear regression models and selected the one that has the largest impact on the change of systolic blood pressure and provides the most accurate predictions based on the dataset
* Explored mostly related variables to the change of systolic blood pressure reading (BPSysAve) and the best predictors for combined systolic blood pressure accurate reading
* Checked model inferences, predictability and scalability
* Performed diagnostic check
# [Project 5: How is diabetes readmission rate related to patients’ pathologic conditions and medications?](https://github.com/alisamao09/STA-303)
* Constructed several GLMs and GLMMs and chose the one with the best predictability, relatively good inferences and scalability
* Explored the best diabetes readmission rate predictors (“readmitted”)
* Analyzed the rudimentary information of patients, medications and laboratory tests taken during the diabetic encounter to identify patients with worse treatment outcomes and made them targeted to interventions to improve their outcomes and reduce costs by fewer readmission
* Performed diagnostic check
* Interpreted the final model and discussed limitations and potentials
# [Project 6: Map interaction design](https://github.com/alisamao09/Map-interaction-design)
* Applied shapes to water condition improvement methods for visual representation
* Designed and formatted the charts, and set up tool tips
* Arranged objects in containers 
* Designed the layout for the mobile app and the website
# [Project 7: Covid-19 What’s all the fuss?](https://github.com/alisamao09/ARC-480)
* Demonstrated patterns between COVID-19 case counts and the ongoing discussion of the virus on social media
* Scraped key phrases in tweets regarding COVID by ScrapeStorm, filtering them by tweet location (Toronto) and months (March to December)
* Found the most frequent words by calculating word frequencies using WriteWords
* Represented the varying frequency (number of appearances) of words within tweets by months by the Height of words
* Represented death cases in Toronto during the same time period by hospital bed changes in size
* Visualized the variation of word frequencies and death cases in Grasshopper:
- Created a list containing all data (number of words and cases) by month (8 months in all), extruded them using the data as the height (scaled death cases by 0.001 due to its huge amount)
- Visualized those changes by changing number slider, from the first month to the final month
- Applied materials to texts and the hospital bed
* Represented the rate of social activity of the Toronto Public Health account by birds flying around the words, according to data found on SocialBlade
* Analyzed limitations, subjectivity, data bias and the potential of this project
![](/images/WX20201208-200425%402x.png)
[Here's the video!](https://www.youtube.com/watch?v=ysZuOS9UK90)
# [Experimental project: how does the distance between the hand and the head of the chopstick and the side of hands affect the total time needed to pick up all red beans in a bowl by chopsticks?](https://github.com/alisamao09/Design-and-Analysis-of-Experiments)
* Used factorial design, performed 20 experiments in total, two distances of 15cm and 10cm are set between the thumb and the chopstick head
* Took influence factors into considerations and tried to eliminate other factors
* Constructed linear model, interaction plot, QQ plot, confidence intervals, and T-tests etc.
# [Miscellaneous](https://github.com/alisamao09/Miscellaneous-projects)
1. Design and Analysis of an Experiment
2. Data visualization with the depth of the water and the sound volume
3. Re-construct artworks by Python in Grasshopper

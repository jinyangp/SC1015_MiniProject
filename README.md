# SC1015 Mini-Project DSF3 Group Team 6

## About
This is a end-to-end mini-project for SC1015 (Introduction to Data Science and Artificial Intelligence) which is centred about competitive powerlifting from [openpowerlifting.org](https://openpowerlifting.gitlab.io/opl-csv/bulk-csv.html). The data set was retrieved on 14 March 2022. To follow along with this project, please refer to the [main notebook](https://github.com/jinyangp/SC1015_MiniProject/blob/main/JupyterNotebooks/main.ipynb).
 
 A brief summary of the notebook is as follows(in order):
 1. Data Extraction
 2. Exploratory Data Analysis (EDA)
 3. Data Preprocessing
 4. Model Building - KMeans Clustering
 5. Results and Conclusion

## Problem Definition
 - What makes every division unique? What features can we use to differentiate the divisions?
 - Can we identify exceptional powerlifters? What makes them exceptional?
 
## Models Used
 - KMeans Clustering
 
## Conclusion
 
 - What categorises the divisions?
   - Age and Glossbrenner(TotalKg) were the most effective features in categorising the divisions
   - BodyweightKg was not as effective
 
 - Other observations relating to division
    - Doing well in Sub-Juniors is not reflective of a powerlifter's future performance
    - Prestiguous events like MR-O may not be as highly competitive as expected
 
 - Can we identify exceptional powerlifters? What makes them exceptional?
   - Yes, can be identified by considering Glossbrenner, BodyweightKg and Age
   - Young Age (<45 years of age)
   - Moderate BodyweightKg ( <= 110kg)
 
## Lessons learnt
- Handling large amount of missing data
- Determining feature importance for selected features (Principal Component Analysis)  
- Scaling of data values (StandardScaler and MinMaxScaler)
- Building a clustering model (KMeans)
- Deriving data-driven insights from model
 
## Contributors
- @jinyangp - Data Extraction, EDA, Data Preprocessing, Results and Conclusion
- @lamkaiyi - Data Extraction, Data Preprocessing, Model Building
- @ngwenlu - EDA, Results and Conclusion
 
## References
- https://openpowerlifting.org/
- https://towardsdatascience.com/pca-clearly-explained-how-when-why-to-use-it-and-feature-importance-a-guide-in-python-7c274582c37e
- https://builtin.com/data-science/step-step-explanation-principal-component-analysis
- https://barbend.com/2022-mr-olympia-qualification-system/

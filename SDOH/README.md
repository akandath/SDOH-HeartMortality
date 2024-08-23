[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/nT4M_vAo)
# Sprint 2 - 90803
### Machine Learning Foundations with Python
#### Spring 2024

---

> Modify here: 

For this Lab, you will need to do the following:

1. Git clone your repo to your local machine (look back at Lab 1 if you have any doubts), using the SSH connection.
2. Open the `Sprint2_S24_TeamName` jupyter notebook and work through it.
3. It is advisable to work on different branches and, in the end, merge your branches to `main`.
4. Periodically go back to the terminal to commit your changes to your Jupyter Notebook. Do not wait until the end; make sure to commit for at least every question in the notebook. Remember that doing a commit involves:
	-  Making changes to your jupyter notebook
	-  Adding changes to your staging area (`git add`)
	-  Committing, with a descriptive message of the task you are committing (`git commit -m "descriptive message"`).
	-  Add a gitignore `git add .gitignore` - for the files you want the commit to ignore. For example, in MacOS you might want to ignore `.DS_Store`. Add this to your gitignore `echo .DS_Store >> .gitignore`. Other files that you might want to include here are `ipynb_checkpoints/*`.
	-  Here are some links if you want to read more on [ipynb checkpoints](https://stackoverflow.com/questions/46421663/what-are-jupyter-notebook-checkpoint-files-for) or how to [gitignore](https://stackoverflow.com/questions/35916658/how-to-git-ignore-ipython-notebook-checkpoints-anywhere-in-repository) them.
5. When you are ready to push back to your GitHub remote repo, make sure to:
	- Have any branches merged into `main`
	- `git push origin main`
	- Have your passphrase at hand
	- After the first push, remember to always `git pull` before working on your local repo (to make sure you're up to date) and then `git push` when you are ready to push changes back to your remote repo.



## Notes on this Sprint - To Modify
- Please follow the instructions provided in the videos (CANVAS)
- Once you are done, please answer the questions below. Make sure you have discussed and come to a consensus when addressing the following questions.

> Modify here: 

**1. List the names of all your teammates:**
> Ashwin Kandath, Siva Komaragiri, Nicolle Vigil

**2. Agree as a team, what branching strategy do you plan to use in your final projects? Justify your choices**

> Feature branching strategy is what we plan on using for our final projects. 
 

**3.Communication: Outline how the team will communicate — including frequency and methods (e.g., email, WhatsApp, team meetings).  What is the maximum expected response time?**

> Our team will be using Whatsapp & Discord as our main methods of communication. For team meetings we will be using zoom. We plan on connecting twice a week for regular check ins and progess.

**4. Decision-Making: How will decisions be made in this team? How will you stay on track? Do you plan on having meetings or any strategies for working through your final project**

> We will keep each other accountable during our twice weekly meetings. Based on each teammates workload, we will ensure to balance the work in such a way that we're all on the same page.


**5. As with any team project there is always the possibility of conflict arising, if it does in the future, how will you resolve differences? List at least two strategies**

> We will address the conflict by talking to each other and ensuring there is no communication gaps between all the teammates.
> We will try to identify the root cause and also ensure that we don't leave any task till the last minute so that team does not have time pressure in completeing the tasks and have enough time to work through it, along with increasing the frequency of the deadlines and being on track.

**6.Commitments: How will you handle different levels of participation and commitment? What process will you follow if someone does not live up to his/her/their responsibilities? (3-5 sentences)**

> We will do SWOT analysis on the situation at hand and ensure to resolve it in a peaceful manner.
> We will show empathy and understand what their problems are in terms of not living up to their responsibilites, and then tackle that peacefully. 


**7.Diversity: How will you accommodate different learning and working styles? Talk about your own styles and schedules for working and come to an agreement (3-6 sentences)**


> Suprisingly we all have similar working styles after discussing about this.
> I (siva) likes using pomodoro techniques to finish tasks, whereas Ashwin likes time blocking technique, and Nicolle likes a mix of both. 

# Sprint 3 & 4:- 

# Title: Predicting Mortality from Heart Disease and Diabetes Using Social Determinants of Health

## Group Members:
> Ashwin Kandath - akandath@andrew.cmu.edu

> Siva Komaragiri - skomarag@andrew.cmu.edu

> Nicolle Vigil - nvigil@andrew.cmu.edu

### Problem Statement:
How will healthcare systems and the insurance industry adapt to changing climatic conditions and social determinants of health?

### Project Description:
Brief Description: This project explores the impact of social determinants of health (SDOH) and environmental factors on mortality rates from heart disease and diabetes. It seeks to understand how these external factors contribute to the burden on healthcare systems and insurance expenditures.

### Relevance: 
Given the global prevalence of heart disease and diabetes, understanding the broader determinants of health is crucial for developing effective prevention and management strategies.

### Affected Parties: 
This research primarily impacts the general public, healthcare providers, and insurance companies, with a focus on the U.S. population.

### Occurrence: 
This ongoing issue is exacerbated by the current trends in climate change, urbanization, and socio-economic disparities.

### Motivation: 
Our team is driven by the potential to influence public health policies and healthcare practices through our findings, contributing to more resilient healthcare systems and communities.

### Dataset Description:
> Source: Our datasets are sourced from the CDC for SDOH data and NASA/NOAA for environmental data, alongside health outcomes data from the Global Burden of Disease Study.

> Access Link: Codebook ([https://www.ahrq.gov/sites/default/files/wysiwyg/sdoh/SDOH_2017_Codebook_1_0.xlsx](url))

> Format and Metadata: The datasets are primarily in CSV format, encompassing a range of variables from climate data (e.g., temperature, precipitation) to health outcomes (e.g., mortality rates) and socio-economic indicators.

> Variables Overview: Variables include, but are not limited to, temperature, precipitation, socio-economic status indicators, health insurance coverage, and mortality rates from heart disease and diabetes.

### Refined Research Questions:-

#### How to Predict Mortality Rates/Incidence from Heart Disease and Diabetes Using Socio-economic and Environmental Factors?
	Target Variable: Current mortality rates from heart disease and diabetes.
	Task Type: Regression Analysis. (predictive/correlation)
	Refinement: We’re shifting the focus from correlation analysis to predicting current mortality rates using a comprehensive set of socio-economic and environmental factors. This question aims to utilize regression models to understand how various factors contribute to mortality rates, providing actionable insights for healthcare interventions.


#### Using the SDOH dataset, which social determinant of health model best predicts diabetes risk by classifying them into various risk levels of diabetes and assesing insights generated from the models?
	Target Variable: Vulnerability level (e.g., High, Medium, Low) based on thresholds of Diabetes Risk rates across counties in the US.
	Task Type: Classification.
	Refinement: Instead of predicting future mortality rates, this question focuses on classifying populations into vulnerability categories based on current socio-economic and environmental conditions. The model could inform healthcare providers and policymakers about which populations are most at risk, facilitating targeted preventive measures.


#### How to Identify Clusters of U.S. Regions with Similar Health Outcomes and Contributing Factors for Heart Disease and Diabetes?
	Target Variable: Not applicable (unsupervised learning).
	Task Type: Clustering (Unsupervised Learning).
	Refinement: Here we introduce an unsupervised learning aspect to the project by exploring patterns and similarities among U.S. regions in terms of health outcomes and the socio-economic and environmental factors that contribute to those outcomes. The clusters identified can reveal insights into how different factors interplay in varying geographical contexts, potentially guiding region-specific healthcare strategies.
 
#### Future Scope:
The insights gained from this project could pave the way for incorporating machine learning to predict health outcomes based on a wide array of environmental data. Future research could extend to other diseases influenced by environmental factors, such as respiratory or infectious diseases, utilizing advanced machine learning techniques to enhance predictive accuracy and inform targeted intervention strategies.

# Sprint 5

## Model Evaluation

### Prediction

Firstly, we implemented cross-validation to validate our model across different data subsets, ensuring its generalizability. This technique minimized variance in our model evaluation, providing a more reliable performance assessment..In terms of performance metrics, we utilized Mean Squared Error (MSE) and R-squared (R^2) to enhance interpretability. Lower MSE and RMSE values and higher R^2 and MAE values indicated better model performance. 

Hyperparameter tuning, through Grid Search, allows us to fine-tune our model's parameters, capturing the relationships between these complex variables. This optimization ensures our model is finely calibrated to the unique challenges posed by the interaction of  socio-economic factors and environmental conditions on health outcomes. For understanding feature importance we analyzed key socio-economic and environmental factors influencing mortality rates. This analysis provided invaluable insights for targeted for possible healthcare interventions. 
In essence, by hyperparameter tuning and cross-validation, we aim to craft a Ridge Regression model that not only predicts accurately but also resonates with the intricacies of mortality determinants. This meticulous approach enables us to develop insights that are actionable and impactful for healthcare interventions tailored to the multifaceted challenges of heart disease and diabetes management.

### Classification Model Evaluation

The evaluation of the Logistic Regression, Random Forest, AdaBoost, and XGBoost models on a dataset predicting diabetes risk levels provides detailed insights into their respective performances and capabilities:

1. Logistic Regression:
- Achieved an accuracy of approximately 60.06%, with a slight improvement from the initial model's 58%.
- Demonstrated improvements in recall for the Low Risk (from 0.58 to 0.78) and Medium Risk (from 0.56 to 0.75) categories.
- However, the recall for the High Risk category decreased significantly (from 0.58 to 0.45), suggesting a decline in performance for the most critical category.

2. Random Forest Classifier:
- Achieved an accuracy of approximately 61%, showing marginal improvements over the initial model.
- Reported a balanced performance across different risk categories with a slight improvement in recall for the Low Risk category.
- Maintained similar performance levels for the Medium and High Risk categories, demonstrating stable reliability.

3. AdaBoost Classifier:
- Recorded an accuracy of approximately 59%, slightly lower than the Random Forest model but competitive.
- Exhibited higher sensitivity (recall) for the Low Risk category, accurately identifying more actual positive cases.
- The model's performance varied across classes, better handling the Medium Risk category in terms of F1-score, although it misclassified a number of High Risk cases.


4. XGBoost Classifier:
- After tuning hyperparameters, the optimized XGBoost model achieved an accuracy of approximately 64%, showing strong performance.
- The model was particularly effective in predicting "Medium Risk" cases with the highest precision and recall.
- Best accuracy found during GridSearchCV was 71.60%, suggesting that the model can effectively utilize training data with the right settings.
- These insights highlight the distinct strengths and weaknesses of each model in managing different risk levels in the diabetes dataset. While Logistic Regression showed improvements in recall for lower risk categories, it struggled with High Risk cases.
- Random Forest and AdaBoost demonstrated more balanced performances across risk categories, with AdaBoost excelling in sensitivity for lower risks. XGBoost, with its parameter tuning, provided the best accuracy, making it a strong candidate for further development and application in similar tasks.


### Unsupervised learning
> The models used for this section were, kmeans++, Agglomerate clustering, and GaussianMixture . Dimensionality reduction was needed in order to improve the the clustering algorithm outcomes and obtain better silhouette scores. This is since this clustering algorithms perform better with less number of features.


**Best kmeans**
| Metric | Silhouette Score |
| ---               | ----------- |
|Calinski-Harabasz| k=3 0.196|


**Agglomerate Clustering**
| Metric| Silhouette Score |
| ---               | ----------- |
| Average linkage   |  0.92 |


______________________________________

**GaussianMixture**
| Metric | Silhouette Score |
| ---               | ----------- |
|     |  0.08




Out of the three clustering models Agglomerate Clustering had the best Silhouette Score with an optimal k = 2. This k provided a decent ammount of separation among all the methods with minimal data misclassification. 




## Ethical concsiderations
> **Transparency:** We have made sure that the data we have used is open source and it does not have any unique identifiers which could help to identify a specific individual, community, or geography.  We have also removed unique identifier like State, stateid from the dataset so that there is no state-specific bias is there in the data.


> **Fairness and Equity:**  We have used the SDOH data to inform the development and optimization of healthcare interventions and services aimed at improving health outcomes and not with an intention to exploit or harm the general public.

## Additional models

> Q1: Support Vector Regression (SVR): SVR predicts mortality rates from heart disease based on socio-economic and environmental factors while maximizing the margin between data points and the hyperplane. It considers the spatial distribution of data points in the feature space and finds the optimal hyperplane that separates them, making accurate predictions. We have speicfically used it because it does well to handle non linear relations between input variables.

> Q2 XGBoost: XGBoost was chosen as an additional model due to its robustness and efficiency in dealing with structured data. It's renowned for its ability to manage a mix of categorical and numerical features, as well as its capability to automatically handle missing data—features that are particularly pertinent given the intricate nature of social health determinants. Furthermore, XGBoost offers advanced functionalities like regularization to prevent overfitting and tree-pruning options, making it an ideal candidate for developing a nuanced understanding of risk classification. Its use of gradient boosting frameworks adds an extra layer of precision by building one tree at a time and correcting the previous trees' errors. This iterative refinement is critical when the goal is not just to predict but also to understand the relative influence of various social factors on diabetes risk.

> Q3 GaussianMixture: 



## Disclaimer/Sensitive Content

### Sensitive Content Warning: 
This project delves into the connections between social determinants of health (SDOH), environmental factors, and mortality rates associated with heart disease and diabetes. It addresses potentially distressing topics related to health disparities, systemic inequalities, and the economic implications of healthcare burdens and insurance expenditures. Reader discretion is advised, as the content may evoke emotional or sensitive responses related to health, mortality, and societal challenges.

### Disclaimer
The research conducted is based on publicly available data and information and was used solely for academic purposes. The author recognizes the sensitive nature of the topic of heart disease related deaths . Any findings or conclusions drawn from the analysis were presented with caution and awareness of the potential impact they may have on affected communities. The author acknowledges the complexity of the issues surrounding the same and recognizes the need for continued efforts to address these problems. This research is intended only to understand the ongoing discourse and address this important issue and contribute to the collective efforts toward creating a more equitable society.








#### References:
Source: [https://www.ahrq.gov/sdoh/data-analytics/sdoh-data.html](https://www.ahrq.gov/sites/default/files/wysiwyg/sdoh/SDOH_2017_COUNTY_1_0.xlsx)
From the above link we used the 2017 County year data under the “County Data 2009-2020” column.
SDOH [https://www.ehidc.org/sites/default/files/resources/files/SDOH%20Ethical%20Guidelines%206.27.19%20FINAL.pdf]
SVR [https://www.analyticsvidhya.com/blog/2020/03/support-vector-regression-tutorial-for-machine-learning/#:~:text=SVR%20can%20handle%20non%2Dlinear,variables%20and%20the%20target%20variable.]

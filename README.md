# Mathematics-In-Class-Assignment
## Project Description  
### Overview  
This in-class assignment, as part of the Advanced Mathematics and Statistics for Data Science and AI course, involves a series of structured tasks designed to apply mathematical and statistical concepts in a practical, data-driven context. The assignment is segmented into various sub-tasks, each aimed at enhancing the students' understanding and application of statistical methods in real-world scenarios.  

### Task Details
The overarching goal is to analyze provided datasets to study various statistical phenomena, particularly focusing on mobile usage and its potential correlation with visual search target acquisition speed. The assignment includes two main elements:

**Part1**: Involves tasks such as data quality check, data relationship/distribution analysis, bivariate correlations, linear and multiple regression analyses, and scenario-based analyses.  
**Part2**: Encompasses more advanced tasks like identifying dataset types (linear/non-linear; single/multi-label), applying loss functions (L1, L2, Log, Categorical cross-entropy, Hinge loss), visual comparison of loss functions, assessing with metrics based on classification/regression, kernel transformation on non-linear datasets, creating overfitting scenarios in regression and classification, and applying regularization methods.  

### Mathematics and Statistics Involved
The project incorporates statistical concepts like data pre-processing, frequency distribution analysis, bivariate correlation, linear and multiple regression, hypothesis testing, loss function application, kernel transformation, and regularization techniques. These methods are crucial for understanding data relationships and making informed predictions.  
### Outcomes of Each Sub Task
Each sub-task provides insights into different aspects of the datasets, from data quality to complex variable relationships and the impact of various statistical techniques.  
### Challenges and Resolutions
**Challenges**: Grasping intricate data relationships, correctly applying statistical methods, and avoiding overfitting.  
**Resolution**: Methodical approach to data analysis, careful selection of statistical methods, and validation of assumptions.  

### Libraries needed:
#### pandas, numpy, matplotlib, seaborn, statsmodels, TensorFlow, scikit-learn   
import pandas as pd  
import numpy as np  
import matplotlib.pyplot as plt  
import seaborn as sns  
import statsmodels.api as sm  
import tensorflow as tf  
from sklearn.model_selection import train_test_split, GridSearchCV  
from sklearn.linear_model import LinearRegression, Ridge, Lasso, LogisticRegression  
from sklearn.metrics import mean_squared_error, mean_absolute_error, accuracy_score, classification_report, confusion_matrix, log_loss, hinge_loss  
from sklearn.preprocessing import StandardScaler, OneHotEncoder  
from sklearn.svm import SVC  
from sklearn.pipeline import Pipeline  
from sklearn.ensemble import RandomForestRegressor  
from sklearn.tree import DecisionTreeClassifier  
from sklearn.compose import ColumnTransformer  
from statsmodels.formula.api import ols  
from scipy.stats import shapiro, levene, ttest_ind  
from statsmodels.graphics.gofplots import qqplot  
from statsmodels.stats.multicomp import pairwise_tukeyhsd  
from statsmodels.multivariate.manova import MANOVA  
from sklearn import datasets  

### Video Link:  
https://www.dropbox.com/scl/fi/x9qhxly46vwz2h6l9kw2o/ChenxiCAO_Inclassassignment_video.mp4?rlkey=rfu3ixdf3qcinfgoplpmr6twk&dl=0  
import warnings  

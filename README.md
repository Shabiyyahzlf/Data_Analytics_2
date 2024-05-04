# Type of Data Analysis
## Descriptive
Descriptive analytics involves the statistical analysis of past data to uncover patterns and correlations. It aims to describe events, phenomena, or outcomes, providing insights into past occurrences and serving as a foundation for trend analysis in business.

In descriptive analytics, several things can be used in solving:
- Metrics (Count, Mean, Mode, Std deviation, Min, Max, Avg, Sum, unique values)
- Searching
- Filtering
- Interpreting Result
### Metrics
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/f6f779df-1da9-4b7a-8be5-5228b746f571" /></div>

Function describe()
- Count: The total number of elements in the column
- Mean: The mean average of the element in the column.
- Std: The standard deviation is the square root of the average of the squared deviations from the mean
- Min: The smallest value of the element in the column
- Max: The largest_value of the element in the column
- Quartiles: Values that divide a dataset into four equal parts, providing insights into the spread and distribution of the data.

## Diagnostic
Diagnostic analytics is a form of data analysis used to understand the reasons behind occurrences. It delves into trends and relationships among variables to pinpoint the underlying causes. This type of analysis follows descriptive analytics, which focuses on identifying what happened.

Several things can help with diagnostic analytics:
1. Data drilling
2. Data mining
3. Data Relationship

# Data Aggregation and Interpretation Metrics
Data aggregation involves combining and summarizing individual data points into a larger dataset, while interpretation metrics are measures used to make sense of aggregated data, providing insights and understanding.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/7803c4a4-a797-4ed6-8c86-5d49c6cd018a" /></div>

## Interpretation: Storytelling
In 1930, the prestigious football competition known as the "World Cup" was held for the first time, marking an event eagerly anticipated worldwide until 2014, the year covered by this dataset. Throughout this period, the World Cup has been a highly anticipated event, with numerous matches played in stadiums across the globe.

Over the years, from 1930 to 2014, the average number of goals scored by the home team was 1.82, with a standard deviation of 1.62, while the visiting team scored an average of 1.02 goals, with a standard deviation of 1.07. The highest number of goals scored by the home team in a single match was 10, compared to 7 goals by the visiting team.

On average, nearly 45,000 spectators attended each match, filling stadiums worldwide to enjoy the games and support their favorite teams. Analysis of halftime performance revealed that the home team had an advantage in scoring with an average of 0.71 goals per half, with a standard deviation of approximately 0.94 goals. The record for the most goals scored by the home team in the first half of a match was 6.

Conversely, the visiting team scored an average of 0.42 goals per half, with a standard deviation of approximately 0.67 goals. The highest-recorded number of goals by the visiting team in the first half was 5.

Overall, the football competition during this period experienced rapid growth, with matches starting in 1930 and reaching their peak in 2014. However, there was variation in the number of matches each year, with the earlier period (1930-1960) featuring around 10 matches per year, while in recent years, the number has surged to over 50 matches per year. This reflects the evolution and changes in the dynamics of football competition over the past few decades.

# Exploratory Data Analysis Method
## Import Python Libraries
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/8cfa23e0-a097-4e89-8b73-8de82afec760" /></div>

## Data Cleansing
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/7a90bb20-017a-45f2-a476-efc99ee34800" /></div>

## Exploratory Data Analysis (EDA) 
involves several methods to delve into datasets and uncover valuable insights:

### 1. Identifying Data Relationships 
EDA helps identify relationships between different variables in the dataset. This can be done through visualizations such as scatter plots, correlation matrices, and heatmaps, which reveal how variables are related to each other.
### 2. Describing Data Drilling Concepts 
Data drilling involves examining data at different levels of granularity. Granularity refers to the level of detail or specificity in the data. EDA explores data at various granularities to understand patterns and trends. For example, drilling down from yearly data to monthly or daily data provides a more detailed perspective.
### 3. Describing Data Mining Concepts:
#### Correlation Analysis 
EDA examines correlations between variables to identify patterns and relationships. Correlation matrices and scatter plots are commonly used to visualize correlations.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/9e608fb8-ebc7-4ab9-b4f1-bc71c898ae8d" /></div>
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/bdc2be91-6dff-4f8d-9d0e-4891b95bfde0" /></div>

### Anomalies
- Anomalies are data or values that deviate from the expected pattern in a dataset.
- They may include nonsensical values, such as negative ages or fractional quantities, which are unrealistic in real-world scenarios, such as negative age (-15 years), which are implausible in real-world contexts.
- Anomalies can be detected through exploratory data analysis (EDA) techniques, such as visualizations like box plots and histograms.
### Outliers
- Outliers are data points that significantly differ from the majority of the dataset. Such as an age of 80 years is not inherently unreasonable in the context of human age, but its value is significantly distant from the general average, making it an outlier.
- They represent notable deviations from the dataset's norm and may indicate interesting insights or data errors.
- Outliers are identified using EDA methods like box plots, scatter plots, and z-score analysis.
##### Anomaly is an outlier `HOWEVER` not all outliers are anomalies.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/05ff2cbf-a478-442f-b880-6878a1cc33f6" /></div>

#### Outliers
Outliers `don't always need to be discarded`; they can be reasonable but fall into the outlier category due to their limited quantity.
#### Anomalies
Anomalies `must be removed` as they deviate significantly from the expected pattern or are logically implausible.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/5041f8f7-4ef2-48ca-83bc-1f63a089ac1e" /></div>
Finding first quantile and third quantile
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/5ba88e0e-5657-4e63-83af-e2699cccc3fc" /></div>

Find the IQR which is the difference between third and first quartile
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/c69cc334-c0b6-4dc4-83a7-acbdbd9b57c4" /></div>

Find lower and upper bound
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/b141c254-08b7-4d24-81a2-9b13131db9eb" /></div>

### Handling Outlier
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/a57b3047-ee2b-4ba5-829d-02c10d92e5c3" /></div>
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/c50968f0-5c6b-43cb-afc8-6a8607227969" /></div>

# Hypothesis Testing
A statistical hypothesis test is a procedure in statistical analysis aimed at determining whether the available data provides enough evidence to support a specific hypothesis. This process usually entails computing a test statistic based on the data. Subsequently, a decision is made by comparing the test statistic to a critical value or by assessing a p-value derived from the test statistic.

## T-test
The t-test assesses the difference in means between two groups of data. It's a hypothesis test conducted using random samples from each group. Through this test, analysts determine if the same treatment yields consistent results in both groups or if there are differences.

Accepted hypotheses are:
- Ho: No difference between the groups.
- Ha: Difference exists despite the same treatment

## Z-test
The z-test compares means or proportions between two groups when the sample size is large (typically n > 30) and the population standard deviation is known. It's akin to the t-test but relies on the standard normal distribution (Z-distribution). Commonly used for hypothesis testing when the population standard deviation is known.

Accepted hypotheses are:
- Ho: There is no significant difference between the groups.
- Ha: A significant difference exists despite the same treatment.
### Import Python Libraries
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/aaff50d4-c569-4490-9200-13b623e99d12" /></div>
An experiment on the `effects of anti-anxiety medicine on memory recall when being primed with happy or sad memories`. The participants were done on novel Islanders whom mimic real-life humans in response to external factors.

Drugs of interest (known-as) [Dosage 1, 2, 3]:

A - Alprazolam (Xanax, Long-term) [1mg/3mg/5mg]

T - Triazolam (Halcion, Short-term) [0.25mg/0.5mg/0.75mg]

S- Sugar Tablet (Placebo) [1 tab/2tabs/3tabs]
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/90514f2e-276b-4eb3-a164-9c731c6b6641" /></div>

- `first_name` : First name of Islander
- `last_name` : Last. name of Islander
- `age` : Age of Islander
- `Happy_Saf_group` : Happy or. Sad Memory priming block
- `Dosage` : 1-3 to indicate the level of dosage (low - medium - over recommended daily intake)
- `Drug` : Type of Drug administered to Islander
- `Mem_Score_Before` : Seconds - how long it took to finish a memory test before drug exposure
- `Mem_Score_After` : Seconds - how long it took to finish a memory test after addiction achieved
- `Diff` : Seconds - difference between memory score before and after

<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/9b556a72-d9b7-4442-9812-439f44ae3e56" /></div>

### T-test
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/026bafb0-12af-423d-966a-38b1ac5708d1" /></div>

##### At a significance level of 5%, drug exposure has had a significant impact on the time required to complete the memory test.

# Evaluate and Explain Libraries
#### Import Python Libraries
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/13231ebb-8fb1-4379-8f10-9ba0b397d46f" /></div>

#### Load Dataset
We use the “Salary_Data” dataset to involves predicting about the salary or wages of workers or individuals based on experience.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/6233c106-d032-48ed-9847-89b962f93afb" /></div>

#### Check Data Condition
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/85317548-f780-40d9-aeca-2e09d184e239" /></div>

#### Check Missing Value
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/a67360e4-e82a-45fc-9ecf-4eefdf54c7cb" /></div>

#### Data Cleansing
Data is Clean
##  Explanatory Data Analysis
### Distribution of YearsExperience
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/01456e9f-ebc6-4c61-8b2c-c32ccc6df9ff" /></div>

### Distribution of Salary
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/49cd2b78-ecaf-4ee7-bb97-6f4b053f1f95" /></div>

## Preprocessing Modeling
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/040c881c-feb4-45fc-b366-022f32e302b9" /></div>

## Machine Learning Regression
Regression is a statistical method used to understand and quantify the relationship between one dependent variable and one or more independent variables. It aims to model the relationship between the variables and predict the value of the dependent variable based on the values of the independent variables.

### Simple Linear Regression (SLR)
Simple Linear Regression is a statistical method used to model the relationship between a single independent variable and a dependent variable by fitting a linear equation to the observed data.

#### Fitting Into Training
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/b59f0fbb-d1f1-46ee-8cab-c801211c76ce" /></div>

#### Predict The Result
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/1b75b94d-f29a-477d-b7a4-d1b671f52a13" /></div>

#### Plot The Result
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/58597993-d7ce-4240-867f-7182b6abb9fa" /></div>

<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/0d1e0704-cedf-4054-b843-d9dbb47df86c" /></div>

<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/76e2ee42-7d86-4e1d-8637-a97f4f401284" /></div>

## Evaluate Model
### Mean Squared Error (MSE)
A regression model evaluation metric that is used to calculate the error between the values predicted by the model and the actual values. MSE is the average of the squared differences between the predicted value and the actual value.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/c37be15d-53e2-4ac8-89af-7065a6245a04" /></div>

### Mean Absoulute Error (MAE)
A regression model evaluation metric that is used to calculate the error between the values predicted by the model and the actual values.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/45fa5f65-e408-4ef2-b585-f21bda6b9016" /></div>

### R-Squared (R2)
R-squared or R² is one of the regression model evaluation metrics used to calculate the level of success of the model in describing the variance of the target variable.
<div align="center"><img src="https://github.com/Shabiyyahzlf/Data_Analytics_2/assets/89763971/7ef2635e-de26-4c00-87df-519a517fc4d2" /></div>

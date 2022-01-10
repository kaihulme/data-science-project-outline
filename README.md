
# data-science-project-outline

Outline of data science project workflow. It can be applied to other Kaggle competitions or data science projects in general.

## Project outline

A data science project or Kaggle competition can generally fit into the following workflow.

1. Define the problem definition.
2. Get the data.
3. Analyse, identify patterns and explore the data.
4. Clean, sort and prepare the data.
5. Create a number of models to solve the problem to find a best approach.
6. Tune the model for best results.
7. Report on and visualise findings for a final solution.
8. Launch system or submit results.

## Problem definition

The first step to a data science project is figuring out what it is we wish to solve. We need to get an idea of what the problem is and define a question to answer. In the case of Kaggle competitions the question is already defined.

At this stage we may also want to develop an early understanding about the domain of the problem. It is a good idea to get an initial overview of the issue at hand to give a better idea of patterns to look for in the data.

### Workflow goals

The data science solutions workflow solves for seven major goals.

- **Classifying.** We may want to classify or categorize our samples. We may also want to understand the implications or correlation of different classes with our solution goal.

- **Correlating.** One can approach the problem based on available features within the training dataset. Which features within the dataset contribute significantly to our solution goal? Statistically speaking is there a correlation among a feature and solution goal? As the feature values change does the solution state change as well, and visa-versa? This can be tested both for numerical and categorical features in the given dataset. We may also want to determine correlation among features other than survival for subsequent goals and workflow stages. Correlating certain features may help in creating, completing, or correcting features.

- **Converting.** For modelling stage, one needs to prepare the data. Depending on the choice of model algorithm one may require all features to be converted to numerical equivalent values. So for instance converting text categorical values to numeric values.

- **Completing.** Data preparation may also require us to estimate any missing values within a feature. Model algorithms may work best when there are no missing values.

- **Correcting.** We may also analyse the given training dataset for errors or possibly inaccurate values within features and try to correct these values or exclude the samples containing the errors. One way to do this is to detect any outliers among our samples or features. We may also completely discard a feature if it is not contributing to the analysis or may significantly skew the results.

- **Creating.** Can we create new features based on an existing feature or a set of features, such that the new feature follows the correlation, conversion, completeness goals.

- **Charting.** How to select the right visualization plots and charts depending on nature of the data and the solution goals.

## Get the data

1. Create workspace with somewhere to store data.
2. Create Python environment with Jupyter notebook.
3. Download the data into the workspace.
4. Put data into a DataFrame and take an initial look at size and type of data.
5. Create a train and test set.

We should start by creating a place to work from, with a data directory, Python environment with the necessary dependencies along with a Jupyter notebook to work from. We will either want to place the data in the directory or download it from within the notebook itself.

We will want to get the data and put it into an easy to use form such as a Pandas DataFrame. From here we will want to have a look at the size and type of the data.

We will then want to split the data into a train and test set if not already done so.

## Data exploration

- Which features are in the dataset?
	- which are categorical
		- which are nominal, ordinal, ratio, interval based?
	- which are numerical
		- which are discrete, continuous, time series based?
- What are the data types of each feature?
- Which features have mixed data types (int and string etc.)?
- Which features may contains errors and typos?
- Which features contain outliers?
- Which features contain missing data?
- What is the distribution across the numerical features?
- What is the distribution across the categorical features?

List assumptions made from analysis:
- **Target**. List the target feature and how we wish to correlate features to it.
- **Fixes**. List features missing data, containing outliers, and possible errors.
- **Selection**. List features which may not have much relation to the target feature and could be dropped, i.e. names and ids.
- **Creation**. List features that could be created which have promising correlation with the target feature, i.e. extracting other features from features, creating bands for numerical features, combining features, fixing mixed data types, and categorising outliers.
- **Assumptions**. List initial assumptions about certain features which have the most importance to the task.

## Data preparation



## Modelling



## Tuning



## Report



## Launch and submit

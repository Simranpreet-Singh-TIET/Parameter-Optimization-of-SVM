# Parameter-Optimization-of-SVM
## Sampling Assignment

**Dataset Used:** [Adult Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/adult/)

| Number of Instances:  | 48842 |
|-----------------------|--------|
| Number of Attributes: | 14    |

Predict whether income exceeds $50K/yr based on census data. Also known as "Census Income" dataset

## Dataset Characteristics
Multivariate

## Subject Area
Social

## Associated Tasks
Classification

## Attribute Type
Categorical,Integer


## Attribute Information:

**Input variables (based on physicochemical tests):**<br />
   1 - Age <br />
   2 - Workclass <br />
   3 - fnlgwt <br />
   4 - education <br />
   5 - educationnum<br />
   6 - maritalstatus<br />
   7 - occupation<br />
   8 - relationship<br />
   9 - race<br />
   10 - sex<br />
   11 - capitalgain<br />
   12 - capitalloss<br />
   13 - hoursperweek<br />
   14 - nativecountry<br />
**Output variable (based on sensory data):**<br /> 
   15 - class (score between 0 and 1)

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Results

The best parameters of SVC for the given dataset are:
- Kernel : rbf
- C : 6.596029  
- Gamma : 0.059894  

The above parameter gave a maximum accuracy of 0.8562 .

### Convergence graph  : 


![Screenshot 2023-04-20 044123](https://user-images.githubusercontent.com/75215253/233219122-3eb31a55-38db-4219-b442-b09e405caf27.png)

## Submission by :
**Name** : Simranpreet Singh
<br>
**Roll No** : 102003485


# Data Science Primer : 

### Chapter 1: Bird's Eye View : 

* **Machine learning is not about algorithms.** 
...and individual algorithms are only one piece of the puzzle. The rest of the puzzle is how you apply them the right way.

#### `What makes machine learning so special? 

M achine learning is the practice of teaching computers how to learn patterns from data, often for making decisions or predictions.

For true machine learning, the computer must be able to learn patterns that it's not explicitly programmed to identify.

#### Key Terminology 

Model - a set of patterns learned from data.

Algorithm - a specific ML process used to train a model.

Training data - the dataset from which the algorithm learns the model.

Test data - a new dataset for reliably evaluating model performance.

Test data - a new dataset for reliably evaluating model performance.

Target variable - A specific variable you're trying to predict.

Observations - Data points (rows) in the dataset.

#### Machine Learning Tasks

Academic machine learning starts with and focuses on individual algorithms. However, in applied machine learning, you should first pick the right machine learning task for the job.

* A task is a specific objective for your algorithms.

* Algorithms can be swapped in and out, as long as you pick the right task.

In fact, you should always try multiple algorithms because you most likely won't know which one will perform best for your dataset.

#### The 3 Elements of Great Machine Learning

1. A skilled chef (human guidance)
First, even though we are "teaching computers to learn on their own," human guidance plays a huge role.

2. Fresh ingredients (clean, relevant data)
The second essential element is the quality of your data.

3.  Don't overcook it (avoid overfitting)
One of the most dangerous pitfalls in machine learning is overfitting. An overfit model has "memorized" the noise in the training set, instead of learning the true underlying patterns.

#### Supervised Learning: includes tasks for "labeled" data (i.e. you have a target variable).

  * In practice, it's often used as an advanced form of predictive modeling.
  * Each observation must be labeled with a "correct answer."
  * Only then can you build a predictive model because you must tell the algorithm what's "correct" while training it (hence, "supervising" it).
  * Regression is the task for modeling continuous target variables.
  * Classification is the task for modeling categorical (a.k.a. "class") target variables.
  
#### Unsupervised learning: includes tasks for "unlabeled" data (i.e. you do not have a target variable).

  * In practice, it's often used either as a form of automated data analysis or automated signal extraction.
  * Unlabeled data has no predetermined "correct answer."
  * You'll allow the algorithm to directly learn patterns from the data (without "supervision").
  * Clustering is the most common unsupervised learning task, and it's for finding groups within your data.
  
  
  
## 2. Exploratory Analysis:
  
First, you'll want to answer a set of basic questions about the dataset:

  * How many observations do I have?
  * How many features?
  * What are the data types of my features? Are they numeric? Categorical?
  * Do I have a target variable?
  
 Also, , the following can be done:
 1. Plot Numerical Distributions.
 2. Plot Categorical Distributions.
 3. Plot Segmentations.
 4. Study Correlations.
 
### Data Cleaning


Data cleaning is one those things that everyone does but no one really talks about. Sure, it’s not the "sexiest" part of machine learning. And no, there aren’t hidden tricks and secrets to uncover.

However, proper data cleaning can make or break your project. Professional data scientists usually spend a very large portion of their time on this step.

Better data beats fancier algorithms.

In other words... garbage in gets you garbage out. Even if you forget everything else from this course, please remember this point.

In fact, if you have a properly cleaned dataset, even simple algorithms can learn impressive insights from the data!

## 5. Algorithm Selection:

##### Why Linear Regression is Flawed?
Simple linear regression models fit a "straight line" (technically a hyperplane depending on the number of features, but it's the same idea). 
In practice, they rarely perform well. We actually recommend skipping them for most machine learning problems.

Their main advantage is that they are easy to interpret and understand. However, our goal is not to study the data and write a research report. 
Our goal is to build a model that can make accurate predictions.

In this regard, simple linear regression suffers from two major flaws:

  1. It's prone to overfit with many input features.
  2. It cannot easily express non-linear relationships.
  


 ## 6. Model Training:
 This is done by the following:
   1. Exploring the data.
   2. Cleaning the data.
   3. Engineering new features.
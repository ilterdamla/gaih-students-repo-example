# GAIH Student Repo Example
![](img/newlogo.png)

**Course Date:** 23.03.2021  
**Name:** Damla  
**Surname:** İlter  
**Email:** damla.ilter@msgsu.edu.tr  

**Note:** Your homeworks can be formats like ".ipynb" and ".py". **Not ".txt" files!!** Make sure that your codes works.  

## Project Name
Homework 1


1) How would you define Machine Learning?
  
  In recent times, machine learning (ML) and data science have gained popularity like never
before. This field is expected to grow exponentially in the coming years. First of all, what is
machine learning? And why does someone need to take pains to understand the principles?
One simple example could be good recommendations in e-commerce websites when someone went to search for a particular book or any other
product recommendations which were bought together to provide an idea to users which
they might like. Sounds magic, right? In fact, utilizing machine learning, can achieve much
more than this. Machine learning is a branch of study in which a model can learn automatically from the
experiences based on data without exclusively being modeled like in statistical models.
Over a period and with more data, model predictions will become better.
Machine learning is the branch of computer science that utilizes past experience to learn
from and use its knowledge to make future decisions. Machine learning is at the
intersection of computer science, engineering, and statistics. The goal of machine learning is
to generalize a detectable pattern or to create an unknown rule from given examples. 


2) What are the differences between Supervised and Unsupervised Learning? Specify example 3 algorithms for each of these.

    Machine learning is broadly classified into three categories but nonetheless, based on the
situation, these categories can be combined to achieve the desired results for particular
applications:
    -Supervised learning: This is teaching machines to learn the relationship between
other variables and a target variable, similar to the way in which a teacher
provides feedback to students on their performance. The major segments within
supervised learning are as follows:
     *Classification problem
     *Regression problem
     *Crossvalidation
     (Logistic regression, Support vector machine, Lasso, Decision tree)
   -Unsupervised learning: In unsupervised learning, algorithms learn by
themselves without any supervision or without any target variable provided. It is
a question of finding hidden patterns and relations in the given data. The
categories in unsupervised learning are as follows:
      *Dimensionality reduction
      *Clustering
      (Artificial neural network, Factor analysis, Bayesian models)
    - Reinforcement learning: This allows the machine or agent to learn its behavior
based on feedback from the environment. In reinforcement learning, the agent
takes a series of decisive actions without supervision and, in the end, a reward
will be given, either +1 or -1. Based on the final payoff/reward, the agent
reevaluates its paths. Reinforcement learning problems are closer to the artificial
intelligence methodology rather than frequently used machine learning
algorithms.

3) What are the test and validation set, and why would you want to use them?

    Generally, the term “validation set” is used interchangeably with the term “test set” and refers to a sample of the dataset held back from training the model. The evaluation of a model skill on the training dataset would result in a biased score. Therefore the model is evaluated on the held-out sample to give an unbiased estimate of model skill. This is typically called a train-test split approach to algorithm evaluation. the “validation dataset” is predominately used to describe the evaluation of models when tuning hyperparameters and data preparation, and the “test dataset” is predominately used to describe the evaluation of a final tuned model when comparing it to other final models.
That the notions of “validation dataset” and “test dataset” may disappear when adopting alternate resampling methods like k-fold cross validation, especially when the resampling methods are nested.

4) What are the main preprocessing steps? Explain them in detail. Why we need to prepare our data?

 Data preprocessing is an important step in the data mining process. The phrase "garbage in, garbage out" is particularly applicable to data mining and machine learning projects. Data-gathering methods are often loosely controlled, resulting in out-of-range values (e.g., Income: −100), impossible data combinations (e.g., Sex: Male, Pregnant: Yes), and missing values, etc. Analyzing data that has not been carefully screened for such problems can produce misleading results. Thus, the representation and quality of data is first and foremost before running any analysis. Often, data preprocessing is the most important phase of a machine learning project, especially in computational biology.
If there is much irrelevant and redundant information present or noisy and unreliable data, then knowledge discovery during the training phase is more difficult. Data preparation and filtering steps can take considerable amount of processing time. Data preprocessing includes cleaning, Instance selection, normalization, transformation, feature extraction and selection, etc. The product of data preprocessing is the final training set.
Data preprocessing may affect the way in which outcomes of the final data processing can be interpreted.

5) How you can explore countionus and discrete variables?

   Discrete can only assume certain values and there are usually "gaps" between values. Eg. Number of bedrooms in a house, number of hammers sold (1,2,3,... etc).
   Continuous can assume any value within a specified range. Eg. Pressure in a tire, weight of pork chop, height of students in a class.
   
   
 6) Analyse the plot given below. (What is the plot and variable type, check the distribution and make comment about how you can preproccess it.)
      This can be a histogram with normalized frequencies and an overlay line plot of values to estimated probabilities. The  example of kernel density estimation for a bimodal data sample is given below. The example creates the data distribution, fits the kernel density estimation (KDE) model, then plots the histogram of the data sample and the Probability denstiy function (PDF) from the KDE model. Note that your results will differ given the random nature of the data sample. We can see that the PDF is a good fit for the histogram. It is not very smooth and could be made more so by setting the “bandwidth”. The KernelDensity class is powerful and does support estimating the PDF for multidimensional data.
   
---

### Certification
![](img/TopLearnerCertificate.png)


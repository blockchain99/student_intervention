# student_intervention
A local school district has a goal to reach a 95% graduation rate by the end of the decade by identifying students
who need intervention before they drop out of school. As a software engineer contacted by the school district, 
your task is to model the factors that predict how likely a student is to pass their high school final exam, 
by constructing an intervention system that leverages supervised learning techniques. 
The board of supervisors has asked that you find the most effective model that uses the least amount of computation costs
to save on the budget. You will need to analyze the dataset on students' performance and develop a model 
that will predict the likelihood that a given student will pass, quantifying whether an intervention is necessary.

#### What I implemented 
In this project, I implemented the supervised Learning models to predict the likelihood that a given student will pass,
quantifying whether an intervention is necessary by training a model with student data.  
Also, I simulatted various models with decision Trees, SVMs, Neural Networks, grid search (GridSearchCV) to find 
the optimal solution to the customer in terms of performance and cost saving.

#### My recommendation is GaussianNB for this project, 
which calculate a Gaussian conditional probability based on the data and no need for parameter tuning. 
But for reference, I present option "B", Service Vector Machine(SVM) tunining up result as follows.
Service Vector Machine, Tuned model has a F1 score of 0.825806451613 with Best params: {'C': 1, 'gamma': 0.1} 
, which is far better than 0.8052, testing F1 score of untuned SVM.

### Data
Data for this project is privided as student-data.csv, which is in https://github.com/blockchain99/student_intervention directory
This data is read by 
student_data = pd.read_csv("student-data.csv")

### Installation and usage
Program is written in python 2.7, it one may need anaconda shoulde be installed(including numpy, scipy, pandas, matplotlib, jupyter) ( https://docs.continuum.io/anaconda/install ) or install python 2.7 and then install Numpy, Scipy, Pandas, matplotlib,jupyter manually as follows.

sudo pip install numpy scipy matplotlib
after anaconda installed , one may need to jupyter run, by type in command line and hit the enter. > jupyter notebook and then upload and select student_intervention-YOONSUPARK.ipynb in web page.

### Meta

Yoonsu Park - http://www.patternics.com Distributed under the MIT license. See LICENSE for more information( https://en.wikipedia.org/wiki/MIT_License ). https://github.com/blockchain99/student_intervention

# student_intervention
### Project Introduction 
A local school district has a goal to reach a 95% graduation rate by the end of the decade by identifying students
who need intervention before they drop out of school. As a software engineer contacted by the school district, 
your task is to model the factors that predict how likely a student is to pass their high school final exam, 
by constructing an intervention system that leverages supervised learning techniques. 
The board of supervisors has asked that you find the most effective model that uses the least amount of computation costs
to save on the budget. You will need to analyze the dataset on students' performance and develop a model 
that will predict the likelihood that a given student will pass, quantifying whether an intervention is necessary.

### What I implemented 
#####In this project, I implemented the supervised Learning models to predict the likelihood that a given student will pass,
quantifying whether an intervention is necessary by training a model with student data.  

#####Also, I simulatted various models with decision Trees, SVMs, Neural Networks, grid search (GridSearchCV) to find 
the optimal solution to the customer in terms of performance and cost saving.

#### My recommendation is GaussianNB for this project, 
which calculate a Gaussian conditional probability based on the data and no need for parameter tuning. 

#####
But for reference, I present option "B", Service Vector Machine(SVM) tunining up result as follows.
Service Vector Machine, Tuned model has a F1 score of 0.825806451613 with Best params: {'C': 1, 'gamma': 0.1} 
, which is far better than 0.8052, testing F1 score of untuned SVM.


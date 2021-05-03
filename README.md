## About Me ##
Hi there! I am Maynard Miranda an aspiring Data Scientist and a Master of Science Student at Georgia Institute of Technology. 

I am currently working on a non-profit organization here in Washington D.C. My current role is leading business and IT-related projects such as system migration, internal audit, and process improvement. 

My undergraduate degree is Bachelor of Science in Industrial Engineering which I took from Adamson University. Then, I took a Master of Science in Engineering Management at George Washington University. I also have several professional certifications such as Management Essentials from Harvard Business School, Lean Six Sigma Black Belt from Dartmouth College, Lean Six Sigma Green Belt from the University of Michigan, Certified Systems Engineering Professional from Internation Council of Systems Engineering, and Certified Associate in Project Management from Project Management Institute.

Lastly,  I am currently studying MS Analytics at Georgia Institute of Technology and planning to launch my data science career soon. I am excited to see how my strong leadership and management skills plus the newly developed data science skills will help my organization achieve its goals.

Here is my LinkedIn Profile [Maynard Miranda](https://www.linkedin.com/in/maynard-emmanuel-miranda-ab5428169/) feel free to contact me anytime.

## Projects ##

### [Breast Cancer Prediction: Classification Models](https://github.com/mebmiranda/Breast-Cancer-Prediction/blob/main/Breast%20Cancer%20Prediction%20(Logistic%20Regression%2C%20K-Nearest%20Neighbors%2C%20Support%20Vector%20Machine).ipynb) ###
* Performed down-scaling to match the counts of the Benign and Malignant Tumor responses. Initially, Benign has 212 counts and Malignant has 357 counts. 145 random Malignant rows were dropped. 
* Splitted the dataset into a training set and test set
* Scaled the predictor variables to eliminate variance on the means and standard deviations.
* Generated Logistic Regression Model using the training dataset
* Used the Logistic Regression Model to predict the test set and analyzed the model's efficiency.
* Generated K-Nearest Neighbors Model using the training dataset
* Used the K-Nearest Neighbors to predict the test set and analyzed the model's efficiency
* Generated Support Vector Machine Model using the training dataset
* Used the Support Vector Machine to predict the test set and analyzed the model's efficiency
* Determined which model among the 3 models is best fit for the problem.

### [Bank Loan Proportion: Markov Chain Analysis](https://github.com/mebmiranda/Bank-Loan-Portfolio/blob/main/Bank%20Loan%20Portfolio%20Markov%20Analysis.ipynb) ###
* Generated 1,000 random past loan transactions. For example, from "Good Loan" to "Bad Loan."
* Computed the conditional probability for each of the loan types. For example, the probability of "Good Loan" given "Bad Loan."
* Generated 200 random current loans and computed the current year's loan proportion.
* Created Markov Transition Matrix
* Wrote a function that performs Markov Chain Analysis
* Used the Markov Chain function to determine the year 2 loan proportion, year 3 loan proportion, and the in-the-long run proportion of the bank's loan portfolio.

### [Advertising Sales Forecasting: Linear Regression and Assumptions](https://github.com/mebmiranda/Linear-Regression-and-Assumptions/blob/main/Advertising%20Dataset%20(Linear%20Regression%20and%20Assumptions).ipynb) ###
* Determined if there is a Multicollinearity on the predictor variables. Based on the analysis, there is no Multicollinearity on the predictor variables. 
* Determined if there is a linear relationship between the predictor variables and response variable. Radio and Newspaper do not have a linear relationship with Sales, hence, the two predictor variables were not included in the model.
* Generated the Linear Regression Model. The model has a 0.932 Coefficient of Determination which means that 93.2% of the data fit the regression model.
* Analyzed if Residuals has Autocorrelation using the Durbin Watson Test. The test result suggests that there is a positive low autocorrelation on the residual which is acceptable.
* Determine if the Residuals have Homoscedasticity or Heteroscedasticity relationship. The Residual Plot shows that there is a Homoscedasticity relationship on the residuals.
* Determine if the Residuals are Normally Distributed. The Quartile-Quartile Plot shows that the Residuals are Normally Distributed.

### [Traveling Salesman Problem: Simulated Annealing](https://github.com/mebmiranda/Traveling-Salesman-Problem/blob/main/Traveling%20Salesperson%20Problem%20-%20Simulated%20Annealing%20.ipynb) ###
* Used Euclidean Distance formula to compute the distance from one location to another.
* Computed the initial path's total distance which is the distance from Location 0 to Location 1, and so on until the last Location, and the distance going back from the Last Location to Location 0.
* Generated 2 random numbers to determine which cities will be swap on the next iteration. 
* Computed the new path's total distance. If this new path is shorter, accept it. Otherwise, accept it with probability p
* The formula for p is p = exp((old distance - new distance)/k) where k is the temperature of the system
* Generate random probability and if p is better than the generated random probability, accept the new path.


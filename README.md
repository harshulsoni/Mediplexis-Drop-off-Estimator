#Mediplexis – Drop-off Estimator

A pharma company Mediplexis, based in the United States, has several products in the various therapy areas. For one of their popular drug addressing 4 conditions. The company has observed that lot of patients are dropping-off the therapy, the company wants to determine feasibility if people who are ging to drop can be detected at early-stage.

Mediplexis wants to run a POC with ZS to:

Create a prediction algorithms to determine the feasibility if people who are going to drop can be detected at early-stage 
based on set of metrics related to early indicators for patients which they have anonymized and provided to ZS for analysis.
The company classify a patient into 3 categories:

Persistent (P)
Dose Stretcher (DS)
Drop-off (DO)
Datasets

The participants would be provided with the following datasets:

train.csv
test.csv
profile.csv
submission_format.csv
A valid submission has the following format:

PID	PID_State
5001	DO
5002	DS
5003	P
5004	DO
5005	DO
5006	DS
5007	P
5008	DS
5009	DO
Evaluation Metric:

Let Tp be the true positives, Fp be the false positives, Tn be the true negatives and Fn be the false negatives. Now we define precision and recall:


Misclassification Error Rate is the selected evaluation metric for the challenge:


Pi : Predicted class for each patient

Ai : Actual class for each patient (not provided to you for test dataset)

n : Total number of patients in the test dataset

During the competition, only a subset of the test data set will be used for evaluating submissions. The subset chosen will be the same for each participant. However, the final standings will be evaluated against the remaining subset of the test data.


The main libraries involved in this tutorial are:
Pandas for data manipulation
Matplotlib and seaborn for data visualization
Numpy for multidimensional array computing
sklearn for machine learning and predictive modeling


Installation procedure

A very easy way to install these packages is to download and install the Conda distribution that encapsulates them all. This distribution is available on all platforms (Windows, Linux and Mac OSX).

Open terminal
type 'jupyter notebook'
select 718IT13.ipynb
execute all.

output: 718IT13.csv
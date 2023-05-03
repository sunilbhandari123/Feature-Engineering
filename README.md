# Feature-Engineering

# Different type of missing Missing Data


# 1. Missing Completely at random (MCAR)


There is no absolute relationship between the data missing and any other values observed or missing within the datasets.


# 2. Missing Data not at random (MNAR)

There is absolute some relationship between the data missing and any other values,observed or missing within the datasets.


# 3. Missing At Random



# Technique of handeling missing values


1. Mean/Median Mode Replacement.
2. Random Sample Imputation
3. Capturing Nan values with a new features
4. End of distrubtion imputation
5. Abitaracy imputation
6. Frequency Categories Imputation


# 1. Mean/Median/Mode Replacement 

used at MCAR 
Replacable NAN with most frequent occurance of the variable
After replacement check the standard deviation if the difference is small then it is fine otherwise it is the matter of worries.

Advantages:
1.Easy to implement
2.Faster

Disadvantages:
1.Distorance of orginal variable


#2. Random Sample Imputation

Take the random observation from the datasets and we use this observation to replace the nan values.

When sholud we use:
At  MCAR

Advantages:
-Easy to implement
-There is no distorance in variance

Disadvantage:
-In every sitution randomness wont work.


# 3. Capturing nan values with  a new feature

It work well if the data are not missing completely random
ie MNAR


Advantage:
-Easy to implement.
-capturing the importance of missing values.

Disadvantage.
-Increase cure of dimensinionality.


#4. End of distribution imputation.

used in not missing completely at random 
we have to look at the end of the right hand side of normal distribution and we can replace the nan values with that values
It will handle the outlier with an ease.


#5. Aritrary imputation 

It consist of replacing the nan values by an arbitary value
This method was found out in kaggle competation

AD:
-captures the importance of missing values if there is one

DisAd:
-Distort the original distribution of the variable.
-hard to decide which values to use



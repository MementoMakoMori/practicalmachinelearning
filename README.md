## Practical Machine Learning
### JHU/Coursera Data Science Certificate
### R. Holley, April-May 2020

## INTRO
This project was completed for Johns Hopkins University and Coursera's Data Science Certificate course 'Practical Machine Learning.' The goal of this project is to create a machine learning model that correctly identifies if the wearer of accelerometers is correctly performing a weight lifting exercise. The sensors were on the waist, right bicep, and right wrist of each of the six subjects, as well on the dumbbell used. Each subject was a male between the ages of 20-28 years, without prior weight lifting training. During the data collection, the subject were supervised by an experienced weight lifter to ensure they performed both correct and incorrect methods for the data set.
My script first cleans the data of extraneous variables, subsets some rows as a cross-validation set, then builds a Random Forest model to use for prediction. Parallelization while model-building was key for an efficient and useful program. 

## DATA
The original full dataset is **not** included in this repository. It is necessary to the run the PredictionAssignment.Rmd file, and can be dowloaded from the [UCI Machine Learning Repository.](http://archive.ics.uci.edu/ml/datasets/Weight+Lifting+Exercises+monitored+with+Inertial+Measurement+Units) The R script reads the data from the Downloads folder, but those lines could be easily changed to different file paths as needed. For the purpose of this course, Prof. Jeff Leek separated the data into training data and a test set, which makes it slightly different than the full dataset original from UCI.


## INFO
R version 3.6.3 (2020-02-29) -- "Holding the Windsock"
Copyright (C) 2020 The R Foundation for Statistical Computing
Platform: x86_64-pc-linux-gnu (64-bit)

Added to Github under the GNU General Public License, v3.0.

### R Libraries
* caret 6.0-86
* ggplot2 3.3.2
* parallel 3.6.3
* doParallel 1.0.15
* gbm 2.1.8

## FILES
* README.md
* PredictionAssignment.Rmd
* index.html
* LICENSE

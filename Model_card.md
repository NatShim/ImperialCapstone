# Model Card: Course recommendation system

The model analysed in this card recommends the courses to students registered with the online course provider. The model goal is comparing several approaches. Currently the models only work with students who takes at least one course and were added to database. The model can be transfer to an app and the code can be used to retrain the model and provide recommendations for new entries. 

## Model Description

**Input:** student id (integer), student profile (scores for each key word/genre), list of the available courses (titles, description, kew words/genres)

**Output:** List of 10 recommended courses for each student from the test list

**Model Architecture:** 
1.	Profile based method – similarity of user profile and course profile (recommendation cors are dot product of user profile vector and course genre vector)
3.	Clustering based – K-mean clustering approach with PCA


## Performance

The recommendation system at this stage of the development doesn’t have any performance measurement. But at further stages, when it goes live, the percentage of the ‘successful” recommendation (the courses were viewed/enrolled/completed) can be considered as a performance metrics.

## Limitations

Currently there is no "cold" recommendation implementation. Also limited suer rating is used (course completed vs course viewed)

## Trade-offs

None

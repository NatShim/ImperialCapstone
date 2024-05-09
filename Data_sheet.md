# Datasheet Card

•	First dataset – courses description with keywords/genres:
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-ML321EN-SkillsNetwork/labs/datasets/course_genre.csv
•	Second dataset – course rating:
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-ML321EN-SkillsNetwork/labs/datasets/ratings.csv
•	Third dataset – courses description:
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-ML321EN-SkillsNetwork/labs/datasets/course_processed.csv

## Motivation
Answer the following questions:
●	For what purpose was the dataset created? Was there a specific task in mind? Was there a specific gap that needed to be filled? Please provide a description.
o	Answer: to test different approaches for building an effective recommendation system. 
●	Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?
o	Answer: IBM – Skills Network

## Composition
Answer the following questions:
●	What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? Please provide details.
o	Answer: 1 – course id (object), course title (object), fourteen key words (binary); 2 – user id (integer) , course id (object), rating (float, 2.0 – viewed, 3.0 – completed); 3 – course if (object), course title (object), course description (object) 
●	Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set? If the dataset is a sample, then what is the larger set? Is the sample representative of the larger set (e.g., geographic coverage)? If so, please describe how this representativeness was validated/verified. If it is not representative of the larger set, please describe why not (e.g., to cover a more diverse range of instances, because instances were withheld or unavailable).
o	Answer: full dataset 
●	What does each instance consist of? Raw data? Unprocessed? Text, images?
o	Answer: processed data – objects and numbers
●	Are there any labels to the data?
o	Answer: no
●	Is there any missing information from individual instances?
o	Answer: No
●	Are relationships between individual instances made explicit?
o	Answer: Yes
●	Are there recommended data splits (e.g. train / test)? Provide a description of the splits, and the rationale behind them.
o	Answer: no
●	Is the dataset self-contained, or does it link to or otherwise rely on external resources (e.g., websites, tweets, other datasets)? 
o	Answer: Self-contained
●	Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)? If so, please provide a description.
o	Answer: No
●	Does the dataset contain data that, if viewed directly, might be offensive, insulting, threatening, or might otherwise cause anxiety? If so, please describe why.
o	Answer: No
●	Does the dataset identify any subpopulations (e.g., by age, gender)?
o	Answer: Unknown to the authors of the datasheet
●	Is it possible to identify individuals (i.e., one or more natural persons), either directly or indirectly (i.e., in combination with other data) from the dataset? If so, please describe how.
o	Answer: It is possible to analyse all courses the subject rated and link it to the subject, if you know which courses this subject attempted.
●	Does the dataset contain data that might be considered sensitive in any way (e.g., data that reveals race or ethnic origins, sexual orientations, religious beliefs, political opinions or union memberships, or locations; financial or health data; biometric or genetic data; forms of government identification, such as social security numbers; criminal history)? If so, please provide a description. 
o	Answer: No
●	Any other comments?
o	Answer: None

## Collection process
•	The data was collected from learning platform with the task of building and test simple recommendation models. 
•	The data for fifth dataset were sampling randomly. 
•	Over what time frame was the data collected? Unknown
o	Answer: Unknown to the authors of the datasheet
●	Were there any ethical review processes conducted (e.g. by an institutional reviewing board?)
o	Answer: Unknown to the authors of the datasheet
●	Were the individuals notified of the collection of the data?
o	Answer: Unknown to the authors of the datasheet
●	Did the individuals consent to their data being collected?
o	Answer: Unknown to the authors of the datasheet
●	If consent was obtained, were the consenting individuals provided with a mechanism to revoke their consent in the future or for certain uses? 
o	Answer: Unknown to the authors of the datasheet
●	Has an analysis of the potential impact of the dataset and its use on data subjects (e.g., a data protection impact analysis) been conducted? 
o	Answer: Unknown to the authors of the datasheet
●	Any other comments?
o	Answer: None

## Preprocessing/cleaning/labelling
Answer the following questions:
●	Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
o	Answer: Unknown to the authors of the datasheet
●	Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 
o	Answer: Unknown to the authors of the datasheet
●	Any other comments?
o	Answer: None

## Uses
Answer the following questions:
●	What other tasks could the dataset be used for? 
o	Answer: To accumulate statistic about the most popular courses
●	Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
o	Answer: Unknown to the authors of the datasheet
●	Are there tasks for which the dataset should not be used? If so, please provide a description.
o	Answer: None
●	Any other comments?
o	Answer: None

## Distribution
Answer the following questions:
●	Will the dataset be distributed to third parties outside of the entity (e.g., company, institution, organization) on behalf of which the dataset was created? If so, please provide a description.
o	Answer: Unknown to the authors of the datasheet
●	How will the dataset be distributed?
o	Answer: Unknown to the authors of the datasheet
●	When will the dataset be distributed?
o	Answer: Unknown to the authors of the datasheet
●	Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)? If so, please describe this license and/or ToU, and provide a link or other access point to, or otherwise reproduce, any relevant licensing terms or ToU, as well as any fees associated with these restrictions. 
o	Answer: Unknown to the authors of the datasheet
●	Any other comments?
o	Answer: None

## Maintenance
Answer the following questions:
●	Who will be maintaining the dataset?
o	Answer: IBM
●	Any other comments?
o	Answer: None




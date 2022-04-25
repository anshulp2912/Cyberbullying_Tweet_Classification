# CYBER BULLYING GUI NOTEBOOK
---
## NCSU CSC 591: Algorithms for Data Guided Buisness Intelligence
#### Contributors: Anmolika Goyal(agoyal4), Anshul Navinbhai Patel(apatel28), Shubhangi Jain(sjain29)
---
### Introduction
As social media usage grows across all age groups, the great majority of individuals rely on this crucial medium for day-to-day communication. Because of the pervasiveness of social media, cyberbullying may affect anybody at any time or from any location, and the internet's relative anonymity makes such personal attacks more difficult to stop than conventional bullying.


In light of this, this dataset comprises over 47000 tweets labeled with the following cyberbullying categories: Age, Ethnicity, Gender, Religion, Other sort of cyberbullying, Not cyberbullying.

Trigger Warning: These tweets either describe a bullying occurrence or are the crime itself; consequently, read them only if you are comfortable.

### Contents
- src [Source Codes]
  - Cyberbullying_model.ipynb [ Python Notebook for Modelling ]
  - Cyberbullying_EDA.ipynb [ Python Notebook for Exploratory Data Analysis ]
  - Cyberbullying_GUI.ipynb [ Python Notebook for GUI ]
- data [cyberbullying_tweets.csv]
- models [.zip](https://drive.google.com/file/d/1BXoB4Dyz_d2NMJrc_9HkJXn3I6JA0g06/view?usp=sharing)

### Implementation
  - We did initial data exploration to understand the attributes of the dataset. The dataset was plotted on a pie chart which showed a balanced data consisting of 6 different cyber bullying types based on gender, age, religion etc. Word cloud for different cyber bullying types illustrated common words that are generally observed in such tweets. 
  - The data was cleaned and processed to visualize top 10 words and their frequency for each bullying type.
  - Additionally, a dynamic table was created on the cleaned data to view common usernames, hashtags and the frequency of their tweets sorted by the count in descending order.


### Steps to Run
To visualise and get understanding of Dataset:
  - Open [Notebook](https://github.com/anshulp2912/Cyberbullying_Tweet_Classification/blob/main/src/cyberbullying_EDA.ipynb)
  - Run the cell to get results

To generate models on Dataset:
  - Open [Notebook](https://github.com/anshulp2912/Cyberbullying_Tweet_Classification/blob/main/src/Cyberbullying_model.ipynb)
  - Follow the steps to generate models as described in the notebook

To predict classes on trained models:
  - Open [Notebook](https://github.com/anshulp2912/Cyberbullying_Tweet_Classification/blob/main/src/cyberbullying_GUI.ipynb)
  - Follow the steps to load models as described in the notebook
  - Run the last cell: Gradio will generate a link.
  - Open the link, enter your text, choose your model and hit SUBMIT!!

### Results

### References
- https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification
- https://www.kaggle.com/code/abhishek/approaching-almost-any-nlp-problem-on-kaggle

# Offensive Tweets Classification - OffensEval 2019 - Codalab Challenge
This Challenge was completed in the context of the NLP module from Imperial College taught by Lucia Specia. 

## Creators of the Project :
[Adrian Löwenstein](https://www.linkedin.com/in/adrian-löwenstein/) - [Mihai Lung](https://www.linkedin.com/in/mihailung/) - [Pierre-Louis Saint](https://github.com/p-saint) 

## Proposed Implementation : 
The Implementation proposed during this project relies on the GloVe word embedding, strong data processing and different networks such as GRU, LTSM or CNN. 

## Description of the Project

The following description was taken on Codalab : [Link](https://competitions.codalab.org/competitions/20011#learn_the_details)

Offensive language is pervasive in social media. Individuals frequently take advantage of the perceived anonymity of computer-mediated communication, using this to engage in behavior that many of them would not consider in real life. Online communities, social media platforms, and technology companies have been investing heavily in ways to cope with offensive language to prevent abusive behavior in social media.

One of the most effective strategies for tackling this problem is to use computational methods to identify offense, aggression, and hate speech in user-generated content (e.g. posts, comments, microblogs, etc.). This topic has attracted significant attention in recent years as evidenced in recent publications (Waseem et al. 2017; Davidson et al., 2017, Malmasi and Zampieri, 2018, Kumar et al. 2018) and workshops such as ALW and TRAC.

In OffensEval we break down offensive content into three sub-tasks taking the type and target of offenses into account.

### Sub-tasks

- Sub-task A - Offensive language identification 
- Sub-task B - Automatic categorization of offense types 
- Sub-task C - Offense target identification.

### Data

The data is retrieved from social media and distributed in tab separated format. The trial and traininga data are available in the "Participate" tab. Please register to the competition to download the files.

Participants are allowed to use external resources and other datasets for this task. Please indicate which resources were used when submitting your results.


## Description of the Content of this Repo 
This repository contains the final submission of the project. 
- The report explaining the main steps and architectures of the network used
- The Jupyter Notebook containing all the code for implementing and training the classifiers. 

## Results

### Worldwide Results of the Competition : 

- Sub-task A - Rank : 62nd - F1 Score : 0.748752209
- Sub-task B - Rank : 5th - F1 Score : 0.715679443
- Sub-task C - Rank : 11th - F1 Score : 0.580794253

### Imperial College Results of the Competiton : 


- Sub-task A - Rank : 21st - F1 Score : 0.748752209
- Sub-task B - Rank : 1st - F1 Score : 0.715679443
- Sub-task C - Rank : 1st - F1 Score : 0.580794253

### Best Performing Implementation :

The classifier that performed the best accross the different tasks was the Convolutional Neural Network (CNN)


### Confusion Matrix for each subtask 


<img src="https://github.com/adrianlwn/SemEval-2019-Task-6/raw/master/images/Sub-task_A%2C_adrianlwn_CodaLab_549184.png" width="280" height="280"> <img src="https://github.com/adrianlwn/SemEval-2019-Task-6/raw/master/images/Sub-task_B%2C_adrianlwn_CodaLab_549189.png" width="280" height="280"> <img src="https://github.com/adrianlwn/SemEval-2019-Task-6/raw/master/images/Sub-task_C%2C_adrianlwn_CodaLab_549197.png" width="280" height="280">








    


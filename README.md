# Background

### Motivation

Traditional approches to study a person's emotions usually rely on the paper-and-pencil questionnaires experiments that take place in a lab. However, these methods rely heavily on the subjects' abilities to recall their experiences retrospectively, which might introduce bias. Recently, a research method called [Experience Sampling Method (ESM)](https://en.wikipedia.org/wiki/Experience_sampling_method) is burgeoning, in which the participants are asked to record their temporal feelings at real time or nearly real time. In this way, retrospective biases can be minimized when studying people's daily life experiences.

As part of a research project at the Department of Psychology, Tsinghua University, we developed *EmotionLog Suite*, which aims at combining the ESM and the mobile sensing technology. Using *EmotionLog Suite*, psychological researchers can carry out ESM experiments using mobile phones. It contains two applications: an SWT desktop application for experimenters (called *Psychorus Quest*), and an Android application for participants (called *EmotionLog*). 

Typically, an experiment in EmotionLog Suite is carried out as followed.


### Workflow chart
<img src="Screenshots/Workflow.jpg" alt="Workflow" width="80%"/>

1. Questionnaires design
2. Experiment configurations
3. Upload experiments & questionnaires
4. Join experiment, download questionnaires
5. Questionnaires notified & answered
6. Submit answers
7. Download answers
8. Subject management
9. Data Export

### Contributions: 
- Psychorus Quest
	- **Bisheng Huang**: Core logics, basic user interfaces and interactions
	- **Xiang Li**: UI improvement
- EmotionLog
	- **Bisheng Huang**: Design and development
- Web server
	- **Bisheng Huang**: Development, deployment and maintainance


# Psychorus-Quest

### Overview
Psychorus Quest is a experiment management platform for mobile-sensing experiments in psychological research.  

The following is the detailed introduction of Psychorus Quest. Also, see [EmotionLog](https://github.com/hbisheng/EmotionLog) for more information.
 
### Hierarchies
- Login window
- Register window
- Portal window
    * Questionnaire module
         - Questionnaire design window
         - Questionnaire preview window
    * Experiment module
          - Experiment design window
    * Data Collection module

# Screenshots demo

## Login & Register
<img src="Screenshots/PQ_Login.png" alt="" width="35%"/>
<img src="Screenshots/PQ_Register.png" alt="" width="35%"/>
#### Experimenters need to register & login to use the platform.

## Portial window
<img src="Screenshots/PQ_MainShell.png" style="max-width:100%;" />
#### The entrances to the three main modules of Psychorus Quest.

## Questionnaire design module: Questionnaire List
<img src="Screenshots/PQ_QuestionnaireMainShell.png" style="max-width:77%;"/>
#### This window will show a list of the questionnaires managed by the experimenter. 
#### Choose a questionnaire to edit and the questionnaire edit window will prompt out.


## Questionnaire design module: Questionnaire Edit
<img src="Screenshots/PQ_QuestionnaireDesignShell.png" alt="" width="100%"/>
#### A questionnaire can have serveral pages. 
#### Each page can have serveral questions with different types(single choice, multiple choice, range selection, etc.).

## Questionnaire design module: Questionnaire Preview
<img src="Screenshots/PQ_QuestionnairePreview.png" alt="" width="50%"/>
#### Preview the questionnaire on the desktop. 
#### The questionnaires will actually be answered on the phone.

## Experiment management module: Experiment List
<img src="Screenshots/PQ_ExperimentMainShell.png" alt="" width="82%"/>
#### A list of experiment being managed.

## Experiment management module: Experiment Panel
<img src="Screenshots/PQ_ExperimentDesign.png" alt="" width="82%"/>
#### An experiment has an invitation code. Participant can join an experiment by entering the its code.
#### Serveral questionnaires can be binded to one experiment. Each binded questionnaire will have its own sampling strategy (when and how often the questionnaires will be delivered to the user). 
#### Once a participant joins an experiment, it will appear in the experiment's subject list.
#### Advance configurations includes binding a customized wristband to a certain subject.

## Data Collection module
<img src="Screenshots/PQ_DataCollection.png" alt="" width="90%"/>
#### Within this window, experimenters will be able to collect questionnaire answers, to get some statistics about the data, and to dump the data. 


## Dumped data format: Sample
<img src="Screenshots/PQ_DataDumped.png" alt="" width="100%"/>
#### A sample of the dumped data, in csv format.


# Copyright
#####The software is currently for internal uses only. 
#####北京汇心心理科技有限公司 版权所有 Copyright © 2015-2017, Psychorus, All Rights Reserved

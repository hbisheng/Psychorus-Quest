# Background

## Intuition

Traditional approches to study a person's emotions usually rely on the paper-and-pencil questionnaires experiments that take place in a lab. However, these methods rely heavily on the subjects' abilities to recall their experiences retrospectively, which might introduce bias. Recently, a research method called [Experience Sampling Method (ESM)](https://en.wikipedia.org/wiki/Experience_sampling_method) is burgeoning, in which the participants are asked to record their temporal feelings at real time or nearly real time. In this way, retrospective biases can be minimized when studying people's daily life experiences.

As part of a research project at the Department of Psychology, Tsinghua University, we developed *EmotionLog Suite*, which aims to combine the ESM and the mobile sensing technology. Using *EmotionLog Suite* , psychological researchers can carry out ESM experiments using mobile phones. It contains two applications: an SWT desktop application for experimenters(called *Psychorus Quest*), and an Android application for participants(called *EmotionLog*). 

Typically, an experiment in EmotionLog Suite is carried out as followed.

## Workflow

1. (Within Psychorus Quest) Experimenters will design questionnaires, which contains serveral questions of differnt type, and configure their experiments, which contains serveral.
2. (Within EmotionLog) The participants will use the Android application to join certain experiment. 
3. (Within EmotionLog) Based on the sampling strategy the experimenters had specified, certain exp-related questionnaires will be delivered to the participant at a certain time. The subjects will answer the questionnaires and submit their answers. 
4. (Within Psychorus Quest) After the subjects submit their answers, the experimenters will be able to collect the answers and dump the data into certain format. 

The following is the detailed introduction of Psychours Quest. Also, see [EmotionLog](https://github.com/hbisheng/EmotionLog) for more information.

# Psychorus-Quest

## Overview 
Psychorus Quest is a experiment management platform for mobile-sensing experiments in psychological research.  

## Contributions: 
- Bisheng Huang: back logics, basic user interfaces and interactions
- Xiang Li: UI improvement

## Hierarchies of the Psychorus Quest:
- Login window
- Register window
- Portal window // Show the entrances to the three main modules
    * Questionnaire module
         - Questionnaire design window
         - Questionnaire preview window
    * Experiment module
          - Experiment design window
    * Data Collection module

# Screenshots demo
![MainShell](Screenshots/PQ_MainShell.png)

![QuestionnaireMainShell](Screenshots/PQ_QuestionnaireMainShell.png)

![QuestionnaireDesignShell](Screenshots/PQ_QuestionnaireDesignShell.png)

![QuestionnairePreview](Screenshots/PQ_QuestionnairePreview.png)

![ExperimentMainShell](Screenshots/PQ_ExperimentMainShell.png)
An experiment has an invitation code.


![ExperimentDesign](Screenshots/PQ_ExperimentDesign.png)

![DataCollection](Screenshots/PQ_DataCollection.png)

![DataDumped](Screenshots/PQ_DataDumped.png)

![Login Prompt](Screenshots/PQ_Login.png)

![Register Prompt](Screenshots/PQ_Register.png)


北京汇心心理科技有限公司 版权所有
Copyright © 2015-2017, Psychorus, All Rights Reserved
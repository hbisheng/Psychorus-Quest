# Psychorus-Quest

Psychorus Quest is an SWT desktop application for psychological experiment management on windows. It's used for experimenters to design questionnaires, configure experiments and manage participants information. Carry out ESM experiments.

# Contributions: 
- Bisheng Huang: back logics, basic user interfaces and interactions
- Xiang Li: UI improvement


# Platform logics
1. At first questionnaires are designed within Psychorus Quest,
2. An experiment contains several questionnaires, each is binded with a sampling strategy.
3. Questionnaires, Experiment, subjects, configurations are stored both locally and on the web server. 
4. <link>EmotionLog</link>: An Android application used by subjests. Join experiment. Complete Questionnaires. Upload to a web server.
5. Subjects management. As part of ESM, Each subject can be binded to a wristband. Further configure the band.
6. Data collection module, download from web servers and dump them into csv formats.
Draw a graph.

# Hierarchies of the Psychorus Quest:
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

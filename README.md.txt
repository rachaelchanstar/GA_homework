# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SF-DAT-21 | Unit Project 1: Research Design Write-Up

> **Assigned:** Thursday, February 25, 2016.
>
> **Deadline:** Thursday, March 3, 2016 6:30PM Pacific Time.
>
> **Submission:**
>
> - Please submit your homework via GitHub and send a private message on [Slack](https://sf-dat-21.slack.com) to Azi or Jeremiah with a link to it.

---

## PROMPT

"A problem well-stated is half-solved" -- Charles Kettering

Welcome to Data Science!  In this first project you will create a framework to scope out data science projects.  This framework will provide you with a guide to develop a well-articulated problem statement and analysis plan that will be robust and reproducible.

**Goal:** Create a structured iPython notebook using markup.

---

## DELIVERABLES

### Completed iPython Notebook

- **Requirements:**
  - Identify features of the dataset, including the outcome and covariates/predictors.
  Looks like it is a dataset for grad school applications.  
  
  Outcome- Admit 
  Covariates/Predictors = GRE, GPA, Prestige
  
  - Create a data dictionary with classification of available variables.
      Variable	Description	Type of Variable
        Admit	0 = not admit, 1 = admit	Categorical
        GRE 	admission exam score X	int
        GPA 	school performance X	int
        Prestige 	1-4 Tier of school, 1 the higest ranking	Categorical

  
  - Write a high quality problem statement.
  The acceptance rate is below 35%
  
  
  
  - State the risks and assumptions of your data.
  Lack of recommendation letter or work experience information. It might impact the acceptance decision
  The source of the data. 
  
  
  - Outline exploratory analysis methods.
  The objectives of EDA are to:

Suggest hypotheses about the causes of observed phenomena
- high gre / gpa / prestige => higher chance to get in UCLA 

Assess assumptions on which statistical inference will be based
- testing hypotheses 

Support the selection of appropriate statistical tools and techniques
Provide a basis for further data collection through surveys or experiments[5]

  

- **Bonus:**
  - Practice writing an alternative problem statement for your dataset.
  - Articulate the risks and assumptions of this alternative model.

---

## RESOURCES

### Dataset

The dataset is available [here](../dataset).

### Starter code

For this project we will be using an iPython notebook.  Notebooks are a handy way to communicate your research with your team and share your analysis.  Using markup syntax will allow you create more visually appealing notebooks.

* Open the [starter code notebook](./code/unit-project-1-starter-code.ipynb) in Anaconda.

### Sample Deliverables

Check out the [sample notebook](./code/unit-project-1-sample.ipynb), which includes a data dictionary and responses to questions.  Wonder how to format your notebook the same way?  Simply double-click on any section to view the markdown.

![Sample Notebook](./assets/unit-project-1-sample.jpg)

### Suggestions for Getting Started

- Get used to the iPython Notebook layout.  Play around with keyboard shortcuts.
- Try out basic markdown for commonly used formats; look up commands for headers, bold, italic, tables.
- **Read the docs for iPython Notebooks.**  Most of the time, there is a tutorial that you can follow, but not always, and learning to read documentation is crucial to your success as a data scientist!

### Additional Links

- [iPython Notebook Shortcuts](https://ipython.org/ipython-doc/1/interactive/notebook.html#keyboard-shortcuts)
- [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [iPython Notebook Docs](http://ipython.readthedocs.org/en/stable/)

---

## EVALUATION

The rubric is available [here](./rubric).

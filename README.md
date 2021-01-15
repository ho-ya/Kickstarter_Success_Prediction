# Kickstarter Campaign Success Prediction

**collaborators:** Philipp Becker and Yannic Holländer

**created**: October 2020 as part of the neuefische bootcamp

## Abstract

Kickstarter is a global crowdfunding platform launched in 2009. Its mission statement is to "help bring creative projects to life". So far, more than 445,000 campaigns have been funded. Popular categories include films, music, stage shows, comics, journalism, video games, technology, publishing, and food-related projects. But what factors determine wheather a project gets funded or not? How do successful campaigns differ from unsuccessful ones? The goal of this project is to answer these questions.

As part of this assignment we adopt a hypothetical business case: The stakeholder in this case would be the Kickstarter corporation itself. Understanding what factors control campaign sucess in is benefitial for the company, as this information could be passed on to campaign creators via the Kickstarter website. The user would receive promts that guide them through the set up process. Thus, the user can better structure their project, set realistic goals, fill in the right kind of information and spend their resources more efficiently. Comparable sites already do something similar. All in all this could lead to a better success rate of campaigns across the board and to a higher user satisfaction.

There is a second part to this business case. Kickstarter earns a comission from the pledges of every successful project. If we can provide a model that accurately predicts which campaigns will succeed and which fail, Kickstarter could promote the promising campaigns on their homepage and expose more potential backers to these specific campaigns, ensuring a higher backer count, more pledges and a larger comission. 

With this business case in mind, we will investigate the accompanying data in an exploratory data analysis and then train different machine learning models on it, choosing the one that best predicts success.

<table><tr>
<td> <img align="center" src="images/Wordcloud_Success.png" width="500" /> </td>
<td> <img align="center" src="images/Wordcloud_Fail.png" width="500" /> </td>
</tr></table>

## Files and Directories

In this repository there are the following files and folders:

* **data/** - A directory containing the provided raw data that was originally split up into 56 different .csv-files.
* **images/** - A directory containing all images created during the project as .png-files. Files created in the notebook are saves here. The images are used in the final presentation.
* **Notebook_Kickstarter_prediction.ipynb** - The notebook that documents this project. The data cleaning, exploratory data analysis, model training as well as model evaluation are all performed and commented on in here.
* **Presentation.pdf** - The summary of findings of this project. These findings were presented in the context of the neuefische data science bootcamp
